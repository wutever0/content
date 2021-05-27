---
title: 'TypeError: invalid arguments'
slug: Web/JavaScript/Reference/Errors/Typed_array_invalid_arguments
tags:
- Error
- Errors
- JavaScript
- TypeError
---
{{jsSidebar("Errors")}}

The JavaScript exception "invalid arguments" occurs when
[typed array](/en-US/docs/Web/JavaScript/Typed_arrays) constructors are provided
with a wrong argument.

## Message

```js
TypeError: invalid arguments (Firefox)
```

## Error type

{{jsxref("TypeError")}}

## What went wrong?

[Typed array](/en-US/docs/Web/JavaScript/Typed_arrays) constructors require
either

- a length,
- another typed array,
- array-like objects,
- iterable objects or
- an {{jsxref("ArrayBuffer")}} object

to create a new typed array. Other constructor arguments will not create a valid
typed array.

## Examples

### No strings in typed arrays

Typed arrays, for example a {{jsxref("Uint8Array")}}, can't be
constructed from a string. In fact, strings can't be in typed arrays at all.

```js example-bad
var ta = new Uint8Array("nope");
// TypeError: invalid arguments
```

Different ways to create a valid {{jsxref("Uint8Array")}}:

```js example-good
// From a length
var uint8 = new Uint8Array(2);
uint8[0] = 42;
console.log(uint8[0]); // 42
console.log(uint8.length); // 2
console.log(uint8.BYTES_PER_ELEMENT); // 1

// From an array
var arr = new Uint8Array([21,31]);
console.log(arr[1]); // 31

// From another TypedArray
var x = new Uint8Array([21, 31]);
var y = new Uint8Array(x);
console.log(y[0]); // 21

// From an ArrayBuffer
var buffer = new ArrayBuffer(8);
var z = new Uint8Array(buffer, 1, 4);

// From an iterable
var iterable = function*(){ yield* [1,2,3]; }();
var uint8 = new Uint8Array(iterable);
// Uint8Array[1, 2, 3]
```

## See also

- [Typed arrays](/en-US/docs/Web/JavaScript/Typed_arrays)
- {{jsxref("ArrayBuffer")}}
- {{jsxref("Uint8Array")}}
