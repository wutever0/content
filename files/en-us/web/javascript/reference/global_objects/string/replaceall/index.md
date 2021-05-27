---
title: String.prototype.replaceAll()
slug: Web/JavaScript/Reference/Global_Objects/String/replaceAll
tags:
- JavaScript
- Method
- Prototype
- Reference
- String
- regex
- Polyfill
browser-compat: javascript.builtins.String.replaceAll
---
{{JSRef}}

The **`replaceAll()`** method returns a new string with all matches of a
`pattern` replaced by a `replacement`. The `pattern` can be a string or a
{{jsxref("RegExp")}}, and the `replacement` can be a string or a
function to be called for each match.

The original string is left unchanged.

{{EmbedInteractiveExample("pages/js/string-replaceall.html")}}

## Syntax

```js
replaceAll(regexp, newSubstr)
replaceAll(regexp, replacerFunction)

replaceAll(substr, newSubstr)
replaceAll(substr, replacerFunction)
```

> **Note:** When using a \`<var>regexp</var>\` you have to set the global ("g")
> flag; otherwise, it will throw a `TypeError`: "replaceAll must be called with
> a global RegExp".

### Parameters

- `regexp` (pattern)
  - : A {{jsxref("RegExp")}} object or literal with the global flag. The
    matches are replaced with `newSubstr` or the value returned by the specified
    `replacerFunction`. A RegExp without the global ("g") flag will throw a
    `TypeError`: "replaceAll must be called with a global RegExp".
- `substr`
  - : A {{jsxref("String")}} that is to be replaced by `newSubstr`. It
    is treated as a literal string and is _not_ interpreted as a regular
    expression.
- `newSubstr` (replacement)
  - : The {{jsxref("String")}} that replaces the substring specified by
    the specified `regexp` or `substr` parameter. A number of special
    replacement patterns are supported; see the
    "[Specifying a string as a parameter](#Specifying_a_string_as_a_parameter)"
    section below.
- `replacerFunction` (replacement)
  - : A function to be invoked to create the new substring to be used to replace
    the matches to the given `regexp` or `substr`. The arguments supplied to
    this function are described in the
    "[Specifying a function as a parameter](#Specifying_a_function_as_a_parameter)"
    section below.

### Return value

A new string, with all matches of a pattern replaced by a replacement.

## Description

This method does not change the calling {{jsxref("String")}} object. It
returns a new string.

### Specifying a string as a parameter

The replacement string can include the following special replacement patterns:

<table class="standard-table"><thead><tr><th class="header" scope="col">Pattern</th><th class="header" scope="col">Inserts</th></tr></thead><tbody><tr><td><code>$$</code></td><td>Inserts a <code>"$"</code>.</td></tr><tr><td><code>$&#x26;</code></td><td>Inserts the matched substring.</td></tr><tr><td><code>$`</code></td><td>Inserts the portion of the string that precedes the matched substring.</td></tr><tr><td><code>$'</code></td><td>Inserts the portion of the string that follows the matched substring.</td></tr><tr><td><code>$<var>n</var></code></td><td>Where <code><var>n</var></code> is a positive integer less than 100, inserts the
<code><var>n</var></code>th parenthesized submatch string, provided the first
argument was a {{jsxref("RegExp")}} object. Note that this is
<code>1</code>-indexed.</td></tr></tbody></table>

### Specifying a function as a parameter

You can specify a function as the second parameter. In this case, the function
will be invoked after the match has been performed. The function's result
(return value) will be used as the replacement string. (**Note:** The
above-mentioned special replacement patterns do _not_ apply in this case.)

Note that if the first argument of an `replaceAll()` invocation is a
{{jsxref("RegExp")}} object or regular expression literal, the function
will be invoked multiple times.

The arguments to the function are as follows:

<table class="standard-table"><thead><tr><th class="header" scope="col">Possible name</th><th class="header" scope="col">Supplied value</th></tr></thead><tbody><tr><td><code>match</code></td><td>The matched substring. (Corresponds to <code>$&#x26;</code> above.)</td></tr><tr><td><code>p1, p2, ...</code></td><td>The <var>n</var>th string found by a parenthesized capture group, provided the
first argument to <code>replaceAll()</code> was a {{jsxref("RegExp")}} object.
(Corresponds to <code>$1</code>, <code>$2</code>, etc. above.) For example,
if <code>/(\a+)(\b+)/</code>, was given, <code>p1</code> is the match for
<code>\a+</code>, and <code>p2</code> for <code>\b+</code>.</td></tr><tr><td><code>offset</code></td><td>The offset of the matched substring within the whole string being examined. (For
example, if the whole string was <code>'abcd'</code>, and the matched substring
was <code>'bc'</code>, then this argument will be <code>1</code>.)</td></tr><tr><td><code>string</code></td><td>The whole string being examined.</td></tr></tbody></table>

(The exact number of arguments depends on whether the first argument is a
{{jsxref("RegExp")}} object—and, if so, how many parenthesized
submatches it specifies.)

## Examples

### Using replaceAll

```js
'aabbcc'.replaceAll('b', '.');
// 'aa..cc'
```

### Non-global regex throws

When using a regular expression search value, it must be global. This won't
work:

```js example-bad
'aabbcc'.replaceAll(/b/, '.');
TypeError: replaceAll must be called with a global RegExp
```

This will work:

```js example-good
'aabbcc'.replaceAll(/b/g, '.');
"aa..cc"
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- A polyfill of `String.prototype.replaceAll` is available in
  [`core-js`](https://github.com/zloirock/core-js#ecmascript-string-and-regexp)
- {{jsxref("String.prototype.replace", "String.prototype.replace()")}}
- {{jsxref("String.prototype.match", "String.prototype.match()")}}
- {{jsxref("RegExp.prototype.exec", "RegExp.prototype.exec()")}}
- {{jsxref("RegExp.prototype.test", "RegExp.prototype.test()")}}
