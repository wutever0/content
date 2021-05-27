---
title: Standard built-in objects
slug: Web/JavaScript/Reference/Global_Objects
tags:
  - JavaScript
  - Landing page
  - Overview
  - Reference
---
{{JSSidebar("Objects")}}

This chapter documents all of JavaScript's standard, built-in objects, including
their methods and properties.

The term "global objects" (or standard built-in objects) here is not to be
confused with **the global object**. Here, "global objects" refer to **objects
in the global scope**.

The **global object** itself can be accessed using the
{{JSxRef("Operators/this", "this")}} operator in the global scope.
In fact, the global scope **consists of** the properties of the global object,
including inherited properties, if any.

Other objects in the global scope are either
[created by the user script](/en-US/docs/Web/JavaScript/Guide/Working_with_Objects#creating_new_objects)
or provided by the host application. The host objects available in browser
contexts are documented in the [API reference](/en-US/docs/Web/API).

For more information about the distinction between the
[DOM](/en-US/docs/Web/API/Document_Object_Model) and core
[JavaScript](/en-US/docs/Web/JavaScript), see
[JavaScript technologies overview](/en-US/docs/Web/JavaScript/JavaScript_technologies_overview).

## Standard objects by category

### Value properties

These global properties return a simple value. They have no properties or
methods.

- {{JSxRef("Infinity")}}
- {{JSxRef("NaN")}}
- {{JSxRef("undefined")}}
- {{JSxRef("globalThis")}}

### Function properties

These global functions—functions which are called globally, rather than on an
object—directly return their results to the caller.

<div class="twocolumns"><ul><li>{{JSxRef("Global_Objects/eval", "eval()")}}</li><li>{{Non-Standard_Inline}} {{JSxRef("Global_Objects/uneval", "uneval()")}} </li><li>{{JSxRef("Global_Objects/isFinite", "isFinite()")}}</li><li>{{JSxRef("Global_Objects/isNaN", "isNaN()")}}</li><li>{{JSxRef("Global_Objects/parseFloat", "parseFloat()")}}</li><li>{{JSxRef("Global_Objects/parseInt", "parseInt()")}}</li><li>{{JSxRef("Global_Objects/encodeURI", "encodeURI()")}}</li><li>{{JSxRef("Global_Objects/encodeURIComponent", "encodeURIComponent()")}}</li><li>{{JSxRef("Global_Objects/decodeURI", "decodeURI()")}}</li><li>{{JSxRef("Global_Objects/decodeURIComponent", "decodeURIComponent()")}}</li><li><strong>Deprecated</strong><ul><li>{{Deprecated_Inline}} {{JSxRef("Global_Objects/escape", "escape()")}}</li><li>{{Deprecated_Inline}} {{JSxRef("Global_Objects/unescape", "unescape()")}}</li></ul></li></ul></div>

### Fundamental objects

These are the fundamental, basic objects upon which all other objects are based.
This includes general objects, booleans, functions, and symbols.

- {{JSxRef("Object")}}
- {{JSxRef("Function")}}
- {{JSxRef("Boolean")}}
- {{JSxRef("Symbol")}}

### Error objects

Error objects are a special type of fundamental object. They include the basic
{{JSxRef("Error")}} type, as well as several specialized error types.

<div class="twocolumns"><ul><li>{{JSxRef("Error")}}</li><li>{{JSxRef("AggregateError")}} </li><li>{{JSxRef("EvalError")}}</li><li>{{JSxRef("InternalError")}}</li><li>{{JSxRef("RangeError")}}</li><li>{{JSxRef("ReferenceError")}}</li><li>{{JSxRef("SyntaxError")}}</li><li>{{JSxRef("TypeError")}}</li><li>{{JSxRef("URIError")}}</li></ul></div>

### Numbers and dates

These are the base objects representing numbers, dates, and mathematical
calculations.

- {{JSxRef("Number")}}
- {{JSxRef("BigInt")}}
- {{JSxRef("Math")}}
- {{JSxRef("Date")}}

### Text processing

These objects represent strings and support manipulating them.

- {{JSxRef("String")}}
- {{JSxRef("RegExp")}}

### Indexed collections

These objects represent collections of data which are ordered by an index value.
This includes (typed) arrays and array-like constructs.

<div class="twocolumns"><ul><li>{{JSxRef("Array")}}</li><li>{{JSxRef("Int8Array")}}</li><li>{{JSxRef("Uint8Array")}}</li><li>{{JSxRef("Uint8ClampedArray")}}</li><li>{{JSxRef("Int16Array")}}</li><li>{{JSxRef("Uint16Array")}}</li><li>{{JSxRef("Int32Array")}}</li><li>{{JSxRef("Uint32Array")}}</li><li>{{JSxRef("Float32Array")}}</li><li>{{JSxRef("Float64Array")}}</li><li>{{JSxRef("BigInt64Array")}}</li><li>{{JSxRef("BigUint64Array")}}</li></ul></div>

### Keyed collections

These objects represent collections which use keys. The iterable collections
({{JSxRef("Map")}} and {{JSxRef("Set")}}) contain elements which
are easily iterated in the order of insertion.

- {{JSxRef("Map")}}
- {{JSxRef("Set")}}
- {{JSxRef("WeakMap")}}
- {{JSxRef("WeakSet")}}

### Structured data

These objects represent and interact with structured data buffers and data coded
using JavaScript Object Notation (JSON).

- {{JSxRef("ArrayBuffer")}}
- {{JSxRef("SharedArrayBuffer")}}
- {{JSxRef("Atomics")}}
- {{JSxRef("DataView")}}
- {{JSxRef("JSON")}}

### Control abstraction objects

Control abstractions can help to structure code, especially async code (without
using deeply nested callbacks, for example).

- {{JSxRef("Promise")}}
- {{JSxRef("Generator")}}
- {{JSxRef("GeneratorFunction")}}
- {{JSxRef("AsyncFunction")}}
- {{JSxRef("Global_Objects/AsyncGenerator", "AsyncGenerator")}}
- {{JSxRef("Global_Objects/AsyncGeneratorFunction", "AsyncGeneratorFunction")}}

### Reflection

- {{JSxRef("Reflect")}}
- {{JSxRef("Proxy")}}

### Internationalization

Additions to the ECMAScript core for language-sensitive functionalities.

<div class="twocolumns"><ul><li>{{JSxRef("Intl")}}</li><li>{{JSxRef("Global_Objects/Intl/Collator", "Intl.Collator")}}</li><li>{{JSxRef("Global_Objects/Intl/DateTimeFormat", "Intl.DateTimeFormat")}}</li><li>{{JSxRef("Global_Objects/Intl/ListFormat", "Intl.ListFormat")}}</li><li>{{JSxRef("Global_Objects/Intl/NumberFormat", "Intl.NumberFormat")}}</li><li>{{JSxRef("Global_Objects/Intl/PluralRules", "Intl.PluralRules")}}</li><li>{{JSxRef("Global_Objects/Intl/RelativeTimeFormat", "Intl.RelativeTimeFormat")}}</li><li>{{JSxRef("Global_Objects/Intl/Locale", "Intl.Locale")}}</li></ul></div>

### WebAssembly

<div class="twocolumns"><ul><li>{{JSxRef("WebAssembly")}}</li><li>{{JSxRef("WebAssembly.Module")}}</li><li>{{JSxRef("WebAssembly.Instance")}}</li><li>{{JSxRef("WebAssembly.Memory")}}</li><li>{{JSxRef("WebAssembly.Table")}}</li><li>{{JSxRef("WebAssembly.CompileError")}}</li><li>{{JSxRef("WebAssembly.LinkError")}}</li><li>{{JSxRef("WebAssembly.RuntimeError")}}</li></ul></div>

### Other

- {{JSxRef("Functions/arguments", "arguments")}}
