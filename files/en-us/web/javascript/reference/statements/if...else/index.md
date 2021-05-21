---
title: if...else
slug: Web/JavaScript/Reference/Statements/if...else
tags:
- JavaScript
- Language feature
- Reference
- Statement
- else
- if
browser-compat: javascript.statements.if_else
---
{{jsSidebar("Statements")}}

<span class="seoSummary"

> The <strong><code>if</code></strong> statement executes a statement if a
> specified condition is {{Glossary("truthy")}}. If the condition is
> {{Glossary("falsy")}}, another statement can be executed.</span

{{EmbedInteractiveExample("pages/js/statement-ifelse.html")}}

## Syntax

<pre class="brush: js">
if (<var>condition</var>) {
   <var>statement1</var>
} else {
   <var>statement2</var>
}
</pre>

- `condition`

  - : An
    [expression](/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#Expressions)

    that is considered to be either {{Glossary("truthy")}} or
    {{Glossary("falsy")}}.

- `statement1`

  - : Statement that is executed if <var>condition</var>

    is {{Glossary("truthy")}}. Can be any statement, including further
    nested `if` statements. To execute multiple statements, use a
    [block](/en-US/docs/Web/JavaScript/Reference/Statements/block) statement (
    `{ ... }` ) to group those statements. To execute no statements, use an
    [empty](/en-US/docs/Web/JavaScript/Reference/Statements/Empty) statement.

- `statement2`
  - : Statement that is executed if `condition` is {{Glossary("falsy")}}
    and the `else` clause exists. Can be any statement, including block
    statements and further nested `if` statements.

## Description

Multiple `if...else` statements can be nested to create an `else if` clause.
Note that there is no `elseif` (in one word) keyword in JavaScript.

<pre class="brush: js">
if (<var>condition1</var>)
  <var>statement1</var>
else if (<var>condition2</var>)
  <var>statement2</var>
else if (<var>condition3</var>)
  <var>statement3</var>
...
else
  <var>statementN</var>
</pre>

To see how this works, this is how it would look if the nesting were properly
indented:

<pre class="brush: js">
if (<var>condition1</var>)
  <var>statement1</var>
else
  if (<var>condition2</var>)
    <var>statement2</var>
  else
    if (<var>condition3</var>)
...
</pre>

To execute multiple statements within a clause, use a block statement
(`{ ... }`) to group those statements. In general, it is a good practice to
always use block statements, especially in code involving nested `if`
statements:

<pre class="brush: js">
if (<var>condition</var>) {
  <var>statements1</var>
} else {
  <var>statements2</var>
}
</pre>

Do not confuse the primitive Boolean values `true` and `false` with truthiness
or falsiness of the
{{jsxref("Global_Objects/Boolean", "Boolean")}} object. Any
value that is not `false`, `undefined`, `null`, `0`, `-0`, `NaN`, or the empty
string (`""`), and any object, including a Boolean object whose value is
`false`, is considered {{Glossary("truthy")}} when used as the condition.
For example:

```js
var b = new Boolean(false);
if (b) // this condition is truthy
```

## Examples

### Using if...else

```js
if (cipher_char === from_char) {
  result = result + to_char;
  x++;
} else {
  result = result + clear_char;
}
```

### Using else if

Note that there is no `elseif` syntax in JavaScript. However, you can write it
with a space between `else` and `if`:

```js
if (x > 50) {
  /* do something */
} else if (x > 5) {
  /* do something */
} else {
  /* do something */
}
```

### Assignment within the conditional expression

It is advisable to not use simple assignments in a conditional expression,
because the assignment can be confused with equality when glancing over the
code. For example, do not use the following code:

```js example-bad
if (x = y) {
  /* do something */
}
```

If you need to use an assignment in a conditional expression, a common practice
is to put additional parentheses around the assignment. For example:

```js example-good
if ((x = y)) {
  /* do something */
}
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- {{jsxref("Statements/block", "block")}}
- {{jsxref("Statements/switch", "switch")}}
- [Conditional operator](/en-US/docs/JavaScript/Reference/Operators/Conditional_Operator)
