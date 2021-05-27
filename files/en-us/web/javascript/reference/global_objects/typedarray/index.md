---
title: TypedArray
slug: Web/JavaScript/Reference/Global_Objects/TypedArray
tags:
- Class
- JavaScript
- TypedArray
- TypedArrays
- Polyfill
browser-compat: javascript.builtins.TypedArray
---
{{JSRef}}

A **_TypedArray_** object describes an array-like view of an underlying
[binary data buffer](/en-US/docs/Web/JavaScript/Reference/Global_Objects/ArrayBuffer).
There is no global property named `TypedArray`, nor is there a directly visible
`TypedArray` constructor. Instead, there are a number of different global
properties, whose values are typed array constructors for specific element
types, listed below. On the following pages you will find common properties and
methods that can be used with any typed array containing elements of any type.

{{EmbedInteractiveExample("pages/js/typedarray-constructor.html")}}

## Description

ECMAScript 2015 defines a `TypedArray` constructor that serves as the
`[[Prototype]]` of all `TypedArray` constructors. This constructor is not
directly exposed: there is no global `%TypedArray%` or `TypedArray` property. It
is only directly accessible through `Object.getPrototypeOf(Int8Array)` and
similar. All `TypedArray`s constructors inherit common properties from the
`%TypedArray%` constructor function. Additionally, all typed array prototypes
(<code><var>TypedArray</var>.prototype</code>) have `%TypedArray%.prototype` as
their `[[Prototype]]`.

The `%TypedArray%` constructor on its own is not particularly useful. Calling it
or using it in a `new` expression will throw a {{jsxref("TypeError")}},
except when used during object creation in JS engines that support subclassing.
There are at present no such engines, so `%TypedArray%` is only useful to
polyfill functions or properties onto all `TypedArray` constructors.

When creating an instance of a `TypedArray` (e.g. `Int8Array`), an array buffer
is created internally in memory or, if an `ArrayBuffer` object is given as
constructor argument, then this is used instead. The buffer address is saved as
an internal property of the instance and all the methods of
<code>%<var>TypedArray</var>%.prototype</code>, i.e. set value and get value
etc., operate on that array buffer address.

### TypedArray objects

<table class="standard-table"><thead><tr><th class="header" scope="col">Type</th><th class="header" scope="col">Value Range</th><th class="header" scope="col">Size in bytes</th><th class="header" scope="col">Description</th><th class="header" scope="col">Web IDL type</th><th class="header" scope="col">Equivalent C type</th></tr></thead><tbody><tr><td>{{jsxref("Int8Array")}}</td><td><code>-128</code> to <code>127</code></td><td>1</td><td>8-bit two's complement signed integer</td><td><code>byte</code></td><td><code>int8_t</code></td></tr><tr><td>{{jsxref("Uint8Array")}}</td><td><code>0</code> to <code>255</code></td><td>1</td><td>8-bit unsigned integer</td><td><code>octet</code></td><td><code>uint8_t</code></td></tr><tr><td>{{jsxref("Uint8ClampedArray")}}</td><td><code>0</code> to <code>255</code></td><td>1</td><td>8-bit unsigned integer (clamped)</td><td><code>octet</code></td><td><code>uint8_t</code></td></tr><tr><td>{{jsxref("Int16Array")}}</td><td><code>-32768</code> to <code>32767</code></td><td>2</td><td>16-bit two's complement signed integer</td><td><code>short</code></td><td><code>int16_t</code></td></tr><tr><td>{{jsxref("Uint16Array")}}</td><td><code>0</code> to <code>65535</code></td><td>2</td><td>16-bit unsigned integer</td><td><code>unsigned short</code></td><td><code>uint16_t</code></td></tr><tr><td>{{jsxref("Int32Array")}}</td><td><code>-2147483648</code> to <code>2147483647</code></td><td>4</td><td>32-bit two's complement signed integer</td><td><code>long</code></td><td><code>int32_t</code></td></tr><tr><td>{{jsxref("Uint32Array")}}</td><td><code>0</code> to <code>4294967295</code></td><td>4</td><td>32-bit unsigned integer</td><td><code>unsigned long</code></td><td><code>uint32_t</code></td></tr><tr><td>{{jsxref("Float32Array")}}</td><td><code>1.2E-38</code> to
<code>3.4E38</code></td><td>4</td><td>32-bit IEEE floating point number (7 significant digits e.g.,
<code>1.234567</code>)</td><td><code>unrestricted float</code></td><td><code>float</code></td></tr><tr><td>{{jsxref("Float64Array")}}</td><td><code>5E-324</code> to
<code>1.8E308</code></td><td>8</td><td>64-bit IEEE floating point number (16 significant digits e.g.,
<code>1.23456789012345</code>)</td><td><code>unrestricted double</code></td><td><code>double</code></td></tr><tr><td>{{jsxref("BigInt64Array")}}</td><td><code>-2^63</code> to <code>2^63 - 1</code></td><td>8</td><td>64-bit two's complement signed integer</td><td><code>bigint</code></td><td><code>int64_t (signed long long)</code></td></tr><tr><td>{{jsxref("BigUint64Array")}}</td><td><code>0</code> to <code>2^64 - 1</code></td><td>8</td><td>64-bit unsigned integer</td><td><code>bigint</code></td><td><code>uint64_t (unsigned long long)</code></td></tr></tbody></table>

## Constructor

This object cannot be instantiated directly. Instead, you create an instance of
an array of a particular type, such as a {{jsxref("Int8Array")}} or a
{{jsxref("BigInt64Array")}}. These objects all have a common syntax for
their constructors:

```js
new TypedArray()
new TypedArray(length)
new TypedArray(typedArray)
new TypedArray(object)

new TypedArray(buffer)
new TypedArray(buffer, byteOffset)
new TypedArray(buffer, byteOffset, length)
```

Where <var>TypedArray</var> is a constructor for one of the concrete types.

### Parameters

- `length`
  - : When called with a `length` argument, an internal array buffer is created
    in memory, of size `length` _multiplied by `BYTES_PER_ELEMENT`_ bytes,
    containing zeros.
- `typedArray`
  - : When called with a `typedArray` argument, which can be an object of any of
    the typed array types (such as `Int32Array`), the `typedArray` gets copied
    into a new typed array. Each value in `typedArray` is converted to the
    corresponding type of the constructor before being copied into the new
    array. The length of the new typed array will be same as the length of the
    `typedArray` argument.
- `object`
  - : When called with an `object` argument, a new typed array is created as if
    by the <code><var>TypedArray</var>.from()</code> method.
- `buffer`, `byteOffset`, `length`
  - : When called with a `buffer`, and optionally a `byteOffset` and a `length`
    argument, a new typed array view is created that views the specified
    {{jsxref("ArrayBuffer")}}. The `byteOffset` and `length` parameters
    specify the memory range that will be exposed by the typed array view. If
    both are omitted, all of `buffer` is viewed; if only `length` is omitted,
    the remainder of `buffer` is viewed.

## Static properties

- {{jsxref("TypedArray.BYTES_PER_ELEMENT")}}
  - : Returns a number value of the element size for the different `TypedArray`
    objects.
- {{jsxref("TypedArray.name")}}
  - : Returns the string value of the constructor name (e.g, "`Int8Array`").
- {{jsxref("TypedArray.@@species", "get TypedArray[@@species]")}}
  - : The constructor function used to create derived objects.
- {{jsxref("TypedArray.prototype")}}
  - : Prototype for `TypedArray` objects.

## Static methods

- {{jsxref("TypedArray.from()")}}
  - : Creates a new `TypedArray` from an array-like or iterable object. See also
    {{jsxref("Array.from()")}}.
- {{jsxref("TypedArray.of()")}}
  - : Creates a new `TypedArray` with a variable number of arguments. See also
    {{jsxref("Array.of()")}}.

## Instance properties

- {{jsxref("TypedArray.prototype.buffer")}}
  - : Returns the {{jsxref("ArrayBuffer")}} referenced by the typed
    array. Fixed at construction time and thus **read only**.
- {{jsxref("TypedArray.prototype.byteLength")}}
  - : Returns the length (in bytes) of the typed array. Fixed at construction
    time and thus **read only.**
- {{jsxref("TypedArray.prototype.byteOffset")}}
  - : Returns the offset (in bytes) of the typed array from the start of its
    {{jsxref("ArrayBuffer")}}. Fixed at construction time and thus **read
    only.**
- {{jsxref("TypedArray.prototype.length")}}
  - : Returns the number of elements held in the typed array. Fixed at
    construction time and thus **read only.**

## Instance methods

- {{jsxref("TypedArray.prototype.at()")}}
  - : Takes an integer value and returns the item at that index. This method
    allows for negative integers, which count back from the last item.
- {{jsxref("TypedArray.prototype.copyWithin()")}}
  - : Copies a sequence of array elements within the array. See also
    {{jsxref("Array.prototype.copyWithin()")}}.
- {{jsxref("TypedArray.prototype.entries()")}}
  - : Returns a new array iterator object that contains the key/value pairs for
    each index in the array. See also
    {{jsxref("Array.prototype.entries()")}}.
- {{jsxref("TypedArray.prototype.every()")}}
  - : Tests whether all elements in the array pass the test provided by a
    function. See also {{jsxref("Array.prototype.every()")}}.
- {{jsxref("TypedArray.prototype.fill()")}}
  - : Fills all the elements of an array from a start index to an end index with
    a static value. See also {{jsxref("Array.prototype.fill()")}}.
- {{jsxref("TypedArray.prototype.filter()")}}
  - : Creates a new array with all of the elements of this array for which the
    provided filtering function returns `true`. See also
    {{jsxref("Array.prototype.filter()")}}.
- {{jsxref("TypedArray.prototype.find()")}}
  - : Returns the found value in the array, if an element in the array satisfies
    the provided testing function, or `undefined` if not found. See also
    {{jsxref("Array.prototype.find()")}}.
- {{jsxref("TypedArray.prototype.findIndex()")}}
  - : Returns the found index in the array, if an element in the array satisfies
    the provided testing function or `-1` if not found. See also
    {{jsxref("Array.prototype.findIndex()")}}.
- {{jsxref("TypedArray.prototype.forEach()")}}
  - : Calls a function for each element in the array. See also
    {{jsxref("Array.prototype.forEach()")}}.
- {{jsxref("TypedArray.prototype.includes()")}}
  - : Determines whether a typed array includes a certain element, returning
    `true` or `false` as appropriate. See also
    {{jsxref("Array.prototype.includes()")}}.
- {{jsxref("TypedArray.prototype.indexOf()")}}
  - : Returns the first (least) index of an element within the array equal to
    the specified value, or `-1` if none is found. See also
    {{jsxref("Array.prototype.indexOf()")}}.
- {{jsxref("TypedArray.prototype.join()")}}
  - : Joins all elements of an array into a string. See also
    {{jsxref("Array.prototype.join()")}}.
- {{jsxref("TypedArray.prototype.keys()")}}
  - : Returns a new array iterator that contains the keys for each index in the
    array. See also {{jsxref("Array.prototype.keys()")}}.
- {{jsxref("TypedArray.prototype.lastIndexOf()")}}
  - : Returns the last (greatest) index of an element within the array equal to
    the specified value, or `-1` if none is found. See also
    {{jsxref("Array.prototype.lastIndexOf()")}}.
- {{jsxref("TypedArray.prototype.map()")}}
  - : Creates a new array with the results of calling a provided function on
    every element in this array. See also
    {{jsxref("Array.prototype.map()")}}.
- {{jsxref("TypedArray.prototype.reduce()")}}
  - : Apply a function against an accumulator and each value of the array (from
    left-to-right) as to reduce it to a single value. See also
    {{jsxref("Array.prototype.reduce()")}}.
- {{jsxref("TypedArray.prototype.reduceRight()")}}
  - : Apply a function against an accumulator and each value of the array (from
    right-to-left) as to reduce it to a single value. See also
    {{jsxref("Array.prototype.reduceRight()")}}.
- {{jsxref("TypedArray.prototype.reverse()")}}
  - : Reverses the order of the elements of an array — the first becomes the
    last, and the last becomes the first. See also
    {{jsxref("Array.prototype.reverse()")}}.
- {{jsxref("TypedArray.prototype.set()")}}
  - : Stores multiple values in the typed array, reading input values from a
    specified array.
- {{jsxref("TypedArray.prototype.slice()")}}
  - : Extracts a section of an array and returns a new array. See also
    {{jsxref("Array.prototype.slice()")}}.
- {{jsxref("TypedArray.prototype.some()")}}
  - : Returns `true` if at least one element in this array satisfies the
    provided testing function. See also
    {{jsxref("Array.prototype.some()")}}.
- {{jsxref("TypedArray.prototype.sort()")}}
  - : Sorts the elements of an array in place and returns the array. See also
    {{jsxref("Array.prototype.sort()")}}.
- {{jsxref("TypedArray.prototype.subarray()")}}
  - : Returns a new `TypedArray` from the given start and end element index.
- {{jsxref("TypedArray.prototype.values()")}}
  - : Returns a new array iterator object that contains the values for each
    index in the array. See also
    {{jsxref("Array.prototype.values()")}}.
- {{jsxref("TypedArray.prototype.toLocaleString()")}}
  - : Returns a localized string representing the array and its elements. See
    also {{jsxref("Array.prototype.toLocaleString()")}}.
- {{jsxref("TypedArray.prototype.toString()")}}
  - : Returns a string representing the array and its elements. See also
    {{jsxref("Array.prototype.toString()")}}.
- {{jsxref("TypedArray.prototype.@@iterator()",
    "TypedArray.prototype[@@iterator]()")}}
  - : Returns a new array iterator object that contains the values for each
    index in the array.

## Examples

### New is required

Starting with ECMAScript 2015, `TypedArray` constructors must be constructed
with the {{jsxref("Operators/new", "new")}} operator. Calling a
`TypedArray` constructor as a function without `new` will throw a
{{jsxref("TypeError")}}.

```js example-bad
var dv = Int8Array([1, 2, 3]);
// TypeError: calling a builtin Int8Array constructor
// without new is forbidden
```

```js example-good
var dv = new Int8Array([1, 2, 3]);
```

### Property access

You can reference elements in the array using standard array index syntax (that
is, using bracket notation). However, getting or setting indexed properties on
typed arrays will not search in the prototype chain for this property, even when
the indices are out of bound. Indexed properties will consult the
{{jsxref("ArrayBuffer")}} and will never look at object properties. You
can still use named properties, just like with all objects.

```js
// Setting and getting using standard array syntax
var int16 = new Int16Array(2);
int16[0] = 42;
console.log(int16[0]); // 42

// Indexed properties on prototypes are not consulted (Fx 25)
Int8Array.prototype[20] = 'foo';
(new Int8Array(32))[20]; // 0
// even when out of bound
Int8Array.prototype[20] = 'foo';
(new Int8Array(8))[20]; // undefined
// or with negative integers
Int8Array.prototype[-1] = 'foo';
(new Int8Array(8))[-1]; // undefined

// Named properties are allowed, though (Fx 30)
Int8Array.prototype.foo = 'bar';
(new Int8Array(32)).foo; // "bar"
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- A polyfill of typed arrays is available in
  [`core-js`](https://github.com/zloirock/core-js#ecmascript-typed-arrays)
- [JavaScript typed arrays](/en-US/docs/Web/JavaScript/Typed_arrays)
- {{jsxref("ArrayBuffer")}}
- {{jsxref("DataView")}}
- [TextDecoder](/en-US/docs/Web/API/TextDecoder) — Helper that decode strings
  from numerical data
