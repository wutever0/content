---
title: String.prototype.slice()
slug: Web/JavaScript/Reference/Global_Objects/String/slice
tags:
- JavaScript
- Method
- Prototype
- Reference
- String
browser-compat: javascript.builtins.String.slice
---
{{JSRef}}

The **`slice()`** method extracts a section of a string and returns it as a new
string, without modifying the original string.

{{EmbedInteractiveExample("pages/js/string-slice.html", "taller")}}

## Syntax

```js
slice(beginIndex)
slice(beginIndex, endIndex)
```

### Parameters

- `beginIndex`

  - : The zero-based index at which to begin extraction. If negative, it is
    treated as <code><var>str</var>.length + <var>beginIndex</var></code>. (For
    example, if `beginIndex` is `-3`, it is treated as
    <code><var>str</var>.length - 3</code>.) If `beginIndex` is not a number
    after
    {{jsxref('Number', 'Number(<var>beginIndex</var>)')}}, it
    is treated as `0`.

    If `beginIndex` is greater than or equal to
    <code><var>str</var>.length</code>, an empty string is returned.

- `endIndex` {{optional_inline}}

  - : The zero-based index _before_ which to end extraction. The character at
    this index will not be included.

    If `endIndex` is omitted or undefined, or greater than
    <code><var>str</var>.length</code>, `slice()` extracts to the end of the
    string. If negative, it is treated as <code><var>str</var>.length +
    <var>endIndex</var></code>. (For example, if `endIndex` is `-3`, it is
    treated as <code><var>str</var>.length - 3</code>.) If it is not undefined,
    and <code>Number(<var>endIndex</var>)</code> is not positive, an empty
    string is returned.

    If `endIndex` is specified, `endIndex` should be greater than `beginIndex`,
    otherwise an empty string is returned. (For example, `slice(-3, 0)`,
    `slice(-1, -3)`, or `slice(3, 1)` returns `""`.)

### Return value

A new string containing the extracted section of the string.

## Description

`slice()` extracts the text from one string and returns a new string. Changes to
the text in one string do not affect the other string.

`slice()` extracts up to but not including `endIndex`.
<code><var>str</var>.slice(1, 4)</code> extracts the second character through
the fourth character (characters indexed `1`, `2`, and `3`).

As an example, <code><var>str</var>.slice(2, -1)</code> extracts the third
character through the second to last character in the string.

## Examples

### Using `slice()` to create a new string

The following example uses `slice()` to create a new string.

```js
let str1 = 'The morning is upon us.', // the length of str1 is 23.
    str2 = str1.slice(1, 8),
    str3 = str1.slice(4, -2),
    str4 = str1.slice(12),
    str5 = str1.slice(30);
console.log(str2)  // OUTPUT: he morn
console.log(str3)  // OUTPUT: morning is upon u
console.log(str4)  // OUTPUT: is upon us.
console.log(str5)  // OUTPUT: ""
```

### Using `slice()` with negative indexes

The following example uses `slice()` with negative indexes.

```js
let str = 'The morning is upon us.'
str.slice(-3)      // returns 'us.'
str.slice(-3, -1)  // returns 'us'
str.slice(0, -1)   // returns 'The morning is upon us'
```

This example counts backwards from the end of the string by `11` to find the
start index and forwards from the start of the string by `16` to find the end
index.

```js
console.log(str.slice(-11, 16)) // => "is u"
```

Here it counts forwards from the start by `11` to find the start index and
backwards from the end by `7` to find the end index.

```js
console.log(str.slice(11, -7)) // => " is u"
```

These arguments count backwards from the end by `5` to find the start index and
backwards from the end by `1` to find the end index.

```js
console.log(str.slice(-5, -1)) // => "n us"
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- {{jsxref("String.prototype.substr()")}}
- {{jsxref("String.prototype.substring()")}}
- {{jsxref("Array.prototype.slice()")}}
