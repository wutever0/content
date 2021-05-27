---
title: Intl.DisplayNames() constructor
slug: Web/JavaScript/Reference/Global_Objects/Intl/DisplayNames/DisplayNames
tags:
  - Constructor
  - DisplayNames
  - Internationalization
  - Intl
  - JavaScript
  - Localization
  - Reference
browser-compat: javascript.builtins.Intl.DisplayNames.DisplayNames
---
{{JSRef}}

The **`Intl.DisplayNames()`** constructor creates
{{jsxref("Intl/DisplayNames", "Intl.DisplayNames")}} objects
that enable the consistent translation of language, region and script display
names.

{{EmbedInteractiveExample("pages/js/intl-displaynames.html")}}

<!-- The source for this interactive example is stored in a GitHub repository. If you'd like to contribute to the interactive examples project, please clone https://github.com/mdn/interactive-examples and send us a pull request. -->

## Syntax

```js
new Intl.DisplayNames()
new Intl.DisplayNames(locales)
new Intl.DisplayNames(locales, options)
```

### Parameters

- `locales` {{optional_inline}}
  - : A string with a BCP 47 language tag, or an array of such strings. For the
    general form and interpretation of the `locales` argument, see the
    {{jsxref("Global_Objects/Intl", "Intl",
			"#Locale_identification_and_negotiation", 1)}}
    page. The following Unicode extension key is allowed:
    - `nu`
      - : The numbering system to be used. Possible values include: "`arab`",
        "`arabext`", "`bali`", "`beng`", "`deva`", "`fullwide`", "`gujr`",
        "`guru`", "`hanidec`", "`khmr`", "`knda`", "`laoo`", "`latn`", "`limb`",
        "`mlym`", "`mong`", "`mymr`", "`orya`", "`tamldec`", "`telu`", "`thai`",
        "`tibt`".
- `options` {{optional_inline}}
  - : An object with some or all of the following properties:
    <dl><dt><code>localeMatcher</code></dt><dd>The locale matching algorithm to use. Possible values are
    "<code>lookup</code>" and "<code>best fit</code>"; the default is
    "<code>best fit</code>". For information about this option, see the
    {{jsxref("Global_Objects/Intl", "Intl", "#Locale_negotiation", 1)}} page.</dd><dt><code>style</code></dt><dd>The formatting style to use, the default is "<code>long</code>".<ul><li>"<code>narrow</code>"</li><li>"<code>short</code>"</li><li>"<code>long</code>"</li></ul></dd><dt><code>type</code></dt><dd>The type to use.<ul><li>"<code>language</code>"</li><li>"<code>region</code>"</li><li>"<code>script</code>"</li><li>"<code>currency</code>"</li></ul></dd><dt><code>fallback</code></dt><dd>The fallback to use, the default is "<code>code</code>".<ul><li>"<code>code</code>"</li><li>"<code>none</code>"</li></ul></dd></dl>

## Examples

### Basic usage

In basic use without specifying a locale, a formatted string in the default
locale and with default options is returned.

```js
console.log((new Intl.DisplayNames([], {type: 'language'})).of('US'));
// Expected output: 'us'
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- {{jsxref("Intl.DisplayNames")}}
- {{jsxref("Global_Objects/Intl", "Intl")}}
