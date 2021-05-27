---
title: JSON
slug: Web/JavaScript/Reference/Global_Objects/JSON
tags:
  - JSON
  - JavaScript
  - Namespace
  - Object
  - Reference
browser-compat: javascript.builtins.JSON
---
{{JSRef}}

<span class="seoSummary">The <strong><code>JSON</code></strong> object contains
methods for parsing <a href="https://json.org/">JavaScript Object Notation</a>
({{glossary("JSON")}}) and converting values to JSON. It can't be called
or constructed, and aside from its two method properties, it has no interesting
functionality of its own.</span>

## Description

### JavaScript and JSON differences

JSON is a syntax for serializing objects, arrays, numbers, strings, booleans,
and {{jsxref("null")}}. It is based upon JavaScript syntax but is distinct
from it: some JavaScript is _not_ JSON.

- **Objects and Arrays**
  - : Property names must be double-quoted strings;
    [trailing commas](/en-US/docs/Web/JavaScript/Reference/Trailing_commas) are
    forbidden.
- **Numbers**
  - : Leading zeros are prohibited. A decimal point must be followed by at least
    one digit. `NaN` and `Infinity` are unsupported.
- **Any JSON text is a valid JavaScript expression...**
  - : ...But only in JavaScript engines that have implemented the
    [proposal to make all JSON text valid ECMA-262](https://github.com/tc39/proposal-json-superset).
    In engines that haven't implemented the proposal, U+2028 LINE SEPARATOR and
    U+2029 PARAGRAPH SEPARATOR are allowed in string literals and property keys
    in JSON; but their use in these features in JavaScript string literals is a
    {{jsxref("SyntaxError")}}.

Consider this example where {{jsxref("JSON.parse()")}} parses the
string as JSON and {{jsxref("Global_Objects/eval")}} executes the
string as JavaScript:

```js
let code = '"\u2028\u2029"'
JSON.parse(code)  // evaluates to "\u2028\u2029" in all engines
eval(code)        // throws a SyntaxError in old engines
```

Other differences include allowing only double-quoted strings and having no
provisions for {{jsxref("undefined")}} or comments. For those who wish
to use a more human-friendly configuration format based on JSON, there is
[JSON5](https://json5.org/), used by the Babel compiler, and the more commonly
used [YAML](https://en.wikipedia.org/wiki/YAML).

### Full JSON syntax

The full JSON syntax is as follows:

<pre class="brush: js"><var>JSON</var> = <strong>null</strong>
    <em>or</em> <strong>true</strong> <em>or</em> <strong>false</strong>
    <em>or</em> <var>JSONNumber</var>
    <em>or</em> <var>JSONString</var>
    <em>or</em> <var>JSONObject</var>
    <em>or</em> <var>JSONArray</var>

<var>JSONNumber</var> = <strong>-</strong> <var>PositiveNumber</var>
          <em>or</em> <var>PositiveNumber</var>
<var>PositiveNumber</var> = DecimalNumber
              <em>or</em> <var>DecimalNumber</var> <strong>.</strong> <var>Digits</var>
              <em>or</em> <var>DecimalNumber</var> <strong>.</strong> <var>Digits</var> <var>ExponentPart</var>
              <em>or</em> <var>DecimalNumber</var> <var>ExponentPart</var>
<var>DecimalNumber</var> = <strong>0</strong>
             <em>or</em> <var>OneToNine</var> <var>Digits</var>
<var>ExponentPart</var> = <strong>e</strong> <var>Exponent</var>
            <em>or</em> <strong>E</strong> <var>Exponent</var>
<var>Exponent</var> = <var>Digits</var>
        <em>or</em> <strong>+</strong> <var>Digits</var>
        <em>or</em> <strong>-</strong> <var>Digits</var>
<var>Digits</var> = <var>Digit</var>
      <em>or</em> <var>Digits</var> <var>Digit</var>
<var>Digit</var> = <strong>0</strong> through <strong>9</strong>
<var>OneToNine</var> = <strong>1</strong> through <strong>9</strong>

<var>JSONString</var> = <strong>""</strong>
          <em>or</em> <strong>"</strong> <var>StringCharacters</var> <strong>"</strong>
<var>StringCharacters</var> = <var>StringCharacter</var>
                <em>or</em> <var>StringCharacters</var> <var>StringCharacter</var>
<var>StringCharacter</var> = any character
                  <em>except</em> <strong>"</strong> <em>or</em> <strong>\</strong> <em>or</em> U+0000 through U+001F
               <em>or</em> <var>EscapeSequence</var>
<var>EscapeSequence</var> = <strong>\"</strong> <em>or</em> <strong>\/</strong> <em>or</em> <strong>\\</strong> <em>or</em> <strong>\b</strong> <em>or</em> <strong>\f</strong> <em>or</em> <strong>\n</strong> <em>or</em> <strong>\r</strong> <em>or</em> <strong>\t</strong>
              <em>or</em> <strong>\u</strong> <var>HexDigit</var> <var>HexDigit</var> <var>HexDigit</var> <var>HexDigit</var>
<var>HexDigit</var> = <strong>0</strong> through <strong>9</strong>
        <em>or</em> <strong>A</strong> through <strong>F</strong>
        <em>or</em> <strong>a</strong> through <strong>f</strong>

<var>JSONObject</var> = <strong>{</strong> <strong>}</strong>
          <em>or</em> <strong>{</strong> <var>Members</var> <strong>}</strong>
<var>Members</var> = <var>JSONString</var> <strong>:</strong> <var>JSON</var>
       <em>or</em> <var>Members</var> <strong>,</strong> <var>JSONString</var> <strong>:</strong> <var>JSON</var>

<var>JSONArray</var> = <strong>[</strong> <strong>]</strong>
         <em>or</em> <strong>[</strong> <var>ArrayElements</var> <strong>]</strong>
<var>ArrayElements</var> = <var>JSON</var>
             <em>or</em> <var>ArrayElements</var> <strong>,</strong> <var>JSON</var>
</pre>

Insignificant {{glossary("whitespace")}} may be present anywhere
except within a `JSONNumber` (numbers must contain no whitespace) or
`JSONString` (where it is interpreted as the corresponding character in the
string, or would cause an error). The tab character
([U+0009](http://unicode-table.com/en/0009/)), carriage return
([U+000D](http://unicode-table.com/en/000D/)), line feed
([U+000A](http://unicode-table.com/en/000A/)), and space
([U+0020](http://unicode-table.com/en/0020/)) characters are the only valid
whitespace characters.

## Static methods

- {{jsxref("JSON.parse()", "JSON.parse(<var>text</var>[, <var>reviver</var>])")}}
  - : Parse the string `text` as JSON, optionally transform the produced value
    and its properties, and return the value. Any violations of the JSON syntax,
    including those pertaining to the differences between JavaScript and JSON,
    cause a {{jsxref("SyntaxError")}} to be thrown. The `reviver` option
    allows for interpreting what the `replacer` has used to stand in for other
    datatypes.
- {{jsxref("JSON.stringify()", "JSON.stringify(<var>value</var>[,
    <var>replacer</var>[, <var>space</var>]])")}}
  - : Return a JSON string corresponding to the specified value, optionally
    including only certain properties or replacing property values in a
    user-defined manner. By default, all instances of
    {{jsxref("undefined")}} are replaced with {{jsxref("null")}},
    and other unsupported native data types are censored. The `replacer` option
    allows for specifying other behavior.

## Examples

### Example JSON

```json
{
  "browsers": {
    "firefox": {
      "name": "Firefox",
      "pref_url": "about:config",
      "releases": {
        "1": {
          "release_date": "2004-11-09",
          "status": "retired",
          "engine": "Gecko",
          "engine_version": "1.7"
        }
      }
    }
  }
}
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- {{jsxref("Date.prototype.toJSON()")}}
- [JSON Diff](http://www.jsondiff.com/) checker
- [JSON Beautifier/editor](http://jsonbeautifier.org/)
- [JSON Parser](http://jsonparser.org/)
- [JSON Validator](https://tools.learningcontainer.com/json-validator/)
