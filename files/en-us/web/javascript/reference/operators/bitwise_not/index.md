---
title: Bitwise NOT (~)
slug: Web/JavaScript/Reference/Operators/Bitwise_NOT
tags:
- Bitwise operator
- JavaScript
- Language feature
- Operator
- Reference
browser-compat: javascript.operators.bitwise_not
---
{{jsSidebar("Operators")}}

The bitwise NOT operator (`~`) inverts the bits of its operand.

{{EmbedInteractiveExample("pages/js/expressions-bitwise-not.html")}}

## Syntax

<pre class="brush: js"><code><var>~a</var></code>
</pre>

## Description

The operands are converted to 32-bit integers and expressed by a series of bits
(zeroes and ones). Numbers with more than 32 bits get their most significant
bits discarded. For example, the following integer with more than 32 bits will
be converted to a 32 bit integer:

```js
Before: 11100110111110100000000000000110000000000001
After:              10100000000000000110000000000001
```

Each bit in the first operand is paired with the corresponding bit in the second
operand: _first bit_ to _first bit_, _second bit_ to _second bit_, and so on.

The operator is applied to each pair of bits, and the result is constructed
bitwise.

The truth table for the `NOT` operation is:

<table class="standard-table">
  <thead>
    <tr>
      <th class="header" scope="col">a</th>
      <th class="header" scope="col">NOT a</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <td>1</td>
      <td>0</td>
    </tr>
  </tbody>
</table>

```js
 9 (base 10) = 00000000000000000000000000001001 (base 2)
               --------------------------------
~9 (base 10) = 11111111111111111111111111110110 (base 2) = -10 (base 10)
```

Bitwise NOTing any number `x` yields `-(x + 1)`. For example, `~-5` yields `4`.

Note that due to using 32-bit representation for numbers both `~-1` and
`~4294967295` (2^32 - 1) results in `0`.

## Examples

### Using bitwise NOT

```js
~0;  // -1
~-1; // 0
~1;  // -2
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- [Bitwise operators in the JS guide](/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#Bitwise)
