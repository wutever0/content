---
title: Intl.DateTimeFormat() constructor
slug: Web/JavaScript/Reference/Global_Objects/Intl/DateTimeFormat/DateTimeFormat
tags:
  - Constructor
  - DateTimeFormat
  - Internationalization
  - Intl
  - JavaScript
  - Localization
  - Reference
browser-compat: javascript.builtins.Intl.DateTimeFormat.DateTimeFormat
---
{{JSRef}}

The **`Intl.DateTimeFormat()`** constructor creates
{{jsxref("Intl/DateTimeFormat", "Intl.DateTimeFormat")}}
objects that enable language-sensitive date and time formatting.

{{EmbedInteractiveExample("pages/js/intl-datetimeformat.html", "taller")}}

<!-- The source for this interactive example is stored in a GitHub repository. If you'd like to contribute to the interactive examples project, please clone https://github.com/mdn/interactive-examples and send us a pull request. -->

## Syntax

```js
new Intl.DateTimeFormat()
new Intl.DateTimeFormat(locales)
new Intl.DateTimeFormat(locales, options)
```

### Parameters

- `locales` {{optional_inline}}
  - : A string with a BCP 47 language tag, or an array of such strings. To use
    the browser's default locale, pass an empty array. Unicode extension are
    supported (for example "`en-US-u-ca-buddhist`"). For the general form and
    interpretation of the `locales` argument, see the
    {{jsxref("Global_Objects/Intl", "Intl",
			"#Locale_identification_and_negotiation", 1)}}
    page. The following Unicode extension keys are allowed:
    - `nu`
      - : Numbering system. Possible values include: "`arab`", "`arabext`",
        "`bali`", "`beng`", "`deva`", "`fullwide`", "`gujr`", "`guru`",
        "`hanidec`", "`khmr`", "`knda`", "`laoo`", "`latn`", "`limb`", "`mlym`",
        "`mong`", "`mymr`", "`orya`", "`tamldec`", "`telu`", "`thai`", "`tibt`".
    - `ca`
      - : Calendar. Possible values include: "`buddhist`", "`chinese`",
        "`coptic`", "`ethiopia`", "`ethiopic`", "`gregory`", "`hebrew`",
        "`indian`", "`islamic`", "`iso8601`", "`japanese`", "`persian`",
        "`roc`".
    - `hc`
      - : Hour cycle. Possible values include: "`h11`", "`h12`", "`h23`",
        "`h24`".
- `options` {{optional_inline}}
  - : An object with some or all of the following properties:
    <dl><dt><code>dateStyle</code></dt><dd>The date formatting style to use when calling <code>format()</code>.
    Possible values include:<ul><li>"<code>full</code>"</li><li>"<code>long</code>"</li><li>"<code>medium</code>"</li><li>"<code>short</code>"</li></ul><div class="notecard note"><p><strong>Note:</strong> <code>dateStyle</code> can be used with <code>timeStyle</code>, but
    not with other options (e.g. <code>weekday</code>,
    <code>hour</code>, <code>month</code>, etc.).</p></div></dd><dt><code>timeStyle</code></dt><dd><p>The time formatting style to use when calling <code>format()</code>.
    Possible values include:</p><ul><li>"<code>full</code>"</li><li>"<code>long</code>"</li><li>"<code>medium</code>"</li><li>"<code>short</code>"</li></ul><div class="notecard note"><p><strong>Note:</strong> <code>timeStyle</code> can be used with <code>dateStyle</code>, but
    not with other options (e.g. <code>weekday</code>,
    <code>hour</code>, <code>month</code>, etc.).</p></div></dd><dt><code>calendar</code></dt><dd>Calendar. Possible values include: "<code>buddhist</code>",
    "<code>chinese</code>", " <code>coptic</code>", "<code>ethiopia</code>",
    "<code>ethiopic</code>", "<code>gregory</code>", " <code>hebrew</code>",
    "<code>indian</code>", "<code>islamic</code>", "<code>iso8601</code>", "
    <code>japanese</code>", "<code>persian</code>", "<code>roc</code>".</dd><dt><code>dayPeriod</code></dt><dd>The way day periods should be expressed. Possible values include:
    "<code>narrow</code>", "<code>short</code>", " <code>long</code>".</dd><dt><code>numberingSystem</code></dt><dd>Numbering System. Possible values include: "<code>arab</code>",
    "<code>arabext</code>", " <code>bali</code>", "<code>beng</code>",
    "<code>deva</code>", "<code>fullwide</code>", " <code>gujr</code>",
    "<code>guru</code>", "<code>hanidec</code>", "<code>khmr</code>", "
    <code>knda</code>", "<code>laoo</code>", "<code>latn</code>",
    "<code>limb</code>", "<code>mlym</code>", " <code>mong</code>",
    "<code>mymr</code>", "<code>orya</code>", "<code>tamldec</code>", "
    <code>telu</code>", "<code>thai</code>", "<code>tibt</code>".</dd><dt><code>localeMatcher</code></dt><dd>The locale matching algorithm to use. Possible values are
    "<code>lookup</code>" and "<code>best fit</code>"; the default is
    "<code>best fit</code>". For information about this option, see the
    {{jsxref("Global_Objects/Intl", "Intl", "#Locale_negotiation", 1)}} page.</dd><dt><code>timeZone</code></dt><dd>The time zone to use. The only value implementations must recognize is
    "<code>UTC</code>"; the default is the runtime's default time zone.
    Implementations may also recognize the time zone names of the <a href="https://www.iana.org/time-zones">IANA time zone database</a>,
    such as "<code>Asia/Shanghai</code>", "<code>Asia/Kolkata</code>",
    "<code>America/New_York</code>".</dd><dt><code>hour12</code></dt><dd>Whether to use 12-hour time (as opposed to 24-hour time). Possible values
    are <code>true</code> and <code>false</code>; the default is locale
    dependent. This option overrides the <code>hc</code> language tag and/or
    the <code>hourCycle</code> option in case both are present.</dd><dt><code>hourCycle</code></dt><dd>The hour cycle to use. Possible values are "<code>h11</code>",
    "<code>h12</code>", "<code>h23</code>", or "<code>h24</code>". This option
    overrides the <code>hc</code> language tag, if both are present, and the
    <code>hour12</code> option takes precedence in case both options have been
    specified.</dd><dt><code>formatMatcher</code></dt><dd>The format matching algorithm to use. Possible values are
    "<code>basic</code>" and "<code>best fit</code>"; the default is
    "<code>best fit</code>". See the following paragraphs for information
    about the use of this property.</dd></dl>
    The following properties describe the date-time components to use in formatted
    output, and their desired representations. Implementations are required to
    support at least the following subsets:
    *   `weekday`, `year`, `month`,
        `day`, `hour`, `minute`,
        `second`
    *   `weekday`, `year`, `month`,
        `day`
    *   `year`, `month`, `day`
    *   `year`, `month`
    *   `month`, `day`
    *   `hour`, `minute`, `second`
    *   `hour`, `minute`
    Implementations may support other subsets, and requests will be negotiated
    against all available subset-representation combinations to find the best
    match. Two algorithms are available for this negotiation and selected by the
    `formatMatcher` property: A [fully
    specified "`basic`" algorithm](http://www.ecma-international.org/ecma-402/1.0/#BasicFormatMatcher) and an
    implementation-dependent "`best fit`" algorithm.
    <dl><dt><code>weekday</code></dt><dd>The representation of the weekday. Possible values are:<ul><li>"<code>long</code>" (e.g., <code>Thursday</code>)</li><li>"<code>short</code>" (e.g., <code>Thu</code>)</li><li>"<code>narrow</code>" (e.g., <code>T</code>). Two weekdays may
    have the same narrow style for some locales (e.g.
    <code>Tuesday</code>'s narrow style is also <code>T</code>).</li></ul></dd><dt><code>era</code></dt><dd>The representation of the era. Possible values are:<ul><li>"<code>long</code>" (e.g., <code>Anno Domini</code>)</li><li>"<code>short</code>" (e.g., <code>AD</code>)</li><li>"<code>narrow</code>" (e.g., <code>A</code>)</li></ul></dd><dt><code>year</code></dt><dd>The representation of the year. Possible values are:<ul><li>"<code>numeric</code>" (e.g., <code>2012</code>)</li><li>"<code>2-digit</code>" (e.g., <code>12</code>)</li></ul></dd><dt><code>month</code></dt><dd>The representation of the month. Possible values are:<ul><li>"<code>numeric</code>" (e.g., <code>2</code>)</li><li>"<code>2-digit</code>" (e.g., <code>02</code>)</li><li>"<code>long</code>" (e.g., <code>March</code>)</li><li>"<code>short</code>" (e.g., <code>Mar</code>)</li><li>"<code>narrow</code>" (e.g., <code>M</code>). Two months may have
    the same narrow style for some locales (e.g. <code>May</code>'s
    narrow style is also <code>M</code>).</li></ul></dd><dt><code>day</code></dt><dd>The representation of the day. Possible values are:<ul><li>"<code>numeric</code>" (e.g., <code>1</code>)</li><li>"<code>2-digit</code>" (e.g., <code>01</code>)</li></ul></dd><dt><code>hour</code></dt><dd>The representation of the hour. Possible values are
    "<code>numeric</code>", "<code>2-digit</code>".</dd><dt><code>minute</code></dt><dd>The representation of the minute. Possible values are
    "<code>numeric</code>", "<code>2-digit</code>".</dd><dt><code>second</code></dt><dd>The representation of the second. Possible values are
    "<code>numeric</code>", "<code>2-digit</code>".</dd><dt><code>fractionalSecondDigits</code></dt><dd>The number of digits used to represent fractions of a second (any
    additional digits are truncated). Possible values are:<ul><li><code>0</code> (Fractional part dropped.)</li><li><code>1</code> (Fractional part represented as 1 digit. For
    example, 736 is formatted as <code>7</code>.)</li><li><code>2</code> (Fractional part represented as 2 digits. For
    example, 736 is formatted as <code>73</code>.)</li><li><code>3</code> (Fractional part represented as 3 digits. For
    example, 736 is formatted as <code>736</code>.)</li></ul></dd><dt><code>timeZoneName</code></dt><dd>The representation of the time zone name. Possible values are:<ul><li>"<code>long</code>" (e.g., <code>British Summer Time</code>)</li><li>"<code>short</code>" (e.g., <code>GMT+1</code>)</li></ul></dd></dl>
    <p class="noinclude">The default value for each date-time component property is
    {{jsxref("undefined")}}, but if all component properties are
    {{jsxref("undefined")}}, then <code>year</code>, <code>month</code>, and
    <code>day</code> are assumed to be "<code>numeric</code>".</p>

## Examples

### Using DateTimeFormat

In basic use without specifying a locale, `DateTimeFormat` uses the default
locale and default options.

```js
var date = new Date(Date.UTC(2012, 11, 20, 3, 0, 0));

// toLocaleString without arguments depends on the implementation,
// the default locale, and the default time zone
console.log(new Intl.DateTimeFormat().format(date));
// → "12/19/2012" if run with en-US locale (language) and time zone America/Los_Angeles (UTC-0800)
```

### Using timeStyle and dateStyle

```js
let o = new Intl.DateTimeFormat("en" , {
  timeStyle: "short"
});
console.log(o.format(Date.now())); // "13:31 AM"

let o = new Intl.DateTimeFormat("en" , {
  dateStyle: "short"
});
console.log(o.format(Date.now())); // "07/07/20"

let o = new Intl.DateTimeFormat("en" , {
  timeStyle: "medium",
  dateStyle: "short"
});
console.log(o.format(Date.now())); // "07/07/20, 13:31:55 AM"
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- {{jsxref("Intl.DateTimeFormat")}}
- {{jsxref("Global_Objects/Intl", "Intl")}}
