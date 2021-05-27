---
title: 'SyntaxError: missing variable name'
slug: Web/JavaScript/Reference/Errors/No_variable_name
tags:
  - Error
  - Errors
  - JavaScript
  - SyntaxError
---
{{jsSidebar("Errors")}}

The JavaScript exception "missing variable name" occurs way too often as naming
things is so hard. Or maybe a comma is wrong. Check for typos!

## Message

```js
SyntaxError: missing variable name (Firefox)
SyntaxError: Unexpected token = (Chrome)
```

## Error type

{{jsxref("SyntaxError")}}

## What went wrong?

A variable is missing a name. This is likely due to a syntax error in your code.
Probably a comma is wrong somewhere or you struggled with coming up with a name.
Totally understandable! Naming things is so hard.

- Check to ensure the previous lines / declaration does not end with a comma
  instead of a semi-colon.

## Examples

### Missing a variable name

```js example-bad
var = "foo";
```

It's tough coming up with good variable names. We all have been there.

```js example-good
var ohGodWhy = "foo";
```

### Reserved keywords can't be variable names

There are a few variable names that are
[reserved keywords](/en-US/docs/Web/JavaScript/Reference/Lexical_grammar#keywords).
You can't use these. Sorry :(

```js example-bad
var debugger = "whoop";
// SyntaxError: missing variable name
```

### Declaring multiple variables

Pay special attention to commas when declaring multiple variables. Is there an
excess comma? Did you accidentally add commas instead of semicolons?

```js example-bad
var x, y = "foo",
var x, = "foo"

var first = document.getElementById('one'),
var second = document.getElementById('two'),

// SyntaxError: missing variable name
```

The fixed version:

```js example-good
var x, y = "foo";
var x = "foo";

var first = document.getElementById('one');
var second = document.getElementById('two');
```

### Arrays

{{jsxref("Array")}} literals in JavaScript need square brackets around the
values. This won't work:

```js example-bad
var arr = 1,2,3,4,5;
// SyntaxError: missing variable name
```

This would be correct:

```js example-good
var arr = [1,2,3,4,5];
```

## See also

- [Good variable names](http://wiki.c2.com/?GoodVariableNames)
- {{jsxref("Statements/var", "var")}}
- [Variable declarations in the JavaScript Guide](/en-US/docs/Web/JavaScript/Guide/Grammar_and_types#declarations)
