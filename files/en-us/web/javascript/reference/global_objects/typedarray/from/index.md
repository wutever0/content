---
title: TypedArray.from()
slug: Web/JavaScript/Reference/Global_Objects/TypedArray/from
tags:
- ECMAScript 2015
- JavaScript
- Method
- TypedArray
- TypedArrays
- from
- Polyfill
browser-compat: javascript.builtins.TypedArray.from
---
{{JSRef}}

The **<code><var>TypedArray</var>.from()</code>** method creates a new
[typed array](/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray#TypedArray_objects)
from an array-like or iterable object. This method is nearly the same as
{{jsxref("Array.from()")}}.

{{EmbedInteractiveExample("pages/js/typedarray-from.html","shorter")}}

## Syntax

```js
// Arrow function
TypedArray.from(arrayLike, (currentValue) => { ... } )
TypedArray.from(arrayLike, (currentValue, index) => { ... } )
TypedArray.from(arrayLike, (currentValue, index, array) => { ... } )

// Mapping function
TypedArray.from(arrayLike, mapFn)
TypedArray.from(arrayLike, mapFn, thisArg)

// Inline mapping function
TypedArray.from(arrayLike, function mapFn(currentValue) { ... })
TypedArray.from(arrayLike, function mapFn(currentValue, index) { ... })
TypedArray.from(arrayLike, function mapFn(currentValue, index, array){ ... })
TypedArray.from(arrayLike, function mapFn(currentValue, index, array) { ... }, thisArg)
```

Where `TypedArray` is one of:

<div class="threecolumns"><ul><li>{{jsxref("Int8Array")}}</li><li>{{jsxref("Uint8Array")}}</li><li>{{jsxref("Uint8ClampedArray")}}</li><li>{{jsxref("Int16Array")}}</li><li>{{jsxref("Uint16Array")}}</li><li>{{jsxref("Int32Array")}}</li><li>{{jsxref("Uint32Array")}}</li><li>{{jsxref("Float32Array")}}</li><li>{{jsxref("Float64Array")}}</li><li>{{jsxref("BigInt64Array")}}</li><li>{{jsxref("BigUint64Array")}}</li></ul></div>

### Parameters

- `arrayLike`
  - : An array-like or iterable object to convert to a typed array.
- `mapFn` {{optional_inline}}
  - : Map function to call on every element of the typed array.
- `thisArg` {{optional_inline}}
  - : Value to use as `this` when executing `mapFn`.

### Return value

A new {{jsxref("TypedArray")}} instance.

## Description

<code><var>TypedArray</var>.from()</code> lets you create typed arrays from:

- array-like objects (objects with a `length` property and indexed elements); or
- [iterable objects](/en-US/docs/Web/JavaScript/Guide/iterable) (objects where
  you can get its elements, such as {{jsxref("Map")}} and
  {{jsxref("Set")}}).

<code><var>TypedArray</var>.from()</code> has the optional parameter `mapFn`,
which allows you to execute a
{{jsxref("Array.prototype.map", "map()")}} function on each
element of the typed array (or subclass object) that is being created. This
means that the following are equivalent:

- <code><var>TypedArray</var>.from(<var>obj</var>, <var>mapFn</var>,
  <var>thisArg</var>)</code>
- <code><var>TypedArray</var>.from(Array.prototype.map.call(<var>obj</var>,
  <var>mapFn</var>, <var>thisArg</var>))</code>

  .

The `length` property of the `from()` method is `1`.

### Differences from Array.from()

Some subtle distinctions between {{jsxref("Array.from()")}} and
<code><var>TypedArray</var>.from()</code>:

- If the `thisArg` value passed to

  <code><var>TypedArray</var>.from()</code>

  is not a constructor,

  <code><var>TypedArray</var>.from()</code>

  will throw a {{jsxref("TypeError")}}, where `Array.from()` defaults
  to creating a new {{jsxref("Array")}}.

- <code><var>TypedArray</var>.from()</code>

  uses `[[Put]]` where `Array.from()` uses `[[DefineProperty]]`. Hence, when
  working with {{jsxref("Proxy")}} objects, it calls
  {{jsxref("Global_Objects/Proxy/handler/set", "handler.set")}}
  to create new elements rather than
  {{jsxref("Global_Objects/Proxy/handler/defineProperty",
        "handler.defineProperty()")}}.

- When the `source` parameter is an iterator, the

  <code><var>TypedArray</var>.from()</code>

  first collects all the values from the iterator, then creates an instance of
  `thisArg` using the count, then sets the values on the instance.
  `Array.from()` sets each value as it receives them from the iterator, then
  sets its `length` at the end.

- When `Array.from()` gets an array-like which isn't an iterator, it respects
  holes.

  <code><var>TypedArray</var>.from()</code>

  will ensure the result is dense.

## Examples

### From an iterable object (Set)

```js
const s = new Set([1, 2, 3]);
Uint8Array.from(s);
// Uint8Array [ 1, 2, 3 ]
```

### From a string

```js
Int16Array.from('123');
// Int16Array [ 1, 2, 3 ]
```

### Use with arrow function and map

Using an arrow function as the map function to manipulate the elements

```js
Float32Array.from([1, 2, 3], x => x + x);
// Float32Array [ 2, 4, 6 ]
```

### Generate a sequence of numbers

```js
Uint8Array.from({length: 5}, (v, k) => k);
// Uint8Array [ 0, 1, 2, 3, 4 ]
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- A polyfill of `TypedArray.from` is available in
  [`core-js`](https://github.com/zloirock/core-js#ecmascript-typed-arrays)
- {{jsxref("TypedArray.of()")}}
- {{jsxref("Array.from()")}}
- {{jsxref("Array.prototype.map()")}}
- [A polyfill](https://github.com/behnammodi/polyfill/blob/v0.0.1/int-8-array.polyfill.js)
