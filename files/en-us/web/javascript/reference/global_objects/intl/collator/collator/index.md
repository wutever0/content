---
title: Intl.Collator() constructor
slug: Web/JavaScript/Reference/Global_Objects/Intl/Collator/Collator
tags:
  - Collator
  - Constructor
  - Internationalization
  - Intl
  - JavaScript
  - Localization
  - Reference
browser-compat: javascript.builtins.Intl.Collator.Collator
---
{{JSRef}}

The **`Intl.Collator()`** constructor creates
{{jsxref("Intl/Collator", "Intl.Collator")}} objects that enable
language-sensitive string comparison.

{{EmbedInteractiveExample("pages/js/intl-collator.html")}}

<!-- The source for this interactive example is stored in a GitHub repository. If you'd like to contribute to the interactive examples project, please clone https://github.com/mdn/interactive-examples and send us a pull request. -->

## Syntax

```js
new Intl.Collator()
new Intl.Collator(locales)
new Intl.Collator(locales, options)
```

### Parameters

- `locales` {{optional_inline}}

  - : Optional. A string with a BCP 47 language tag, or an array of such
    strings. For the general form and interpretation of the `locales` argument,
    see the
    {{jsxref("Global_Objects/Intl", "Intl page",
			"#Locale_identification_and_negotiation", 1)}}.

    The following Unicode extension keys are allowed:

    > **Note:** These keys can usually also be set with `options` (as listed
    > below). When both are set, the `options` property takes precedence.

    - `co`
      - : Variant collations for certain locales. Possible values include:
        "`big5han`", "`dict`", "`direct`", "`ducet`", "`gb2312`", "`phonebk`",
        "`phonetic`", "`pinyin`", "`reformed`", "`searchjl`", "`stroke`",
        "`trad`", "`unihan`". This option can be also be set through the
        `options` property "`collation`".
    - `kn`
      - : Whether numeric collation should be used, such that "1" < "2" < "10".
        Possible values are "`true`" and "`false`". This option can be also be
        set through the `options` property "`numeric`".
    - `kf`
      - : Whether upper case or lower case should sort first. Possible values
        are "`upper`", "`lower`", or "`false`" (use the locale's default). This
        option can be also be set through the `options` property "`caseFirst`".

- `options` {{optional_inline}}
  - : An object with some or all of the following properties:
    <dl><dt><code>localeMatcher</code></dt><dd>The locale matching algorithm to use. Possible values are
    "<code>lookup</code>" and "<code>best fit</code>"; the default is
    "<code>best fit</code>". For information about this option, see the
    {{jsxref("Global_Objects/Intl", "Intl", "#Locale_negotiation", 1)}} page.</dd><dt><code>usage</code></dt><dd>Whether the comparison is for sorting or for searching for matching
    strings. Possible values are "<code>sort</code>" and
    "<code>search</code>"; the default is "<code>sort</code>".</dd><dt><code>sensitivity</code></dt><dd><p>Which differences in the strings should lead to non-zero result values.
    Possible values are:</p><ul><li>"<code>base</code>": Only strings that differ in base letters
    compare as unequal. Examples: a ≠ b, a = á, a = A.</li><li>"<code>accent</code>": Only strings that differ in base letters or
    accents and other diacritic marks compare as unequal. Examples: a
    ≠ b, a ≠ á, a = A.</li><li>"<code>case</code>": Only strings that differ in base letters or
    case compare as unequal. Examples: a ≠ b, a = á, a ≠ A.</li><li>"<code>variant</code>": Strings that differ in base letters,
    accents and other diacritic marks, or case compare as unequal.
    Other differences may also be taken into consideration. Examples:
    a ≠ b, a ≠ á, a ≠ A.</li></ul><p>The default is "<code>variant</code>" for usage "<code>sort</code>";
    it's locale dependent for usage "<code>search</code>".</p></dd><dt><code>ignorePunctuation</code></dt><dd>Whether punctuation should be ignored. Possible values are
    <code>true</code> and <code>false</code>; the default is
    <code>false</code>.</dd><dt><code>numeric</code></dt><dd>Whether numeric collation should be used, such that "1" &#x3C; "2" &#x3C;
    "10". Possible values are <code>true</code> and <code>false</code>; the
    default is <code>false</code>.<div class="note notecard"><p><strong>Note:</strong> This option can also be set through the <code>kn</code> Unicode
    extension key; if both are provided, this <code>options</code>
    property takes precedence.</p></div></dd><dt><code>caseFirst</code></dt><dd>Whether upper case or lower case should sort first. Possible values are
    "<code>upper</code>", "<code>lower</code>", or "<code>false</code>" (use
    the locale's default). This option can be set through an
    <code><var>options</var></code> property or through a Unicode extension
    key; if both are provided, the <code><var>options</var></code> property
    takes precedence.<div class="note notecard"><p><strong>Note:</strong> This option can also be set through the <code>kf</code> Unicode
    extension key; if both are provided, this <code>options</code>
    property takes precedence.</p></div></dd><dt><code>collation</code></dt><dd>Variant collations for certain locales. Possible values include:
    "<code>big5han</code>", "<code>dict</code>", "<code>direct</code>",
    "<code>ducet</code>", "<code>gb2312</code>", "<code>phonebk</code>" (only
    supported in German), "<code>phonetic</code>", "<code>pinyin</code>",
    "<code>reformed</code>", "<code>searchjl</code>", "<code>stroke</code>",
    "<code>trad</code>", "<code>unihan</code>".<div class="note notecard"><p><strong>Note:</strong> This option can also be set through the <code>co</code> Unicode
    extension key; if both are provided, this <code>options</code>
    property takes precedence.</p></div></dd></dl>

## Examples

### Using Collator

The following example demonstrates the different potential results for a string
occurring before, after, or at the same level as another:

```js
console.log(new Intl.Collator().compare('a', 'c')); // → a negative value
console.log(new Intl.Collator().compare('c', 'a')); // → a positive value
console.log(new Intl.Collator().compare('a', 'a')); // → 0
```

Note that the results shown in the code above can vary between browsers and
browser versions. This is because the values are implementation-specific. That
is, the specification requires only that the before and after values are
negative and positive.

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- {{jsxref("Intl.Collator")}}
- {{jsxref("Intl")}}
