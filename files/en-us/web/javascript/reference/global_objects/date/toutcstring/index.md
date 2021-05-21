---
title: Date.prototype.toUTCString()
slug: Web/JavaScript/Reference/Global_Objects/Date/toUTCString
tags:
- Date
- JavaScript
- Method
- Prototype
- Reference
browser-compat: javascript.builtins.Date.toUTCString
---
{{JSRef}}

The **`toUTCString()`** method converts a date to a string, using the UTC time
zone.

Based on
[rfc7231](https://datatracker.ietf.org/doc/html/rfc7231#section-7.1.1.1) and
modified according to
[ecma-262 toUTCString](https://www.ecma-international.org/ecma-262/10.0/index.html#sec-date.prototype.toutcstring),
it can have negative values in the
[2021 version](https://tc39.es/ecma262/#sec-date.prototype.toutcstring)

{{EmbedInteractiveExample("pages/js/date-toutcstring.html","shorter")}}

## Syntax

```js
toUTCString()
```

### Return value

A string representing the given date using the UTC time zone.

## Description

The value returned by `toUTCString()` is a string in the form <code

> <var>Www</var>, <var>dd</var> <var>Mmm</var> <var>yyyy</var>
> <var>hh</var>:<var>mm</var>:<var>ss</var> GMT</code
>
> , Where:

<table class="standard-table">
  <thead>
    <tr>
      <th scope="col">Format String</th>
      <th scope="col">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code><var>Www</var></code>
      </td>
      <td>Day of week, as three letters (e.g. Sun, Mon, ...)</td>
    </tr>
    <tr>
      <td>
        <code><var>dd</var></code>
      </td>
      <td>Day of month, as two digits with leading zero if required</td>
    </tr>
    <tr>
      <td>
        <code><var>Mmm</var></code>
      </td>
      <td>Month, as three letters (e.g. Jan, Feb, ...)</td>
    </tr>
    <tr>
      <td>
        <code><var>yyyy</var></code>
      </td>
      <td>Year, as four or more digits with leading zeroes if required</td>
    </tr>
    <tr>
      <td>
        <code><var>hh</var></code>
      </td>
      <td>Hour, as two digits with leading zero if required</td>
    </tr>
    <tr>
      <td>
        <code><var>mm</var></code>
      </td>
      <td>Minute, as two digits with leading zero if required</td>
    </tr>
    <tr>
      <td>
        <code><var>ss</var></code>
      </td>
      <td>Seconds, as two digits with leading zero if required</td>
    </tr>
  </tbody>
</table>

Prior to ECMAScript 2018, the format of the return value varied according to the
platform. The most common return value was an RFC-1123 formatted date stamp,
which is a slightly updated version of RFC-822 date stamps.

## Examples

### Using toUTCString()

```js
let today = new Date('Wed, 14 Jun 2017 00:00:00 PDT');
let UTCstring = today.toUTCString(); // Wed, 14 Jun 2017 07:00:00 GMT
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- {{jsxref("Date.prototype.toLocaleString()")}}
- {{jsxref("Date.prototype.toDateString()")}}
- {{jsxref("Date.prototype.toISOString()")}}
