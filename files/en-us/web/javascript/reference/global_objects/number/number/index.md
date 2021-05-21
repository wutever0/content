---
title: Number() constructor
slug: Web/JavaScript/Reference/Global_Objects/Number/Number
tags:
  - Constructor
  - JavaScript
  - Number
  - Reference
browser-compat: javascript.builtins.Number.Number
---
{{JSRef}}

The **`Number()` constructor** creates a {{jsxref("Number")}} object.

## Syntax

<pre class="brush: js">
new Number(<var>value</var>)
</pre>

### Parameters

- `value`
  - : The numeric value of the object being created.

## Examples

### Creating Number objects

```js
const a = new Number('123'); // a === 123 is false
const b = Number('123');     // b === 123 is true
a instanceof Number;         // is true
b instanceof Number;         // is false
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- {{jsxref("NaN")}}
- The {{jsxref("Math")}} global object
- Integers with arbitrary precision: {{jsxref("BigInt")}}
