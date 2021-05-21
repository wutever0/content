---
title: Meta programming
slug: Web/JavaScript/Guide/Meta_programming
tags:
  - ECMAScript 2015
  - Guide
  - JavaScript
  - Proxy
  - Reflect
  - l10n:priority
---
{{jsSidebar("JavaScript Guide")}}{{PreviousNext("Web/JavaScript/Guide/Iterators_and_Generators", "Web/JavaScript/Guide/Modules")}}

Starting with ECMAScript 2015, JavaScript gains support for the
{{jsxref("Proxy")}} and {{jsxref("Reflect")}} objects allowing you
to intercept and define custom behavior for fundamental language operations
(e.g. property lookup, assignment, enumeration, function invocation, etc). With
the help of these two objects you are able to program at the meta level of
JavaScript.

## Proxies

Introduced in ECMAScript 6, {{jsxref("Proxy")}} objects allow you to
intercept certain operations and to implement custom behaviors.

For example, getting a property on an object:

<pre class="brush: js">
let <var>handler</var> = {
  get: function(<var>target</var>, name) {
    return name in <var>target</var> ? <var>target</var>[name] : 42
  }
}

let p = new Proxy({}, <var>handler</var>)
p.a = 1
console.log(p.a, p.b) // 1, 42
</pre>

The `Proxy` object defines a <dfn

> <code><var>target</var></code></dfn
>
> (an empty object here) and a <dfn <code><var>handler</var></code></dfn
>
> object, in which a `get` <dfn>trap</dfn> is implemented. Here, an object that
> is proxied will not return `undefined` when getting undefined properties, but
> will instead return the number `42`.

Additional examples are available on the {{jsxref("Proxy")}} reference
page.

### Terminology

The following terms are used when talking about the functionality of proxies.

- {{jsxref("Global_Objects/Proxy/Proxy","handler","","true")}}
  - : Placeholder object which contains traps.
- traps
  - : The methods that provide property access. (This is analogous to the
    concept of _traps_ in operating systems.)
- target
  - : Object which the proxy virtualizes. It is often used as storage backend
    for the proxy. Invariants (semantics that remain unchanged) regarding object
    non-extensibility or non-configurable properties are verified against the
    target.
- invariants
  - : Semantics that remain unchanged when implementing custom operations are
    called _invariants_ . If you violate the invariants of a handler, a
    {{jsxref("TypeError")}} will be thrown.

## Handlers and traps

The following table summarizes the available traps available to `Proxy` objects.
See the
[reference pages](/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/Proxy)
for detailed explanations and examples.

| Handler / trap                                                                                                   | Interceptions                                                                                                                                                                                                                                                                            | Invariants                                                  |
| ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------- |
| {{jsxref("Global_Objects/Proxy/Proxy/getPrototypeOf", "handler.getPrototypeOf()")}} | {{jsxref("Object.getPrototypeOf()")}} {{jsxref("Reflect.getPrototypeOf()")}} {{jsxref("Object/proto", "__proto__")}} {{jsxref("Object.prototype.isPrototypeOf()")}} {{jsxref("Operators/instanceof", "instanceof")}} | \* `getPrototypeOf` method must return an object or `null`. |

- If `target` is not extensible,

      <code>Object.getPrototypeOf(<var>proxy</var>)</code>


       method must return the same value as

      <code>Object.getPrototypeOf(<var>target</var>)</code>


      .                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |

  |
  {{jsxref("Global_Objects/Proxy/Proxy/setPrototypeOf", "handler.setPrototypeOf()")}}
  | {{jsxref("Object.setPrototypeOf()")}}
  {{jsxref("Reflect.setPrototypeOf()")}} | If `target` is not
  extensible, the `prototype` parameter must be the same value as
  <code>Object.getPrototypeOf(<var>target</var>)</code> . | |
  {{jsxref("Global_Objects/Proxy/Proxy/isExtensible", "handler.isExtensible()")}}
  | {{jsxref("Object.isExtensible()")}}
  {{jsxref("Reflect.isExtensible()")}} |
  <code>Object.isExtensible(<var>proxy</var>)</code> must return the same value
  as <code>Object.isExtensible(<var>target</var>)</code> . | |
  {{jsxref("Global_Objects/Proxy/Proxy/preventExtensions", "handler.preventExtensions()")}}
  | {{jsxref("Object.preventExtensions()")}}
  {{jsxref("Reflect.preventExtensions()")}} |
  <code>Object.preventExtensions(<var>proxy</var>)</code> only returns `true` if
  <code>Object.isExtensible(<var>proxy</var>)</code> is `false`. | |
  {{jsxref("Global_Objects/Proxy/Proxy/getOwnPropertyDescriptor", "handler.getOwnPropertyDescriptor()")}}
  | {{jsxref("Object.getOwnPropertyDescriptor()")}}
  {{jsxref("Reflect.getOwnPropertyDescriptor()")}} | \*
  `getOwnPropertyDescriptor` must return an object or `undefined`.

- A property cannot be reported as non-existent if it exists as a
  non-configurable own property of `target`.
- A property cannot be reported as non-existent if it exists as an own property
  of `target` and `target` is not extensible.
- A property cannot be reported as existent if it does not exists as an own
  property of `target` and `target` is not extensible.
- A property cannot be reported as non-configurable if it does not exist as an
  own property of `target` or if it exists as a configurable own property of
  `target`.
- The result of

      <code>Object.getOwnPropertyDescriptor(<var>target</var>)</code>


       can be applied to `target` using `Object.defineProperty` and will not throw an exception. |

  |
  {{jsxref("Global_Objects/Proxy/Proxy/defineProperty", "handler.defineProperty()")}}
  | {{jsxref("Object.defineProperty()")}}
  {{jsxref("Reflect.defineProperty()")}} | \* A property cannot be
  added if `target` is not extensible.

- A property cannot be added as (or modified to be) non-configurable if it does
  not exist as a non-configurable own property of `target`.
- A property may not be non-configurable if a corresponding configurable
  property of `target` exists.
- If a property has a corresponding target object property, then

  <code

  > Object.defineProperty(<var>target</var>, <var>prop</var>,
  > <var>descriptor</var>)</code

  will not throw an exception.

- In strict mode, a `false` value returned from the `defineProperty` handler
  will throw a {{jsxref("TypeError")}} exception. | |
  {{jsxref("Global_Objects/Proxy/Proxy/has", "handler.has()")}}
  | _ Property query _ : `foo in proxy`
- Inherited property query

  - : <code>foo in Object.create(<var>proxy</var>)</code>

    {{jsxref("Reflect.has()")}} | \* A property cannot be reported as
    non-existent, if it exists as a non-configurable own property of `target`.

- A property cannot be reported as non-existent if it exists as an own property
  of `target` and `target` is not extensible. | |
  {{jsxref("Global_Objects/Proxy/Proxy/get", "handler.get()")}}
  | _ Property access _ : <code><var>proxy</var>[foo]</code>

          <code><var>proxy</var>.bar</code>

- Inherited property access

  - : <code>Object.create(<var>proxy</var>)[foo]</code>

    {{jsxref("Reflect.get()")}} | \* The value reported for a property
    must be the same as the value of the corresponding `target` property if
    `target`'s property is a non-writable, non-configurable data property.

- The value reported for a property must be `undefined` if the corresponding
  `target` property is non-configurable accessor property that has undefined as
  its `[[Get]]` attribute. | |
  {{jsxref("Global_Objects/Proxy/Proxy/set", "handler.set()")}}
  | _ Property assignment _ : <code><var>proxy</var>[foo] = bar</code>

          <code><var>proxy</var>.foo = bar</code>

- Inherited property assignment

  - : <code>Object.create(<var>proxy</var>)[foo] = bar</code>

    {{jsxref("Reflect.set()")}} | \* Cannot change the value of a
    property to be different from the value of the corresponding `target`
    property if the corresponding `target` property is a non-writable,
    non-configurable data property.

- Cannot set the value of a property if the corresponding `target` property is a
  non-configurable accessor property that has `undefined` as its `[[Set]]`
  attribute.
- In strict mode, a `false` return value from the `set` handler will throw a
  {{jsxref("TypeError")}} exception. | |
  {{jsxref("Global_Objects/Proxy/Proxy/deleteProperty", "handler.deleteProperty()")}}
  | _ Property deletion _ : <code>delete <var>proxy</var>[foo]</code>

          <code>delete <var>proxy</var>.foo</code>


          {{jsxref("Reflect.deleteProperty()")}}                                                                                               | A property cannot be deleted if it exists as a non-configurable own property of `target`.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |

  |
  {{jsxref("Global_Objects/Proxy/handler/enumerate", "handler.enumerate()")}}
  | _ Property enumeration / `for...in`: _ : <code>for (let name in
  <var>proxy</var>) {...}</code>

          {{jsxref("Reflect.enumerate()")}}                                                                                                                                      | The `enumerate` method must return an object.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |

  |
  {{jsxref("Global_Objects/Proxy/Proxy/ownKeys", "handler.ownKeys()")}}
  | {{jsxref("Object.getOwnPropertyNames()")}}
  {{jsxref("Object.getOwnPropertySymbols()")}}
  {{jsxref("Object.keys()")}} {{jsxref("Reflect.ownKeys()")}}
  | \* The result of `ownKeys` is a List.

- The Type of each result List element is either {{jsxref("String")}} or
  {{jsxref("Symbol")}}.
- The result List must contain the keys of all non-configurable own properties
  of `target`.
- If the `target` object is not extensible, then the result List must contain
  all the keys of the own properties of `target` and no other values. | |
  {{jsxref("Global_Objects/Proxy/Proxy/apply", "handler.apply()")}}
  | `proxy(..args)` {{jsxref("Function.prototype.apply()")}} and
  {{jsxref("Function.prototype.call()")}}
  {{jsxref("Reflect.apply()")}} | There are no invariants for the
  <code><var>handler</var>.apply</code> method. | |
  {{jsxref("Global_Objects/Proxy/Proxy/construct", "handler.construct()")}}
  | `new proxy(...args)` {{jsxref("Reflect.construct()")}} | The
  result must be an `Object`. |

## Revocable `Proxy`

The {{jsxref("Proxy.revocable()")}} method is used to create a
revocable `Proxy` object. This means that the proxy can be revoked via the
function `revoke` and switches the proxy off.

Afterwards, any operation on the proxy leads to a
{{jsxref("TypeError")}}.

```js
let revocable = Proxy.revocable({}, {
  get: function(target, name) {
    return '[[' + name + ']]'
  }
})
let proxy = revocable.proxy
console.log(proxy.foo)  // "[[foo]]"

revocable.revoke()

console.log(proxy.foo)  // TypeError is thrown
proxy.foo = 1           // TypeError again
delete proxy.foo        // still TypeError
typeof proxy            // "object", typeof doesn't trigger any trap
```

## Reflection

{{jsxref("Reflect")}} is a built-in object that provides methods for
interceptable JavaScript operations. The methods are the same as those of the
{{jsxref("Global_Objects/Proxy/Proxy","proxy handlers","","true")}}.

`Reflect` is not a function object.

`Reflect` helps with forwarding default operations from the handler to the
`target`.

With {{jsxref("Reflect.has()")}} for example, you get the
[`in` operator](/en-US/docs/Web/JavaScript/Reference/Operators/in) as a
function:

```js
Reflect.has(Object, 'assign') // true
```

### A better `apply` function

In ES5, you typically use the
{{jsxref("Function.prototype.apply()")}} method to call a function
with a given `this` value and `arguments` provided as an array (or an
[array-like object](/en-US/docs/Web/JavaScript/Guide/Indexed_collections#working_with_array-like_objects)).

```js
Function.prototype.apply.call(Math.floor, undefined, [1.75])
```

With {{jsxref("Reflect.apply")}} this becomes less verbose and easier
to understand:

```js
Reflect.apply(Math.floor, undefined, [1.75])
// 1

Reflect.apply(String.fromCharCode, undefined, [104, 101, 108, 108, 111])
// "hello"

Reflect.apply(RegExp.prototype.exec, /ab/, ['confabulation']).index
// 4

Reflect.apply(''.charAt, 'ponies', [3])
// "i"
```

### Checking if property definition has been successful

With {{jsxref("Object.defineProperty")}}, which returns an object
if successful, or throws a {{jsxref("TypeError")}} otherwise, you would
use a {{jsxref("Statements/try...catch","try...catch")}} block
to catch any error that occurred while defining a property. Because
{{jsxref("Reflect.defineProperty")}} returns a Boolean success
status, you can just use an
{{jsxref("Statements/if...else","if...else")}} block here:

```js
if (Reflect.defineProperty(target, property, attributes)) {
  // success
} else {
  // failure
}
```

{{PreviousNext("Web/JavaScript/Guide/Iterators_and_Generators", "Web/JavaScript/Guide/Modules")}}
