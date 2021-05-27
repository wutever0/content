---
title: Date.prototype.getUTCMonth()
slug: Web/JavaScript/Reference/Global_Objects/Date/getUTCMonth
tags:
- Date
- JavaScript
- Method
- Prototype
- Reference
browser-compat: javascript.builtins.Date.getUTCMonth
---
{{JSRef}}

The **`getUTCMonth()`** returns the month of the specified date according to
universal time, as a zero-based value (where zero indicates the first month of
the year).

{{EmbedInteractiveExample("pages/js/date-getutcmonth.html")}}

## Syntax

```js
getUTCMonth()
```

### Return value

An integer number, between 0 and 11, corresponding to the month of the given
date according to universal time. 0 for January, 1 for February, 2 for March,
and so on.

## Examples

### Using getUTCMonth()

The following example assigns the month portion of the current date to the
variable `month`.

```js
var today = new Date();
var month = today.getUTCMonth();
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- {{jsxref("Date.prototype.getMonth()")}}
- {{jsxref("Date.prototype.setUTCMonth()")}}
