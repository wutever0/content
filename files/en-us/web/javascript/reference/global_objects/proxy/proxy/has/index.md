---
title: handler.has()
slug: Web/JavaScript/Reference/Global_Objects/Proxy/Proxy/has
tags:
- ECMAScript 2015
- JavaScript
- Method
- Proxy
browser-compat: javascript.builtins.Proxy.handler.has
---
{{JSRef}}

The **`handler.has()`** method is a trap for the
{{jsxref("Operators/in", "in")}} operator.

{{EmbedInteractiveExample("pages/js/proxyhandler-has.html", "taller")}}

## Syntax

<pre class="brush: js">
const <var>p</var> = new Proxy(<var>target</var>, {
  has: function(<var>target</var>, <var>prop</var>) {
  }
});
</pre>

### Parameters

The following parameters are passed to `has()` method. `this` is bound to the
handler.

- `target`
  - : The target object.
- `prop`
  - : The name or {{jsxref("Symbol")}} of the property to check for
    existence.

### Return value

The `has()` method must return a boolean value.

## Description

The **`handler.has()`** method is a trap for the
{{jsxref("Operators/in", "in")}} operator.

### Interceptions

This trap can intercept these operations:

- Property query:

  <code><var>foo</var> in <var>proxy</var></code>

- Inherited property query:

  <code>foo in Object.create(<var>proxy</var>)</code>

- `with` check:

  <code>with(<var>proxy</var>) { (<var>foo</var>); }</code>

- {{jsxref("Reflect.has()")}}

### Invariants

If the following invariants are violated, the proxy will throw a
{{jsxref("TypeError")}}:

- A property cannot be reported as non-existent, if it exists as a
  non-configurable own property of the target object.
- A property cannot be reported as non-existent, if it exists as an own property
  of the target object and the target object is not extensible.

## Examples

### Trapping the in operator

The following code traps the {{jsxref("Operators/in", "in")}}
operator.

```js
const p = new Proxy({}, {
  has: function(target, prop) {
    console.log('called: ' + prop);
    return true;
  }
});

console.log('a' in p); // "called: a"
                       // true
```

The following code violates an invariant.

```js example-bad
const obj = { a: 10 };
Object.preventExtensions(obj);

const p = new Proxy(obj, {
  has: function(target, prop) {
    return false;
  }
});

'a' in p; // TypeError is thrown
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- {{jsxref("Proxy")}}
- {{jsxref("Proxy.handler", "handler")}}
- {{jsxref("Operators/in", "in")}} operator
- {{jsxref("Reflect.has()")}}
