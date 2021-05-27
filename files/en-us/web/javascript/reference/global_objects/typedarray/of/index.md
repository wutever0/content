---
title: TypedArray.of()
slug: Web/JavaScript/Reference/Global_Objects/TypedArray/of
tags:
- ECMAScript 2015
- JavaScript
- Method
- TypedArray
- TypedArrays
- Polyfill
browser-compat: javascript.builtins.TypedArray.of
---
{{JSRef}}

The **<code><var>TypedArray</var>.of()</code>** method creates a new
[typed array](/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray#TypedArray_objects)
from a variable number of arguments. This method is nearly the same as
{{jsxref("Array.of()")}}.

{{EmbedInteractiveExample("pages/js/typedarray-of.html","shorter")}}

## Syntax

```js
TypedArray.of(element0)
TypedArray.of(element0, element1)
TypedArray.of(element0, element1, ... , elementN)
```

Where `TypedArray` is one of:

<div class="threecolumns"><ul><li>{{jsxref("Int8Array")}}</li><li>{{jsxref("Uint8Array")}}</li><li>{{jsxref("Uint8ClampedArray")}}</li><li>{{jsxref("Int16Array")}}</li><li>{{jsxref("Uint16Array")}}</li><li>{{jsxref("Int32Array")}}</li><li>{{jsxref("Uint32Array")}}</li><li>{{jsxref("Float32Array")}}</li><li>{{jsxref("Float64Array")}}</li><li>{{jsxref("BigInt64Array")}}</li><li>{{jsxref("BigUint64Array")}}</li></ul></div>

### Parameters

- <code><var>element<var>N</var></var></code>
  - : Elements of which to create the typed array.

### Return value

A new {{jsxref("TypedArray")}} instance.

## Description

Some subtle distinctions between {{jsxref("Array.of()")}} and
<code><var>TypedArray</var>.of()</code>:

- If the `this` value passed to

  <code><var>TypedArray</var>.of()</code>

  is not a constructor,

  <code><var>TypedArray</var>.of()</code>

  will throw a {{jsxref("TypeError")}}, where `Array.of()` defaults to
  creating a new {{jsxref("Array")}}.

- <code><var>TypedArray</var>.of()</code>

  uses `[[Put]]` where `Array.of()` uses `[[DefineProperty]]`. Hence, when
  working with {{jsxref("Proxy")}} objects, it calls
  {{jsxref("Global_Objects/Proxy/handler/set",
    "handler.set")}}
  to create new elements rather than
  {{jsxref("Global_Objects/Proxy/handler/defineProperty", "handler.defineProperty()")}}.

## Examples

### Using of()

```js
Uint8Array.of(1);            // Uint8Array [ 1 ]
Int8Array.of('1', '2', '3'); // Int8Array [ 1, 2, 3 ]
Float32Array.of(1, 2, 3);    // Float32Array [ 1, 2, 3 ]
Int16Array.of(undefined);    // Int16Array [ 0 ]
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- A polyfill of `TypedArray.of` is available in
  [`core-js`](https://github.com/zloirock/core-js#ecmascript-typed-arrays)
- {{jsxref("TypedArray.from()")}}
- {{jsxref("Array.of()")}}
