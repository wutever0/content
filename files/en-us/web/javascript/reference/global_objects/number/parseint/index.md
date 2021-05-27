---
title: Number.parseInt()
slug: Web/JavaScript/Reference/Global_Objects/Number/parseInt
tags:
- ECMAScript 2015
- JavaScript
- Method
- Number
- Polyfill
browser-compat: javascript.builtins.Number.parseInt
---
{{JSRef}}

The **`Number.parseInt()`** method parses a string argument and returns an
integer of the specified radix or base.

{{EmbedInteractiveExample("pages/js/number-parseint.html", "taller")}}

## Syntax

```js
Number.parseInt(string)
Number.parseInt(string, radix)
```

### Parameters

<dl><dt><code><var>string</var></code></dt><dd>The value to parse. If this argument is not a string, then it is converted to one
using the <code><a href="https://tc39.es/ecma262/#sec-tostring">ToString</a></code>
abstract operation. Leading whitespace in this argument is ignored.</dd><dt><code><var>radix</var></code><var> {{optional_inline}}</var></dt><dd>An integer between <code>2</code> and <code>36</code> that represents the
<em>radix</em> (the base in mathematical numeral systems) of the
<code><var>string</var></code>.<p>If <code>radix</code> is undefined or <code>0</code>, it is assumed to be <code>10</code> except when the number begins with the code unit pairs <code>0x</code> or <code>0X</code>, in which case a radix of <code>16</code> is assumed.</p></dd></dl>

### Return value

An integer parsed from the given `string`.

If the `radix` is smaller than `2` or bigger than `36`, and the first
non-whitespace character cannot be converted to a number,
{{jsxref("NaN")}} is returned.

## Polyfill

```js
if (Number.parseInt === undefined) {
    Number.parseInt = window.parseInt
}
```

## Examples

### Number.parseInt vs parseInt

This method has the same functionality as the global
{{jsxref("parseInt",
  "parseInt()")}} function:

```js
Number.parseInt === parseInt // true
```

and is part of ECMAScript 2015 (its purpose is modularization of globals).
Please see {{jsxref("parseInt", "parseInt()")}} for more detail and
examples.

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- A polyfill of `Number.parseInt` is available in
  [`core-js`](https://github.com/zloirock/core-js#ecmascript-number)
- The {{jsxref("Number")}} object it belongs to.
- The global {{jsxref("parseInt", "parseInt()")}} method.
