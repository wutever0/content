---
title: Generator.prototype.throw()
slug: Web/JavaScript/Reference/Global_Objects/Generator/throw
tags:
  - ECMAScript 2015
  - Generator
  - JavaScript
  - Method
  - Prototype
  - Reference
browser-compat: javascript.builtins.Generator.throw
---
{{JSRef}}

<span class="seoSummary"

> The <strong><code>throw()</code></strong> method resumes the execution of a
> generator by throwing an error into it and returns an object with two
> properties <code>done</code> and <code>value</code>.</span

## Syntax

```js
throw(exception)
```

### Parameters

- `exception`

  - : The exception to throw. For debugging purposes, it is useful to make it an

    `instanceof` {{jsxref("Error")}}.

### Return value

An {{jsxref("Global_Objects/Object", "Object")}} with two
properties:

- `done` (boolean)
  - :
    - Has the value `true` if the iterator is past the end of the iterated
      sequence. In this case `value` optionally specifies the _return value_ of
      the iterator.
    - Has the value `false` if the iterator was able to produce the next value
      in the sequence. This is equivalent of not specifying the `done` property
      altogether.
- `value`

  - : Any JavaScript value returned by the iterator. Can be omitted when `done`

    is `true` .

## Examples

### Using throw()

The following example shows a simple generator and an error that is thrown using
the `throw` method. An error can be caught by a
{{jsxref("Statements/try...catch", "try...catch")}} block as
usual.

```js
function* gen() {
  while(true) {
    try {
       yield 42;
    } catch(e) {
      console.log('Error caught!');
    }
  }
}

const g = gen();
g.next();
// { value: 42, done: false }
g.throw(new Error('Something went wrong'));
// "Error caught!"
// { value: 42, done: false }
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- {{jsxref("Statements/function*", "function*")}}
