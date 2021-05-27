# Report from 5/27/2021, 9:23:36 PM
## Top 20 unhandled elements
- code (362)
- pre.brush:.js (301)
- tr (238)
- td (153)
- th[scope="col"] (147)
- table.standard-table (79)
- th[scope="row"] (55)
- var (53)
- th.header[scope="col"] (43)
- dl (34)
- span.seoSummary (25)
- dfn (16)
- kbd (13)
- div.note (8)
- table (6)
- span.blob-code-inner.blob-code-marker (5)
- table.fullwidth-table (4)
- p.summary (4)
- sub (4)
- figure (3)
## Details per Document
### [/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
#### Invalid AST transformations
##### tr (130:3) => tableRow
```
type: 'html'
value: '<th scope="row">Variable</th>',type: 'html'
value: '<th scope="col">Explanation</th>',type: 'html'
value: '<th scope="col">Example</th>'
```
##### tr (137:3) => tableRow
```
type: 'html'
value: '<th scope="row">{{R2xvc3NhcnkoIlN0cmluZyIp}}</th>'
```
##### tr (142:3) => tableRow
```
type: 'html'
value: '<th scope="row">{{R2xvc3NhcnkoIk51bWJlciIp}}</th>'
```
##### tr (147:3) => tableRow
```
type: 'html'
value: '<th scope="row">{{R2xvc3NhcnkoIkJvb2xlYW4iKQ==}}</th>'
```
##### tr (152:3) => tableRow
```
type: 'html'
value: '<th scope="row">{{R2xvc3NhcnkoIkFycmF5Iik=}}</th>'
```
##### tr (159:3) => tableRow
```
type: 'html'
value: '<th scope="row">{{R2xvc3NhcnkoIk9iamVjdCIp}}</th>'
```
##### table.standard-table (128:1) => table
```
type: 'html'
value: '<tr><th scope="row">Variable</th><th scope="col">Explanation</th><th scope="col">Example</th></tr>',type: 'html'
value: '<tr><th scope="row">{{R2xvc3NhcnkoIlN0cmluZyIp}}</th><td>This is a sequence of text known as a string. To signify that the value is a string, enclose it in single quote marks.</td><td><code>let myVariable = 'Bob';</code></td></tr>',type: 'html'
value: '<tr><th scope="row">{{R2xvc3NhcnkoIk51bWJlciIp}}</th><td>This is a number. Numbers don't have quotes around them.</td><td><code>let myVariable = 10;</code></td></tr>',type: 'html'
value: '<tr><th scope="row">{{R2xvc3NhcnkoIkJvb2xlYW4iKQ==}}</th><td>This is a True/False value. The words <code>true</code> and <code>false</code> are special keywords that don't need quote marks.</td><td><code>let myVariable = true;</code></td></tr>',type: 'html'
value: '<tr><th scope="row">{{R2xvc3NhcnkoIkFycmF5Iik=}}</th><td>This is a structure that allows you to store multiple values in a single reference.</td><td><code>let myVariable = [1,'Bob','Steve',10];</code><br>Refer to each member of the array like this:<br><code>myVariable[0]</code>, <code>myVariable[1]</code>, etc.</td></tr>',type: 'html'
value: '<tr><th scope="row">{{R2xvc3NhcnkoIk9iamVjdCIp}}</th><td>This can be anything. Everything in JavaScript is an object and can be stored in a variable. Keep this in mind as you learn.</td><td><code>let myVariable = document.querySelector('h1');</code><br>All of the above examples too.</td></tr>'
```
##### tr (189:3) => tableRow
```
type: 'html'
value: '<th scope="row">Operator</th>',type: 'html'
value: '<th scope="col">Explanation</th>',type: 'html'
value: '<th scope="col">Symbol(s)</th>',type: 'html'
value: '<th scope="col">Example</th>'
```
##### code (201:8) => text
```
type: 'element'
tagName: 'br'
properties: 

children: 

```
##### tr (197:3) => tableRow
```
type: 'html'
value: '<th scope="row">Addition</th>'
```
##### code (208:8) => text
```
type: 'element'
tagName: 'br'
properties: 

children: 

```
##### tr (204:3) => tableRow
```
type: 'html'
value: '<th scope="row">Subtraction, Multiplication, Division</th>'
```
##### tr (212:3) => tableRow
```
type: 'html'
value: '<th scope="row">Assignment</th>'
```
##### code (222:8) => text
```
type: 'element'
tagName: 'br'
properties: 

children: 

```
##### tr (218:3) => tableRow
```
type: 'html'
value: '<th scope="row">Equality</th>'
```
##### code (232:8) => text
```
type: 'element'
tagName: 'br'
properties: 

children: 

```
##### code (237:8) => text
```
type: 'element'
tagName: 'br'
properties: 

children: 

```
##### td (229:4) => tableCell
```
type: 'paragraph'
summary: '
JavaScript is a programming language that adds interactivity to your website. This happens in games, in the behavior of responses when buttons are pressed or with data entry on forms; with dynamic styling; with animation, etc. This article helps you get started with JavaScript and furthers your understanding of what is possible.
'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'For "Not", the basic expression is '
  type: 'inlineCode'
  value: 'true'
  type: 'text'
  value: ', but the comparison returns '
  type: 'inlineCode'
  value: 'false'
  type: 'text'
  value: ' because we negate it:',type: 'paragraph'
summary: '
JavaScript is a programming language that adds interactivity to your website. This happens in games, in the behavior of responses when buttons are pressed or with data entry on forms; with dynamic styling; with animation, etc. This article helps you get started with JavaScript and furthers your understanding of what is possible.
'
shouldWrap: 'true'
children: 
  type: 'html'
  value: '<code>let myVariable = 3;<br>!(myVariable === 3);</code>',type: 'paragraph'
summary: '
JavaScript is a programming language that adds interactivity to your website. This happens in games, in the behavior of responses when buttons are pressed or with data entry on forms; with dynamic styling; with animation, etc. This article helps you get started with JavaScript and furthers your understanding of what is possible.
'
shouldWrap: 'true'
children: 
  type: 'text'
  value: '"Does-not-equal" gives basically the same result with different syntax. Here we are testing "is '
  type: 'inlineCode'
  value: 'myVariable'
  type: 'text'
  value: ' NOT equal to 3". This returns'
  type: 'inlineCode'
  value: ' false'
  type: 'text'
  value: ' because '
  type: 'inlineCode'
  value: 'myVariable'
  type: 'text'
  value: ' IS equal to 3:',type: 'paragraph'
summary: '
JavaScript is a programming language that adds interactivity to your website. This happens in games, in the behavior of responses when buttons are pressed or with data entry on forms; with dynamic styling; with animation, etc. This article helps you get started with JavaScript and furthers your understanding of what is possible.
'
shouldWrap: 'true'
children: 
  type: 'html'
  value: '<code>let myVariable = 3;<br>myVariable !== 3;</code>'
```
##### tr (225:3) => tableRow
```
type: 'html'
value: '<th scope="row">Not, Does-not-equal</th>',type: 'html'
value: '<td><p>For "Not", the basic expression is <code>true</code>, but the comparison returns <code>false</code> because we negate it:</p><p><code>let myVariable = 3;<br>!(myVariable === 3);</code></p><p>"Does-not-equal" gives basically the same result with different syntax. Here we are testing "is <code>myVariable</code> NOT equal to 3". This returns<code> false</code> because <code>myVariable</code> IS equal to 3:</p><p><code>let myVariable = 3;<br>myVariable !== 3;</code></p></td>'
```
##### table.standard-table (187:1) => table
```
type: 'html'
value: '<tr><th scope="row">Operator</th><th scope="col">Explanation</th><th scope="col">Symbol(s)</th><th scope="col">Example</th></tr>',type: 'html'
value: '<tr><th scope="row">Addition</th><td>Add two numbers together or combine two strings.</td><td><code>+</code></td><td><code>6 + 9;<br>'Hello ' + 'world!';</code></td></tr>',type: 'html'
value: '<tr><th scope="row">Subtraction, Multiplication, Division</th><td>These do what you'd expect them to do in basic math.</td><td><code>-</code>, <code>*</code>, <code>/</code></td><td><code>9 - 3;<br>8 * 2; // multiply in JS is an asterisk<br>9 / 3;</code></td></tr>',type: 'html'
value: '<tr><th scope="row">Assignment</th><td>As you've seen already: this assigns a value to a variable.</td><td><code>=</code></td><td><code>let myVariable = 'Bob';</code></td></tr>',type: 'html'
value: '<tr><th scope="row">Equality</th><td>This performs a test to see if two values are equal. It returns a <code>true</code>/<code>false</code> (Boolean) result.</td><td><code>===</code></td><td><code>let myVariable = 3;<br>myVariable === 4;</code></td></tr>',type: 'html'
value: '<tr><th scope="row">Not, Does-not-equal</th><td>This returns the logically opposite value of what it precedes. It turns a <code>true</code> into a <code>false</code>, etc.. When it is used alongside the Equality operator, the negation operator tests whether two values are <em>not</em> equal.</td><td><code>!</code>, <code>!==</code></td><td><p>For "Not", the basic expression is <code>true</code>, but the comparison returns <code>false</code> because we negate it:</p><p><code>let myVariable = 3;<br>!(myVariable === 3);</code></p><p>"Does-not-equal" gives basically the same result with different syntax. Here we are testing "is <code>myVariable</code> NOT equal to 3". This returns<code> false</code> because <code>myVariable</code> IS equal to 3:</p><p><code>let myVariable = 3;<br>myVariable !== 3;</code></p></td></tr>'
```
### Missing conversion rules
- div.warning (45:1)
- img[alt][src="hello-world.png"][style="display: block; margin: 0px auto;"] (59:143)
- div.note (62:1)
- div.note (74:1)
- div.warning (82:1)
- div.note (92:1)
- div.note (96:1)
- div.note (100:1)
- div.note (104:1)
- th[scope="row"] (131:4)
- th[scope="col"] (132:4)
- th[scope="col"] (133:4)
- th[scope="row"] (138:4)
- th[scope="row"] (143:4)
- th[scope="row"] (148:4)
- th[scope="row"] (153:4)
- th[scope="row"] (160:4)
- pre.brush:.js[style="font-size: 14px;"] (180:1)
- th[scope="row"] (190:4)
- th[scope="col"] (191:4)
- th[scope="col"] (192:4)
- th[scope="col"] (193:4)
- th[scope="row"] (198:4)
- th[scope="row"] (205:4)
- th[scope="row"] (213:4)
- th[scope="row"] (219:4)
- th[scope="row"] (226:4)
- div.note (246:1)
- div.note (295:1)
- img[alt][src="website-screen-scripted.png"][style="display: block; margin: 0px auto;"] (421:4)
### [/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript)
#### Invalid AST transformations
##### pre.brush:.js (71:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'not'
```
##### code (251:419) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'operator'
```
##### tr (543:3) => tableRow
```
type: 'html'
value: '<th scope="col">Method name</th>',type: 'html'
value: '<th scope="col">Description</th>'
```
##### table (541:1) => table
```
type: 'html'
value: '<tr><th scope="col">Method name</th><th scope="col">Description</th></tr>'
```
### Missing conversion rules
- th[scope="col"] (544:4)
- th[scope="col"] (545:4)
### [/en-US/docs/Web/JavaScript/Data_structures](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures)
#### Invalid AST transformations
##### tr (183:3) => tableRow
```
type: 'html'
value: '<th scope="col">Attribute</th>',type: 'html'
value: '<th scope="col">Type</th>',type: 'html'
value: '<th scope="col">Description</th>',type: 'html'
value: '<th scope="col">Default value</th>'
```
##### td (206:4) => tableCell
```
type: 'paragraph'
summary: 'Programming languages all have built-in data structures, but these often differ from one language to another. This article attempts to list the built-in data structures available in JavaScript and what properties they have. These can be used to build other data structures. Wherever possible, comparisons with other languages are drawn.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'If '
  type: 'inlineCode'
  value: 'true'
  type: 'text'
  value: ', the property will be enumerated in '
  type: 'link'
  title: 

  url: '/en-US/docs/Web/JavaScript/Reference/Statements/for...in'
  children: 
    type: 'text'
    value: 'for...in'
  type: 'text'
  value: ' loops.'
  type: 'break'
  type: 'text'
  value: 'See also '
  type: 'link'
  title: 

  url: '/en-US/docs/Web/JavaScript/Enumerability_and_ownership_of_properties'
  children: 
    type: 'text'
    value: 'Enumerability and ownership of properties'
  type: 'text'
  value: '.'
```
##### tr (203:3) => tableRow
```
type: 'html'
value: '<td><p>If <code>true</code>, the property will be enumerated in <a href="/en-US/docs/Web/JavaScript/Reference/Statements/for...in">for...in</a> loops.<br>See also <a href="/en-US/docs/Web/JavaScript/Enumerability_and_ownership_of_properties">Enumerability and ownership of properties</a>.</p></td>'
```
##### table.standard-table (180:1) => table
```
type: 'text'
value: 'Attributes of a data property',type: 'html'
value: '<tr><th scope="col">Attribute</th><th scope="col">Type</th><th scope="col">Description</th><th scope="col">Default value</th></tr>',type: 'html'
value: '<tr><td>[[Enumerable]]</td><td>Boolean</td><td><p>If <code>true</code>, the property will be enumerated in <a href="/en-US/docs/Web/JavaScript/Reference/Statements/for...in">for...in</a> loops.<br>See also <a href="/en-US/docs/Web/JavaScript/Enumerability_and_ownership_of_properties">Enumerability and ownership of properties</a>.</p></td><td><code>false</code></td></tr>'
```
##### tr (224:3) => tableRow
```
type: 'html'
value: '<th scope="col">Attribute</th>',type: 'html'
value: '<th scope="col">Type</th>',type: 'html'
value: '<th scope="col">Description</th>'
```
##### table.standard-table (221:1) => table
```
type: 'text'
value: 'Obsolete attributes (as of ECMAScript 3, renamed in ECMAScript 5)',type: 'html'
value: '<tr><th scope="col">Attribute</th><th scope="col">Type</th><th scope="col">Description</th></tr>'
```
##### tr (256:3) => tableRow
```
type: 'html'
value: '<th scope="col">Attribute</th>',type: 'html'
value: '<th scope="col">Type</th>',type: 'html'
value: '<th scope="col">Description</th>',type: 'html'
value: '<th scope="col">Default value</th>'
```
##### table.standard-table (253:1) => table
```
type: 'text'
value: 'Attributes of an accessor property',type: 'html'
value: '<tr><th scope="col">Attribute</th><th scope="col">Type</th><th scope="col">Description</th><th scope="col">Default value</th></tr>'
```
##### tr (313:3) => tableRow
```
type: 'html'
value: '<th class="header" scope="col">Type</th>',type: 'html'
value: '<th class="header" scope="col">Value Range</th>',type: 'html'
value: '<th class="header" scope="col">Size in bytes</th>',type: 'html'
value: '<th class="header" scope="col">Description</th>',type: 'html'
value: '<th class="header" scope="col">Web IDL type</th>',type: 'html'
value: '<th class="header" scope="col">Equivalent C type</th>'
```
##### table.standard-table (311:1) => table
```
type: 'html'
value: '<tr><th class="header" scope="col">Type</th><th class="header" scope="col">Value Range</th><th class="header" scope="col">Size in bytes</th><th class="header" scope="col">Description</th><th class="header" scope="col">Web IDL type</th><th class="header" scope="col">Equivalent C type</th></tr>'
```
### Missing conversion rules
- th[scope="col"] (184:4)
- th[scope="col"] (185:4)
- th[scope="col"] (186:4)
- th[scope="col"] (187:4)
- th[scope="col"] (225:4)
- th[scope="col"] (226:4)
- th[scope="col"] (227:4)
- th[scope="col"] (257:4)
- th[scope="col"] (258:4)
- th[scope="col"] (259:4)
- th[scope="col"] (260:4)
- th.header[scope="col"] (314:4)
- th.header[scope="col"] (315:4)
- th.header[scope="col"] (316:4)
- th.header[scope="col"] (317:4)
- th.header[scope="col"] (318:4)
- th.header[scope="col"] (319:4)
### [/en-US/docs/Web/JavaScript/Enumerability_and_ownership_of_properties](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Enumerability_and_ownership_of_properties)
#### Invalid AST transformations
##### td (35:7) => tableCell
```
type: 'paragraph'
summary: 'Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false.'
shouldWrap: 'true'
children: 
  type: 'link'
  title: 

  url: '/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/propertyIsEnumerable'
  children: 
    type: 'inlineCode'
    value: 'propertyIsEnumerable',type: 'paragraph'
summary: 'Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false.'
shouldWrap: 'true'
children: 
  type: 'link'
  title: 

  url: '/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/hasOwnProperty'
  children: 
    type: 'inlineCode'
    value: 'hasOwnProperty'
```
##### tr (31:5) => tableRow
```
type: 'html'
value: '<td><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/propertyIsEnumerable">propertyIsEnumerable</a></code></p><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/hasOwnProperty">hasOwnProperty</a></code></p></td>'
```
##### td (46:7) => tableCell
```
type: 'paragraph'
summary: 'Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false.'
shouldWrap: 'true'
children: 
  type: 'link'
  title: 

  url: '/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/hasOwnProperty'
  children: 
    type: 'inlineCode'
    value: 'hasOwnProperty'
  type: 'text'
  value: ' – filtered to exclude enumerables using '
  type: 'link'
  title: 

  url: '/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/propertyIsEnumerable'
  children: 
    type: 'inlineCode'
    value: 'propertyIsEnumerable'
```
##### tr (42:5) => tableRow
```
type: 'html'
value: '<td><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/hasOwnProperty">hasOwnProperty</a></code> – filtered to exclude enumerables using <code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/propertyIsEnumerable">propertyIsEnumerable</a></code></p></td>'
```
##### td (56:7) => tableCell
```
type: 'paragraph'
summary: 'Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false.'
shouldWrap: 'true'
children: 
  type: 'link'
  title: 

  url: '/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/hasOwnProperty'
  children: 
    type: 'inlineCode'
    value: 'hasOwnProperty'
```
##### tr (52:5) => tableRow
```
type: 'html'
value: '<td><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/hasOwnProperty">hasOwnProperty</a></code></p></td>'
```
##### table (21:1) => table
```
type: 'html'
value: '<tr><th>Enumerable</th><td><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/propertyIsEnumerable">propertyIsEnumerable</a></code></p><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/hasOwnProperty">hasOwnProperty</a></code></p></td><td>Not available without extra code</td><td>Not available without extra code</td></tr>',type: 'html'
value: '<tr><th>Nonenumerable</th><td><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/hasOwnProperty">hasOwnProperty</a></code> – filtered to exclude enumerables using <code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/propertyIsEnumerable">propertyIsEnumerable</a></code></p></td><td>Not available without extra code</td><td>Not available without extra code</td></tr>',type: 'html'
value: '<tr><th>Enumerable and Nonenumerable</th><td><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/hasOwnProperty">hasOwnProperty</a></code></p></td><td><code><a href="/en-US/docs/Web/JavaScript/Reference/Operators/in">in</a></code></td><td>Not available without extra code</td></tr>'
```
##### td (81:7) => tableCell
```
type: 'paragraph'
summary: 'Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false.'
shouldWrap: 'true'
children: 
  type: 'link'
  title: 

  url: '/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys'
  children: 
    type: 'inlineCode'
    value: 'Object.keys',type: 'paragraph'
summary: 'Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false.'
shouldWrap: 'true'
children: 
  type: 'link'
  title: 

  url: '/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyNames'
  children: 
    type: 'inlineCode'
    value: 'getOwnPropertyNames'
  type: 'text'
  value: ' ',type: 'paragraph'
summary: 'Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false.'
shouldWrap: 'true'
children: 
  type: 'link'
  title: 

  url: '/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertySymbols'
  children: 
    type: 'inlineCode'
    value: 'getOwnPropertySymbols'
```
##### tr (77:5) => tableRow
```
type: 'html'
value: '<td><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys">Object.keys</a></code></p><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyNames">getOwnPropertyNames</a></code> </p><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertySymbols">getOwnPropertySymbols</a></code></p></td>'
```
##### td (101:7) => tableCell
```
type: 'paragraph'
summary: 'Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false.'
shouldWrap: 'true'
children: 
  type: 'link'
  title: 

  url: '/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyNames'
  children: 
    type: 'inlineCode'
    value: 'getOwnPropertyNames',type: 'paragraph'
summary: 'Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false.'
shouldWrap: 'true'
children: 
  type: 'link'
  title: 

  url: '/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertySymbols'
  children: 
    type: 'inlineCode'
    value: 'getOwnPropertySymbols'
```
##### tr (97:5) => tableRow
```
type: 'html'
value: '<td><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyNames">getOwnPropertyNames</a></code></p><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertySymbols">getOwnPropertySymbols</a></code></p></td>'
```
##### table (67:1) => table
```
type: 'html'
value: '<tr><th>Enumerable</th><td><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys">Object.keys</a></code></p><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyNames">getOwnPropertyNames</a></code> </p><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertySymbols">getOwnPropertySymbols</a></code></p></td><td>Not available without extra code</td><td>Not available without extra code</td></tr>',type: 'html'
value: '<tr><th>Enumerable and Nonenumerable</th><td><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyNames">getOwnPropertyNames</a></code></p><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertySymbols">getOwnPropertySymbols</a></code></p></td><td>Not available without extra code</td><td>Not available without extra code</td></tr>'
```
##### td (127:7) => tableCell
```
type: 'paragraph'
summary: 'Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false.'
shouldWrap: 'true'
children: 
  type: 'link'
  title: 

  url: '/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys'
  children: 
    type: 'inlineCode'
    value: 'Object.keys',type: 'paragraph'
summary: 'Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false.'
shouldWrap: 'true'
children: 
  type: 'link'
  title: 

  url: '/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyNames'
  children: 
    type: 'inlineCode'
    value: 'getOwnPropertyNames'
  type: 'text'
  value: ' ',type: 'paragraph'
summary: 'Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false.'
shouldWrap: 'true'
children: 
  type: 'link'
  title: 

  url: '/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertySymbols'
  children: 
    type: 'inlineCode'
    value: 'getOwnPropertySymbols'
```
##### td (132:7) => tableCell
```
type: 'paragraph'
summary: 'Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false.'
shouldWrap: 'true'
children: 
  type: 'link'
  title: 

  url: '/en-US/docs/Web/JavaScript/Reference/Statements/for...in'
  children: 
    type: 'inlineCode'
    value: 'for..in',type: 'paragraph'
summary: 'Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: '(excluding symbols)'
```
##### tr (123:5) => tableRow
```
type: 'html'
value: '<td><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys">Object.keys</a></code></p><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyNames">getOwnPropertyNames</a></code> </p><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertySymbols">getOwnPropertySymbols</a></code></p></td>',type: 'html'
value: '<td><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Statements/for...in">for..in</a></code></p><p>(excluding symbols)</p></td>'
```
##### td (150:7) => tableCell
```
type: 'paragraph'
summary: 'Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false.'
shouldWrap: 'true'
children: 
  type: 'link'
  title: 

  url: '/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyNames'
  children: 
    type: 'inlineCode'
    value: 'getOwnPropertyNames',type: 'paragraph'
summary: 'Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false.'
shouldWrap: 'true'
children: 
  type: 'link'
  title: 

  url: '/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertySymbols'
  children: 
    type: 'inlineCode'
    value: 'getOwnPropertySymbols'
```
##### tr (146:5) => tableRow
```
type: 'html'
value: '<td><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyNames">getOwnPropertyNames</a></code></p><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertySymbols">getOwnPropertySymbols</a></code></p></td>'
```
##### table (113:1) => table
```
type: 'html'
value: '<tr><th>Enumerable</th><td><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys">Object.keys</a></code></p><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyNames">getOwnPropertyNames</a></code> </p><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertySymbols">getOwnPropertySymbols</a></code></p></td><td><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Statements/for...in">for..in</a></code></p><p>(excluding symbols)</p></td><td>Not available without extra code</td></tr>',type: 'html'
value: '<tr><th>Enumerable and Nonenumerable</th><td><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyNames">getOwnPropertyNames</a></code></p><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertySymbols">getOwnPropertySymbols</a></code></p></td><td>Not available without extra code</td><td>Not available without extra code</td></tr>'
```
### [/en-US/docs/Web/JavaScript/Equality_comparisons_and_sameness](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Equality_comparisons_and_sameness)
#### Invalid AST transformations
##### tr (257:3) => tableRow
```
type: 'html'
value: '<th scope="col">x</th>',type: 'html'
value: '<th scope="col">y</th>',type: 'html'
value: '<th scope="col"><code>==</code></th>',type: 'html'
value: '<th scope="col"><code>===</code></th>',type: 'html'
value: '<th scope="col"><code>Object.is</code></th>',type: 'html'
value: '<th scope="col"><code>SameValueZero</code></th>'
```
##### table.standard-table (254:1) => table
```
type: 'text'
value: 'Sameness Comparisons',type: 'html'
value: '<tr><th scope="col">x</th><th scope="col">y</th><th scope="col"><code>==</code></th><th scope="col"><code>===</code></th><th scope="col"><code>Object.is</code></th><th scope="col"><code>SameValueZero</code></th></tr>'
```
##### dl (484:1) => paragraph
```
type: 'code'
lang: 'js'
meta: ''
value: 'let stoppingForce = obj.mass * -obj.velocity;',type: 'paragraph'
summary: 'There are four equality algorithms in ES2015:'
children: 
  type: 'text'
  value: 'If '
  type: 'inlineCode'
  value: 'obj.velocity'
  type: 'text'
  value: ' is '
  type: 'inlineCode'
  value: '0'
  type: 'text'
  value: ' (or computes to '
  type: 'inlineCode'
  value: '0'
  type: 'text'
  value: '), a '
  type: 'inlineCode'
  value: '-0'
  type: 'text'
  value: ' is introduced at that place and propagates out into '
  type: 'inlineCode'
  value: 'stoppingForce'
  type: 'text'
  value: '.'
```
### Missing conversion rules
- th[scope="col"] (258:4)
- th[scope="col"] (259:4)
- th[scope="col"] (260:4)
- th[scope="col"] (261:4)
- th[scope="col"] (262:4)
- th[scope="col"] (263:4)
### [/en-US/docs/Web/JavaScript/Guide/Control_flow_and_error_handling](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Control_flow_and_error_handling)
#### Invalid AST transformations
##### pre.brush:.js (37:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'statement_1'
```
##### pre.brush:.js (98:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'condition'
```
##### pre.brush:.js (118:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'condition_1'
```
##### pre.brush:.js (138:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'condition'
```
##### pre.brush:.js (222:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'expression'
```
##### pre.brush:.js (273:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'fruittype'
```
##### pre.brush:.js (330:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'expression'
```
##### pre.brush:.js (413:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'catchID'
```
### Missing conversion rules
- dfn (34:34)
### [/en-US/docs/Web/JavaScript/Guide/Details_of_the_Object_Model](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Details_of_the_Object_Model)
#### Invalid AST transformations
##### tr (60:3) => tableRow
```
type: 'html'
value: '<th scope="row">Category</th>',type: 'html'
value: '<th scope="col">Class-based (Java)</th>',type: 'html'
value: '<th scope="col">Prototype-based (JavaScript)</th>'
```
##### tr (67:3) => tableRow
```
type: 'html'
value: '<th scope="row">Class vs. Instance</th>'
```
##### tr (72:3) => tableRow
```
type: 'html'
value: '<th scope="row">Definition</th>'
```
##### tr (77:3) => tableRow
```
type: 'html'
value: '<th scope="row">Creation of new object</th>'
```
##### tr (82:3) => tableRow
```
type: 'html'
value: '<th scope="row">Construction of object hierarchy</th>'
```
##### tr (87:3) => tableRow
```
type: 'html'
value: '<th scope="row">Inheritance model</th>'
```
##### tr (92:3) => tableRow
```
type: 'html'
value: '<th scope="row">Extension of properties</th>'
```
##### table.standard-table (57:1) => table
```
type: 'text'
value: 'Comparison of class-based (Java) and prototype-based (JavaScript) object systems',type: 'html'
value: '<tr><th scope="row">Category</th><th scope="col">Class-based (Java)</th><th scope="col">Prototype-based (JavaScript)</th></tr>',type: 'html'
value: '<tr><th scope="row">Class vs. Instance</th><td>Class and instance are distinct entities.</td><td>All objects can inherit from another object.</td></tr>',type: 'html'
value: '<tr><th scope="row">Definition</th><td>Define a class with a class definition; instantiate a class with constructor methods.</td><td>Define and create a set of objects with constructor functions.</td></tr>',type: 'html'
value: '<tr><th scope="row">Creation of new object</th><td>Create a single object with the <code>new</code> operator.</td><td>Same.</td></tr>',type: 'html'
value: '<tr><th scope="row">Construction of object hierarchy</th><td>Construct an object hierarchy by using class definitions to define subclasses of existing classes.</td><td>Construct an object hierarchy by assigning an object as the prototype associated with a constructor function.</td></tr>',type: 'html'
value: '<tr><th scope="row">Inheritance model</th><td>Inherit properties by following the class chain.</td><td>Inherit properties by following the prototype chain.</td></tr>',type: 'html'
value: '<tr><th scope="row">Extension of properties</th><td>Class definition specifies <em>all</em> properties of all instances of a class. Cannot add properties dynamically at run time.</td><td>Constructor function or prototype specifies an <em>initial set</em> of properties. Can add or remove properties dynamically to individual objects or to the entire set of objects.</td></tr>'
```
### Missing conversion rules
- th[scope="row"] (61:4)
- th[scope="col"] (62:4)
- th[scope="col"] (63:4)
- th[scope="row"] (68:4)
- th[scope="row"] (73:4)
- th[scope="row"] (78:4)
- th[scope="row"] (83:4)
- th[scope="row"] (88:4)
- th[scope="row"] (93:4)
- figure (310:1)
- figure (319:1)
- figure (414:1)
### [/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
#### Invalid AST transformations
##### pre.brush:.js (44:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'operand1'
```
##### pre.brush:.js (51:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'operator'
```
##### pre.brush:.js (56:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'operand'
```
##### table.standard-table (71:1) => table
```
type: 'text'
value: 'Compound assignment operators'
```
##### tr (268:5) => tableRow
```
type: 'html'
value: '<th scope="col">Operator</th>',type: 'html'
value: '<th scope="col">Description</th>',type: 'html'
value: '<th scope="col">Examples returning true</th>'
```
##### td (280:7) => tableCell
```
type: 'paragraph'
summary: 'This chapter describes JavaScript's expressions and operators,
  including assignment, comparison, arithmetic, bitwise, logical, string, ternary and
  more.'
shouldWrap: 'true'
children: 
  type: 'inlineCode'
  value: '"3" == var1'
```
##### tr (275:5) => tableRow
```
type: 'html'
value: '<td><code>3 == var1</code><p><code>"3" == var1</code></p><code>3 == '3'</code></td>'
```
##### code (290:11) => text
```
type: 'element'
tagName: 'br'
properties: 

children: 

```
##### code (309:11) => text
```
type: 'element'
tagName: 'br'
properties: 

children: 

```
##### code (318:11) => text
```
type: 'element'
tagName: 'br'
properties: 

children: 

```
##### code (327:11) => text
```
type: 'element'
tagName: 'br'
properties: 

children: 

```
##### code (336:11) => text
```
type: 'element'
tagName: 'br'
properties: 

children: 

```
##### code (345:11) => text
```
type: 'element'
tagName: 'br'
properties: 

children: 

```
##### table.standard-table (265:1) => table
```
type: 'text'
value: 'Comparison operators',type: 'html'
value: '<tr><th scope="col">Operator</th><th scope="col">Description</th><th scope="col">Examples returning true</th></tr>',type: 'html'
value: '<tr><td><a href="/en-US/docs/Web/JavaScript/Reference/Operators#equality">Equal</a>
(<code>==</code>)</td><td>Returns <code>true</code> if the operands are equal.</td><td><code>3 == var1</code><p><code>"3" == var1</code></p><code>3 == '3'</code></td></tr>'
```
##### tr (453:5) => tableRow
```
type: 'html'
value: '<th scope="col">Operator</th>',type: 'html'
value: '<th scope="col">Usage</th>',type: 'html'
value: '<th scope="col">Description</th>'
```
##### table.standard-table (450:1) => table
```
type: 'text'
value: 'Bitwise operators',type: 'html'
value: '<tr><th scope="col">Operator</th><th scope="col">Usage</th><th scope="col">Description</th></tr>'
```
##### tr (540:5) => tableRow
```
type: 'html'
value: '<th scope="col">Expression</th>',type: 'html'
value: '<th scope="col">Result</th>',type: 'html'
value: '<th scope="col">Binary Description</th>'
```
##### table.standard-table (537:1) => table
```
type: 'text'
value: 'Bitwise operator examples',type: 'html'
value: '<tr><th scope="col">Expression</th><th scope="col">Result</th><th scope="col">Binary Description</th></tr>'
```
##### pre.brush:.js (769:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'condition'
```
##### tr (1022:5) => tableRow
```
type: 'html'
value: '<th scope="col">Operator type</th>',type: 'html'
value: '<th scope="col">Individual operators</th>'
```
##### table.standard-table (1019:1) => table
```
type: 'text'
value: 'Operator precedence',type: 'html'
value: '<tr><th scope="col">Operator type</th><th scope="col">Individual operators</th></tr>'
```
### Missing conversion rules
- th[scope="col"] (269:7)
- th[scope="col"] (270:7)
- th[scope="col"] (271:7)
- table.fullwidth-table (374:1)
- th[scope="col"] (454:7)
- th[scope="col"] (455:7)
- th[scope="col"] (456:7)
- th[scope="col"] (541:7)
- th[scope="col"] (542:7)
- th[scope="col"] (543:7)
- table.fullwidth-table (593:1)
- table.fullwidth-table (646:1)
- th[scope="col"] (1023:7)
- th[scope="col"] (1024:7)
### [/en-US/docs/Web/JavaScript/Guide/Grammar_and_types](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Grammar_and_types)
#### Invalid AST transformations
##### code (242:122) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'variable'
```
##### tr (626:3) => tableRow
```
type: 'html'
value: '<th scope="col">Character</th>',type: 'html'
value: '<th scope="col">Meaning</th>'
```
##### code (673:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'XXX'
```
##### code (678:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'XX'
```
##### td (679:4) => tableCell
```
type: 'paragraph'
summary: 'This chapter discusses JavaScript's basic grammar, variable declarations, data types and literals.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'The character with the Latin-1 encoding specified by the two hexadecimal digits '
  type: 'emphasis'
  children: 
    type: 'text'
    value: 'XX'
  type: 'text'
  value: ' between '
  type: 'inlineCode'
  value: '00'
  type: 'text'
  value: ' and '
  type: 'inlineCode'
  value: 'FF'
  type: 'text'
  value: '.'
  type: 'break'
  type: 'text'
  value: 'For example, '
  type: 'inlineCode'
  value: '\xA9'
  type: 'text'
  value: ' is the hexadecimal sequence for the copyright symbol.'
```
##### tr (677:3) => tableRow
```
type: 'html'
value: '<td><p>The character with the Latin-1 encoding specified by the two hexadecimal digits <em>XX</em> between <code>00</code> and <code>FF</code>.<br>For example, <code>\xA9</code> is the hexadecimal sequence for the copyright symbol.</p></td>'
```
##### code (685:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'XXXX'
```
##### code (690:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: '{XXXXX}'
```
##### table.standard-table (623:1) => table
```
type: 'text'
value: 'Table: JavaScript special characters',type: 'html'
value: '<tr><th scope="col">Character</th><th scope="col">Meaning</th></tr>',type: 'html'
value: '<tr><td><code>\x<em>XX</em></code></td><td><p>The character with the Latin-1 encoding specified by the two hexadecimal digits <em>XX</em> between <code>00</code> and <code>FF</code>.<br>For example, <code>\xA9</code> is the hexadecimal sequence for the copyright symbol.</p></td></tr>'
```
### Missing conversion rules
- th[scope="col"] (627:4)
- th[scope="col"] (628:4)
### [/en-US/docs/Web/JavaScript/Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)
#### Invalid AST transformations
##### p.summary (12:1) => text
```
type: 'element'
tagName: 'a'
properties: 
  href: '/en-US/docs/Web/JavaScript'
children: 
  type: 'text'
  value: 'JavaScript'
```
### [/en-US/docs/Web/JavaScript/Guide/Indexed_collections](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Indexed_collections)
#### Invalid AST transformations
##### pre.brush:.js (26:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'element0'
```
##### code (31:4) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'element0'
```
##### pre.brush:.js (37:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'arrayLength'
```
##### code (75:12) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'N'
```
##### code (395:97) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'callback'
```
##### tr (497:3) => tableRow
```
type: 'html'
value: '<th class="header" scope="col">Type</th>',type: 'html'
value: '<th class="header" scope="col">Value Range</th>',type: 'html'
value: '<th class="header" scope="col">Size in bytes</th>',type: 'html'
value: '<th class="header" scope="col">Description</th>',type: 'html'
value: '<th class="header" scope="col">Web IDL type</th>',type: 'html'
value: '<th class="header" scope="col">Equivalent C type</th>'
```
##### table.standard-table (495:1) => table
```
type: 'html'
value: '<tr><th class="header" scope="col">Type</th><th class="header" scope="col">Value Range</th><th class="header" scope="col">Size in bytes</th><th class="header" scope="col">Description</th><th class="header" scope="col">Web IDL type</th><th class="header" scope="col">Equivalent C type</th></tr>'
```
### Missing conversion rules
- dfn (16:11)
- th.header[scope="col"] (498:4)
- th.header[scope="col"] (499:4)
- th.header[scope="col"] (500:4)
- th.header[scope="col"] (501:4)
- th.header[scope="col"] (502:4)
- th.header[scope="col"] (503:4)
### [/en-US/docs/Web/JavaScript/Guide/Introduction](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Introduction)
#### Invalid AST transformations
##### tr (66:3) => tableRow
```
type: 'html'
value: '<th scope="col">JavaScript</th>',type: 'html'
value: '<th scope="col">Java</th>'
```
##### table.standard-table (63:1) => table
```
type: 'text'
value: 'JavaScript compared to Java',type: 'html'
value: '<tr><th scope="col">JavaScript</th><th scope="col">Java</th></tr>'
```
### Missing conversion rules
- th[scope="col"] (67:4)
- th[scope="col"] (68:4)
- kbd (115:29)
- kbd (115:45)
- kbd (115:62)
- kbd (115:99)
- kbd (115:114)
- kbd (115:132)
- kbd (148:10)
- kbd (148:25)
- kbd (148:45)
- kbd (148:61)
### [/en-US/docs/Web/JavaScript/Guide/Iterators_and_Generators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Iterators_and_Generators)
#### Invalid AST transformations
##### pre.brush:.js (45:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'start'
```
##### pre.brush:.js (93:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'start'
```
##### pre.brush:.js (112:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'it'
```
##### code (204:42) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### code (232:351) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'value'
```
### [/en-US/docs/Web/JavaScript/Guide/Keyed_collections](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Keyed_collections)
#### Invalid AST transformations
##### code (23:271) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'key'
  type: 'element'
  tagName: 'var'
  properties: 

  children: 
    type: 'text'
    value: ', '
    type: 'element'
    tagName: 'var'
    properties: 

    children: 
      type: 'text'
      value: 'value'
    type: 'text'
    value: ']'
```
### [/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)
#### Invalid AST transformations
##### p.summary (15:1) => text
```
type: 'element'
tagName: 'a'
properties: 
  href: '/en-US/docs/Web/JavaScript/Guide'
children: 
  type: 'text'
  value: 'JavaScript Guide'
```
##### pre.brush:.js (133:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'statement'
```
##### code (150:20) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'i'
```
##### pre.brush:.js (164:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'condition'
```
##### code (235:17) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'label'
```
##### code (236:22) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'statement'
```
##### pre.brush:.js (264:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'label'
```
##### pre.brush:.js (327:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'label'
```
##### pre.brush:.js (450:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'variable'
```
### [/en-US/docs/Web/JavaScript/Guide/Meta_programming](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Meta_programming)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'handler'
```
##### code (76:63) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'proxy'
```
##### code (76:153) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'target'
```
##### td (73:4) => tableCell
```
type: 'list'
ordered: 'false'
start: 

spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'getPrototypeOf'
      type: 'text'
      value: ' method must return an object or '
      type: 'inlineCode'
      value: 'null'
      type: 'text'
      value: '.'
  type: 'listItem'
  spread: 'true'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'If '
      type: 'inlineCode'
      value: 'target'
      type: 'text'
      value: ' is not extensible, '
    type: 'html'
    value: '<code>Object.getPrototypeOf(<var>proxy</var>)</code>'
    type: 'paragraph'
    children: 
      type: 'text'
      value: ' method must return the same value as '
    type: 'html'
    value: '<code>Object.getPrototypeOf(<var>target</var>)</code>'
    type: 'paragraph'
    children: 
      type: 'text'
      value: '.'
```
##### tr (66:3) => tableRow
```
type: 'html'
value: '<td><ul><li><code>getPrototypeOf</code> method must return an object or <code>null</code>.</li><li>If <code><var>target</var></code> is not extensible, <code>Object.getPrototypeOf(<var>proxy</var>)</code> method must return the same value as <code>Object.getPrototypeOf(<var>target</var>)</code>.</li></ul></td>'
```
##### code (84:124) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'target'
```
##### code (90:8) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'proxy'
```
##### code (90:89) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'target'
```
##### code (96:8) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'proxy'
```
##### code (96:98) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'proxy'
```
##### code (109:24) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'target'
```
##### td (102:4) => tableCell
```
type: 'list'
ordered: 'false'
start: 

spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'getOwnPropertyDescriptor'
      type: 'text'
      value: ' must return an object or '
      type: 'inlineCode'
      value: 'undefined'
      type: 'text'
      value: '.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'A property cannot be reported as non-existent if it exists as a non-configurable own property of '
      type: 'inlineCode'
      value: 'target'
      type: 'text'
      value: '.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'A property cannot be reported as non-existent if it exists as an own property of '
      type: 'inlineCode'
      value: 'target'
      type: 'text'
      value: ' and '
      type: 'inlineCode'
      value: 'target'
      type: 'text'
      value: ' is not extensible.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'A property cannot be reported as existent if it does not exists as an own property of '
      type: 'inlineCode'
      value: 'target'
      type: 'text'
      value: ' and '
      type: 'inlineCode'
      value: 'target'
      type: 'text'
      value: ' is not extensible.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'A property cannot be reported as non-configurable if it does not exist as an own property of '
      type: 'inlineCode'
      value: 'target'
      type: 'text'
      value: ' or if it exists as a configurable own property of '
      type: 'inlineCode'
      value: 'target'
      type: 'text'
      value: '.'
  type: 'listItem'
  spread: 'true'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'The result of '
    type: 'html'
    value: '<code>Object.getOwnPropertyDescriptor(<var>target</var>)</code>'
    type: 'paragraph'
    children: 
      type: 'text'
      value: ' can be applied to '
      type: 'inlineCode'
      value: 'target'
      type: 'text'
      value: ' using '
      type: 'inlineCode'
      value: 'Object.defineProperty'
      type: 'text'
      value: ' and will not throw an exception.'
```
##### tr (98:3) => tableRow
```
type: 'html'
value: '<td><ul><li><code>getOwnPropertyDescriptor</code> must return an object or <code>undefined</code>.</li><li>A property cannot be reported as non-existent if it exists as a non-configurable own property of <code><var>target</var></code>.</li><li>A property cannot be reported as non-existent if it exists as an own property of <code><var>target</var></code> and <code><var>target</var></code> is not extensible.</li><li>A property cannot be reported as existent if it does not exists as an own property of <code><var>target</var></code> and <code><var>target</var></code> is not extensible.</li><li>A property cannot be reported as non-configurable if it does not exist as an own property of <code><var>target</var></code> or if it exists as a configurable own property of <code><var>target</var></code>.</li><li>The result of <code>Object.getOwnPropertyDescriptor(<var>target</var>)</code> can be applied to <code><var>target</var></code> using <code>Object.defineProperty</code> and will not throw an exception.</li></ul></td>'
```
##### code (122:73) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'target'
```
##### td (117:4) => tableCell
```
type: 'list'
ordered: 'false'
start: 

spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'A property cannot be added if '
      type: 'inlineCode'
      value: 'target'
      type: 'text'
      value: ' is not extensible.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'A property cannot be added as (or modified to be) non-configurable if it does not exist as a non-configurable own property of '
      type: 'inlineCode'
      value: 'target'
      type: 'text'
      value: '.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'A property may not be non-configurable if a corresponding configurable property of '
      type: 'inlineCode'
      value: 'target'
      type: 'text'
      value: ' exists.'
  type: 'listItem'
  spread: 'true'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'If a property has a corresponding target object property, then '
    type: 'html'
    value: '<code>Object.defineProperty(<var>target</var>, <var>prop</var>, <var>descriptor</var>)</code>'
    type: 'paragraph'
    children: 
      type: 'text'
      value: ' will not throw an exception.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'In strict mode, a '
      type: 'inlineCode'
      value: 'false'
      type: 'text'
      value: ' value returned from the '
      type: 'inlineCode'
      value: 'defineProperty'
      type: 'text'
      value: ' handler will throw a {{anN4cmVmKCJUeXBlRXJyb3IiKQ==}} exception.'
```
##### tr (113:3) => tableRow
```
type: 'html'
value: '<td><ul><li>A property cannot be added if <code><var>target</var></code> is not extensible.</li><li>A property cannot be added as (or modified to be) non-configurable if it does not exist as a non-configurable own property of <code><var>target</var></code>.</li><li>A property may not be non-configurable if a corresponding configurable property of <code><var>target</var></code> exists.</li><li>If a property has a corresponding target object property, then <code>Object.defineProperty(<var>target</var>, <var>prop</var>, <var>descriptor</var>)</code> will not throw an exception.</li><li>In strict mode, a <code>false</code> value returned from the <code>defineProperty</code> handler will throw a {{anN4cmVmKCJUeXBlRXJyb3IiKQ==}} exception.</li></ul></td>'
```
##### code (134:10) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'proxy'
```
##### td (129:4) => tableCell
```
type: 'list'
spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'Property query'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'inlineCode'
          value: 'foo in proxy'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'Inherited property query'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'html'
          value: '<code>foo in Object.create(<var>proxy</var>)</code>'
          type: 'break'
          type: 'text'
          value: '{{anN4cmVmKCJSZWZsZWN0LmhhcygpIik=}}'
```
##### td (138:4) => tableCell
```
type: 'list'
ordered: 'false'
start: 

spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'A property cannot be reported as non-existent, if it exists as a non-configurable own property of '
      type: 'inlineCode'
      value: 'target'
      type: 'text'
      value: '.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'A property cannot be reported as non-existent if it exists as an own property of '
      type: 'inlineCode'
      value: 'target'
      type: 'text'
      value: ' and '
      type: 'inlineCode'
      value: 'target'
      type: 'text'
      value: ' is not extensible.'
```
##### tr (127:3) => tableRow
```
type: 'html'
value: '<td><dl><dt>Property query</dt><dd><code>foo in proxy</code></dd><dt>Inherited property query</dt><dd><code>foo in Object.create(<var>proxy</var>)</code><br>{{anN4cmVmKCJSZWZsZWN0LmhhcygpIik=}}</dd></dl></td>',type: 'html'
value: '<td><ul><li>A property cannot be reported as non-existent, if it exists as a non-configurable own property of <code><var>target</var></code>.</li><li>A property cannot be reported as non-existent if it exists as an own property of <code><var>target</var></code> and <code><var>target</var></code> is not extensible.</li></ul></td>'
```
##### code (150:10) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'proxy'
```
##### code (151:6) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'proxy'
```
##### code (153:10) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'proxy'
```
##### td (147:4) => tableCell
```
type: 'list'
spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'Property access'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'html'
          value: '<code><var>proxy</var>[foo]</code>'
          type: 'break'
          type: 'html'
          value: '<code><var>proxy</var>.bar</code>'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'Inherited property access'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'html'
          value: '<code>Object.create(<var>proxy</var>)[foo]</code>'
          type: 'break'
          type: 'text'
          value: '{{anN4cmVmKCJSZWZsZWN0LmdldCgpIik=}}'
```
##### td (157:4) => tableCell
```
type: 'list'
ordered: 'false'
start: 

spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'The value reported for a property must be the same as the value of the corresponding '
      type: 'inlineCode'
      value: 'target'
      type: 'text'
      value: ' property if '
      type: 'inlineCode'
      value: 'target'
      type: 'text'
      value: ''s property is a non-writable, non-configurable data property.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'The value reported for a property must be '
      type: 'inlineCode'
      value: 'undefined'
      type: 'text'
      value: ' if the corresponding '
      type: 'inlineCode'
      value: 'target'
      type: 'text'
      value: ' property is non-configurable accessor property that has undefined as its '
      type: 'inlineCode'
      value: '[[Get]]'
      type: 'text'
      value: ' attribute.'
```
##### tr (145:3) => tableRow
```
type: 'html'
value: '<td><dl><dt>Property access</dt><dd><code><var>proxy</var>[foo]</code><br><code><var>proxy</var>.bar</code></dd><dt>Inherited property access</dt><dd><code>Object.create(<var>proxy</var>)[foo]</code><br>{{anN4cmVmKCJSZWZsZWN0LmdldCgpIik=}}</dd></dl></td>',type: 'html'
value: '<td><ul><li>The value reported for a property must be the same as the value of the corresponding <code><var>target</var></code> property if <code><var>target</var></code>'s property is a non-writable, non-configurable data property.</li><li>The value reported for a property must be <code>undefined</code> if the corresponding <code><var>target</var></code> property is non-configurable accessor property that has undefined as its <code>[[Get]]</code> attribute.</li></ul></td>'
```
##### code (169:10) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'proxy'
```
##### code (170:6) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'proxy'
```
##### code (172:10) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'proxy'
```
##### td (166:4) => tableCell
```
type: 'list'
spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'Property assignment'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'html'
          value: '<code><var>proxy</var>[foo] = bar</code>'
          type: 'break'
          type: 'html'
          value: '<code><var>proxy</var>.foo = bar</code>'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'Inherited property assignment'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'html'
          value: '<code>Object.create(<var>proxy</var>)[foo] = bar</code>'
          type: 'break'
          type: 'text'
          value: '{{anN4cmVmKCJSZWZsZWN0LnNldCgpIik=}}'
```
##### td (176:4) => tableCell
```
type: 'list'
ordered: 'false'
start: 

spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'Cannot change the value of a property to be different from the value of the corresponding '
      type: 'inlineCode'
      value: 'target'
      type: 'text'
      value: ' property if the corresponding '
      type: 'inlineCode'
      value: 'target'
      type: 'text'
      value: ' property is a non-writable, non-configurable data property.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'Cannot set the value of a property if the corresponding '
      type: 'inlineCode'
      value: 'target'
      type: 'text'
      value: ' property is a non-configurable accessor property that has '
      type: 'inlineCode'
      value: 'undefined'
      type: 'text'
      value: ' as its '
      type: 'inlineCode'
      value: '[[Set]]'
      type: 'text'
      value: ' attribute.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'In strict mode, a '
      type: 'inlineCode'
      value: 'false'
      type: 'text'
      value: ' return value from the '
      type: 'inlineCode'
      value: 'set'
      type: 'text'
      value: ' handler will throw a {{anN4cmVmKCJUeXBlRXJyb3IiKQ==}} exception.'
```
##### tr (164:3) => tableRow
```
type: 'html'
value: '<td><dl><dt>Property assignment</dt><dd><code><var>proxy</var>[foo] = bar</code><br><code><var>proxy</var>.foo = bar</code></dd><dt>Inherited property assignment</dt><dd><code>Object.create(<var>proxy</var>)[foo] = bar</code><br>{{anN4cmVmKCJSZWZsZWN0LnNldCgpIik=}}</dd></dl></td>',type: 'html'
value: '<td><ul><li>Cannot change the value of a property to be different from the value of the corresponding <code><var>target</var></code> property if the corresponding <code><var>target</var></code> property is a non-writable, non-configurable data property.</li><li>Cannot set the value of a property if the corresponding <code><var>target</var></code> property is a non-configurable accessor property that has <code>undefined</code> as its <code>[[Set]]</code> attribute.</li><li>In strict mode, a <code>false</code> return value from the <code>set</code> handler will throw a {{anN4cmVmKCJUeXBlRXJyb3IiKQ==}} exception.</li></ul></td>'
```
##### code (189:10) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'proxy'
```
##### code (190:6) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'proxy'
```
##### td (186:4) => tableCell
```
type: 'list'
spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'Property deletion'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'html'
          value: '<code>delete <var>proxy</var>[foo]</code>'
          type: 'break'
          type: 'html'
          value: '<code>delete <var>proxy</var>.foo</code>'
          type: 'break'
          type: 'text'
          value: '{{anN4cmVmKCJSZWZsZWN0LmRlbGV0ZVByb3BlcnR5KCkiKQ==}}'
```
##### tr (184:3) => tableRow
```
type: 'html'
value: '<td><dl><dt>Property deletion</dt><dd><code>delete <var>proxy</var>[foo]</code><br><code>delete <var>proxy</var>.foo</code><br>{{anN4cmVmKCJSZWZsZWN0LmRlbGV0ZVByb3BlcnR5KCkiKQ==}}</dd></dl></td>'
```
##### code (201:10) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'proxy'
```
##### td (198:4) => tableCell
```
type: 'list'
spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'Property enumeration / '
      type: 'inlineCode'
      value: 'for...in'
      type: 'text'
      value: ':'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'html'
          value: '<code>for (let name in <var>proxy</var>) {...}</code>'
          type: 'break'
          type: 'text'
          value: '{{anN4cmVmKCJSZWZsZWN0LmVudW1lcmF0ZSgpIik=}}'
```
##### tr (196:3) => tableRow
```
type: 'html'
value: '<td><dl><dt>Property enumeration / <code>for...in</code>:</dt><dd><code>for (let name in <var>proxy</var>) {...}</code><br>{{anN4cmVmKCJSZWZsZWN0LmVudW1lcmF0ZSgpIik=}}</dd></dl></td>'
```
##### td (213:4) => tableCell
```
type: 'list'
ordered: 'false'
start: 

spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'The result of '
      type: 'inlineCode'
      value: 'ownKeys'
      type: 'text'
      value: ' is a List.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'The Type of each result List element is either {{anN4cmVmKCJTdHJpbmciKQ==}} or {{anN4cmVmKCJTeW1ib2wiKQ==}}.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'The result List must contain the keys of all non-configurable own properties of '
      type: 'inlineCode'
      value: 'target'
      type: 'text'
      value: '.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'If the '
      type: 'inlineCode'
      value: 'target'
      type: 'text'
      value: ' object is not extensible, then the result List must contain all the keys of the own properties of '
      type: 'inlineCode'
      value: 'target'
      type: 'text'
      value: ' and no other values.'
```
##### tr (207:3) => tableRow
```
type: 'html'
value: '<td><ul><li>The result of <code>ownKeys</code> is a List.</li><li>The Type of each result List element is either {{anN4cmVmKCJTdHJpbmciKQ==}} or {{anN4cmVmKCJTeW1ib2wiKQ==}}.</li><li>The result List must contain the keys of all non-configurable own properties of <code><var>target</var></code>.</li><li>If the <code><var>target</var></code> object is not extensible, then the result List must contain all the keys of the own properties of <code><var>target</var></code> and no other values.</li></ul></td>'
```
##### code (227:40) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'handler'
```
##### table.standard-table (57:1) => table
```
type: 'html'
value: '<tr><td>{{anN4cmVmKCJHbG9iYWxfT2JqZWN0cy9Qcm94eS9Qcm94eS9nZXRQcm90b3R5cGVPZiIsICJoYW5kbGVyLmdldFByb3RvdHlwZU9mKCkiKQ==}}</td><td>{{anN4cmVmKCJPYmplY3QuZ2V0UHJvdG90eXBlT2YoKSIp}}<br>{{anN4cmVmKCJSZWZsZWN0LmdldFByb3RvdHlwZU9mKCkiKQ==}}<br>{{anN4cmVmKCJPYmplY3QvcHJvdG8iLCAiX19wcm90b19fIik=}}<br>{{anN4cmVmKCJPYmplY3QucHJvdG90eXBlLmlzUHJvdG90eXBlT2YoKSIp}}<br>{{anN4cmVmKCJPcGVyYXRvcnMvaW5zdGFuY2VvZiIsICJpbnN0YW5jZW9mIik=}}</td><td><ul><li><code>getPrototypeOf</code> method must return an object or <code>null</code>.</li><li>If <code><var>target</var></code> is not extensible, <code>Object.getPrototypeOf(<var>proxy</var>)</code> method must return the same value as <code>Object.getPrototypeOf(<var>target</var>)</code>.</li></ul></td></tr>',type: 'html'
value: '<tr><td>{{anN4cmVmKCJHbG9iYWxfT2JqZWN0cy9Qcm94eS9Qcm94eS9nZXRPd25Qcm9wZXJ0eURlc2NyaXB0b3IiLCAiaGFuZGxlci5nZXRPd25Qcm9wZXJ0eURlc2NyaXB0b3IoKSIp}}</td><td>{{anN4cmVmKCJPYmplY3QuZ2V0T3duUHJvcGVydHlEZXNjcmlwdG9yKCkiKQ==}}<br>{{anN4cmVmKCJSZWZsZWN0LmdldE93blByb3BlcnR5RGVzY3JpcHRvcigpIik=}}</td><td><ul><li><code>getOwnPropertyDescriptor</code> must return an object or <code>undefined</code>.</li><li>A property cannot be reported as non-existent if it exists as a non-configurable own property of <code><var>target</var></code>.</li><li>A property cannot be reported as non-existent if it exists as an own property of <code><var>target</var></code> and <code><var>target</var></code> is not extensible.</li><li>A property cannot be reported as existent if it does not exists as an own property of <code><var>target</var></code> and <code><var>target</var></code> is not extensible.</li><li>A property cannot be reported as non-configurable if it does not exist as an own property of <code><var>target</var></code> or if it exists as a configurable own property of <code><var>target</var></code>.</li><li>The result of <code>Object.getOwnPropertyDescriptor(<var>target</var>)</code> can be applied to <code><var>target</var></code> using <code>Object.defineProperty</code> and will not throw an exception.</li></ul></td></tr>',type: 'html'
value: '<tr><td>{{anN4cmVmKCJHbG9iYWxfT2JqZWN0cy9Qcm94eS9Qcm94eS9kZWZpbmVQcm9wZXJ0eSIsICJoYW5kbGVyLmRlZmluZVByb3BlcnR5KCkiKQ==}}</td><td>{{anN4cmVmKCJPYmplY3QuZGVmaW5lUHJvcGVydHkoKSIp}}<br>{{anN4cmVmKCJSZWZsZWN0LmRlZmluZVByb3BlcnR5KCkiKQ==}}</td><td><ul><li>A property cannot be added if <code><var>target</var></code> is not extensible.</li><li>A property cannot be added as (or modified to be) non-configurable if it does not exist as a non-configurable own property of <code><var>target</var></code>.</li><li>A property may not be non-configurable if a corresponding configurable property of <code><var>target</var></code> exists.</li><li>If a property has a corresponding target object property, then <code>Object.defineProperty(<var>target</var>, <var>prop</var>, <var>descriptor</var>)</code> will not throw an exception.</li><li>In strict mode, a <code>false</code> value returned from the <code>defineProperty</code> handler will throw a {{anN4cmVmKCJUeXBlRXJyb3IiKQ==}} exception.</li></ul></td></tr>',type: 'html'
value: '<tr><td>{{anN4cmVmKCJHbG9iYWxfT2JqZWN0cy9Qcm94eS9Qcm94eS9oYXMiLCAiaGFuZGxlci5oYXMoKSIp}}</td><td><dl><dt>Property query</dt><dd><code>foo in proxy</code></dd><dt>Inherited property query</dt><dd><code>foo in Object.create(<var>proxy</var>)</code><br>{{anN4cmVmKCJSZWZsZWN0LmhhcygpIik=}}</dd></dl></td><td><ul><li>A property cannot be reported as non-existent, if it exists as a non-configurable own property of <code><var>target</var></code>.</li><li>A property cannot be reported as non-existent if it exists as an own property of <code><var>target</var></code> and <code><var>target</var></code> is not extensible.</li></ul></td></tr>',type: 'html'
value: '<tr><td>{{anN4cmVmKCJHbG9iYWxfT2JqZWN0cy9Qcm94eS9Qcm94eS9nZXQiLCAiaGFuZGxlci5nZXQoKSIp}}</td><td><dl><dt>Property access</dt><dd><code><var>proxy</var>[foo]</code><br><code><var>proxy</var>.bar</code></dd><dt>Inherited property access</dt><dd><code>Object.create(<var>proxy</var>)[foo]</code><br>{{anN4cmVmKCJSZWZsZWN0LmdldCgpIik=}}</dd></dl></td><td><ul><li>The value reported for a property must be the same as the value of the corresponding <code><var>target</var></code> property if <code><var>target</var></code>'s property is a non-writable, non-configurable data property.</li><li>The value reported for a property must be <code>undefined</code> if the corresponding <code><var>target</var></code> property is non-configurable accessor property that has undefined as its <code>[[Get]]</code> attribute.</li></ul></td></tr>',type: 'html'
value: '<tr><td>{{anN4cmVmKCJHbG9iYWxfT2JqZWN0cy9Qcm94eS9Qcm94eS9zZXQiLCAiaGFuZGxlci5zZXQoKSIp}}</td><td><dl><dt>Property assignment</dt><dd><code><var>proxy</var>[foo] = bar</code><br><code><var>proxy</var>.foo = bar</code></dd><dt>Inherited property assignment</dt><dd><code>Object.create(<var>proxy</var>)[foo] = bar</code><br>{{anN4cmVmKCJSZWZsZWN0LnNldCgpIik=}}</dd></dl></td><td><ul><li>Cannot change the value of a property to be different from the value of the corresponding <code><var>target</var></code> property if the corresponding <code><var>target</var></code> property is a non-writable, non-configurable data property.</li><li>Cannot set the value of a property if the corresponding <code><var>target</var></code> property is a non-configurable accessor property that has <code>undefined</code> as its <code>[[Set]]</code> attribute.</li><li>In strict mode, a <code>false</code> return value from the <code>set</code> handler will throw a {{anN4cmVmKCJUeXBlRXJyb3IiKQ==}} exception.</li></ul></td></tr>',type: 'html'
value: '<tr><td>{{anN4cmVmKCJHbG9iYWxfT2JqZWN0cy9Qcm94eS9Qcm94eS9kZWxldGVQcm9wZXJ0eSIsICJoYW5kbGVyLmRlbGV0ZVByb3BlcnR5KCkiKQ==}}</td><td><dl><dt>Property deletion</dt><dd><code>delete <var>proxy</var>[foo]</code><br><code>delete <var>proxy</var>.foo</code><br>{{anN4cmVmKCJSZWZsZWN0LmRlbGV0ZVByb3BlcnR5KCkiKQ==}}</dd></dl></td><td>A property cannot be deleted if it exists as a non-configurable own property of <code><var>target</var></code>.</td></tr>',type: 'html'
value: '<tr><td>{{anN4cmVmKCJHbG9iYWxfT2JqZWN0cy9Qcm94eS9oYW5kbGVyL2VudW1lcmF0ZSIsICJoYW5kbGVyLmVudW1lcmF0ZSgpIik=}}</td><td><dl><dt>Property enumeration / <code>for...in</code>:</dt><dd><code>for (let name in <var>proxy</var>) {...}</code><br>{{anN4cmVmKCJSZWZsZWN0LmVudW1lcmF0ZSgpIik=}}</dd></dl></td><td>The <code>enumerate</code> method must return an object.</td></tr>',type: 'html'
value: '<tr><td>{{anN4cmVmKCJHbG9iYWxfT2JqZWN0cy9Qcm94eS9Qcm94eS9vd25LZXlzIiwgImhhbmRsZXIub3duS2V5cygpIik=}}</td><td>{{anN4cmVmKCJPYmplY3QuZ2V0T3duUHJvcGVydHlOYW1lcygpIik=}}<br>{{anN4cmVmKCJPYmplY3QuZ2V0T3duUHJvcGVydHlTeW1ib2xzKCkiKQ==}}<br>{{anN4cmVmKCJPYmplY3Qua2V5cygpIik=}}<br>{{anN4cmVmKCJSZWZsZWN0Lm93bktleXMoKSIp}}</td><td><ul><li>The result of <code>ownKeys</code> is a List.</li><li>The Type of each result List element is either {{anN4cmVmKCJTdHJpbmciKQ==}} or {{anN4cmVmKCJTeW1ib2wiKQ==}}.</li><li>The result List must contain the keys of all non-configurable own properties of <code><var>target</var></code>.</li><li>If the <code><var>target</var></code> object is not extensible, then the result List must contain all the keys of the own properties of <code><var>target</var></code> and no other values.</li></ul></td></tr>'
```
### Missing conversion rules
- dfn (34:44)
- dfn (34:115)
- dfn (34:194)
### [/en-US/docs/Web/JavaScript/Guide/Numbers_and_dates](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Numbers_and_dates)
#### Invalid AST transformations
##### tr (102:3) => tableRow
```
type: 'html'
value: '<th scope="col">Property</th>',type: 'html'
value: '<th scope="col">Description</th>'
```
##### table.standard-table (99:1) => table
```
type: 'text'
value: 'Properties of ',type: 'inlineCode'
value: 'Number',type: 'html'
value: '<tr><th scope="col">Property</th><th scope="col">Description</th></tr>'
```
##### table.standard-table (143:1) => table
```
type: 'text'
value: 'Methods of ',type: 'inlineCode'
value: 'Number'
```
##### tr (186:3) => tableRow
```
type: 'html'
value: '<th scope="col">Method</th>',type: 'html'
value: '<th scope="col">Description</th>'
```
##### table.standard-table (183:1) => table
```
type: 'text'
value: 'Methods of ',type: 'inlineCode'
value: 'Number.prototype',type: 'html'
value: '<tr><th scope="col">Method</th><th scope="col">Description</th></tr>'
```
##### tr (226:3) => tableRow
```
type: 'html'
value: '<th scope="col">Method</th>',type: 'html'
value: '<th scope="col">Description</th>'
```
##### td (253:4) => tableCell
```
type: 'paragraph'
summary: 'This chapter introduces the concepts, objects and functions used to work with and perform calculations using numbers and dates in JavaScript. This includes using numbers written in various bases including decimal, binary, and hexadecimal, as well as the use of the global {{anN4cmVmKCJNYXRoIik=}} object to perform a wide variety of mathematical operations on numbers.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: '{{anN4cmVmKCJNYXRoLnBvdyIsICJwb3coKSIp}}, {{anN4cmVmKCJNYXRoLmV4cCIsICJleHAoKSIp}}, {{anN4cmVmKCJNYXRoLmV4cG0xIiwgImV4cG0xKCkiKQ==}}, {{anN4cmVmKCJNYXRoLmxvZzEwIiwgImxvZzEwKCkiKQ==}}, {{anN4cmVmKCJNYXRoLmxvZzFwIiwgImxvZzFwKCkiKQ==}}, {{anN4cmVmKCJNYXRoLmxvZzIiLCAibG9nMigpIik=}}'
```
##### tr (252:3) => tableRow
```
type: 'html'
value: '<td><p>{{anN4cmVmKCJNYXRoLnBvdyIsICJwb3coKSIp}}, {{anN4cmVmKCJNYXRoLmV4cCIsICJleHAoKSIp}}, {{anN4cmVmKCJNYXRoLmV4cG0xIiwgImV4cG0xKCkiKQ==}}, {{anN4cmVmKCJNYXRoLmxvZzEwIiwgImxvZzEwKCkiKQ==}}, {{anN4cmVmKCJNYXRoLmxvZzFwIiwgImxvZzFwKCkiKQ==}}, {{anN4cmVmKCJNYXRoLmxvZzIiLCAibG9nMigpIik=}}</p></td>'
```
##### table.standard-table (223:1) => table
```
type: 'text'
value: 'Methods of ',type: 'inlineCode'
value: 'Math',type: 'html'
value: '<tr><th scope="col">Method</th><th scope="col">Description</th></tr>',type: 'html'
value: '<tr><td><p>{{anN4cmVmKCJNYXRoLnBvdyIsICJwb3coKSIp}}, {{anN4cmVmKCJNYXRoLmV4cCIsICJleHAoKSIp}}, {{anN4cmVmKCJNYXRoLmV4cG0xIiwgImV4cG0xKCkiKQ==}}, {{anN4cmVmKCJNYXRoLmxvZzEwIiwgImxvZzEwKCkiKQ==}}, {{anN4cmVmKCJNYXRoLmxvZzFwIiwgImxvZzFwKCkiKQ==}}, {{anN4cmVmKCJNYXRoLmxvZzIiLCAibG9nMigpIik=}}</p></td><td>Exponential and logarithmic functions.</td></tr>'
```
### Missing conversion rules
- th[scope="col"] (103:4)
- th[scope="col"] (104:4)
- dfn (176:68)
- th[scope="col"] (187:4)
- th[scope="col"] (188:4)
- th[scope="col"] (227:4)
- th[scope="col"] (228:4)
### [/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Assertions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Assertions)
#### Invalid AST transformations
##### tr (26:3) => tableRow
```
type: 'html'
value: '<th scope="col">Characters</th>',type: 'html'
value: '<th scope="col">Meaning</th>'
```
##### td (34:4) => tableCell
```
type: 'paragraph'
summary: 'Assertions include boundaries, which indicate the beginnings and endings of lines and words, and other patterns indicating in some way that a match is possible (including look-ahead, look-behind, and conditional expressions).'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Matches the beginning of input. If the multiline flag is set to true, also matches immediately after a line break character. For example, '
  type: 'inlineCode'
  value: '/^A/'
  type: 'text'
  value: ' does not match the "A" in "an A", but does match the first "A" in "An A".',type: 'blockquote'
children: 
  type: 'paragraph'
  children: 
    type: 'strong'
    children: 
      type: 'text'
      value: 'Note:'
    type: 'text'
    value: ' This character has a different meaning when it appears at the start of a '
    type: 'link'
    title: 

    url: '/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Groups_and_Ranges'
    children: 
      type: 'text'
      value: 'group'
    type: 'text'
    value: '.'
```
##### tr (32:3) => tableRow
```
type: 'html'
value: '<td><p>Matches the beginning of input. If the multiline flag is set to true, also matches immediately after a line break character. For example, <code>/^A/</code> does not match the "A" in "an A", but does match the first "A" in "An A".</p><div class="notecard note"><p><strong>Note:</strong> This character has a different meaning when it appears at the start of a <a href="/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Groups_and_Ranges">group</a>.</p></div></td>'
```
##### td (44:4) => tableCell
```
type: 'paragraph'
summary: 'Assertions include boundaries, which indicate the beginnings and endings of lines and words, and other patterns indicating in some way that a match is possible (including look-ahead, look-behind, and conditional expressions).'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Matches the end of input. If the multiline flag is set to true, also matches immediately before a line break character. For example, '
  type: 'inlineCode'
  value: '/t$/'
  type: 'text'
  value: ' does not match the "t" in "eater", but does match it in "eat".'
```
##### tr (42:3) => tableRow
```
type: 'html'
value: '<td><p>Matches the end of input. If the multiline flag is set to true, also matches immediately before a line break character. For example, <code>/t$/</code> does not match the "t" in "eater", but does match it in "eat".</p></td>'
```
##### td (50:4) => tableCell
```
type: 'paragraph'
summary: 'Assertions include boundaries, which indicate the beginnings and endings of lines and words, and other patterns indicating in some way that a match is possible (including look-ahead, look-behind, and conditional expressions).'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Matches a word boundary. This is the position where a word character is not followed or preceded by another word-character, such as between a letter and a space. Note that a matched word boundary is not included in the match. In other words, the length of a matched word boundary is zero.',type: 'paragraph'
summary: 'Assertions include boundaries, which indicate the beginnings and endings of lines and words, and other patterns indicating in some way that a match is possible (including look-ahead, look-behind, and conditional expressions).'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Examples:',type: 'list'
ordered: 'false'
start: 

spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: '/\bm/'
      type: 'text'
      value: ' matches the "m" in "moon".'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: '/oo\b/'
      type: 'text'
      value: ' does not match the "oo" in "moon", because "oo" is followed by "n" which is a word character.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: '/oon\b/'
      type: 'text'
      value: ' matches the "oon" in "moon", because "oon" is the end of the string, thus not followed by a word character.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: '/\w\b\w/'
      type: 'text'
      value: ' will never match anything, because a word character can never be followed by both a non-word and a word character.',type: 'paragraph'
summary: 'Assertions include boundaries, which indicate the beginnings and endings of lines and words, and other patterns indicating in some way that a match is possible (including look-ahead, look-behind, and conditional expressions).'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'To match a backspace character ('
  type: 'inlineCode'
  value: '[\b]'
  type: 'text'
  value: '), see '
  type: 'link'
  title: 

  url: '/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Character_Classes'
  children: 
    type: 'text'
    value: 'Character Classes'
  type: 'text'
  value: '.'
```
##### tr (48:3) => tableRow
```
type: 'html'
value: '<td><p>Matches a word boundary. This is the position where a word character is not followed or preceded by another word-character, such as between a letter and a space. Note that a matched word boundary is not included in the match. In other words, the length of a matched word boundary is zero.</p><p>Examples:</p><ul><li><code>/\bm/</code> matches the "m" in "moon".</li><li><code>/oo\b/</code> does not match the "oo" in "moon", because "oo" is followed by "n" which is a word character.</li><li><code>/oon\b/</code> matches the "oon" in "moon", because "oon" is the end of the string, thus not followed by a word character.</li><li><code>/\w\b\w/</code> will never match anything, because a word character can never be followed by both a non-word and a word character.</li></ul><p>To match a backspace character (<code>[\b]</code>), see <a href="/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Character_Classes">Character Classes</a>.</p></td>'
```
##### td (67:4) => tableCell
```
type: 'paragraph'
summary: 'Assertions include boundaries, which indicate the beginnings and endings of lines and words, and other patterns indicating in some way that a match is possible (including look-ahead, look-behind, and conditional expressions).'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Matches a non-word boundary. This is a position where the previous and next character are of the same type: Either both must be words, or both must be non-words, for example between two letters or between two spaces. The beginning and end of a string are considered non-words. Same as the matched word boundary, the matched non-word boundary is also not included in the match. For example, '
  type: 'inlineCode'
  value: '/\Bon/'
  type: 'text'
  value: ' matches "on" in "at noon", and '
  type: 'inlineCode'
  value: '/ye\B/'
  type: 'text'
  value: ' matches "ye" in "possibly yesterday".'
```
##### tr (65:3) => tableRow
```
type: 'html'
value: '<td><p>Matches a non-word boundary. This is a position where the previous and next character are of the same type: Either both must be words, or both must be non-words, for example between two letters or between two spaces. The beginning and end of a string are considered non-words. Same as the matched word boundary, the matched non-word boundary is also not included in the match. For example, <code>/\Bon/</code> matches "on" in "at noon", and <code>/ye\B/</code> matches "ye" in "possibly yesterday".</p></td>'
```
##### table.standard-table (24:1) => table
```
type: 'html'
value: '<tr><th scope="col">Characters</th><th scope="col">Meaning</th></tr>',type: 'html'
value: '<tr><td><code>^</code></td><td><p>Matches the beginning of input. If the multiline flag is set to true, also matches immediately after a line break character. For example, <code>/^A/</code> does not match the "A" in "an A", but does match the first "A" in "An A".</p><div class="notecard note"><p><strong>Note:</strong> This character has a different meaning when it appears at the start of a <a href="/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Groups_and_Ranges">group</a>.</p></div></td></tr>',type: 'html'
value: '<tr><td><code>$</code></td><td><p>Matches the end of input. If the multiline flag is set to true, also matches immediately before a line break character. For example, <code>/t$/</code> does not match the "t" in "eater", but does match it in "eat".</p></td></tr>',type: 'html'
value: '<tr><td><code>\b</code></td><td><p>Matches a word boundary. This is the position where a word character is not followed or preceded by another word-character, such as between a letter and a space. Note that a matched word boundary is not included in the match. In other words, the length of a matched word boundary is zero.</p><p>Examples:</p><ul><li><code>/\bm/</code> matches the "m" in "moon".</li><li><code>/oo\b/</code> does not match the "oo" in "moon", because "oo" is followed by "n" which is a word character.</li><li><code>/oon\b/</code> matches the "oon" in "moon", because "oon" is the end of the string, thus not followed by a word character.</li><li><code>/\w\b\w/</code> will never match anything, because a word character can never be followed by both a non-word and a word character.</li></ul><p>To match a backspace character (<code>[\b]</code>), see <a href="/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Character_Classes">Character Classes</a>.</p></td></tr>',type: 'html'
value: '<tr><td><code>\B</code></td><td><p>Matches a non-word boundary. This is a position where the previous and next character are of the same type: Either both must be words, or both must be non-words, for example between two letters or between two spaces. The beginning and end of a string are considered non-words. Same as the matched word boundary, the matched non-word boundary is also not included in the match. For example, <code>/\Bon/</code> matches "on" in "at noon", and <code>/ye\B/</code> matches "ye" in "possibly yesterday".</p></td></tr>'
```
##### tr (82:3) => tableRow
```
type: 'html'
value: '<th scope="col">Characters</th>',type: 'html'
value: '<th scope="col">Meaning</th>'
```
##### td (90:4) => tableCell
```
type: 'paragraph'
summary: 'Assertions include boundaries, which indicate the beginnings and endings of lines and words, and other patterns indicating in some way that a match is possible (including look-ahead, look-behind, and conditional expressions).'
shouldWrap: 'true'
children: 
  type: 'strong'
  children: 
    type: 'text'
    value: 'Lookahead assertion:'
  type: 'text'
  value: ' '
  type: 'text'
  value: 'Matches "x" only if "x" is followed by "y". For example, /'
  type: 'inlineCode'
  value: 'Jack(?=Sprat)/'
  type: 'text'
  value: ' matches "Jack" only if it is followed by "Sprat".'
  type: 'break'
  type: 'inlineCode'
  value: '/Jack(?=Sprat|Frost)/'
  type: 'text'
  value: ' matches "Jack" only if it is followed by "Sprat" or "Frost". However, neither "Sprat" nor "Frost" is part of the match results.'
```
##### tr (88:3) => tableRow
```
type: 'html'
value: '<td><p><strong>Lookahead assertion: </strong>Matches "x" only if "x" is followed by "y". For example, /<code>Jack(?=Sprat)/</code> matches "Jack" only if it is followed by "Sprat".<br><code>/Jack(?=Sprat|Frost)/</code> matches "Jack" only if it is followed by "Sprat" or "Frost". However, neither "Sprat" nor "Frost" is part of the match results.</p></td>'
```
##### td (97:4) => tableCell
```
type: 'paragraph'
summary: 'Assertions include boundaries, which indicate the beginnings and endings of lines and words, and other patterns indicating in some way that a match is possible (including look-ahead, look-behind, and conditional expressions).'
shouldWrap: 'true'
children: 
  type: 'strong'
  children: 
    type: 'text'
    value: 'Negative lookahead assertion:'
  type: 'text'
  value: ' '
  type: 'text'
  value: 'Matches "x" only if "x" is not followed by "y". For example, '
  type: 'inlineCode'
  value: '/\d+(?!\.)/'
  type: 'text'
  value: ' matches a number only if it is not followed by a decimal point. '
  type: 'inlineCode'
  value: '/\d+(?!\.)/.exec('3.141')'
  type: 'text'
  value: ' matches "141" but not "3".'
```
##### tr (95:3) => tableRow
```
type: 'html'
value: '<td><p><strong>Negative lookahead assertion: </strong>Matches "x" only if "x" is not followed by "y". For example, <code>/\d+(?!\.)/</code> matches a number only if it is not followed by a decimal point. <code>/\d+(?!\.)/.exec('3.141')</code> matches "141" but not "3".</p></td>'
```
##### td (103:4) => tableCell
```
type: 'paragraph'
summary: 'Assertions include boundaries, which indicate the beginnings and endings of lines and words, and other patterns indicating in some way that a match is possible (including look-ahead, look-behind, and conditional expressions).'
shouldWrap: 'true'
children: 
  type: 'strong'
  children: 
    type: 'text'
    value: 'Lookbehind assertion:'
  type: 'text'
  value: ' '
  type: 'text'
  value: 'Matches "x" only if "x" is preceded by "y". For example, '
  type: 'inlineCode'
  value: '/(?<=Jack)Sprat/'
  type: 'text'
  value: ' matches "Sprat" only if it is preceded by "Jack". '
  type: 'inlineCode'
  value: '/(?<=Jack|Tom)Sprat/'
  type: 'text'
  value: ' matches "Sprat" only if it is preceded by "Jack" or "Tom". However, neither "Jack" nor "Tom" is part of the match results.'
```
##### tr (101:3) => tableRow
```
type: 'html'
value: '<td><p><strong>Lookbehind assertion: </strong>Matches "x" only if "x" is preceded by "y". For example, <code>/(?&#x3C;=Jack)Sprat/</code> matches "Sprat" only if it is preceded by "Jack". <code>/(?&#x3C;=Jack|Tom)Sprat/</code> matches "Sprat" only if it is preceded by "Jack" or "Tom". However, neither "Jack" nor "Tom" is part of the match results.</p></td>'
```
##### td (109:4) => tableCell
```
type: 'paragraph'
summary: 'Assertions include boundaries, which indicate the beginnings and endings of lines and words, and other patterns indicating in some way that a match is possible (including look-ahead, look-behind, and conditional expressions).'
shouldWrap: 'true'
children: 
  type: 'strong'
  children: 
    type: 'text'
    value: 'Negative lookbehind assertion:'
  type: 'text'
  value: ' '
  type: 'text'
  value: 'Matches "x" only if "x" is not preceded by "y". For example, '
  type: 'inlineCode'
  value: '/(?<!-)\d+/'
  type: 'text'
  value: ' matches a number only if it is not preceded by a minus sign. '
  type: 'inlineCode'
  value: '/(?<!-)\d+/.exec('3')'
  type: 'text'
  value: ' matches "3". '
  type: 'inlineCode'
  value: '/(?<!-)\d+/.exec('-3')'
  type: 'text'
  value: '  match is not found because the number is preceded by the minus sign.'
```
##### tr (107:3) => tableRow
```
type: 'html'
value: '<td><p><strong>Negative lookbehind assertion: </strong>Matches "x" only if "x" is not preceded by "y". For example, <code>/(?&#x3C;!-)\d+/</code> matches a number only if it is not preceded by a minus sign. <code>/(?&#x3C;!-)\d+/.exec('3')</code> matches "3". <code>/(?&#x3C;!-)\d+/.exec('-3')</code>  match is not found because the number is preceded by the minus sign.</p></td>'
```
##### table.standard-table (80:1) => table
```
type: 'html'
value: '<tr><th scope="col">Characters</th><th scope="col">Meaning</th></tr>',type: 'html'
value: '<tr><td><code>x(?=y)</code></td><td><p><strong>Lookahead assertion: </strong>Matches "x" only if "x" is followed by "y". For example, /<code>Jack(?=Sprat)/</code> matches "Jack" only if it is followed by "Sprat".<br><code>/Jack(?=Sprat|Frost)/</code> matches "Jack" only if it is followed by "Sprat" or "Frost". However, neither "Sprat" nor "Frost" is part of the match results.</p></td></tr>',type: 'html'
value: '<tr><td><code>x(?!y)</code></td><td><p><strong>Negative lookahead assertion: </strong>Matches "x" only if "x" is not followed by "y". For example, <code>/\d+(?!\.)/</code> matches a number only if it is not followed by a decimal point. <code>/\d+(?!\.)/.exec('3.141')</code> matches "141" but not "3".</p></td></tr>',type: 'html'
value: '<tr><td><code>(?&#x3C;=y)x</code></td><td><p><strong>Lookbehind assertion: </strong>Matches "x" only if "x" is preceded by "y". For example, <code>/(?&#x3C;=Jack)Sprat/</code> matches "Sprat" only if it is preceded by "Jack". <code>/(?&#x3C;=Jack|Tom)Sprat/</code> matches "Sprat" only if it is preceded by "Jack" or "Tom". However, neither "Jack" nor "Tom" is part of the match results.</p></td></tr>',type: 'html'
value: '<tr><td><code>(?&#x3C;!y)x</code></td><td><p><strong>Negative lookbehind assertion: </strong>Matches "x" only if "x" is not preceded by "y". For example, <code>/(?&#x3C;!-)\d+/</code> matches a number only if it is not preceded by a minus sign. <code>/(?&#x3C;!-)\d+/.exec('3')</code> matches "3". <code>/(?&#x3C;!-)\d+/.exec('-3')</code>  match is not found because the number is preceded by the minus sign.</p></td></tr>'
```
### Missing conversion rules
- th[scope="col"] (27:4)
- th[scope="col"] (28:4)
- th[scope="col"] (83:4)
- th[scope="col"] (84:4)
### [/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Character_Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Character_Classes)
#### Invalid AST transformations
##### tr (24:3) => tableRow
```
type: 'html'
value: '<th scope="col">Characters</th>',type: 'html'
value: '<th scope="col">Meaning</th>'
```
##### td (34:4) => tableCell
```
type: 'paragraph'
summary: 'Character classes distinguish kinds of characters such as, for example, distinguishing between letters and digits.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Has one of the following meanings:',type: 'list'
ordered: 'false'
start: 

spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'Matches any single character '
      type: 'emphasis'
      children: 
        type: 'text'
        value: 'except'
      type: 'text'
      value: ' line terminators: '
      type: 'inlineCode'
      value: '\n'
      type: 'text'
      value: ', '
      type: 'inlineCode'
      value: '\r'
      type: 'text'
      value: ', '
      type: 'inlineCode'
      value: '\u2028'
      type: 'text'
      value: ' or '
      type: 'inlineCode'
      value: '\u2029'
      type: 'text'
      value: '. For example, '
      type: 'inlineCode'
      value: '/.y/'
      type: 'text'
      value: ' matches "my" and "ay", but not "yes", in "yes make my day".'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'Inside a character class, the dot loses its special meaning and matches a literal dot.',type: 'paragraph'
summary: 'Character classes distinguish kinds of characters such as, for example, distinguishing between letters and digits.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Note that the '
  type: 'inlineCode'
  value: 'm'
  type: 'text'
  value: ' multiline flag doesn't change the dot behavior. So to match a pattern across multiple lines, the character class '
  type: 'inlineCode'
  value: '[^]'
  type: 'text'
  value: ' can be used — it will match any character including newlines.',type: 'paragraph'
summary: 'Character classes distinguish kinds of characters such as, for example, distinguishing between letters and digits.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'ES2018 added the '
  type: 'inlineCode'
  value: 's'
  type: 'text'
  value: ' "dotAll" flag, which allows the dot to also match line terminators.'
```
##### tr (32:3) => tableRow
```
type: 'html'
value: '<td><p>Has one of the following meanings:</p><ul><li>Matches any single character <em>except</em> line terminators: <code>\n</code>, <code>\r</code>, <code>\u2028</code> or <code>\u2029</code>. For example, <code>/.y/</code> matches "my" and "ay", but not "yes", in "yes make my day".</li><li>Inside a character class, the dot loses its special meaning and matches a literal dot.</li></ul><p>Note that the <code>m</code> multiline flag doesn't change the dot behavior. So to match a pattern across multiple lines, the character class <code>[^]</code> can be used — it will match any character including newlines.</p><p>ES2018 added the <code>s</code> "dotAll" flag, which allows the dot to also match line terminators.</p></td>'
```
##### td (49:4) => tableCell
```
type: 'paragraph'
summary: 'Character classes distinguish kinds of characters such as, for example, distinguishing between letters and digits.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Matches any digit (Arabic numeral). Equivalent to '
  type: 'inlineCode'
  value: '[0-9]'
  type: 'text'
  value: '. For example, '
  type: 'inlineCode'
  value: '/\d/'
  type: 'text'
  value: ' or '
  type: 'inlineCode'
  value: '/[0-9]/'
  type: 'text'
  value: ' matches "2" in "B2 is the suite number".'
```
##### tr (47:3) => tableRow
```
type: 'html'
value: '<td><p>Matches any digit (Arabic numeral). Equivalent to <code>[0-9]</code>. For example, <code>/\d/</code> or <code>/[0-9]/</code> matches "2" in "B2 is the suite number".</p></td>'
```
##### td (55:4) => tableCell
```
type: 'paragraph'
summary: 'Character classes distinguish kinds of characters such as, for example, distinguishing between letters and digits.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Matches any character that is not a digit (Arabic numeral). Equivalent to '
  type: 'inlineCode'
  value: '[^0-9]'
  type: 'text'
  value: '. For example, '
  type: 'inlineCode'
  value: '/\D/'
  type: 'text'
  value: ' or '
  type: 'inlineCode'
  value: '/[^0-9]/'
  type: 'text'
  value: ' matches "B" in "B2 is the suite number".'
```
##### tr (53:3) => tableRow
```
type: 'html'
value: '<td><p>Matches any character that is not a digit (Arabic numeral). Equivalent to <code>[^0-9]</code>. For example, <code>/\D/</code> or <code>/[^0-9]/</code> matches "B" in "B2 is the suite number".</p></td>'
```
##### td (61:4) => tableCell
```
type: 'paragraph'
summary: 'Character classes distinguish kinds of characters such as, for example, distinguishing between letters and digits.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Matches any alphanumeric character from the basic Latin alphabet, including the underscore. Equivalent to '
  type: 'inlineCode'
  value: '[A-Za-z0-9_]'
  type: 'text'
  value: '. For example, '
  type: 'inlineCode'
  value: '/\w/'
  type: 'text'
  value: ' matches "a" in "apple", "5" in "$5.28", "3" in "3D" and "m" in "Émanuel".'
```
##### tr (59:3) => tableRow
```
type: 'html'
value: '<td><p>Matches any alphanumeric character from the basic Latin alphabet, including the underscore. Equivalent to <code>[A-Za-z0-9_]</code>. For example, <code>/\w/</code> matches "a" in "apple", "5" in "$5.28", "3" in "3D" and "m" in "Émanuel".</p></td>'
```
##### td (67:4) => tableCell
```
type: 'paragraph'
summary: 'Character classes distinguish kinds of characters such as, for example, distinguishing between letters and digits.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Matches any character that is not a word character from the basic Latin alphabet. Equivalent to '
  type: 'inlineCode'
  value: '[^A-Za-z0-9_]'
  type: 'text'
  value: '. For example, '
  type: 'inlineCode'
  value: '/\W/'
  type: 'text'
  value: ' or '
  type: 'inlineCode'
  value: '/[^A-Za-z0-9_]/'
  type: 'text'
  value: ' matches "%" in "50%" and "É" in "Émanuel".'
```
##### tr (65:3) => tableRow
```
type: 'html'
value: '<td><p>Matches any character that is not a word character from the basic Latin alphabet. Equivalent to <code>[^A-Za-z0-9_]</code>. For example, <code>/\W/</code> or <code>/[^A-Za-z0-9_]/</code> matches "%" in "50%" and "É" in "Émanuel".</p></td>'
```
##### td (73:4) => tableCell
```
type: 'paragraph'
summary: 'Character classes distinguish kinds of characters such as, for example, distinguishing between letters and digits.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Matches a single white space character, including space, tab, form feed, line feed, and other Unicode spaces. Equivalent to '
  type: 'inlineCode'
  value: '[ \f\n\r\t\v\u00a0\u1680\u2000-\u200a\u2028\u2029\u202f\u205f\u3000\ufeff]'
  type: 'text'
  value: '. For example, '
  type: 'inlineCode'
  value: '/\s\w*/'
  type: 'text'
  value: ' matches " bar" in "foo bar".'
```
##### tr (71:3) => tableRow
```
type: 'html'
value: '<td><p>Matches a single white space character, including space, tab, form feed, line feed, and other Unicode spaces. Equivalent to <code>[ \f\n\r\t\v\u00a0\u1680\u2000-\u200a\u2028\u2029\u202f\u205f\u3000\ufeff]</code>. For example, <code>/\s\w*/</code> matches " bar" in "foo bar".</p></td>'
```
##### td (79:4) => tableCell
```
type: 'paragraph'
summary: 'Character classes distinguish kinds of characters such as, for example, distinguishing between letters and digits.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Matches a single character other than white space. Equivalent to '
  type: 'inlineCode'
  value: '[^ \f\n\r\t\v\u00a0\u1680\u2000-\u200a\u2028\u2029\u202f\u205f\u3000\ufeff]'
  type: 'text'
  value: '. For example, '
  type: 'inlineCode'
  value: '/\S\w*/'
  type: 'text'
  value: ' matches "foo" in "foo bar".'
```
##### tr (77:3) => tableRow
```
type: 'html'
value: '<td><p>Matches a single character other than white space. Equivalent to <code>[^ \f\n\r\t\v\u00a0\u1680\u2000-\u200a\u2028\u2029\u202f\u205f\u3000\ufeff]</code>. For example, <code>/\S\w*/</code> matches "foo" in "foo bar".</p></td>'
```
##### code (112:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'X'
```
##### td (113:4) => tableCell
```
type: 'paragraph'
summary: 'Character classes distinguish kinds of characters such as, for example, distinguishing between letters and digits.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Matches a control character using '
  type: 'link'
  title: 

  url: 'https://en.wikipedia.org/wiki/Caret_notation'
  children: 
    type: 'text'
    value: 'caret notation'
  type: 'text'
  value: ', where "X" is a letter from A–Z (corresponding to codepoints '
  type: 'inlineCode'
  value: 'U+0001'
  type: 'emphasis'
  children: 
    type: 'text'
    value: '–'
  type: 'inlineCode'
  value: 'U+001F'
  type: 'text'
  value: '). For example, '
  type: 'inlineCode'
  value: '/\cM/'
  type: 'text'
  value: ' matches "\r" in "\r\n".'
```
##### tr (111:3) => tableRow
```
type: 'html'
value: '<td><p>Matches a control character using <a href="https://en.wikipedia.org/wiki/Caret_notation">caret notation</a>, where "X" is a letter from A–Z (corresponding to codepoints <code>U+0001</code><em>–</em><code>U+001F</code>). For example, <code>/\cM/</code> matches "\r" in "\r\n".</p></td>'
```
##### code (118:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'hh'
```
##### code (119:44) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'hh'
```
##### code (122:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'hhhh'
```
##### code (123:50) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'hhhh'
```
##### code (126:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: '{hhhh}'
```
##### code (127:97) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'hhhh'
```
##### code (127:129) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'hhhhh'
```
##### code (130:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'UnicodeProperty'
```
##### code (130:51) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'UnicodeProperty'
```
##### td (135:4) => tableCell
```
type: 'paragraph'
summary: 'Character classes distinguish kinds of characters such as, for example, distinguishing between letters and digits.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Indicates that the following character should be treated specially, or "escaped". It behaves one of two ways.',type: 'list'
ordered: 'false'
start: 

spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'For characters that are usually treated literally, indicates that the next character is special and not to be interpreted literally. For example, '
      type: 'inlineCode'
      value: '/b/'
      type: 'text'
      value: ' matches the character "b". By placing a backslash in front of "b", that is by using '
      type: 'inlineCode'
      value: '/\b/'
      type: 'text'
      value: ', the character becomes special to mean match a word boundary.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'For characters that are usually treated specially, indicates that the next character is not special and should be interpreted literally. For example, "*" is a special character that means 0 or more occurrences of the preceding character should be matched; for example, '
      type: 'inlineCode'
      value: '/a*/'
      type: 'text'
      value: ' means match 0 or more "a"s. To match '
      type: 'inlineCode'
      value: '*'
      type: 'text'
      value: ' literally, precede it with a backslash; for example, '
      type: 'inlineCode'
      value: '/a\*/'
      type: 'text'
      value: ' matches "a*".',type: 'blockquote'
children: 
  type: 'paragraph'
  children: 
    type: 'strong'
    children: 
      type: 'text'
      value: 'Note:'
    type: 'text'
    value: ' To match this character literally, escape it with itself. In other words to search for '
    type: 'inlineCode'
    value: '\'
    type: 'text'
    value: ' use '
    type: 'inlineCode'
    value: '/\\/'
    type: 'text'
    value: '.'
```
##### tr (133:3) => tableRow
```
type: 'html'
value: '<td><p>Indicates that the following character should be treated specially, or "escaped". It behaves one of two ways.</p><ul><li>For characters that are usually treated literally, indicates that the next character is special and not to be interpreted literally. For example, <code>/b/</code> matches the character "b". By placing a backslash in front of "b", that is by using <code>/\b/</code>, the character becomes special to mean match a word boundary.</li><li>For characters that are usually treated specially, indicates that the next character is not special and should be interpreted literally. For example, "*" is a special character that means 0 or more occurrences of the preceding character should be matched; for example, <code>/a*/</code> means match 0 or more "a"s. To match <code>*</code> literally, precede it with a backslash; for example, <code>/a\*/</code> matches "a*".</li></ul><div class="notecard note"><p><strong>Note:</strong> To match this character literally, escape it with itself. In other words to search for <code>\</code> use <code>/\\/</code>.</p></div></td>'
```
##### table.standard-table (22:1) => table
```
type: 'html'
value: '<tr><th scope="col">Characters</th><th scope="col">Meaning</th></tr>',type: 'html'
value: '<tr><td><code>.</code></td><td><p>Has one of the following meanings:</p><ul><li>Matches any single character <em>except</em> line terminators: <code>\n</code>, <code>\r</code>, <code>\u2028</code> or <code>\u2029</code>. For example, <code>/.y/</code> matches "my" and "ay", but not "yes", in "yes make my day".</li><li>Inside a character class, the dot loses its special meaning and matches a literal dot.</li></ul><p>Note that the <code>m</code> multiline flag doesn't change the dot behavior. So to match a pattern across multiple lines, the character class <code>[^]</code> can be used — it will match any character including newlines.</p><p>ES2018 added the <code>s</code> "dotAll" flag, which allows the dot to also match line terminators.</p></td></tr>',type: 'html'
value: '<tr><td><code>\d</code></td><td><p>Matches any digit (Arabic numeral). Equivalent to <code>[0-9]</code>. For example, <code>/\d/</code> or <code>/[0-9]/</code> matches "2" in "B2 is the suite number".</p></td></tr>',type: 'html'
value: '<tr><td><code>\D</code></td><td><p>Matches any character that is not a digit (Arabic numeral). Equivalent to <code>[^0-9]</code>. For example, <code>/\D/</code> or <code>/[^0-9]/</code> matches "B" in "B2 is the suite number".</p></td></tr>',type: 'html'
value: '<tr><td><code>\w</code></td><td><p>Matches any alphanumeric character from the basic Latin alphabet, including the underscore. Equivalent to <code>[A-Za-z0-9_]</code>. For example, <code>/\w/</code> matches "a" in "apple", "5" in "$5.28", "3" in "3D" and "m" in "Émanuel".</p></td></tr>',type: 'html'
value: '<tr><td><code>\W</code></td><td><p>Matches any character that is not a word character from the basic Latin alphabet. Equivalent to <code>[^A-Za-z0-9_]</code>. For example, <code>/\W/</code> or <code>/[^A-Za-z0-9_]/</code> matches "%" in "50%" and "É" in "Émanuel".</p></td></tr>',type: 'html'
value: '<tr><td><code>\s</code></td><td><p>Matches a single white space character, including space, tab, form feed, line feed, and other Unicode spaces. Equivalent to <code>[ \f\n\r\t\v\u00a0\u1680\u2000-\u200a\u2028\u2029\u202f\u205f\u3000\ufeff]</code>. For example, <code>/\s\w*/</code> matches " bar" in "foo bar".</p></td></tr>',type: 'html'
value: '<tr><td><code>\S</code></td><td><p>Matches a single character other than white space. Equivalent to <code>[^ \f\n\r\t\v\u00a0\u1680\u2000-\u200a\u2028\u2029\u202f\u205f\u3000\ufeff]</code>. For example, <code>/\S\w*/</code> matches "foo" in "foo bar".</p></td></tr>',type: 'html'
value: '<tr><td><code>\c<em>X</em></code></td><td><p>Matches a control character using <a href="https://en.wikipedia.org/wiki/Caret_notation">caret notation</a>, where "X" is a letter from A–Z (corresponding to codepoints <code>U+0001</code><em>–</em><code>U+001F</code>). For example, <code>/\cM/</code> matches "\r" in "\r\n".</p></td></tr>',type: 'html'
value: '<tr><td><code>\</code></td><td><p>Indicates that the following character should be treated specially, or "escaped". It behaves one of two ways.</p><ul><li>For characters that are usually treated literally, indicates that the next character is special and not to be interpreted literally. For example, <code>/b/</code> matches the character "b". By placing a backslash in front of "b", that is by using <code>/\b/</code>, the character becomes special to mean match a word boundary.</li><li>For characters that are usually treated specially, indicates that the next character is not special and should be interpreted literally. For example, "*" is a special character that means 0 or more occurrences of the preceding character should be matched; for example, <code>/a*/</code> means match 0 or more "a"s. To match <code>*</code> literally, precede it with a backslash; for example, <code>/a\*/</code> matches "a*".</li></ul><div class="notecard note"><p><strong>Note:</strong> To match this character literally, escape it with itself. In other words to search for <code>\</code> use <code>/\\/</code>.</p></div></td></tr>'
```
### Missing conversion rules
- th[scope="col"] (25:4)
- th[scope="col"] (26:4)
### [/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Cheatsheet](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Cheatsheet)
#### Invalid AST transformations
##### span.seoSummary (13:4) => text
```
type: 'element'
tagName: 'a'
properties: 
  href: '/en-US/docs/Web/JavaScript/Guide/Regular_Expressions'
children: 
  type: 'text'
  value: 'the guide'
```
##### tr (20:3) => tableRow
```
type: 'html'
value: '<th scope="col">Characters</th>',type: 'html'
value: '<th scope="col">Meaning</th>'
```
##### td (30:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Has one of the following meanings:',type: 'list'
ordered: 'false'
start: 

spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'Matches any single character '
      type: 'emphasis'
      children: 
        type: 'text'
        value: 'except'
      type: 'text'
      value: ' line terminators: '
      type: 'inlineCode'
      value: '\n'
      type: 'text'
      value: ', '
      type: 'inlineCode'
      value: '\r'
      type: 'text'
      value: ', '
      type: 'inlineCode'
      value: '\u2028'
      type: 'text'
      value: ' or '
      type: 'inlineCode'
      value: '\u2029'
      type: 'text'
      value: '. For example, '
      type: 'inlineCode'
      value: '/.y/'
      type: 'text'
      value: ' matches "my" and "ay", but not "yes", in "yes make my day".'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'Inside a character class, the dot loses its special meaning and matches a literal dot.',type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Note that the '
  type: 'inlineCode'
  value: 'm'
  type: 'text'
  value: ' multiline flag doesn't change the dot behavior. So to match a pattern across multiple lines, the character class '
  type: 'inlineCode'
  value: '[^]'
  type: 'text'
  value: ' can be used — it will match any character including newlines.',type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'ES2018 added the '
  type: 'inlineCode'
  value: 's'
  type: 'text'
  value: ' "dotAll" flag, which allows the dot to also match line terminators.'
```
##### tr (28:3) => tableRow
```
type: 'html'
value: '<td><p>Has one of the following meanings:</p><ul><li>Matches any single character <em>except</em> line terminators: <code>\n</code>, <code>\r</code>, <code>\u2028</code> or <code>\u2029</code>. For example, <code>/.y/</code> matches "my" and "ay", but not "yes", in "yes make my day".</li><li>Inside a character class, the dot loses its special meaning and matches a literal dot.</li></ul><p>Note that the <code>m</code> multiline flag doesn't change the dot behavior. So to match a pattern across multiple lines, the character class <code>[^]</code> can be used — it will match any character including newlines.</p><p>ES2018 added the <code>s</code> "dotAll" flag, which allows the dot to also match line terminators.</p></td>'
```
##### td (45:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Matches any digit (Arabic numeral). Equivalent to '
  type: 'inlineCode'
  value: '[0-9]'
  type: 'text'
  value: '. For example, '
  type: 'inlineCode'
  value: '/\d/'
  type: 'text'
  value: ' or '
  type: 'inlineCode'
  value: '/[0-9]/'
  type: 'text'
  value: ' matches "2" in "B2 is the suite number".'
```
##### tr (43:3) => tableRow
```
type: 'html'
value: '<td><p>Matches any digit (Arabic numeral). Equivalent to <code>[0-9]</code>. For example, <code>/\d/</code> or <code>/[0-9]/</code> matches "2" in "B2 is the suite number".</p></td>'
```
##### td (51:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Matches any character that is not a digit (Arabic numeral). Equivalent to '
  type: 'inlineCode'
  value: '[^0-9]'
  type: 'text'
  value: '. For example, '
  type: 'inlineCode'
  value: '/\D/'
  type: 'text'
  value: ' or '
  type: 'inlineCode'
  value: '/[^0-9]/'
  type: 'text'
  value: ' matches "B" in "B2 is the suite number".'
```
##### tr (49:3) => tableRow
```
type: 'html'
value: '<td><p>Matches any character that is not a digit (Arabic numeral). Equivalent to <code>[^0-9]</code>. For example, <code>/\D/</code> or <code>/[^0-9]/</code> matches "B" in "B2 is the suite number".</p></td>'
```
##### td (57:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Matches any alphanumeric character from the basic Latin alphabet, including the underscore. Equivalent to '
  type: 'inlineCode'
  value: '[A-Za-z0-9_]'
  type: 'text'
  value: '. For example, '
  type: 'inlineCode'
  value: '/\w/'
  type: 'text'
  value: ' matches "a" in "apple", "5" in "$5.28", and "3" in "3D".'
```
##### tr (55:3) => tableRow
```
type: 'html'
value: '<td><p>Matches any alphanumeric character from the basic Latin alphabet, including the underscore. Equivalent to <code>[A-Za-z0-9_]</code>. For example, <code>/\w/</code> matches "a" in "apple", "5" in "$5.28", and "3" in "3D".</p></td>'
```
##### td (63:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Matches any character that is not a word character from the basic Latin alphabet. Equivalent to '
  type: 'inlineCode'
  value: '[^A-Za-z0-9_]'
  type: 'text'
  value: '. For example, '
  type: 'inlineCode'
  value: '/\W/'
  type: 'text'
  value: ' or '
  type: 'inlineCode'
  value: '/[^A-Za-z0-9_]/'
  type: 'text'
  value: ' matches "%" in "50%".'
```
##### tr (61:3) => tableRow
```
type: 'html'
value: '<td><p>Matches any character that is not a word character from the basic Latin alphabet. Equivalent to <code>[^A-Za-z0-9_]</code>. For example, <code>/\W/</code> or <code>/[^A-Za-z0-9_]/</code> matches "%" in "50%".</p></td>'
```
##### td (69:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Matches a single white space character, including space, tab, form feed, line feed, and other Unicode spaces. Equivalent to '
  type: 'inlineCode'
  value: '[ \f\n\r\t\v\u00a0\u1680\u2000-\u200a\u2028\u2029\u202f\u205f\u3000\ufeff]'
  type: 'text'
  value: '. For example, '
  type: 'inlineCode'
  value: '/\s\w*/'
  type: 'text'
  value: ' matches " bar" in "foo bar".'
```
##### tr (67:3) => tableRow
```
type: 'html'
value: '<td><p>Matches a single white space character, including space, tab, form feed, line feed, and other Unicode spaces. Equivalent to <code>[ \f\n\r\t\v\u00a0\u1680\u2000-\u200a\u2028\u2029\u202f\u205f\u3000\ufeff]</code>. For example, <code>/\s\w*/</code> matches " bar" in "foo bar".</p></td>'
```
##### td (75:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Matches a single character other than white space. Equivalent to '
  type: 'inlineCode'
  value: '[^ \f\n\r\t\v\u00a0\u1680\u2000-\u200a\u2028\u2029\u202f\u205f\u3000\ufeff]'
  type: 'text'
  value: '. For example, '
  type: 'inlineCode'
  value: '/\S\w*/'
  type: 'text'
  value: ' matches "foo" in "foo bar".'
```
##### tr (73:3) => tableRow
```
type: 'html'
value: '<td><p>Matches a single character other than white space. Equivalent to <code>[^ \f\n\r\t\v\u00a0\u1680\u2000-\u200a\u2028\u2029\u202f\u205f\u3000\ufeff]</code>. For example, <code>/\S\w*/</code> matches "foo" in "foo bar".</p></td>'
```
##### code (108:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'X'
```
##### td (109:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Matches a control character using '
  type: 'link'
  title: 

  url: 'https://en.wikipedia.org/wiki/Caret_notation'
  children: 
    type: 'text'
    value: 'caret notation'
  type: 'text'
  value: ', where "X" is a letter from A–Z (corresponding to codepoints '
  type: 'inlineCode'
  value: 'U+0001'
  type: 'emphasis'
  children: 
    type: 'text'
    value: '–'
  type: 'inlineCode'
  value: 'U+001F'
  type: 'text'
  value: '). For example, '
  type: 'inlineCode'
  value: '/\cM/'
  type: 'text'
  value: ' matches "\r" in "\r\n".'
```
##### tr (107:3) => tableRow
```
type: 'html'
value: '<td><p>Matches a control character using <a href="https://en.wikipedia.org/wiki/Caret_notation">caret notation</a>, where "X" is a letter from A–Z (corresponding to codepoints <code>U+0001</code><em>–</em><code>U+001F</code>). For example, <code>/\cM/</code> matches "\r" in "\r\n".</p></td>'
```
##### code (114:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'hh'
```
##### code (115:44) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'hh'
```
##### code (118:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'hhhh'
```
##### code (119:50) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'hhhh'
```
##### code (122:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: '{hhhh}'
```
##### code (123:97) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'hhhh'
```
##### code (123:129) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'hhhhh'
```
##### td (127:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Indicates that the following character should be treated specially, or "escaped". It behaves one of two ways.',type: 'list'
ordered: 'false'
start: 

spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'For characters that are usually treated literally, indicates that the next character is special and not to be interpreted literally. For example, '
      type: 'inlineCode'
      value: '/b/'
      type: 'text'
      value: ' matches the character "b". By placing a backslash in front of "b", that is by using '
      type: 'inlineCode'
      value: '/\b/'
      type: 'text'
      value: ', the character becomes special to mean match a word boundary.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'For characters that are usually treated specially, indicates that the next character is not special and should be interpreted literally. For example, "*" is a special character that means 0 or more occurrences of the preceding character should be matched; for example, '
      type: 'inlineCode'
      value: '/a*/'
      type: 'text'
      value: ' means match 0 or more "a"s. To match '
      type: 'inlineCode'
      value: '*'
      type: 'text'
      value: ' literally, precede it with a backslash; for example, '
      type: 'inlineCode'
      value: '/a\*/'
      type: 'text'
      value: ' matches "a*".',type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Note that some characters like '
  type: 'inlineCode'
  value: ':'
  type: 'text'
  value: ', '
  type: 'inlineCode'
  value: '-'
  type: 'text'
  value: ', '
  type: 'inlineCode'
  value: '@'
  type: 'text'
  value: ', etc. neither have a special meaning when escaped nor when unescaped. Escape sequences like '
  type: 'inlineCode'
  value: '\:'
  type: 'text'
  value: ', '
  type: 'inlineCode'
  value: '\-'
  type: 'text'
  value: ', '
  type: 'inlineCode'
  value: '\@'
  type: 'text'
  value: ' will be equivalent to their literal, unescaped character equivalents in regular expressions. However, in regular expressions with the '
  type: 'link'
  title: 

  url: '/en-US/docs/Web/JavaScript/Guide/Regular_Expressions#advanced_searching_with_flags_2'
  children: 
    type: 'text'
    value: 'unicode flag'
  type: 'text'
  value: ', these will cause an '
  type: 'emphasis'
  children: 
    type: 'text'
    value: 'invalid identity escape'
  type: 'text'
  value: ' error. This is done to ensure backward compatibility with existing code that uses new escape sequences like '
  type: 'inlineCode'
  value: '\p'
  type: 'text'
  value: ' or '
  type: 'inlineCode'
  value: '\k'
  type: 'text'
  value: '.',type: 'blockquote'
children: 
  type: 'paragraph'
  children: 
    type: 'strong'
    children: 
      type: 'text'
      value: 'Note:'
    type: 'text'
    value: ' To match this character literally, escape it with itself. In other words to search for '
    type: 'inlineCode'
    value: '\'
    type: 'text'
    value: ' use '
    type: 'inlineCode'
    value: '/\\/'
    type: 'text'
    value: '.'
```
##### tr (125:3) => tableRow
```
type: 'html'
value: '<td><p>Indicates that the following character should be treated specially, or "escaped". It behaves one of two ways.</p><ul><li>For characters that are usually treated literally, indicates that the next character is special and not to be interpreted literally. For example, <code>/b/</code> matches the character "b". By placing a backslash in front of "b", that is by using <code>/\b/</code>, the character becomes special to mean match a word boundary.</li><li>For characters that are usually treated specially, indicates that the next character is not special and should be interpreted literally. For example, "*" is a special character that means 0 or more occurrences of the preceding character should be matched; for example, <code>/a*/</code> means match 0 or more "a"s. To match <code>*</code> literally, precede it with a backslash; for example, <code>/a\*/</code> matches "a*".</li></ul><p>Note that some characters like <code>:</code>, <code>-</code>, <code>@</code>, etc. neither have a special meaning when escaped nor when unescaped. Escape sequences like <code>\:</code>, <code>\-</code>, <code>\@</code> will be equivalent to their literal, unescaped character equivalents in regular expressions. However, in regular expressions with the <a href="/en-US/docs/Web/JavaScript/Guide/Regular_Expressions#advanced_searching_with_flags_2">unicode flag</a>, these will cause an <em>invalid identity escape</em> error. This is done to ensure backward compatibility with existing code that uses new escape sequences like <code>\p</code> or <code>\k</code>.</p><div class="notecard note"><p><strong>Note:</strong> To match this character literally, escape it with itself. In other words to search for <code>\</code> use <code>/\\/</code>.</p></div></td>'
```
##### table.standard-table (18:1) => table
```
type: 'html'
value: '<tr><th scope="col">Characters</th><th scope="col">Meaning</th></tr>',type: 'html'
value: '<tr><td><code>.</code></td><td><p>Has one of the following meanings:</p><ul><li>Matches any single character <em>except</em> line terminators: <code>\n</code>, <code>\r</code>, <code>\u2028</code> or <code>\u2029</code>. For example, <code>/.y/</code> matches "my" and "ay", but not "yes", in "yes make my day".</li><li>Inside a character class, the dot loses its special meaning and matches a literal dot.</li></ul><p>Note that the <code>m</code> multiline flag doesn't change the dot behavior. So to match a pattern across multiple lines, the character class <code>[^]</code> can be used — it will match any character including newlines.</p><p>ES2018 added the <code>s</code> "dotAll" flag, which allows the dot to also match line terminators.</p></td></tr>',type: 'html'
value: '<tr><td><code>\d</code></td><td><p>Matches any digit (Arabic numeral). Equivalent to <code>[0-9]</code>. For example, <code>/\d/</code> or <code>/[0-9]/</code> matches "2" in "B2 is the suite number".</p></td></tr>',type: 'html'
value: '<tr><td><code>\D</code></td><td><p>Matches any character that is not a digit (Arabic numeral). Equivalent to <code>[^0-9]</code>. For example, <code>/\D/</code> or <code>/[^0-9]/</code> matches "B" in "B2 is the suite number".</p></td></tr>',type: 'html'
value: '<tr><td><code>\w</code></td><td><p>Matches any alphanumeric character from the basic Latin alphabet, including the underscore. Equivalent to <code>[A-Za-z0-9_]</code>. For example, <code>/\w/</code> matches "a" in "apple", "5" in "$5.28", and "3" in "3D".</p></td></tr>',type: 'html'
value: '<tr><td><code>\W</code></td><td><p>Matches any character that is not a word character from the basic Latin alphabet. Equivalent to <code>[^A-Za-z0-9_]</code>. For example, <code>/\W/</code> or <code>/[^A-Za-z0-9_]/</code> matches "%" in "50%".</p></td></tr>',type: 'html'
value: '<tr><td><code>\s</code></td><td><p>Matches a single white space character, including space, tab, form feed, line feed, and other Unicode spaces. Equivalent to <code>[ \f\n\r\t\v\u00a0\u1680\u2000-\u200a\u2028\u2029\u202f\u205f\u3000\ufeff]</code>. For example, <code>/\s\w*/</code> matches " bar" in "foo bar".</p></td></tr>',type: 'html'
value: '<tr><td><code>\S</code></td><td><p>Matches a single character other than white space. Equivalent to <code>[^ \f\n\r\t\v\u00a0\u1680\u2000-\u200a\u2028\u2029\u202f\u205f\u3000\ufeff]</code>. For example, <code>/\S\w*/</code> matches "foo" in "foo bar".</p></td></tr>',type: 'html'
value: '<tr><td><code>\c<em>X</em></code></td><td><p>Matches a control character using <a href="https://en.wikipedia.org/wiki/Caret_notation">caret notation</a>, where "X" is a letter from A–Z (corresponding to codepoints <code>U+0001</code><em>–</em><code>U+001F</code>). For example, <code>/\cM/</code> matches "\r" in "\r\n".</p></td></tr>',type: 'html'
value: '<tr><td><code>\</code></td><td><p>Indicates that the following character should be treated specially, or "escaped". It behaves one of two ways.</p><ul><li>For characters that are usually treated literally, indicates that the next character is special and not to be interpreted literally. For example, <code>/b/</code> matches the character "b". By placing a backslash in front of "b", that is by using <code>/\b/</code>, the character becomes special to mean match a word boundary.</li><li>For characters that are usually treated specially, indicates that the next character is not special and should be interpreted literally. For example, "*" is a special character that means 0 or more occurrences of the preceding character should be matched; for example, <code>/a*/</code> means match 0 or more "a"s. To match <code>*</code> literally, precede it with a backslash; for example, <code>/a\*/</code> matches "a*".</li></ul><p>Note that some characters like <code>:</code>, <code>-</code>, <code>@</code>, etc. neither have a special meaning when escaped nor when unescaped. Escape sequences like <code>\:</code>, <code>\-</code>, <code>\@</code> will be equivalent to their literal, unescaped character equivalents in regular expressions. However, in regular expressions with the <a href="/en-US/docs/Web/JavaScript/Guide/Regular_Expressions#advanced_searching_with_flags_2">unicode flag</a>, these will cause an <em>invalid identity escape</em> error. This is done to ensure backward compatibility with existing code that uses new escape sequences like <code>\p</code> or <code>\k</code>.</p><div class="notecard note"><p><strong>Note:</strong> To match this character literally, escape it with itself. In other words to search for <code>\</code> use <code>/\\/</code>.</p></div></td></tr>'
```
##### tr (152:3) => tableRow
```
type: 'html'
value: '<th scope="col">Characters</th>',type: 'html'
value: '<th scope="col">Meaning</th>'
```
##### td (160:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Matches the beginning of input. If the multiline flag is set to true, also matches immediately after a line break character. For example, '
  type: 'inlineCode'
  value: '/^A/'
  type: 'text'
  value: ' does not match the "A" in "an A", but does match the first "A" in "An A".',type: 'blockquote'
children: 
  type: 'paragraph'
  children: 
    type: 'strong'
    children: 
      type: 'text'
      value: 'Note:'
    type: 'text'
    value: ' This character has a different meaning when it appears at the start of a '
    type: 'link'
    title: 

    url: '/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Groups_and_Ranges'
    children: 
      type: 'text'
      value: 'group'
    type: 'text'
    value: '.'
```
##### tr (158:3) => tableRow
```
type: 'html'
value: '<td><p>Matches the beginning of input. If the multiline flag is set to true, also matches immediately after a line break character. For example, <code>/^A/</code> does not match the "A" in "an A", but does match the first "A" in "An A".</p><div class="notecard note"><p><strong>Note:</strong> This character has a different meaning when it appears at the start of a <a href="/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Groups_and_Ranges">group</a>.</p></div></td>'
```
##### td (170:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Matches the end of input. If the multiline flag is set to true, also matches immediately before a line break character. For example, '
  type: 'inlineCode'
  value: '/t$/'
  type: 'text'
  value: ' does not match the "t" in "eater", but does match it in "eat".'
```
##### tr (168:3) => tableRow
```
type: 'html'
value: '<td><p>Matches the end of input. If the multiline flag is set to true, also matches immediately before a line break character. For example, <code>/t$/</code> does not match the "t" in "eater", but does match it in "eat".</p></td>'
```
##### td (176:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Matches a word boundary. This is the position where a word character is not followed or preceded by another word-character, such as between a letter and a space. Note that a matched word boundary is not included in the match. In other words, the length of a matched word boundary is zero.',type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Examples:',type: 'list'
ordered: 'false'
start: 

spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: '/\bm/'
      type: 'text'
      value: ' matches the "m" in "moon".'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: '/oo\b/'
      type: 'text'
      value: ' does not match the "oo" in "moon", because "oo" is followed by "n" which is a word character.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: '/oon\b/'
      type: 'text'
      value: ' matches the "oon" in "moon", because "oon" is the end of the string, thus not followed by a word character.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: '/\w\b\w/'
      type: 'text'
      value: ' will never match anything, because a word character can never be followed by both a non-word and a word character.',type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'To match a backspace character ('
  type: 'inlineCode'
  value: '[\b]'
  type: 'text'
  value: '), see '
  type: 'link'
  title: 

  url: '/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Character_Classes'
  children: 
    type: 'text'
    value: 'Character Classes'
  type: 'text'
  value: '.'
```
##### tr (174:3) => tableRow
```
type: 'html'
value: '<td><p>Matches a word boundary. This is the position where a word character is not followed or preceded by another word-character, such as between a letter and a space. Note that a matched word boundary is not included in the match. In other words, the length of a matched word boundary is zero.</p><p>Examples:</p><ul><li><code>/\bm/</code> matches the "m" in "moon".</li><li><code>/oo\b/</code> does not match the "oo" in "moon", because "oo" is followed by "n" which is a word character.</li><li><code>/oon\b/</code> matches the "oon" in "moon", because "oon" is the end of the string, thus not followed by a word character.</li><li><code>/\w\b\w/</code> will never match anything, because a word character can never be followed by both a non-word and a word character.</li></ul><p>To match a backspace character (<code>[\b]</code>), see <a href="/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Character_Classes">Character Classes</a>.</p></td>'
```
##### td (193:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Matches a non-word boundary. This is a position where the previous and next character are of the same type: Either both must be words, or both must be non-words, for example between two letters or between two spaces. The beginning and end of a string are considered non-words. Same as the matched word boundary, the matched non-word boundary is also not included in the match. For example, '
  type: 'inlineCode'
  value: '/\Bon/'
  type: 'text'
  value: ' matches "on" in "at noon", and '
  type: 'inlineCode'
  value: '/ye\B/'
  type: 'text'
  value: ' matches "ye" in "possibly yesterday".'
```
##### tr (191:3) => tableRow
```
type: 'html'
value: '<td><p>Matches a non-word boundary. This is a position where the previous and next character are of the same type: Either both must be words, or both must be non-words, for example between two letters or between two spaces. The beginning and end of a string are considered non-words. Same as the matched word boundary, the matched non-word boundary is also not included in the match. For example, <code>/\Bon/</code> matches "on" in "at noon", and <code>/ye\B/</code> matches "ye" in "possibly yesterday".</p></td>'
```
##### table.standard-table (150:1) => table
```
type: 'html'
value: '<tr><th scope="col">Characters</th><th scope="col">Meaning</th></tr>',type: 'html'
value: '<tr><td><code>^</code></td><td><p>Matches the beginning of input. If the multiline flag is set to true, also matches immediately after a line break character. For example, <code>/^A/</code> does not match the "A" in "an A", but does match the first "A" in "An A".</p><div class="notecard note"><p><strong>Note:</strong> This character has a different meaning when it appears at the start of a <a href="/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Groups_and_Ranges">group</a>.</p></div></td></tr>',type: 'html'
value: '<tr><td><code>$</code></td><td><p>Matches the end of input. If the multiline flag is set to true, also matches immediately before a line break character. For example, <code>/t$/</code> does not match the "t" in "eater", but does match it in "eat".</p></td></tr>',type: 'html'
value: '<tr><td><code>\b</code></td><td><p>Matches a word boundary. This is the position where a word character is not followed or preceded by another word-character, such as between a letter and a space. Note that a matched word boundary is not included in the match. In other words, the length of a matched word boundary is zero.</p><p>Examples:</p><ul><li><code>/\bm/</code> matches the "m" in "moon".</li><li><code>/oo\b/</code> does not match the "oo" in "moon", because "oo" is followed by "n" which is a word character.</li><li><code>/oon\b/</code> matches the "oon" in "moon", because "oon" is the end of the string, thus not followed by a word character.</li><li><code>/\w\b\w/</code> will never match anything, because a word character can never be followed by both a non-word and a word character.</li></ul><p>To match a backspace character (<code>[\b]</code>), see <a href="/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Character_Classes">Character Classes</a>.</p></td></tr>',type: 'html'
value: '<tr><td><code>\B</code></td><td><p>Matches a non-word boundary. This is a position where the previous and next character are of the same type: Either both must be words, or both must be non-words, for example between two letters or between two spaces. The beginning and end of a string are considered non-words. Same as the matched word boundary, the matched non-word boundary is also not included in the match. For example, <code>/\Bon/</code> matches "on" in "at noon", and <code>/ye\B/</code> matches "ye" in "possibly yesterday".</p></td></tr>'
```
##### tr (208:3) => tableRow
```
type: 'html'
value: '<th scope="col">Characters</th>',type: 'html'
value: '<th scope="col">Meaning</th>'
```
##### td (216:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'strong'
  children: 
    type: 'text'
    value: 'Lookahead assertion:'
  type: 'text'
  value: ' '
  type: 'text'
  value: 'Matches "x" only if "x" is followed by "y". For example, /'
  type: 'inlineCode'
  value: 'Jack(?=Sprat)/'
  type: 'text'
  value: ' matches "Jack" only if it is followed by "Sprat".'
  type: 'break'
  type: 'inlineCode'
  value: '/Jack(?=Sprat|Frost)/'
  type: 'text'
  value: ' matches "Jack" only if it is followed by "Sprat" or "Frost". However, neither "Sprat" nor "Frost" is part of the match results.'
```
##### tr (214:3) => tableRow
```
type: 'html'
value: '<td><p><strong>Lookahead assertion: </strong>Matches "x" only if "x" is followed by "y". For example, /<code>Jack(?=Sprat)/</code> matches "Jack" only if it is followed by "Sprat".<br><code>/Jack(?=Sprat|Frost)/</code> matches "Jack" only if it is followed by "Sprat" or "Frost". However, neither "Sprat" nor "Frost" is part of the match results.</p></td>'
```
##### td (223:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'strong'
  children: 
    type: 'text'
    value: 'Negative lookahead assertion:'
  type: 'text'
  value: ' '
  type: 'text'
  value: 'Matches "x" only if "x" is not followed by "y". For example, '
  type: 'inlineCode'
  value: '/\d+(?!\.)/'
  type: 'text'
  value: ' matches a number only if it is not followed by a decimal point. '
  type: 'inlineCode'
  value: '/\d+(?!\.)/.exec('3.141')'
  type: 'text'
  value: ' matches "141" but not "3".'
```
##### tr (221:3) => tableRow
```
type: 'html'
value: '<td><p><strong>Negative lookahead assertion: </strong>Matches "x" only if "x" is not followed by "y". For example, <code>/\d+(?!\.)/</code> matches a number only if it is not followed by a decimal point. <code>/\d+(?!\.)/.exec('3.141')</code> matches "141" but not "3".</p></td>'
```
##### td (229:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'strong'
  children: 
    type: 'text'
    value: 'Lookbehind assertion:'
  type: 'text'
  value: ' '
  type: 'text'
  value: 'Matches "x" only if "x" is preceded by "y". For example, '
  type: 'inlineCode'
  value: '/(?<=Jack)Sprat/'
  type: 'text'
  value: ' matches "Sprat" only if it is preceded by "Jack". '
  type: 'inlineCode'
  value: '/(?<=Jack|Tom)Sprat/'
  type: 'text'
  value: ' matches "Sprat" only if it is preceded by "Jack" or "Tom". However, neither "Jack" nor "Tom" is part of the match results.'
```
##### tr (227:3) => tableRow
```
type: 'html'
value: '<td><p><strong>Lookbehind assertion: </strong>Matches "x" only if "x" is preceded by "y". For example, <code>/(?&#x3C;=Jack)Sprat/</code> matches "Sprat" only if it is preceded by "Jack". <code>/(?&#x3C;=Jack|Tom)Sprat/</code> matches "Sprat" only if it is preceded by "Jack" or "Tom". However, neither "Jack" nor "Tom" is part of the match results.</p></td>'
```
##### td (235:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'strong'
  children: 
    type: 'text'
    value: 'Negative lookbehind assertion:'
  type: 'text'
  value: ' '
  type: 'text'
  value: 'Matches "x" only if "x" is not preceded by "y". For example, '
  type: 'inlineCode'
  value: '/(?<!-)\d+/'
  type: 'text'
  value: ' matches a number only if it is not preceded by a minus sign. '
  type: 'inlineCode'
  value: '/(?<!-)\d+/.exec('3')'
  type: 'text'
  value: ' matches "3". '
  type: 'inlineCode'
  value: '/(?<!-)\d+/.exec('-3')'
  type: 'text'
  value: '  match is not found because the number is preceded by the minus sign.'
```
##### tr (233:3) => tableRow
```
type: 'html'
value: '<td><p><strong>Negative lookbehind assertion: </strong>Matches "x" only if "x" is not preceded by "y". For example, <code>/(?&#x3C;!-)\d+/</code> matches a number only if it is not preceded by a minus sign. <code>/(?&#x3C;!-)\d+/.exec('3')</code> matches "3". <code>/(?&#x3C;!-)\d+/.exec('-3')</code>  match is not found because the number is preceded by the minus sign.</p></td>'
```
##### table.standard-table (206:1) => table
```
type: 'html'
value: '<tr><th scope="col">Characters</th><th scope="col">Meaning</th></tr>',type: 'html'
value: '<tr><td><code>x(?=y)</code></td><td><p><strong>Lookahead assertion: </strong>Matches "x" only if "x" is followed by "y". For example, /<code>Jack(?=Sprat)/</code> matches "Jack" only if it is followed by "Sprat".<br><code>/Jack(?=Sprat|Frost)/</code> matches "Jack" only if it is followed by "Sprat" or "Frost". However, neither "Sprat" nor "Frost" is part of the match results.</p></td></tr>',type: 'html'
value: '<tr><td><code>x(?!y)</code></td><td><p><strong>Negative lookahead assertion: </strong>Matches "x" only if "x" is not followed by "y". For example, <code>/\d+(?!\.)/</code> matches a number only if it is not followed by a decimal point. <code>/\d+(?!\.)/.exec('3.141')</code> matches "141" but not "3".</p></td></tr>',type: 'html'
value: '<tr><td><code>(?&#x3C;=y)x</code></td><td><p><strong>Lookbehind assertion: </strong>Matches "x" only if "x" is preceded by "y". For example, <code>/(?&#x3C;=Jack)Sprat/</code> matches "Sprat" only if it is preceded by "Jack". <code>/(?&#x3C;=Jack|Tom)Sprat/</code> matches "Sprat" only if it is preceded by "Jack" or "Tom". However, neither "Jack" nor "Tom" is part of the match results.</p></td></tr>',type: 'html'
value: '<tr><td><code>(?&#x3C;!y)x</code></td><td><p><strong>Negative lookbehind assertion: </strong>Matches "x" only if "x" is not preceded by "y". For example, <code>/(?&#x3C;!-)\d+/</code> matches a number only if it is not preceded by a minus sign. <code>/(?&#x3C;!-)\d+/.exec('3')</code> matches "3". <code>/(?&#x3C;!-)\d+/.exec('-3')</code>  match is not found because the number is preceded by the minus sign.</p></td></tr>'
```
##### tr (247:3) => tableRow
```
type: 'html'
value: '<th scope="col">Characters</th>',type: 'html'
value: '<th scope="col">Meaning</th>'
```
##### code (254:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### td (255:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Matches either "x" or "y". For example, '
  type: 'inlineCode'
  value: '/green|red/'
  type: 'text'
  value: ' matches "green" in "green apple" and "red" in "red apple".'
```
##### tr (253:3) => tableRow
```
type: 'html'
value: '<td><p>Matches either "x" or "y". For example, <code>/green|red/</code> matches "green" in "green apple" and "red" in "red apple".</p></td>'
```
##### code (260:8) => text
```
type: 'element'
tagName: 'br'
properties: 

children: 

```
##### td (262:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'A character class. Matches any one of the enclosed characters. You can specify a range of characters by using a hyphen, but if the hyphen appears as the first or last character enclosed in the square brackets it is taken as a literal hyphen to be included in the character class as a normal character.',type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'For example, '
  type: 'inlineCode'
  value: '[abcd]'
  type: 'text'
  value: ' is the same as '
  type: 'inlineCode'
  value: '[a-d]'
  type: 'text'
  value: '. They match the "b" in "brisket", and the "c" in "chop".',type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'For example, '
  type: 'inlineCode'
  value: '[abcd-]'
  type: 'text'
  value: ' and '
  type: 'inlineCode'
  value: '[-abcd]'
  type: 'text'
  value: ' match the "b" in "brisket", the "c" in "chop", and the "-" (hyphen) in "non-profit".',type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'For example, '
  type: 'inlineCode'
  value: '[\w-]'
  type: 'text'
  value: ' is the same as '
  type: 'inlineCode'
  value: '[A-Za-z0-9_-]'
  type: 'text'
  value: '. They both match the "b" in "brisket", the "c" in "chop", and the "n" in "non-profit".'
```
##### tr (259:3) => tableRow
```
type: 'html'
value: '<td><p>A character class. Matches any one of the enclosed characters. You can specify a range of characters by using a hyphen, but if the hyphen appears as the first or last character enclosed in the square brackets it is taken as a literal hyphen to be included in the character class as a normal character.</p><p>For example, <code>[abcd]</code> is the same as <code>[a-d]</code>. They match the "b" in "brisket", and the "c" in "chop".</p><p>For example, <code>[abcd-]</code> and <code>[-abcd]</code> match the "b" in "brisket", the "c" in "chop", and the "-" (hyphen) in "non-profit".</p><p>For example, <code>[\w-]</code> is the same as <code>[A-Za-z0-9_-]</code>. They both match the "b" in "brisket", the "c" in "chop", and the "n" in "non-profit".</p></td>'
```
##### code (274:8) => text
```
type: 'element'
tagName: 'br'
properties: 

children: 

```
##### td (273:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'html'
  value: '<code>[^xyz]<br>[^a-c]</code>'
```
##### td (277:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'A negated or complemented character class. That is, it matches anything that is not enclosed in the brackets. You can specify a range of characters by using a hyphen, but if the hyphen appears as the first or last character enclosed in the square brackets it is taken as a literal hyphen to be included in the character class as a normal character. For example, '
  type: 'inlineCode'
  value: '[^abc]'
  type: 'text'
  value: ' is the same as '
  type: 'inlineCode'
  value: '[^a-c]'
  type: 'text'
  value: '. They initially match "o" in "bacon" and "h" in "chop".',type: 'blockquote'
children: 
  type: 'paragraph'
  children: 
    type: 'strong'
    children: 
      type: 'text'
      value: 'Note:'
    type: 'text'
    value: ' The ^ character may also indicate the '
    type: 'link'
    title: 

    url: '/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Assertions'
    children: 
      type: 'text'
      value: 'beginning of input'
    type: 'text'
    value: '.'
```
##### tr (272:3) => tableRow
```
type: 'html'
value: '<td><p><code>[^xyz]<br>[^a-c]</code></p></td>',type: 'html'
value: '<td><p>A negated or complemented character class. That is, it matches anything that is not enclosed in the brackets. You can specify a range of characters by using a hyphen, but if the hyphen appears as the first or last character enclosed in the square brackets it is taken as a literal hyphen to be included in the character class as a normal character. For example, <code>[^abc]</code> is the same as <code>[^a-c]</code>. They initially match "o" in "bacon" and "h" in "chop".</p><div class="notecard note"><p><strong>Note:</strong> The ^ character may also indicate the <a href="/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Assertions">beginning of input</a>.</p></div></td>'
```
##### code (286:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### code (288:50) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### td (287:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'strong'
  children: 
    type: 'text'
    value: 'Capturing group:'
  type: 'text'
  value: ' '
  type: 'text'
  value: 'Matches '
  type: 'html'
  value: '<code><em>x</em></code>'
  type: 'text'
  value: ' and remembers the match. For example, '
  type: 'inlineCode'
  value: '/(foo)/'
  type: 'text'
  value: ' matches and remembers "foo" in "foo bar". ',type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'A regular expression may have multiple capturing groups. In results, matches to capturing groups typically in an array whose members are in the same order as the left parentheses in the capturing group. This is usually just the order of the capturing groups themselves. This becomes important when capturing groups are nested. Matches are accessed using the index of the result's elements ('
  type: 'inlineCode'
  value: '[1], ..., [n]'
  type: 'text'
  value: ') or from the predefined '
  type: 'inlineCode'
  value: 'RegExp'
  type: 'text'
  value: ' object's properties ('
  type: 'inlineCode'
  value: '$1, ..., $9'
  type: 'text'
  value: ').',type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Capturing groups have a performance penalty. If you don't need the matched substring to be recalled, prefer non-capturing parentheses (see below).',type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'link'
  title: 

  url: '/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/match'
  children: 
    type: 'inlineCode'
    value: 'String.match()'
  type: 'text'
  value: ' won't return groups if the '
  type: 'inlineCode'
  value: '/.../g'
  type: 'text'
  value: ' flag is set. However, you can still use '
  type: 'link'
  title: 

  url: '/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/matchAll'
  children: 
    type: 'inlineCode'
    value: 'String.matchAll()'
  type: 'text'
  value: ' to get all matches.'
```
##### tr (285:3) => tableRow
```
type: 'html'
value: '<td><p><strong>Capturing group: </strong>Matches <code><em>x</em></code> and remembers the match. For example, <code>/(foo)/</code> matches and remembers "foo" in "foo bar". </p><p>A regular expression may have multiple capturing groups. In results, matches to capturing groups typically in an array whose members are in the same order as the left parentheses in the capturing group. This is usually just the order of the capturing groups themselves. This becomes important when capturing groups are nested. Matches are accessed using the index of the result's elements (<code>[1], ..., [n]</code>) or from the predefined <code>RegExp</code> object's properties (<code>$1, ..., $9</code>).</p><p>Capturing groups have a performance penalty. If you don't need the matched substring to be recalled, prefer non-capturing parentheses (see below).</p><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/match">String.match()</a></code> won't return groups if the <code>/.../g</code> flag is set. However, you can still use <code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/matchAll">String.matchAll()</a></code> to get all matches.</p></td>'
```
##### code (298:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'n'
```
##### td (299:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Where "n" is a positive integer. A back reference to the last substring matching the n parenthetical in the regular expression (counting left parentheses). For example, '
  type: 'inlineCode'
  value: '/apple(,)\sorange\1/'
  type: 'text'
  value: ' matches "apple, orange," in "apple, orange, cherry, peach".'
```
##### tr (297:3) => tableRow
```
type: 'html'
value: '<td><p>Where "n" is a positive integer. A back reference to the last substring matching the n parenthetical in the regular expression (counting left parentheses). For example, <code>/apple(,)\sorange\1/</code> matches "apple, orange," in "apple, orange, cherry, peach".</p></td>'
```
##### td (305:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'A back reference to the last substring matching the '
  type: 'strong'
  children: 
    type: 'text'
    value: 'Named capture group'
  type: 'text'
  value: ' '
  type: 'text'
  value: 'specified by '
  type: 'inlineCode'
  value: '<Name>'
  type: 'text'
  value: '.',type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'For example, '
  type: 'inlineCode'
  value: '/(?<title>\w+), yes \k<title>/'
  type: 'text'
  value: ' matches "Sir, yes Sir" in "Do you copy? Sir, yes Sir!".',type: 'blockquote'
children: 
  type: 'paragraph'
  children: 
    type: 'strong'
    children: 
      type: 'text'
      value: 'Note:'
    type: 'text'
    value: ' '
    type: 'inlineCode'
    value: '\k'
    type: 'text'
    value: ' is used literally here to indicate the beginning of a back reference to a Named capture group.'
```
##### tr (303:3) => tableRow
```
type: 'html'
value: '<td><p>A back reference to the last substring matching the <strong>Named capture group </strong>specified by <code>&#x3C;Name></code>.</p><p>For example, <code>/(?&#x3C;title>\w+), yes \k&#x3C;title>/</code> matches "Sir, yes Sir" in "Do you copy? Sir, yes Sir!".</p><div class="notecard note"><p><strong>Note:</strong> <code>\k</code> is used literally here to indicate the beginning of a back reference to a Named capture group.</p></div></td>'
```
##### td (317:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'strong'
  children: 
    type: 'text'
    value: 'Named capturing group:'
  type: 'text'
  value: ' '
  type: 'text'
  value: 'Matches "x" and stores it on the groups property of the returned matches under the name specified by '
  type: 'inlineCode'
  value: '<Name>'
  type: 'text'
  value: '. The angle brackets ('
  type: 'inlineCode'
  value: '<'
  type: 'text'
  value: ' and '
  type: 'inlineCode'
  value: '>'
  type: 'text'
  value: ') are required for group name.',type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'For example, to extract the United States area code from a phone number, we could use '
  type: 'inlineCode'
  value: '/\((?<area>\d\d\d)\)/'
  type: 'text'
  value: '. The resulting number would appear under '
  type: 'inlineCode'
  value: 'matches.groups.area'
  type: 'text'
  value: '.'
```
##### tr (315:3) => tableRow
```
type: 'html'
value: '<td><p><strong>Named capturing group: </strong>Matches "x" and stores it on the groups property of the returned matches under the name specified by <code>&#x3C;Name></code>. The angle brackets (<code>&#x3C;</code> and <code>></code>) are required for group name.</p><p>For example, to extract the United States area code from a phone number, we could use <code>/\((?&#x3C;area>\d\d\d)\)/</code>. The resulting number would appear under <code>matches.groups.area</code>.</p></td>'
```
##### code (324:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### table.standard-table (245:1) => table
```
type: 'html'
value: '<tr><th scope="col">Characters</th><th scope="col">Meaning</th></tr>',type: 'html'
value: '<tr><td><code><em>x</em>|<em>y</em></code></td><td><p>Matches either "x" or "y". For example, <code>/green|red/</code> matches "green" in "green apple" and "red" in "red apple".</p></td></tr>',type: 'html'
value: '<tr><td><code>[xyz]<br>[a-c]</code></td><td><p>A character class. Matches any one of the enclosed characters. You can specify a range of characters by using a hyphen, but if the hyphen appears as the first or last character enclosed in the square brackets it is taken as a literal hyphen to be included in the character class as a normal character.</p><p>For example, <code>[abcd]</code> is the same as <code>[a-d]</code>. They match the "b" in "brisket", and the "c" in "chop".</p><p>For example, <code>[abcd-]</code> and <code>[-abcd]</code> match the "b" in "brisket", the "c" in "chop", and the "-" (hyphen) in "non-profit".</p><p>For example, <code>[\w-]</code> is the same as <code>[A-Za-z0-9_-]</code>. They both match the "b" in "brisket", the "c" in "chop", and the "n" in "non-profit".</p></td></tr>',type: 'html'
value: '<tr><td><p><code>[^xyz]<br>[^a-c]</code></p></td><td><p>A negated or complemented character class. That is, it matches anything that is not enclosed in the brackets. You can specify a range of characters by using a hyphen, but if the hyphen appears as the first or last character enclosed in the square brackets it is taken as a literal hyphen to be included in the character class as a normal character. For example, <code>[^abc]</code> is the same as <code>[^a-c]</code>. They initially match "o" in "bacon" and "h" in "chop".</p><div class="notecard note"><p><strong>Note:</strong> The ^ character may also indicate the <a href="/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Assertions">beginning of input</a>.</p></div></td></tr>',type: 'html'
value: '<tr><td><code>(<em>x</em>)</code></td><td><p><strong>Capturing group: </strong>Matches <code><em>x</em></code> and remembers the match. For example, <code>/(foo)/</code> matches and remembers "foo" in "foo bar". </p><p>A regular expression may have multiple capturing groups. In results, matches to capturing groups typically in an array whose members are in the same order as the left parentheses in the capturing group. This is usually just the order of the capturing groups themselves. This becomes important when capturing groups are nested. Matches are accessed using the index of the result's elements (<code>[1], ..., [n]</code>) or from the predefined <code>RegExp</code> object's properties (<code>$1, ..., $9</code>).</p><p>Capturing groups have a performance penalty. If you don't need the matched substring to be recalled, prefer non-capturing parentheses (see below).</p><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/match">String.match()</a></code> won't return groups if the <code>/.../g</code> flag is set. However, you can still use <code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/matchAll">String.matchAll()</a></code> to get all matches.</p></td></tr>',type: 'html'
value: '<tr><td><code>\<em>n</em></code></td><td><p>Where "n" is a positive integer. A back reference to the last substring matching the n parenthetical in the regular expression (counting left parentheses). For example, <code>/apple(,)\sorange\1/</code> matches "apple, orange," in "apple, orange, cherry, peach".</p></td></tr>',type: 'html'
value: '<tr><td>\k&#x3C;Name></td><td><p>A back reference to the last substring matching the <strong>Named capture group </strong>specified by <code>&#x3C;Name></code>.</p><p>For example, <code>/(?&#x3C;title>\w+), yes \k&#x3C;title>/</code> matches "Sir, yes Sir" in "Do you copy? Sir, yes Sir!".</p><div class="notecard note"><p><strong>Note:</strong> <code>\k</code> is used literally here to indicate the beginning of a back reference to a Named capture group.</p></div></td></tr>',type: 'html'
value: '<tr><td><code>(?&#x3C;Name>x)</code></td><td><p><strong>Named capturing group: </strong>Matches "x" and stores it on the groups property of the returned matches under the name specified by <code>&#x3C;Name></code>. The angle brackets (<code>&#x3C;</code> and <code>></code>) are required for group name.</p><p>For example, to extract the United States area code from a phone number, we could use <code>/\((?&#x3C;area>\d\d\d)\)/</code>. The resulting number would appear under <code>matches.groups.area</code>.</p></td></tr>'
```
##### tr (339:3) => tableRow
```
type: 'html'
value: '<th scope="col">Characters</th>',type: 'html'
value: '<th scope="col">Meaning</th>'
```
##### code (346:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### td (347:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Matches the preceding item "x" 0 or more times. For example, '
  type: 'inlineCode'
  value: '/bo*/'
  type: 'text'
  value: ' matches "boooo" in "A ghost booooed" and "b" in "A bird warbled", but nothing in "A goat grunted".'
```
##### tr (345:3) => tableRow
```
type: 'html'
value: '<td><p>Matches the preceding item "x" 0 or more times. For example, <code>/bo*/</code> matches "boooo" in "A ghost booooed" and "b" in "A bird warbled", but nothing in "A goat grunted".</p></td>'
```
##### code (352:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### td (353:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Matches the preceding item "x" 1 or more times. Equivalent to '
  type: 'inlineCode'
  value: '{1,}'
  type: 'text'
  value: '. For example, '
  type: 'inlineCode'
  value: '/a+/'
  type: 'text'
  value: ' matches the "a" in "candy" and all the "a"'s in "caaaaaaandy".'
```
##### tr (351:3) => tableRow
```
type: 'html'
value: '<td><p>Matches the preceding item "x" 1 or more times. Equivalent to <code>{1,}</code>. For example, <code>/a+/</code> matches the "a" in "candy" and all the "a"'s in "caaaaaaandy".</p></td>'
```
##### code (358:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### td (359:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Matches the preceding item "x" 0 or 1 times. For example, '
  type: 'inlineCode'
  value: '/e?le?/'
  type: 'text'
  value: ' matches the "el" in "angel" and the "le" in "angle."',type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'If used immediately after any of the quantifiers '
  type: 'inlineCode'
  value: '*'
  type: 'text'
  value: ', '
  type: 'inlineCode'
  value: '+'
  type: 'text'
  value: ', '
  type: 'inlineCode'
  value: '?'
  type: 'text'
  value: ', or '
  type: 'inlineCode'
  value: '{}'
  type: 'text'
  value: ', makes the quantifier non-greedy (matching the minimum number of times), as opposed to the default, which is greedy (matching the maximum number of times).'
```
##### tr (357:3) => tableRow
```
type: 'html'
value: '<td><p>Matches the preceding item "x" 0 or 1 times. For example, <code>/e?le?/</code> matches the "el" in "angel" and the "le" in "angle."</p><p>If used immediately after any of the quantifiers <code>*</code>, <code>+</code>, <code>?</code>, or <code>{}</code>, makes the quantifier non-greedy (matching the minimum number of times), as opposed to the default, which is greedy (matching the maximum number of times).</p></td>'
```
##### code (366:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### td (367:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Where "n" is a positive integer, matches exactly "n" occurrences of the preceding item "x". For example, '
  type: 'inlineCode'
  value: '/a{2}/'
  type: 'text'
  value: ' doesn't match the "a" in "candy", but it matches all of the "a"'s in "caandy", and the first two "a"'s in "caaandy".'
```
##### tr (365:3) => tableRow
```
type: 'html'
value: '<td><p>Where "n" is a positive integer, matches exactly "n" occurrences of the preceding item "x". For example, <code>/a{2}/</code> doesn't match the "a" in "candy", but it matches all of the "a"'s in "caandy", and the first two "a"'s in "caaandy".</p></td>'
```
##### code (372:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### td (373:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Where "n" is a positive integer, matches at least "n" occurrences of the preceding item "x". For example, '
  type: 'inlineCode'
  value: '/a{2,}/'
  type: 'text'
  value: ' doesn't match the "a" in "candy", but matches all of the a's in "caandy" and in "caaaaaaandy".'
```
##### tr (371:3) => tableRow
```
type: 'html'
value: '<td><p>Where "n" is a positive integer, matches at least "n" occurrences of the preceding item "x". For example, <code>/a{2,}/</code> doesn't match the "a" in "candy", but matches all of the a's in "caandy" and in "caaaaaaandy".</p></td>'
```
##### code (378:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### code (380:77) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'm'
```
##### td (379:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Where "n" is 0 or a positive integer, "m" is a positive integer, and '
  type: 'html'
  value: '<code><em>m</em> > <em>n</em></code>'
  type: 'text'
  value: ', matches at least "n" and at most "m" occurrences of the preceding item "x". For example, '
  type: 'inlineCode'
  value: '/a{1,3}/'
  type: 'text'
  value: ' matches nothing in "cndy", the "a" in "candy", the two "a"'s in "caandy", and the first three "a"'s in "caaaaaaandy". Notice that when matching "caaaaaaandy", the match is "aaa", even though the original string had more "a"s in it.'
```
##### tr (377:3) => tableRow
```
type: 'html'
value: '<td><p>Where "n" is 0 or a positive integer, "m" is a positive integer, and <code><em>m</em> > <em>n</em></code>, matches at least "n" and at most "m" occurrences of the preceding item "x". For example, <code>/a{1,3}/</code> matches nothing in "cndy", the "a" in "candy", the two "a"'s in "caandy", and the first three "a"'s in "caaaaaaandy". Notice that when matching "caaaaaaandy", the match is "aaa", even though the original string had more "a"s in it.</p></td>'
```
##### code (385:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### code (386:6) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### code (387:6) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### code (388:6) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### code (389:6) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### code (390:6) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### td (384:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'html'
  value: '<code><em>x</em>*?</code>'
  type: 'break'
  type: 'html'
  value: '<code><em>x</em>+?</code>'
  type: 'break'
  type: 'html'
  value: '<code><em>x</em>??</code>'
  type: 'break'
  type: 'html'
  value: '<code><em>x</em>{n}?</code>'
  type: 'break'
  type: 'html'
  value: '<code><em>x</em>{n,}?</code>'
  type: 'break'
  type: 'html'
  value: '<code><em>x</em>{n,m}?</code>'
```
##### td (392:4) => tableCell
```
type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'By default quantifiers like '
  type: 'inlineCode'
  value: '*'
  type: 'text'
  value: ' and '
  type: 'inlineCode'
  value: '+'
  type: 'text'
  value: ' are "greedy", meaning that they try to match as much of the string as possible. The '
  type: 'inlineCode'
  value: '?'
  type: 'text'
  value: ' character after the quantifier makes the quantifier "non-greedy": meaning that it will stop as soon as it finds a match. For example, given a string like "some <foo> <bar> new </bar> </foo> thing":',type: 'list'
ordered: 'false'
start: 

spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: '/<.*>/'
      type: 'text'
      value: ' will match "<foo> <bar> new </bar> </foo>"'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: '/<.*?>/'
      type: 'text'
      value: ' will match "<foo>"'
```
##### tr (383:3) => tableRow
```
type: 'html'
value: '<td><p><code><em>x</em>*?</code><br><code><em>x</em>+?</code><br><code><em>x</em>??</code><br><code><em>x</em>{n}?</code><br><code><em>x</em>{n,}?</code><br><code><em>x</em>{n,m}?</code></p></td>',type: 'html'
value: '<td><p>By default quantifiers like <code>*</code> and <code>+</code> are "greedy", meaning that they try to match as much of the string as possible. The <code>?</code> character after the quantifier makes the quantifier "non-greedy": meaning that it will stop as soon as it finds a match. For example, given a string like "some &#x3C;foo> &#x3C;bar> new &#x3C;/bar> &#x3C;/foo> thing":</p><ul><li><code>/&#x3C;.*>/</code> will match "&#x3C;foo> &#x3C;bar> new &#x3C;/bar> &#x3C;/foo>"</li><li><code>/&#x3C;.*?>/</code> will match "&#x3C;foo>"</li></ul></td>'
```
##### table.standard-table (337:1) => table
```
type: 'html'
value: '<tr><th scope="col">Characters</th><th scope="col">Meaning</th></tr>',type: 'html'
value: '<tr><td><code><em>x</em>*</code></td><td><p>Matches the preceding item "x" 0 or more times. For example, <code>/bo*/</code> matches "boooo" in "A ghost booooed" and "b" in "A bird warbled", but nothing in "A goat grunted".</p></td></tr>',type: 'html'
value: '<tr><td><code><em>x</em>+</code></td><td><p>Matches the preceding item "x" 1 or more times. Equivalent to <code>{1,}</code>. For example, <code>/a+/</code> matches the "a" in "candy" and all the "a"'s in "caaaaaaandy".</p></td></tr>',type: 'html'
value: '<tr><td><code><em>x</em>?</code></td><td><p>Matches the preceding item "x" 0 or 1 times. For example, <code>/e?le?/</code> matches the "el" in "angel" and the "le" in "angle."</p><p>If used immediately after any of the quantifiers <code>*</code>, <code>+</code>, <code>?</code>, or <code>{}</code>, makes the quantifier non-greedy (matching the minimum number of times), as opposed to the default, which is greedy (matching the maximum number of times).</p></td></tr>',type: 'html'
value: '<tr><td><code><em>x</em>{<em>n</em>}</code></td><td><p>Where "n" is a positive integer, matches exactly "n" occurrences of the preceding item "x". For example, <code>/a{2}/</code> doesn't match the "a" in "candy", but it matches all of the "a"'s in "caandy", and the first two "a"'s in "caaandy".</p></td></tr>',type: 'html'
value: '<tr><td><code><em>x</em>{<em>n</em>,}</code></td><td><p>Where "n" is a positive integer, matches at least "n" occurrences of the preceding item "x". For example, <code>/a{2,}/</code> doesn't match the "a" in "candy", but matches all of the a's in "caandy" and in "caaaaaaandy".</p></td></tr>',type: 'html'
value: '<tr><td><code><em>x</em>{<em>n</em>,<em>m</em>}</code></td><td><p>Where "n" is 0 or a positive integer, "m" is a positive integer, and <code><em>m</em> > <em>n</em></code>, matches at least "n" and at most "m" occurrences of the preceding item "x". For example, <code>/a{1,3}/</code> matches nothing in "cndy", the "a" in "candy", the two "a"'s in "caandy", and the first three "a"'s in "caaaaaaandy". Notice that when matching "caaaaaaandy", the match is "aaa", even though the original string had more "a"s in it.</p></td></tr>',type: 'html'
value: '<tr><td><p><code><em>x</em>*?</code><br><code><em>x</em>+?</code><br><code><em>x</em>??</code><br><code><em>x</em>{n}?</code><br><code><em>x</em>{n,}?</code><br><code><em>x</em>{n,m}?</code></p></td><td><p>By default quantifiers like <code>*</code> and <code>+</code> are "greedy", meaning that they try to match as much of the string as possible. The <code>?</code> character after the quantifier makes the quantifier "non-greedy": meaning that it will stop as soon as it finds a match. For example, given a string like "some &#x3C;foo> &#x3C;bar> new &#x3C;/bar> &#x3C;/foo> thing":</p><ul><li><code>/&#x3C;.*>/</code> will match "&#x3C;foo> &#x3C;bar> new &#x3C;/bar> &#x3C;/foo>"</li><li><code>/&#x3C;.*?>/</code> will match "&#x3C;foo>"</li></ul></td></tr>'
```
##### pre.brush:.js (407:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'UnicodePropertyValue'
```
##### dl (419:1) => paragraph
```
type: 'list'
ordered: 'false'
start: 

spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'link'
      title: 

      url: 'https://unicode.org/reports/tr18/#General_Category_Property'
      children: 
        type: 'text'
        value: 'General_Category'
      type: 'text'
      value: ' ('
      type: 'inlineCode'
      value: 'gc'
      type: 'text'
      value: ')'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'link'
      title: 

      url: 'https://unicode.org/reports/tr24/#Script'
      children: 
        type: 'text'
        value: 'Script'
      type: 'text'
      value: ' ('
      type: 'inlineCode'
      value: 'sc'
      type: 'text'
      value: ')'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'link'
      title: 

      url: 'https://unicode.org/reports/tr24/#Script_Extensions'
      children: 
        type: 'text'
        value: 'Script_Extensions'
      type: 'text'
      value: ' ('
      type: 'inlineCode'
      value: 'scx'
      type: 'text'
      value: ')',type: 'paragraph'
summary: 'This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide.'
children: 
  type: 'text'
  value: 'See also '
  type: 'link'
  title: 

  url: 'https://www.unicode.org/Public/UCD/latest/ucd/PropertyValueAliases.txt'
  children: 
    type: 'text'
    value: 'PropertyValueAliases.txt'
```
### Missing conversion rules
- th[scope="col"] (21:4)
- th[scope="col"] (22:4)
- th[scope="col"] (153:4)
- th[scope="col"] (154:4)
- th[scope="col"] (209:4)
- th[scope="col"] (210:4)
- th[scope="col"] (248:4)
- th[scope="col"] (249:4)
- th[scope="col"] (340:4)
- th[scope="col"] (341:4)
### [/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Groups_and_Ranges](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Groups_and_Ranges)
#### Invalid AST transformations
##### tr (25:3) => tableRow
```
type: 'html'
value: '<th scope="col">Characters</th>',type: 'html'
value: '<th scope="col">Meaning</th>'
```
##### code (32:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### td (33:4) => tableCell
```
type: 'paragraph'
summary: 'Groups and ranges indicate groups and ranges of expression characters.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Matches either "x" or "y". For example, '
  type: 'inlineCode'
  value: '/green|red/'
  type: 'text'
  value: ' matches "green" in "green apple" and "red" in "red apple".'
```
##### tr (31:3) => tableRow
```
type: 'html'
value: '<td><p>Matches either "x" or "y". For example, <code>/green|red/</code> matches "green" in "green apple" and "red" in "red apple".</p></td>'
```
##### code (38:8) => text
```
type: 'element'
tagName: 'br'
properties: 

children: 

```
##### td (40:4) => tableCell
```
type: 'paragraph'
summary: 'Groups and ranges indicate groups and ranges of expression characters.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'A character class. Matches any one of the enclosed characters. You can specify a range of characters by using a hyphen, but if the hyphen appears as the first or last character enclosed in the square brackets it is taken as a literal hyphen to be included in the character class as a normal character.',type: 'paragraph'
summary: 'Groups and ranges indicate groups and ranges of expression characters.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'For example, '
  type: 'inlineCode'
  value: '[abcd]'
  type: 'text'
  value: ' is the same as '
  type: 'inlineCode'
  value: '[a-d]'
  type: 'text'
  value: '. They match the "b" in "brisket", and the "c" in "chop".',type: 'paragraph'
summary: 'Groups and ranges indicate groups and ranges of expression characters.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'For example, '
  type: 'inlineCode'
  value: '[abcd-]'
  type: 'text'
  value: ' and '
  type: 'inlineCode'
  value: '[-abcd]'
  type: 'text'
  value: ' match the "b" in "brisket", the "c" in "chop", and the "-" (hyphen) in "non-profit".',type: 'paragraph'
summary: 'Groups and ranges indicate groups and ranges of expression characters.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'For example, '
  type: 'inlineCode'
  value: '[\w-]'
  type: 'text'
  value: ' is the same as '
  type: 'inlineCode'
  value: '[A-Za-z0-9_-]'
  type: 'text'
  value: '. They both match the "b" in "brisket", the "c" in "chop", and the "n" in "non-profit".'
```
##### tr (37:3) => tableRow
```
type: 'html'
value: '<td><p>A character class. Matches any one of the enclosed characters. You can specify a range of characters by using a hyphen, but if the hyphen appears as the first or last character enclosed in the square brackets it is taken as a literal hyphen to be included in the character class as a normal character.</p><p>For example, <code>[abcd]</code> is the same as <code>[a-d]</code>. They match the "b" in "brisket", and the "c" in "chop".</p><p>For example, <code>[abcd-]</code> and <code>[-abcd]</code> match the "b" in "brisket", the "c" in "chop", and the "-" (hyphen) in "non-profit".</p><p>For example, <code>[\w-]</code> is the same as <code>[A-Za-z0-9_-]</code>. They both match the "b" in "brisket", the "c" in "chop", and the "n" in "non-profit".</p></td>'
```
##### code (52:8) => text
```
type: 'element'
tagName: 'br'
properties: 

children: 

```
##### td (51:4) => tableCell
```
type: 'paragraph'
summary: 'Groups and ranges indicate groups and ranges of expression characters.'
shouldWrap: 'true'
children: 
  type: 'html'
  value: '<code>[^xyz]<br>[^a-c]</code>'
```
##### td (55:4) => tableCell
```
type: 'paragraph'
summary: 'Groups and ranges indicate groups and ranges of expression characters.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'A negated or complemented character class. That is, it matches anything that is not enclosed in the brackets. You can specify a range of characters by using a hyphen, but if the hyphen appears as the first or last character enclosed in the square brackets it is taken as a literal hyphen to be included in the character class as a normal character. For example, '
  type: 'inlineCode'
  value: '[^abc]'
  type: 'text'
  value: ' is the same as '
  type: 'inlineCode'
  value: '[^a-c]'
  type: 'text'
  value: '. They initially match "o" in "bacon" and "h" in "chop".',type: 'blockquote'
children: 
  type: 'paragraph'
  children: 
    type: 'strong'
    children: 
      type: 'text'
      value: 'Note:'
    type: 'text'
    value: ' The ^ character may also indicate the '
    type: 'link'
    title: 

    url: '/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Assertions'
    children: 
      type: 'text'
      value: 'beginning of input'
    type: 'text'
    value: '.'
```
##### tr (50:3) => tableRow
```
type: 'html'
value: '<td><p><code>[^xyz]<br>[^a-c]</code></p></td>',type: 'html'
value: '<td><p>A negated or complemented character class. That is, it matches anything that is not enclosed in the brackets. You can specify a range of characters by using a hyphen, but if the hyphen appears as the first or last character enclosed in the square brackets it is taken as a literal hyphen to be included in the character class as a normal character. For example, <code>[^abc]</code> is the same as <code>[^a-c]</code>. They initially match "o" in "bacon" and "h" in "chop".</p><div class="notecard note"><p><strong>Note:</strong> The ^ character may also indicate the <a href="/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Assertions">beginning of input</a>.</p></div></td>'
```
##### code (64:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### code (66:50) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### td (65:4) => tableCell
```
type: 'paragraph'
summary: 'Groups and ranges indicate groups and ranges of expression characters.'
shouldWrap: 'true'
children: 
  type: 'strong'
  children: 
    type: 'text'
    value: 'Capturing group:'
  type: 'text'
  value: ' '
  type: 'text'
  value: 'Matches '
  type: 'html'
  value: '<code><em>x</em></code>'
  type: 'text'
  value: ' and remembers the match. For example, '
  type: 'inlineCode'
  value: '/(foo)/'
  type: 'text'
  value: ' matches and remembers "foo" in "foo bar". ',type: 'paragraph'
summary: 'Groups and ranges indicate groups and ranges of expression characters.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'A regular expression may have multiple capturing groups. In results, matches to capturing groups typically in an array whose members are in the same order as the left parentheses in the capturing group. This is usually just the order of the capturing groups themselves. This becomes important when capturing groups are nested. Matches are accessed using the index of the result's elements ('
  type: 'inlineCode'
  value: '[1], ..., [n]'
  type: 'text'
  value: ') or from the predefined '
  type: 'inlineCode'
  value: 'RegExp'
  type: 'text'
  value: ' object's properties ('
  type: 'inlineCode'
  value: '$1, ..., $9'
  type: 'text'
  value: ').',type: 'paragraph'
summary: 'Groups and ranges indicate groups and ranges of expression characters.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Capturing groups have a performance penalty. If you don't need the matched substring to be recalled, prefer non-capturing parentheses (see below).',type: 'paragraph'
summary: 'Groups and ranges indicate groups and ranges of expression characters.'
shouldWrap: 'true'
children: 
  type: 'link'
  title: 

  url: '/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/match'
  children: 
    type: 'inlineCode'
    value: 'String.match()'
  type: 'text'
  value: ' won't return groups if the '
  type: 'inlineCode'
  value: '/.../g'
  type: 'text'
  value: ' flag is set. However, you can still use '
  type: 'link'
  title: 

  url: '/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/matchAll'
  children: 
    type: 'inlineCode'
    value: 'String.matchAll()'
  type: 'text'
  value: ' to get all matches.'
```
##### tr (63:3) => tableRow
```
type: 'html'
value: '<td><p><strong>Capturing group: </strong>Matches <code><em>x</em></code> and remembers the match. For example, <code>/(foo)/</code> matches and remembers "foo" in "foo bar". </p><p>A regular expression may have multiple capturing groups. In results, matches to capturing groups typically in an array whose members are in the same order as the left parentheses in the capturing group. This is usually just the order of the capturing groups themselves. This becomes important when capturing groups are nested. Matches are accessed using the index of the result's elements (<code>[1], ..., [n]</code>) or from the predefined <code>RegExp</code> object's properties (<code>$1, ..., $9</code>).</p><p>Capturing groups have a performance penalty. If you don't need the matched substring to be recalled, prefer non-capturing parentheses (see below).</p><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/match">String.match()</a></code> won't return groups if the <code>/.../g</code> flag is set. However, you can still use <code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/matchAll">String.matchAll()</a></code> to get all matches.</p></td>'
```
##### code (76:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'n'
```
##### td (77:4) => tableCell
```
type: 'paragraph'
summary: 'Groups and ranges indicate groups and ranges of expression characters.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Where "n" is a positive integer. A back reference to the last substring matching the n parenthetical in the regular expression (counting left parentheses). For example, '
  type: 'inlineCode'
  value: '/apple(,)\sorange\1/'
  type: 'text'
  value: ' matches "apple, orange," in "apple, orange, cherry, peach".'
```
##### tr (75:3) => tableRow
```
type: 'html'
value: '<td><p>Where "n" is a positive integer. A back reference to the last substring matching the n parenthetical in the regular expression (counting left parentheses). For example, <code>/apple(,)\sorange\1/</code> matches "apple, orange," in "apple, orange, cherry, peach".</p></td>'
```
##### td (83:4) => tableCell
```
type: 'paragraph'
summary: 'Groups and ranges indicate groups and ranges of expression characters.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'A back reference to the last substring matching the '
  type: 'strong'
  children: 
    type: 'text'
    value: 'Named capture group'
  type: 'text'
  value: ' specified by '
  type: 'inlineCode'
  value: '<Name>'
  type: 'text'
  value: '.',type: 'paragraph'
summary: 'Groups and ranges indicate groups and ranges of expression characters.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'For example, '
  type: 'inlineCode'
  value: '/(?<title>\w+), yes \k<title>/'
  type: 'text'
  value: ' matches "Sir, yes Sir" in "Do you copy? Sir, yes Sir!".',type: 'blockquote'
children: 
  type: 'paragraph'
  children: 
    type: 'strong'
    children: 
      type: 'text'
      value: 'Note:'
    type: 'text'
    value: ' '
    type: 'inlineCode'
    value: '\k'
    type: 'text'
    value: ' is used literally here to indicate the beginning of a back reference to a Named capture group.'
```
##### tr (81:3) => tableRow
```
type: 'html'
value: '<td><p>A back reference to the last substring matching the <strong>Named capture group</strong> specified by <code>&#x3C;Name></code>.</p><p>For example, <code>/(?&#x3C;title>\w+), yes \k&#x3C;title>/</code> matches "Sir, yes Sir" in "Do you copy? Sir, yes Sir!".</p><div class="notecard note"><p><strong>Note:</strong> <code>\k</code> is used literally here to indicate the beginning of a back reference to a Named capture group.</p></div></td>'
```
##### td (95:4) => tableCell
```
type: 'paragraph'
summary: 'Groups and ranges indicate groups and ranges of expression characters.'
shouldWrap: 'true'
children: 
  type: 'strong'
  children: 
    type: 'text'
    value: 'Named capturing group:'
  type: 'text'
  value: ' '
  type: 'text'
  value: 'Matches "x" and stores it on the groups property of the returned matches under the name specified by '
  type: 'inlineCode'
  value: '<Name>'
  type: 'text'
  value: '. The angle brackets ('
  type: 'inlineCode'
  value: '<'
  type: 'text'
  value: ' and '
  type: 'inlineCode'
  value: '>'
  type: 'text'
  value: ') are required for group name.',type: 'paragraph'
summary: 'Groups and ranges indicate groups and ranges of expression characters.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'For example, to extract the United States area code from a phone number, we could use '
  type: 'inlineCode'
  value: '/\((?<area>\d\d\d)\)/'
  type: 'text'
  value: '. The resulting number would appear under '
  type: 'inlineCode'
  value: 'matches.groups.area'
  type: 'text'
  value: '.'
```
##### tr (93:3) => tableRow
```
type: 'html'
value: '<td><p><strong>Named capturing group: </strong>Matches "x" and stores it on the groups property of the returned matches under the name specified by <code>&#x3C;Name></code>. The angle brackets (<code>&#x3C;</code> and <code>></code>) are required for group name.</p><p>For example, to extract the United States area code from a phone number, we could use <code>/\((?&#x3C;area>\d\d\d)\)/</code>. The resulting number would appear under <code>matches.groups.area</code>.</p></td>'
```
##### code (102:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### table.standard-table (23:1) => table
```
type: 'html'
value: '<tr><th scope="col">Characters</th><th scope="col">Meaning</th></tr>',type: 'html'
value: '<tr><td><code><em>x</em>|<em>y</em></code></td><td><p>Matches either "x" or "y". For example, <code>/green|red/</code> matches "green" in "green apple" and "red" in "red apple".</p></td></tr>',type: 'html'
value: '<tr><td><code>[xyz]<br>[a-c]</code></td><td><p>A character class. Matches any one of the enclosed characters. You can specify a range of characters by using a hyphen, but if the hyphen appears as the first or last character enclosed in the square brackets it is taken as a literal hyphen to be included in the character class as a normal character.</p><p>For example, <code>[abcd]</code> is the same as <code>[a-d]</code>. They match the "b" in "brisket", and the "c" in "chop".</p><p>For example, <code>[abcd-]</code> and <code>[-abcd]</code> match the "b" in "brisket", the "c" in "chop", and the "-" (hyphen) in "non-profit".</p><p>For example, <code>[\w-]</code> is the same as <code>[A-Za-z0-9_-]</code>. They both match the "b" in "brisket", the "c" in "chop", and the "n" in "non-profit".</p></td></tr>',type: 'html'
value: '<tr><td><p><code>[^xyz]<br>[^a-c]</code></p></td><td><p>A negated or complemented character class. That is, it matches anything that is not enclosed in the brackets. You can specify a range of characters by using a hyphen, but if the hyphen appears as the first or last character enclosed in the square brackets it is taken as a literal hyphen to be included in the character class as a normal character. For example, <code>[^abc]</code> is the same as <code>[^a-c]</code>. They initially match "o" in "bacon" and "h" in "chop".</p><div class="notecard note"><p><strong>Note:</strong> The ^ character may also indicate the <a href="/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Assertions">beginning of input</a>.</p></div></td></tr>',type: 'html'
value: '<tr><td><code>(<em>x</em>)</code></td><td><p><strong>Capturing group: </strong>Matches <code><em>x</em></code> and remembers the match. For example, <code>/(foo)/</code> matches and remembers "foo" in "foo bar". </p><p>A regular expression may have multiple capturing groups. In results, matches to capturing groups typically in an array whose members are in the same order as the left parentheses in the capturing group. This is usually just the order of the capturing groups themselves. This becomes important when capturing groups are nested. Matches are accessed using the index of the result's elements (<code>[1], ..., [n]</code>) or from the predefined <code>RegExp</code> object's properties (<code>$1, ..., $9</code>).</p><p>Capturing groups have a performance penalty. If you don't need the matched substring to be recalled, prefer non-capturing parentheses (see below).</p><p><code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/match">String.match()</a></code> won't return groups if the <code>/.../g</code> flag is set. However, you can still use <code><a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/matchAll">String.matchAll()</a></code> to get all matches.</p></td></tr>',type: 'html'
value: '<tr><td><code>\<em>n</em></code></td><td><p>Where "n" is a positive integer. A back reference to the last substring matching the n parenthetical in the regular expression (counting left parentheses). For example, <code>/apple(,)\sorange\1/</code> matches "apple, orange," in "apple, orange, cherry, peach".</p></td></tr>',type: 'html'
value: '<tr><td><code>\k&#x3C;Name></code></td><td><p>A back reference to the last substring matching the <strong>Named capture group</strong> specified by <code>&#x3C;Name></code>.</p><p>For example, <code>/(?&#x3C;title>\w+), yes \k&#x3C;title>/</code> matches "Sir, yes Sir" in "Do you copy? Sir, yes Sir!".</p><div class="notecard note"><p><strong>Note:</strong> <code>\k</code> is used literally here to indicate the beginning of a back reference to a Named capture group.</p></div></td></tr>',type: 'html'
value: '<tr><td><code>(?&#x3C;Name>x)</code></td><td><p><strong>Named capturing group: </strong>Matches "x" and stores it on the groups property of the returned matches under the name specified by <code>&#x3C;Name></code>. The angle brackets (<code>&#x3C;</code> and <code>></code>) are required for group name.</p><p>For example, to extract the United States area code from a phone number, we could use <code>/\((?&#x3C;area>\d\d\d)\)/</code>. The resulting number would appear under <code>matches.groups.area</code>.</p></td></tr>'
```
### Missing conversion rules
- th[scope="col"] (26:4)
- th[scope="col"] (27:4)
### [/en-US/docs/Web/JavaScript/Guide/Regular_Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions)
#### Invalid AST transformations
##### tr (77:3) => tableRow
```
type: 'html'
value: '<th scope="col">Characters / constructs</th>',type: 'html'
value: '<th scope="col">Corresponding article</th>'
```
##### td (85:4) => tableCell
```
type: 'paragraph'
summary: 'Regular expressions are patterns used to match character combinations in strings. In JavaScript, regular expressions are also objects. These patterns are used with the {{anN4cmVmKCJSZWdFeHAuZXhlYyIsICJleGVjKCkiKQ==}} and {{anN4cmVmKCJSZWdFeHAudGVzdCIsICJ0ZXN0KCkiKQ==}} methods of {{anN4cmVmKCJSZWdFeHAiKQ==}}, and with the {{anN4cmVmKCJTdHJpbmcubWF0Y2giLCAibWF0Y2goKSIp}}, {{anN4cmVmKCJTdHJpbmcubWF0Y2hBbGwiLCAibWF0Y2hBbGwoKSIp}}, {{anN4cmVmKCJTdHJpbmcucmVwbGFjZSIsICJyZXBsYWNlKCkiKQ==}}, {{anN4cmVmKCJTdHJpbmcucmVwbGFjZUFsbCIsICJyZXBsYWNlQWxsKCkiKQ==}}, {{anN4cmVmKCJTdHJpbmcuc2VhcmNoIiwgInNlYXJjaCgpIik=}}, and {{anN4cmVmKCJTdHJpbmcuc3BsaXQiLCAic3BsaXQoKSIp}} methods of {{anN4cmVmKCJTdHJpbmciKQ==}}. This chapter describes JavaScript regular expressions.'
shouldWrap: 'true'
children: 
  type: 'link'
  title: 

  url: '/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Character_Classes'
  children: 
    type: 'text'
    value: 'Character classes'
```
##### tr (83:3) => tableRow
```
type: 'html'
value: '<td><p><a href="/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Character_Classes">Character classes</a></p></td>'
```
##### td (91:4) => tableCell
```
type: 'paragraph'
summary: 'Regular expressions are patterns used to match character combinations in strings. In JavaScript, regular expressions are also objects. These patterns are used with the {{anN4cmVmKCJSZWdFeHAuZXhlYyIsICJleGVjKCkiKQ==}} and {{anN4cmVmKCJSZWdFeHAudGVzdCIsICJ0ZXN0KCkiKQ==}} methods of {{anN4cmVmKCJSZWdFeHAiKQ==}}, and with the {{anN4cmVmKCJTdHJpbmcubWF0Y2giLCAibWF0Y2goKSIp}}, {{anN4cmVmKCJTdHJpbmcubWF0Y2hBbGwiLCAibWF0Y2hBbGwoKSIp}}, {{anN4cmVmKCJTdHJpbmcucmVwbGFjZSIsICJyZXBsYWNlKCkiKQ==}}, {{anN4cmVmKCJTdHJpbmcucmVwbGFjZUFsbCIsICJyZXBsYWNlQWxsKCkiKQ==}}, {{anN4cmVmKCJTdHJpbmcuc2VhcmNoIiwgInNlYXJjaCgpIik=}}, and {{anN4cmVmKCJTdHJpbmcuc3BsaXQiLCAic3BsaXQoKSIp}} methods of {{anN4cmVmKCJTdHJpbmciKQ==}}. This chapter describes JavaScript regular expressions.'
shouldWrap: 'true'
children: 
  type: 'link'
  title: 

  url: '/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Assertions'
  children: 
    type: 'text'
    value: 'Assertions'
```
##### tr (89:3) => tableRow
```
type: 'html'
value: '<td><p><a href="/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Assertions">Assertions</a></p></td>'
```
##### code (96:136) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'Number'
```
##### td (97:4) => tableCell
```
type: 'paragraph'
summary: 'Regular expressions are patterns used to match character combinations in strings. In JavaScript, regular expressions are also objects. These patterns are used with the {{anN4cmVmKCJSZWdFeHAuZXhlYyIsICJleGVjKCkiKQ==}} and {{anN4cmVmKCJSZWdFeHAudGVzdCIsICJ0ZXN0KCkiKQ==}} methods of {{anN4cmVmKCJSZWdFeHAiKQ==}}, and with the {{anN4cmVmKCJTdHJpbmcubWF0Y2giLCAibWF0Y2goKSIp}}, {{anN4cmVmKCJTdHJpbmcubWF0Y2hBbGwiLCAibWF0Y2hBbGwoKSIp}}, {{anN4cmVmKCJTdHJpbmcucmVwbGFjZSIsICJyZXBsYWNlKCkiKQ==}}, {{anN4cmVmKCJTdHJpbmcucmVwbGFjZUFsbCIsICJyZXBsYWNlQWxsKCkiKQ==}}, {{anN4cmVmKCJTdHJpbmcuc2VhcmNoIiwgInNlYXJjaCgpIik=}}, and {{anN4cmVmKCJTdHJpbmcuc3BsaXQiLCAic3BsaXQoKSIp}} methods of {{anN4cmVmKCJTdHJpbmciKQ==}}. This chapter describes JavaScript regular expressions.'
shouldWrap: 'true'
children: 
  type: 'link'
  title: 

  url: '/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Groups_and_Ranges'
  children: 
    type: 'text'
    value: 'Groups and ranges'
```
##### tr (95:3) => tableRow
```
type: 'html'
value: '<td><p><a href="/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Groups_and_Ranges">Groups and ranges</a></p></td>'
```
##### code (102:56) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'n'
```
##### code (102:84) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'n'
```
##### code (102:113) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'n'
```
##### td (103:4) => tableCell
```
type: 'paragraph'
summary: 'Regular expressions are patterns used to match character combinations in strings. In JavaScript, regular expressions are also objects. These patterns are used with the {{anN4cmVmKCJSZWdFeHAuZXhlYyIsICJleGVjKCkiKQ==}} and {{anN4cmVmKCJSZWdFeHAudGVzdCIsICJ0ZXN0KCkiKQ==}} methods of {{anN4cmVmKCJSZWdFeHAiKQ==}}, and with the {{anN4cmVmKCJTdHJpbmcubWF0Y2giLCAibWF0Y2goKSIp}}, {{anN4cmVmKCJTdHJpbmcubWF0Y2hBbGwiLCAibWF0Y2hBbGwoKSIp}}, {{anN4cmVmKCJTdHJpbmcucmVwbGFjZSIsICJyZXBsYWNlKCkiKQ==}}, {{anN4cmVmKCJTdHJpbmcucmVwbGFjZUFsbCIsICJyZXBsYWNlQWxsKCkiKQ==}}, {{anN4cmVmKCJTdHJpbmcuc2VhcmNoIiwgInNlYXJjaCgpIik=}}, and {{anN4cmVmKCJTdHJpbmcuc3BsaXQiLCAic3BsaXQoKSIp}} methods of {{anN4cmVmKCJTdHJpbmciKQ==}}. This chapter describes JavaScript regular expressions.'
shouldWrap: 'true'
children: 
  type: 'link'
  title: 

  url: '/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Quantifiers'
  children: 
    type: 'text'
    value: 'Quantifiers'
```
##### tr (101:3) => tableRow
```
type: 'html'
value: '<td><p><a href="/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Quantifiers">Quantifiers</a></p></td>'
```
##### code (108:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'UnicodeProperty'
```
##### code (108:51) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'UnicodeProperty'
```
##### table.standard-table (74:1) => table
```
type: 'text'
value: 'Special characters in regular expressions.',type: 'html'
value: '<tr><th scope="col">Characters / constructs</th><th scope="col">Corresponding article</th></tr>',type: 'html'
value: '<tr><td><code>\</code>, <code>.</code>, <code>\cX</code>, <code>\d</code>, <code>\D</code>, <code>\f</code>, <code>\n</code>, <code>\r</code>, <code>\s</code>, <code>\S</code>, <code>\t</code>, <code>\v</code>, <code>\w</code>, <code>\W</code>, <code>\0</code>, <code>\xhh</code>, <code>\uhhhh</code>, <code>\uhhhhh</code>, <code>[\b]</code></td><td><p><a href="/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Character_Classes">Character classes</a></p></td></tr>',type: 'html'
value: '<tr><td><code>^</code>, <code>$</code>, <code>x(?=y)</code>, <code>x(?!y)</code>, <code>(?&#x3C;=y)x</code>, <code>(?&#x3C;!y)x</code>, <code>\b</code>, <code>\B</code></td><td><p><a href="/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Assertions">Assertions</a></p></td></tr>',type: 'html'
value: '<tr><td><code>(x)</code>, <code>(?:x)</code>, <code>(?&#x3C;Name>x)</code>, <code>x|y</code>, <code>[xyz]</code>, <code>[^xyz]</code>, <code>\<em>Number</em></code></td><td><p><a href="/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Groups_and_Ranges">Groups and ranges</a></p></td></tr>',type: 'html'
value: '<tr><td><code>*</code>, <code>+</code>, <code>?</code>, <code>x{<em>n</em>}</code>, <code>x{<em>n</em>,}</code>, <code>x{<em>n</em>,<em>m</em>}</code></td><td><p><a href="/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Quantifiers">Quantifiers</a></p></td></tr>'
```
##### tr (150:3) => tableRow
```
type: 'html'
value: '<th scope="col">Method</th>',type: 'html'
value: '<th scope="col">Description</th>'
```
##### table.standard-table (147:1) => table
```
type: 'text'
value: 'Methods that use regular expressions',type: 'html'
value: '<tr><th scope="col">Method</th><th scope="col">Description</th></tr>'
```
##### tr (220:3) => tableRow
```
type: 'html'
value: '<th scope="col">Object</th>',type: 'html'
value: '<th scope="col">Property or index</th>',type: 'html'
value: '<th scope="col">Description</th>',type: 'html'
value: '<th scope="col">In this example</th>'
```
##### tr (228:3) => tableRow
```
type: 'html'
value: '<td rowspan="4"><code>myArray</code></td>'
```
##### tr (249:3) => tableRow
```
type: 'html'
value: '<td rowspan="2"><code>myRe</code></td>'
```
##### table.standard-table (217:1) => table
```
type: 'text'
value: 'Results of regular expression execution.',type: 'html'
value: '<tr><th scope="col">Object</th><th scope="col">Property or index</th><th scope="col">Description</th><th scope="col">In this example</th></tr>',type: 'html'
value: '<tr><td rowspan="4"><code>myArray</code></td><td></td><td>The matched string and all remembered substrings.</td><td><code>['dbbd', 'bb', index: 1, input: 'cdbbdbsbz']</code></td></tr>',type: 'html'
value: '<tr><td rowspan="2"><code>myRe</code></td><td><code>lastIndex</code></td><td>The index at which to start the next match. (This property is set only if the regular expression uses the g option, described in <a href="#advanced_searching_with_flags">Advanced Searching With Flags</a>.)</td><td><code>5</code></td></tr>'
```
##### tr (289:3) => tableRow
```
type: 'html'
value: '<th scope="col">Flag</th>',type: 'html'
value: '<th scope="col">Description</th>',type: 'html'
value: '<th scope="col">Corresponding property</th>'
```
##### table.standard-table (286:1) => table
```
type: 'text'
value: 'Regular expression flags',type: 'html'
value: '<tr><th scope="col">Flag</th><th scope="col">Description</th><th scope="col">Corresponding property</th></tr>'
```
### Missing conversion rules
- th[scope="col"] (78:4)
- th[scope="col"] (79:4)
- th[scope="col"] (151:4)
- th[scope="col"] (152:4)
- th[scope="col"] (221:4)
- th[scope="col"] (222:4)
- th[scope="col"] (223:4)
- th[scope="col"] (224:4)
- td[rowSpan="4"] (229:4)
- td[rowSpan="2"] (250:4)
- th[scope="col"] (290:4)
- th[scope="col"] (291:4)
- th[scope="col"] (292:4)
- kbd (405:65)
### [/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Quantifiers](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Quantifiers)
#### Invalid AST transformations
##### tr (28:3) => tableRow
```
type: 'html'
value: '<th scope="col">Characters</th>',type: 'html'
value: '<th scope="col">Meaning</th>'
```
##### code (35:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### td (36:4) => tableCell
```
type: 'paragraph'
summary: 'Quantifiers indicate numbers of characters or expressions to match.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Matches the preceding item "x" 0 or more times. For example, '
  type: 'inlineCode'
  value: '/bo*/'
  type: 'text'
  value: ' matches "boooo" in "A ghost booooed" and "b" in "A bird warbled", but nothing in "A goat grunted".'
```
##### tr (34:3) => tableRow
```
type: 'html'
value: '<td><p>Matches the preceding item "x" 0 or more times. For example, <code>/bo*/</code> matches "boooo" in "A ghost booooed" and "b" in "A bird warbled", but nothing in "A goat grunted".</p></td>'
```
##### code (41:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### td (42:4) => tableCell
```
type: 'paragraph'
summary: 'Quantifiers indicate numbers of characters or expressions to match.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Matches the preceding item "x" 1 or more times. Equivalent to '
  type: 'inlineCode'
  value: '{1,}'
  type: 'text'
  value: '. For example, '
  type: 'inlineCode'
  value: '/a+/'
  type: 'text'
  value: ' matches the "a" in "candy" and all the "a"'s in "caaaaaaandy".'
```
##### tr (40:3) => tableRow
```
type: 'html'
value: '<td><p>Matches the preceding item "x" 1 or more times. Equivalent to <code>{1,}</code>. For example, <code>/a+/</code> matches the "a" in "candy" and all the "a"'s in "caaaaaaandy".</p></td>'
```
##### code (47:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### td (48:4) => tableCell
```
type: 'paragraph'
summary: 'Quantifiers indicate numbers of characters or expressions to match.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Matches the preceding item "x" 0 or 1 times. For example, '
  type: 'inlineCode'
  value: '/e?le?/'
  type: 'text'
  value: ' matches the "el" in "angel" and the "le" in "angle."',type: 'paragraph'
summary: 'Quantifiers indicate numbers of characters or expressions to match.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'If used immediately after any of the quantifiers '
  type: 'inlineCode'
  value: '*'
  type: 'text'
  value: ', '
  type: 'inlineCode'
  value: '+'
  type: 'text'
  value: ', '
  type: 'inlineCode'
  value: '?'
  type: 'text'
  value: ', or '
  type: 'inlineCode'
  value: '{}'
  type: 'text'
  value: ', makes the quantifier non-greedy (matching the minimum number of times), as opposed to the default, which is greedy (matching the maximum number of times).'
```
##### tr (46:3) => tableRow
```
type: 'html'
value: '<td><p>Matches the preceding item "x" 0 or 1 times. For example, <code>/e?le?/</code> matches the "el" in "angel" and the "le" in "angle."</p><p>If used immediately after any of the quantifiers <code>*</code>, <code>+</code>, <code>?</code>, or <code>{}</code>, makes the quantifier non-greedy (matching the minimum number of times), as opposed to the default, which is greedy (matching the maximum number of times).</p></td>'
```
##### code (55:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### td (56:4) => tableCell
```
type: 'paragraph'
summary: 'Quantifiers indicate numbers of characters or expressions to match.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Where "n" is a positive integer, matches exactly "n" occurrences of the preceding item "x". For example, '
  type: 'inlineCode'
  value: '/a{2}/'
  type: 'text'
  value: ' doesn't match the "a" in "candy", but it matches all of the "a"'s in "caandy", and the first two "a"'s in "caaandy".'
```
##### tr (54:3) => tableRow
```
type: 'html'
value: '<td><p>Where "n" is a positive integer, matches exactly "n" occurrences of the preceding item "x". For example, <code>/a{2}/</code> doesn't match the "a" in "candy", but it matches all of the "a"'s in "caandy", and the first two "a"'s in "caaandy".</p></td>'
```
##### code (61:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### td (62:4) => tableCell
```
type: 'paragraph'
summary: 'Quantifiers indicate numbers of characters or expressions to match.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Where "n" is a positive integer, matches at least "n" occurrences of the preceding item "x". For example, '
  type: 'inlineCode'
  value: '/a{2,}/'
  type: 'text'
  value: ' doesn't match the "a" in "candy", but matches all of the a's in "caandy" and in "caaaaaaandy".'
```
##### tr (60:3) => tableRow
```
type: 'html'
value: '<td><p>Where "n" is a positive integer, matches at least "n" occurrences of the preceding item "x". For example, <code>/a{2,}/</code> doesn't match the "a" in "candy", but matches all of the a's in "caandy" and in "caaaaaaandy".</p></td>'
```
##### code (67:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### code (69:77) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'm'
```
##### td (68:4) => tableCell
```
type: 'paragraph'
summary: 'Quantifiers indicate numbers of characters or expressions to match.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Where "n" is 0 or a positive integer, "m" is a positive integer, and '
  type: 'html'
  value: '<code><em>m</em> > <em>n</em></code>'
  type: 'text'
  value: ', matches at least "n" and at most "m" occurrences of the preceding item "x". For example, '
  type: 'inlineCode'
  value: '/a{1,3}/'
  type: 'text'
  value: ' matches nothing in "cndy", the "a" in "candy", the two "a"'s in "caandy", and the first three "a"'s in "caaaaaaandy". Notice that when matching "caaaaaaandy", the match is "aaa", even though the original string had more "a"s in it.'
```
##### tr (66:3) => tableRow
```
type: 'html'
value: '<td><p>Where "n" is 0 or a positive integer, "m" is a positive integer, and <code><em>m</em> > <em>n</em></code>, matches at least "n" and at most "m" occurrences of the preceding item "x". For example, <code>/a{1,3}/</code> matches nothing in "cndy", the "a" in "candy", the two "a"'s in "caandy", and the first three "a"'s in "caaaaaaandy". Notice that when matching "caaaaaaandy", the match is "aaa", even though the original string had more "a"s in it.</p></td>'
```
##### code (74:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### code (75:6) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### code (76:6) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### code (77:6) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### code (78:6) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### code (79:6) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### td (73:4) => tableCell
```
type: 'paragraph'
summary: 'Quantifiers indicate numbers of characters or expressions to match.'
shouldWrap: 'true'
children: 
  type: 'html'
  value: '<code><em>x</em>*?</code>'
  type: 'break'
  type: 'html'
  value: '<code><em>x</em>+?</code>'
  type: 'break'
  type: 'html'
  value: '<code><em>x</em>??</code>'
  type: 'break'
  type: 'html'
  value: '<code><em>x</em>{n}?</code>'
  type: 'break'
  type: 'html'
  value: '<code><em>x</em>{n,}?</code>'
  type: 'break'
  type: 'html'
  value: '<code><em>x</em>{n,m}?</code>'
```
##### td (81:4) => tableCell
```
type: 'paragraph'
summary: 'Quantifiers indicate numbers of characters or expressions to match.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'By default quantifiers like '
  type: 'inlineCode'
  value: '*'
  type: 'text'
  value: ' and '
  type: 'inlineCode'
  value: '+'
  type: 'text'
  value: ' are "greedy", meaning that they try to match as much of the string as possible. The '
  type: 'inlineCode'
  value: '?'
  type: 'text'
  value: ' character after the quantifier makes the quantifier "non-greedy": meaning that it will stop as soon as it finds a match. For example, given a string like "some <foo> <bar> new </bar> </foo> thing":',type: 'list'
ordered: 'false'
start: 

spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: '/<.*>/'
      type: 'text'
      value: ' will match "<foo> <bar> new </bar> </foo>"'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: '/<.*?>/'
      type: 'text'
      value: ' will match "<foo>"'
```
##### tr (72:3) => tableRow
```
type: 'html'
value: '<td><p><code><em>x</em>*?</code><br><code><em>x</em>+?</code><br><code><em>x</em>??</code><br><code><em>x</em>{n}?</code><br><code><em>x</em>{n,}?</code><br><code><em>x</em>{n,m}?</code></p></td>',type: 'html'
value: '<td><p>By default quantifiers like <code>*</code> and <code>+</code> are "greedy", meaning that they try to match as much of the string as possible. The <code>?</code> character after the quantifier makes the quantifier "non-greedy": meaning that it will stop as soon as it finds a match. For example, given a string like "some &#x3C;foo> &#x3C;bar> new &#x3C;/bar> &#x3C;/foo> thing":</p><ul><li><code>/&#x3C;.*>/</code> will match "&#x3C;foo> &#x3C;bar> new &#x3C;/bar> &#x3C;/foo>"</li><li><code>/&#x3C;.*?>/</code> will match "&#x3C;foo>"</li></ul></td>'
```
##### table.standard-table (26:1) => table
```
type: 'html'
value: '<tr><th scope="col">Characters</th><th scope="col">Meaning</th></tr>',type: 'html'
value: '<tr><td><code><em>x</em>*</code></td><td><p>Matches the preceding item "x" 0 or more times. For example, <code>/bo*/</code> matches "boooo" in "A ghost booooed" and "b" in "A bird warbled", but nothing in "A goat grunted".</p></td></tr>',type: 'html'
value: '<tr><td><code><em>x</em>+</code></td><td><p>Matches the preceding item "x" 1 or more times. Equivalent to <code>{1,}</code>. For example, <code>/a+/</code> matches the "a" in "candy" and all the "a"'s in "caaaaaaandy".</p></td></tr>',type: 'html'
value: '<tr><td><code><em>x</em>?</code></td><td><p>Matches the preceding item "x" 0 or 1 times. For example, <code>/e?le?/</code> matches the "el" in "angel" and the "le" in "angle."</p><p>If used immediately after any of the quantifiers <code>*</code>, <code>+</code>, <code>?</code>, or <code>{}</code>, makes the quantifier non-greedy (matching the minimum number of times), as opposed to the default, which is greedy (matching the maximum number of times).</p></td></tr>',type: 'html'
value: '<tr><td><code><em>x</em>{<em>n</em>}</code></td><td><p>Where "n" is a positive integer, matches exactly "n" occurrences of the preceding item "x". For example, <code>/a{2}/</code> doesn't match the "a" in "candy", but it matches all of the "a"'s in "caandy", and the first two "a"'s in "caaandy".</p></td></tr>',type: 'html'
value: '<tr><td><code><em>x</em>{<em>n</em>,}</code></td><td><p>Where "n" is a positive integer, matches at least "n" occurrences of the preceding item "x". For example, <code>/a{2,}/</code> doesn't match the "a" in "candy", but matches all of the a's in "caandy" and in "caaaaaaandy".</p></td></tr>',type: 'html'
value: '<tr><td><code><em>x</em>{<em>n</em>,<em>m</em>}</code></td><td><p>Where "n" is 0 or a positive integer, "m" is a positive integer, and <code><em>m</em> > <em>n</em></code>, matches at least "n" and at most "m" occurrences of the preceding item "x". For example, <code>/a{1,3}/</code> matches nothing in "cndy", the "a" in "candy", the two "a"'s in "caandy", and the first three "a"'s in "caaaaaaandy". Notice that when matching "caaaaaaandy", the match is "aaa", even though the original string had more "a"s in it.</p></td></tr>',type: 'html'
value: '<tr><td><p><code><em>x</em>*?</code><br><code><em>x</em>+?</code><br><code><em>x</em>??</code><br><code><em>x</em>{n}?</code><br><code><em>x</em>{n,}?</code><br><code><em>x</em>{n,m}?</code></p></td><td><p>By default quantifiers like <code>*</code> and <code>+</code> are "greedy", meaning that they try to match as much of the string as possible. The <code>?</code> character after the quantifier makes the quantifier "non-greedy": meaning that it will stop as soon as it finds a match. For example, given a string like "some &#x3C;foo> &#x3C;bar> new &#x3C;/bar> &#x3C;/foo> thing":</p><ul><li><code>/&#x3C;.*>/</code> will match "&#x3C;foo> &#x3C;bar> new &#x3C;/bar> &#x3C;/foo>"</li><li><code>/&#x3C;.*?>/</code> will match "&#x3C;foo>"</li></ul></td></tr>'
```
### Missing conversion rules
- th[scope="col"] (29:4)
- th[scope="col"] (30:4)
### [/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Unicode_Property_Escapes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Unicode_Property_Escapes)
#### Invalid AST transformations
##### pre.brush:.js (30:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'UnicodePropertyValue'
```
### [/en-US/docs/Web/JavaScript/Guide/Text_formatting](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Text_formatting)
#### Invalid AST transformations
##### tr (89:3) => tableRow
```
type: 'html'
value: '<th scope="col">Method</th>',type: 'html'
value: '<th scope="col">Description</th>'
```
##### td (133:4) => tableCell
```
type: 'paragraph'
summary: 'This chapter introduces how to work with strings and text in JavaScript.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Return the string in all lowercase or all uppercase, respectively.'
```
##### tr (131:3) => tableRow
```
type: 'html'
value: '<td><p>Return the string in all lowercase or all uppercase, respectively.</p></td>'
```
##### table.standard-table (84:1) => table
```
type: 'heading'
depth: '4'
children: 
  type: 'text'
  value: 'Methods of '
  type: 'inlineCode'
  value: 'String',type: 'html'
value: '<tr><th scope="col">Method</th><th scope="col">Description</th></tr>',type: 'html'
value: '<tr><td>{{anN4cmVmKCJTdHJpbmcudG9Mb3dlckNhc2UiLCAidG9Mb3dlckNhc2UiKQ==}}, {{anN4cmVmKCJTdHJpbmcudG9VcHBlckNhc2UiLCAidG9VcHBlckNhc2UiKQ==}}</td><td><p>Return the string in all lowercase or all uppercase, respectively.</p></td></tr>'
```
### Missing conversion rules
- th[scope="col"] (90:4)
- th[scope="col"] (91:4)
### [/en-US/docs/Web/JavaScript/Guide/Using_promises](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Using_promises)
#### Invalid AST transformations
##### p.summary (16:1) => text
```
type: 'element'
tagName: 'span'
properties: 
  className: 
    'seoSummary'
children: 
  type: 'text'
  value: 'A {{anN4cmVmKCJQcm9taXNlIik=}} is an object representing the eventual completion or failure of an asynchronous operation. Since most people are consumers of already-created promises, this guide will explain consumption of returned promises before explaining how to create them.'
```
### [/en-US/docs/Web/JavaScript/Guide/Working_with_Objects](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_Objects)
#### Invalid AST transformations
##### code (157:63) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'i'
```
##### code (157:172) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'i'
```
##### code (157:252) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'i'
```
##### code (423:234) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'propertyName'
```
### [/en-US/docs/Web/JavaScript/Inheritance_and_the_prototype_chain](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Inheritance_and_the_prototype_chain)
#### Invalid AST transformations
##### code (31:39) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'func'
```
##### tr (406:5) => tableRow
```
type: 'html'
value: '<th scope="row">Pro(s)</th>'
```
##### td (412:7) => tableCell
```
type: 'paragraph'
summary: 'JavaScript is a bit confusing for developers experienced in class-based languages (like Java or C++), as it is dynamic and does not provide a class implementation per se (the class keyword is introduced in ES2015, but is syntactical sugar, JavaScript remains prototype-based).'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Both of those are generally not problems in practice.'
```
##### tr (410:7) => tableRow
```
type: 'html'
value: '<th scope="row">Con(s)</th>',type: 'html'
value: '<td><div>1. In order to use this method, the function in question must be initialized. During this initialization, the constructor may store unique information that must be generated per-object. This unique information would only be generated once, potentially leading to problems.</div><div>2. The initialization of the constructor may put unwanted methods onto the object.</div><p>Both of those are generally not problems in practice.</p></td>'
```
##### table.standard-table (403:1) => table
```
type: 'text'
value: 'Pros and cons of extending Object.prototype',type: 'html'
value: '<tr><th scope="row">Pro(s)</th><td>Supported in all browsers — including older browsers (going all the way back to IE 5.5). Also, it is very fast, very standard, and very JIT-optimizable.</td></tr>',type: 'html'
value: '<tr><th scope="row">Con(s)</th><td><div>1. In order to use this method, the function in question must be initialized. During this initialization, the constructor may store unique information that must be generated per-object. This unique information would only be generated once, potentially leading to problems.</div><div>2. The initialization of the constructor may put unwanted methods onto the object.</div><p>Both of those are generally not problems in practice.</p></td></tr>'
```
##### tr (458:5) => tableRow
```
type: 'html'
value: '<th scope="row">Pro(s)</th>'
```
##### tr (462:7) => tableRow
```
type: 'html'
value: '<th scope="row">Con(s)</th>'
```
##### table.standard-table (455:1) => table
```
type: 'text'
value: 'Pros and cons of {{anN4cmVmKCJPYmplY3QuY3JlYXRlIik=}}',type: 'html'
value: '<tr><th scope="row">Pro(s)</th><td>Supported in all modern browsers. Allows the direct setting of <code>__proto__</code> in a way that is a single event, which permits the browser to further optimize the object. Also allows the creation of objects without a prototype, using <code>Object.create(null)</code>.</td></tr>',type: 'html'
value: '<tr><th scope="row">Con(s)</th><td>Not supported in IE8 and below. However, as Microsoft has discontinued extended support for systems running IE8 and below, that should not be a concern for most applications. Additionally, the slow object initialization can be a performance black hole if using the second argument, because each object-descriptor property has its own separate descriptor object. When dealing with hundreds of thousands of object descriptors in the form of objects, that lag time might become a serious issue.</td></tr>'
```
##### tr (506:5) => tableRow
```
type: 'html'
value: '<th scope="row">Pro(s)</th>'
```
##### tr (510:7) => tableRow
```
type: 'html'
value: '<th scope="row">Con(s)</th>'
```
##### table.standard-table (503:1) => table
```
type: 'text'
value: 'Pros and cons of {{anN4cmVmKCJPYmplY3Quc2V0UHJvdG90eXBlT2YiKQ==}}',type: 'html'
value: '<tr><th scope="row">Pro(s)</th><td>Supported in all modern browsers. Allows the dynamic manipulation of an object’s prototype and can even force a prototype on a prototype-less object created with <code>Object.create(null)</code>.</td></tr>',type: 'html'
value: '<tr><th scope="row">Con(s)</th><td>Ill-performing. Should be deprecated. Many browsers optimize the prototype and try to guess the location of the method in memory when calling an instance in advance; but setting the prototype dynamically disrupts all those optimizations. It might cause some browsers to recompile your code for de-optimization, to make it work according to the specs. Not supported in IE8 and below.</td></tr>'
```
##### tr (549:5) => tableRow
```
type: 'html'
value: '<th scope="row">Pro(s)</th>'
```
##### tr (554:7) => tableRow
```
type: 'html'
value: '<th scope="row">Con(s)</th>'
```
##### table.standard-table (546:4) => table
```
type: 'text'
value: 'Pros and cons of setting the {{anN4cmVmKCJPYmplY3QvcHJvdG8iLCJfX3Byb3RvX18iKQ==}} property',type: 'html'
value: '<tr><th scope="row">Pro(s)</th><td>Supported in all modern browsers. Setting {{anN4cmVmKCJPYmplY3QvcHJvdG8iLCJfX3Byb3RvX18iKQ==}}
to something that is not an object only fails silently. It does not throw an exception.</td></tr>',type: 'html'
value: '<tr><th scope="row">Con(s)</th><td>Non-performant and deprecated. Many browsers optimize the prototype and try to guess the location of the method in the memory when calling an instance in advance; but setting the prototype dynamically disrupts all those optimizations and can even force some browsers to recompile for de-optimization of your code, to make it work according to the specs. Not supported in IE10 and below.</td></tr>'
```
### Missing conversion rules
- th[scope="row"] (407:7)
- th[scope="row"] (411:7)
- th[scope="row"] (459:7)
- th[scope="row"] (463:7)
- th[scope="row"] (507:7)
- th[scope="row"] (511:7)
- th[scope="row"] (550:7)
- th[scope="row"] (555:7)
### [/en-US/docs/Web/JavaScript/Language_Resources](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Language_Resources)
#### Invalid AST transformations
##### tr (23:3) => tableRow
```
type: 'html'
value: '<th colspan="4">Current editions</th>'
```
##### td (28:4) => tableCell
```
type: 'paragraph'
summary: 'ECMAScript is the scripting language that forms the basis of JavaScript. ECMAScript standardized by the ECMA International standards organization in the ECMA-262 and ECMA-402 specifications. The following ECMAScript standards have been approved or are being worked on:'
shouldWrap: 'true'
children: 
  type: 'link'
  title: 

  url: 'https://www.ecma-international.org/publications/files/ECMA-ST/ECMA-262.pdf'
  children: 
    type: 'text'
    value: 'PDF'
  type: 'text'
  value: ', '
  type: 'link'
  title: 

  url: 'https://ecma-international.org/ecma-262/11.0/index.html'
  children: 
    type: 'text'
    value: 'HTML'
  type: 'text'
  value: ', '
  type: 'link'
  title: 

  url: 'https://tc39.github.io/ecma262/'
  children: 
    type: 'text'
    value: 'Working draft'
  type: 'text'
  value: ', '
  type: 'link'
  title: 

  url: 'https://github.com/tc39/ecma262'
  children: 
    type: 'text'
    value: 'repository'
```
##### tr (26:4) => tableRow
```
type: 'html'
value: '<td><p><a href="https://www.ecma-international.org/publications/files/ECMA-ST/ECMA-262.pdf">PDF</a>, <a href="https://ecma-international.org/ecma-262/11.0/index.html">HTML</a>, <a href="https://tc39.github.io/ecma262/">Working draft</a>, <a href="https://github.com/tc39/ecma262">repository</a></p></td>'
```
##### td (36:4) => tableCell
```
type: 'paragraph'
summary: 'ECMAScript is the scripting language that forms the basis of JavaScript. ECMAScript standardized by the ECMA International standards organization in the ECMA-262 and ECMA-402 specifications. The following ECMAScript standards have been approved or are being worked on:'
shouldWrap: 'true'
children: 
  type: 'link'
  title: 

  url: 'https://www.ecma-international.org/publications/files/ECMA-ST/ECMA-262.pdf'
  children: 
    type: 'text'
    value: 'PDF'
  type: 'text'
  value: ', '
  type: 'link'
  title: 

  url: 'https://ecma-international.org/ecma-262/10.0/index.html'
  children: 
    type: 'text'
    value: 'HTML'
  type: 'text'
  value: ', '
  type: 'link'
  title: 

  url: 'https://tc39.github.io/ecma262/'
  children: 
    type: 'text'
    value: 'Working draft'
  type: 'text'
  value: ', '
  type: 'link'
  title: 

  url: 'https://github.com/tc39/ecma262'
  children: 
    type: 'text'
    value: 'repository'
```
##### tr (34:3) => tableRow
```
type: 'html'
value: '<td><p><a href="https://www.ecma-international.org/publications/files/ECMA-ST/ECMA-262.pdf">PDF</a>, <a href="https://ecma-international.org/ecma-262/10.0/index.html">HTML</a>, <a href="https://tc39.github.io/ecma262/">Working draft</a>, <a href="https://github.com/tc39/ecma262">repository</a></p></td>'
```
##### td (44:4) => tableCell
```
type: 'paragraph'
summary: 'ECMAScript is the scripting language that forms the basis of JavaScript. ECMAScript standardized by the ECMA International standards organization in the ECMA-262 and ECMA-402 specifications. The following ECMAScript standards have been approved or are being worked on:'
shouldWrap: 'true'
children: 
  type: 'link'
  title: 

  url: 'http://ecma-international.org/publications/files/ECMA-ST/Ecma-262.pdf'
  children: 
    type: 'text'
    value: 'PDF'
  type: 'text'
  value: ', '
  type: 'link'
  title: 

  url: 'http://ecma-international.org/ecma-262/9.0/index.html#Title'
  children: 
    type: 'text'
    value: 'HTML'
  type: 'text'
  value: ', '
  type: 'break'
  type: 'link'
  title: 

  url: 'https://tc39.github.io/ecma262/'
  children: 
    type: 'text'
    value: 'Working draft'
  type: 'text'
  value: ', '
  type: 'link'
  title: 

  url: 'https://github.com/tc39/ecma262'
  children: 
    type: 'text'
    value: 'repository'
```
##### tr (42:3) => tableRow
```
type: 'html'
value: '<td><p><a href="http://ecma-international.org/publications/files/ECMA-ST/Ecma-262.pdf">PDF</a>, <a href="http://ecma-international.org/ecma-262/9.0/index.html#Title">HTML</a>, <br><a href="https://tc39.github.io/ecma262/">Working draft</a>, <a href="https://github.com/tc39/ecma262">repository</a></p></td>'
```
##### tr (57:3) => tableRow
```
type: 'html'
value: '<th colspan="4">Obsolete/historical editions</th>'
```
##### table.standard-table (15:1) => table
```
type: 'html'
value: '<tr><th colspan="4">Current editions</th></tr>',type: 'html'
value: '<tr><td>ECMA-262 11th Edition</td><td><p><a href="https://www.ecma-international.org/publications/files/ECMA-ST/ECMA-262.pdf">PDF</a>, <a href="https://ecma-international.org/ecma-262/11.0/index.html">HTML</a>, <a href="https://tc39.github.io/ecma262/">Working draft</a>, <a href="https://github.com/tc39/ecma262">repository</a></p></td><td>2020</td><td>ECMAScript 2020 Language Specification</td></tr>',type: 'html'
value: '<tr><td>ECMA-262 10th Edition</td><td><p><a href="https://www.ecma-international.org/publications/files/ECMA-ST/ECMA-262.pdf">PDF</a>, <a href="https://ecma-international.org/ecma-262/10.0/index.html">HTML</a>, <a href="https://tc39.github.io/ecma262/">Working draft</a>, <a href="https://github.com/tc39/ecma262">repository</a></p></td><td>2019</td><td>ECMAScript 2019 Language Specification</td></tr>',type: 'html'
value: '<tr><td>ECMA-262 9th Edition</td><td><p><a href="http://ecma-international.org/publications/files/ECMA-ST/Ecma-262.pdf">PDF</a>, <a href="http://ecma-international.org/ecma-262/9.0/index.html#Title">HTML</a>, <br><a href="https://tc39.github.io/ecma262/">Working draft</a>, <a href="https://github.com/tc39/ecma262">repository</a></p></td><td>2018</td><td>ECMAScript 2018 Language Specification</td></tr>',type: 'html'
value: '<tr><th colspan="4">Obsolete/historical editions</th></tr>'
```
### Missing conversion rules
- th[colSpan="4"] (24:4)
- th[colSpan="4"] (58:4)
### [/en-US/docs/Web/JavaScript/Memory_Management](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Memory_Management)
#### Invalid AST transformations
##### code (192:4) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'max-old-space-size=6000'
```
### [/en-US/docs/Web/JavaScript/Reference/Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)
#### Invalid AST transformations
##### code (409:260) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'ClassName'
```
##### code (409:467) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'ClassName'
```
### [/en-US/docs/Web/JavaScript/Reference/Classes/static](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes/static)
#### Invalid AST transformations
##### pre.brush:.js (31:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'methodName'
```
### [/en-US/docs/Web/JavaScript/Reference/Deprecated_and_obsolete_features](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Deprecated_and_obsolete_features)
#### Invalid AST transformations
##### td (31:4) => tableCell
```
type: 'paragraph'
summary: 'This page lists features of JavaScript that are deprecated (that is, still available but planned for removal) and obsolete (that is, no longer usable).'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Parenthesized substring matches, if any.'
  type: 'break'
  type: 'strong'
  children: 
    type: 'text'
    value: 'Warning:'
  type: 'text'
  value: ' Using these properties can result in problems, since browser extensions can modify them. Avoid them!'
```
##### tr (29:3) => tableRow
```
type: 'html'
value: '<td><p>Parenthesized substring matches, if any.<br><strong>Warning:</strong> Using these properties can result in problems, since browser extensions can modify them. Avoid them!</p></td>'
```
##### table.standard-table (23:1) => table
```
type: 'html'
value: '<tr><td>{{anN4cmVmKCJSZWdFeHAubiIsICIkMS0kOSIp}}</td><td><p>Parenthesized substring matches, if any.<br><strong>Warning:</strong> Using these properties can result in problems, since browser extensions can modify them. Avoid them!</p></td></tr>'
```
### [/en-US/docs/Web/JavaScript/Reference/Deprecated_and_obsolete_features/The_legacy_Iterator_protocol](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Deprecated_and_obsolete_features/The_legacy_Iterator_protocol)
#### Invalid AST transformations
##### tr (24:3) => tableRow
```
type: 'html'
value: '<th scope="col">Property</th>',type: 'html'
value: '<th scope="col">Value</th>'
```
##### table.standard-table (22:1) => table
```
type: 'html'
value: '<tr><th scope="col">Property</th><th scope="col">Value</th></tr>'
```
### Missing conversion rules
- th[scope="col"] (25:4)
- th[scope="col"] (26:4)
### [/en-US/docs/Web/JavaScript/Reference/Errors/Bad_regexp_flag](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Bad_regexp_flag)
#### Invalid AST transformations
##### tr (48:5) => tableRow
```
type: 'html'
value: '<th scope="col">Flag</th>',type: 'html'
value: '<th scope="col">Description</th>'
```
##### table.standard-table (45:1) => table
```
type: 'text'
value: 'Regular expression flags',type: 'html'
value: '<tr><th scope="col">Flag</th><th scope="col">Description</th></tr>'
```
### Missing conversion rules
- th[scope="col"] (49:7)
- th[scope="col"] (50:7)
### [/en-US/docs/Web/JavaScript/Reference/Errors/Cant_assign_to_property](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Cant_assign_to_property)
#### Invalid AST transformations
##### pre.brush:.js.example-bad (51:1) => text
```
type: 'element'
tagName: 'span'
properties: 
  className: 
    'message-body-wrapper'
children: 
  type: 'element'
  tagName: 'span'
  properties: 
    className: 
      'message-flex-body'
  children: 
    type: 'element'
    tagName: 'span'
    properties: 
      className: 
        'devtools-monospace'
        'message-body'
    children: 
      type: 'text'
      value: 'TypeError: can't assign to property "bar" on "my string": not an object'
```
### [/en-US/docs/Web/JavaScript/Reference/Errors/Precision_range](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Precision_range)
#### Invalid AST transformations
##### tr (46:5) => tableRow
```
type: 'html'
value: '<th scope="col">Method</th>',type: 'html'
value: '<th scope="col">Firefox (SpiderMonkey)</th>',type: 'html'
value: '<th scope="col">Chrome, Opera (V8)</th>'
```
##### table.standard-table (44:1) => table
```
type: 'html'
value: '<tr><th scope="col">Method</th><th scope="col">Firefox (SpiderMonkey)</th><th scope="col">Chrome, Opera (V8)</th></tr>'
```
### Missing conversion rules
- th[scope="col"] (47:7)
- th[scope="col"] (48:7)
- th[scope="col"] (49:7)
### [/en-US/docs/Web/JavaScript/Reference/Errors/Unexpected_token](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Unexpected_token)
### Missing conversion rules
- pre.brush:.js.example-bad.line-numbers.language-js (58:1)
### [/en-US/docs/Web/JavaScript/Reference/Functions/arguments/@@iterator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/arguments/@@iterator)
#### Invalid AST transformations
##### pre.brush:.js (20:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'arguments'
```
### [/en-US/docs/Web/JavaScript/Reference/Functions/arguments](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/arguments)
#### Invalid AST transformations
##### span.summary (15:4) => text
```
type: 'element'
tagName: 'a'
properties: 
  href: '/en-US/docs/Web/JavaScript/Guide/Functions'
children: 
  type: 'text'
  value: 'functions'
```
### [/en-US/docs/Web/JavaScript/Reference/Functions/Default_parameters](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Default_parameters)
#### Invalid AST transformations
##### code (37:42) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'a'
```
### Missing conversion rules
- span.seoSummary (14:4)
### [/en-US/docs/Web/JavaScript/Reference/Functions/get](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/get)
#### Invalid AST transformations
##### pre.brush:.js (22:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'prop'
```
##### pre.brush:.js (85:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'obj'
```
### Missing conversion rules
- abbr[title="ECMAScript 5th edition"] (51:44)
### [/en-US/docs/Web/JavaScript/Reference/Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions)
#### Invalid AST transformations
##### pre.brush:.js (99:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'name'
```
##### pre.brush:.js (124:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'name'
```
##### pre.brush:.js (178:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'name'
```
##### pre.brush:.js (199:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'name'
```
##### pre.brush:.js (249:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'arg1'
```
##### code (253:7) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'arg1'
```
##### pre.brush:.js (282:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'arg1'
```
##### code (286:7) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'arg1'
```
### [/en-US/docs/Web/JavaScript/Reference/Functions/Method_definitions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Method_definitions)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'property'
```
### [/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'a'
```
### Missing conversion rules
- var (53:60)
### [/en-US/docs/Web/JavaScript/Reference/Functions/set](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/set)
#### Invalid AST transformations
##### pre.brush:.js (22:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'prop'
```
### Missing conversion rules
- abbr[title="ECMAScript 5th edition"] (50:44)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Array)
#### Invalid AST transformations
##### code (32:7) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'N'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/concat](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/concat)
#### Invalid AST transformations
##### code (34:7) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'N'
```
##### code (36:5) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'N'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/every](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/every)
#### Invalid AST transformations
##### dl (43:1) => paragraph
```
type: 'list'
spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'element'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The current element being processed in the array.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'index'
      type: 'text'
      value: ' {{T3B0aW9uYWxfaW5saW5l}}'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The index of the current element being processed in the array.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'array'
      type: 'text'
      value: ' {{T3B0aW9uYWxfaW5saW5l}}'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The array '
          type: 'inlineCode'
          value: 'every'
          type: 'text'
          value: ' was called upon.'
```
##### code (119:8) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'callbackfn'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/fill](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/fill)
#### Invalid AST transformations
##### code (49:69) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'start'
```
##### code (50:67) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'end'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/find](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/find)
#### Invalid AST transformations
##### dl (57:1) => paragraph
```
type: 'list'
spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'element'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The current element in the array.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'index'
      type: 'text'
      value: ' {{b3B0aW9uYWxfaW5saW5l}}'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The index (position) of the current element in the array.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'array'
      type: 'text'
      value: ' {{b3B0aW9uYWxfaW5saW5l}}'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The array that '
          type: 'inlineCode'
          value: 'find'
          type: 'text'
          value: ' was called on.'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/flatMap](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/flatMap)
#### Invalid AST transformations
##### dl (45:1) => paragraph
```
type: 'list'
spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'currentValue'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The current element being processed in the array.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'index'
      type: 'text'
      value: '{{b3B0aW9uYWxfaW5saW5l}}'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The index of the current element being processed in the array.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'array'
      type: 'text'
      value: '{{b3B0aW9uYWxfaW5saW5l}}'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The array '
          type: 'inlineCode'
          value: 'map'
          type: 'text'
          value: ' was called upon.'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach)
#### Invalid AST transformations
##### code (165:8) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'fun'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/from](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/from)
#### Invalid AST transformations
##### code (73:5) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'obj'
```
##### code (75:8) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'obj'
```
##### code (191:9) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'callback'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/includes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/includes)
#### Invalid AST transformations
##### code (50:5) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'arr'
```
##### code (99:3) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'arr'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)
#### Invalid AST transformations
##### pre.brush:.js (93:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'n'
```
### Missing conversion rules
- table.fullwidth-table.standard-table (210:1)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/join](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/join)
#### Invalid AST transformations
##### span.seoSummary (15:4) => text
```
type: 'element'
tagName: 'a'
properties: 
  href: '/en-US/docs/Web/JavaScript/Guide/Indexed_collections#Working_with_array-like_objects'
children: 
  type: 'text'
  value: 'array-like
object'
```
##### code (42:48) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'arr'
```
##### pre.brush:.js (75:1) => text
```
type: 'element'
tagName: 'span'
properties: 
  className: 
    'message-body-wrapper'
children: 
  type: 'element'
  tagName: 'span'
  properties: 
    className: 
      'message-flex-body'
  children: 
    type: 'element'
    tagName: 'span'
    properties: 
      className: 
        'devtools-monospace'
        'message-body'
    children: 
      type: 'element'
      tagName: 'span'
      properties: 
        className: 
          'objectBox'
          'objectBox-string'
      children: 
        type: 'text'
        value: '1,a,true''
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/of](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/of)
#### Invalid AST transformations
##### code (45:7) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'N'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/push](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/push)
#### Invalid AST transformations
##### code (32:7) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'N'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce)
#### Invalid AST transformations
##### tr (171:5) => tableRow
```
type: 'html'
value: '<th scope="col"><code><var>callback</var></code> iteration</th>',type: 'html'
value: '<th scope="col"><code><var>accumulator</var></code></th>',type: 'html'
value: '<th scope="col"><code><var>currentValue</var></code></th>',type: 'html'
value: '<th scope="col"><code><var>currentIndex</var></code></th>',type: 'html'
value: '<th scope="col"><code><var>array</var></code></th>',type: 'html'
value: '<th scope="col">return value</th>'
```
##### tr (181:5) => tableRow
```
type: 'html'
value: '<th scope="row">first call</th>'
```
##### tr (189:5) => tableRow
```
type: 'html'
value: '<th scope="row">second call</th>'
```
##### tr (197:5) => tableRow
```
type: 'html'
value: '<th scope="row">third call</th>'
```
##### tr (205:5) => tableRow
```
type: 'html'
value: '<th scope="row">fourth call</th>'
```
##### table.standard-table (169:1) => table
```
type: 'html'
value: '<tr><th scope="col"><code><var>callback</var></code> iteration</th><th scope="col"><code><var>accumulator</var></code></th><th scope="col"><code><var>currentValue</var></code></th><th scope="col"><code><var>currentIndex</var></code></th><th scope="col"><code><var>array</var></code></th><th scope="col">return value</th></tr>',type: 'html'
value: '<tr><th scope="row">first call</th><td><code>0</code></td><td><code>1</code></td><td><code>1</code></td><td><code>[0, 1, 2, 3, 4]</code></td><td><code>1</code></td></tr>',type: 'html'
value: '<tr><th scope="row">second call</th><td><code>1</code></td><td><code>2</code></td><td><code>2</code></td><td><code>[0, 1, 2, 3, 4]</code></td><td><code>3</code></td></tr>',type: 'html'
value: '<tr><th scope="row">third call</th><td><code>3</code></td><td><code>3</code></td><td><code>3</code></td><td><code>[0, 1, 2, 3, 4]</code></td><td><code>6</code></td></tr>',type: 'html'
value: '<tr><th scope="row">fourth call</th><td><code>6</code></td><td><code>4</code></td><td><code>4</code></td><td><code>[0, 1, 2, 3, 4]</code></td><td><code>10</code></td></tr>'
```
##### tr (236:5) => tableRow
```
type: 'html'
value: '<th scope="col"><code><var>callback</var></code> iteration</th>',type: 'html'
value: '<th scope="col"><code><var>accumulator</var></code></th>',type: 'html'
value: '<th scope="col"><code><var>currentValue</var></code></th>',type: 'html'
value: '<th scope="col"><code><var>currentIndex</var></code></th>',type: 'html'
value: '<th scope="col"><code><var>array</var></code></th>',type: 'html'
value: '<th scope="col">return value</th>'
```
##### tr (246:5) => tableRow
```
type: 'html'
value: '<th scope="row">first call</th>'
```
##### tr (254:5) => tableRow
```
type: 'html'
value: '<th scope="row">second call</th>'
```
##### tr (262:5) => tableRow
```
type: 'html'
value: '<th scope="row">third call</th>'
```
##### tr (270:5) => tableRow
```
type: 'html'
value: '<th scope="row">fourth call</th>'
```
##### tr (278:5) => tableRow
```
type: 'html'
value: '<th scope="row">fifth call</th>'
```
##### table.standard-table (234:1) => table
```
type: 'html'
value: '<tr><th scope="col"><code><var>callback</var></code> iteration</th><th scope="col"><code><var>accumulator</var></code></th><th scope="col"><code><var>currentValue</var></code></th><th scope="col"><code><var>currentIndex</var></code></th><th scope="col"><code><var>array</var></code></th><th scope="col">return value</th></tr>',type: 'html'
value: '<tr><th scope="row">first call</th><td><code>10</code></td><td><code>0</code></td><td><code>0</code></td><td><code>[0, 1, 2, 3, 4]</code></td><td><code>10</code></td></tr>',type: 'html'
value: '<tr><th scope="row">second call</th><td><code>10</code></td><td><code>1</code></td><td><code>1</code></td><td><code>[0, 1, 2, 3, 4]</code></td><td><code>11</code></td></tr>',type: 'html'
value: '<tr><th scope="row">third call</th><td><code>11</code></td><td><code>2</code></td><td><code>2</code></td><td><code>[0, 1, 2, 3, 4]</code></td><td><code>13</code></td></tr>',type: 'html'
value: '<tr><th scope="row">fourth call</th><td><code>13</code></td><td><code>3</code></td><td><code>3</code></td><td><code>[0, 1, 2, 3, 4]</code></td><td><code>16</code></td></tr>',type: 'html'
value: '<tr><th scope="row">fifth call</th><td><code>16</code></td><td><code>4</code></td><td><code>4</code></td><td><code>[0, 1, 2, 3, 4]</code></td><td><code>20</code></td></tr>'
```
### Missing conversion rules
- var (71:39)
- th[scope="col"] (172:7)
- th[scope="col"] (173:7)
- th[scope="col"] (174:7)
- th[scope="col"] (175:7)
- th[scope="col"] (176:7)
- th[scope="col"] (177:7)
- th[scope="row"] (182:7)
- th[scope="row"] (190:7)
- th[scope="row"] (198:7)
- th[scope="row"] (206:7)
- th[scope="col"] (237:7)
- th[scope="col"] (238:7)
- th[scope="col"] (239:7)
- th[scope="col"] (240:7)
- th[scope="col"] (241:7)
- th[scope="col"] (242:7)
- th[scope="row"] (247:7)
- th[scope="row"] (255:7)
- th[scope="row"] (263:7)
- th[scope="row"] (271:7)
- th[scope="row"] (279:7)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/ReduceRight](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/ReduceRight)
#### Invalid AST transformations
##### dl (46:1) => paragraph
```
type: 'list'
spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'accumulator'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The value previously returned in the last invocation of the callback, or
'
          type: 'inlineCode'
          value: 'initialValue'
          type: 'text'
          value: ', if supplied. (See below.)'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'currentValue'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The current element being processed in the array.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'index'
      type: 'text'
      value: '{{b3B0aW9uYWxfaW5saW5l}}'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The index of the current element being processed in the array.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'array'
      type: 'text'
      value: '{{b3B0aW9uYWxfaW5saW5l}}'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The array '
          type: 'inlineCode'
          value: 'reduceRight()'
          type: 'text'
          value: ' was called upon.'
```
##### tr (115:5) => tableRow
```
type: 'html'
value: '<th scope="col"><code><var>callback</var></code></th>',type: 'html'
value: '<th scope="col"><code><var>accumulator</var></code></th>',type: 'html'
value: '<th scope="col"><code><var>currentValue</var></code></th>',type: 'html'
value: '<th scope="col"><code><var>index</var></code></th>',type: 'html'
value: '<th scope="col"><code><var>array</var></code></th>',type: 'html'
value: '<th scope="col">return value</th>'
```
##### tr (125:5) => tableRow
```
type: 'html'
value: '<th scope="row">first call</th>'
```
##### tr (133:5) => tableRow
```
type: 'html'
value: '<th scope="row">second call</th>'
```
##### tr (141:5) => tableRow
```
type: 'html'
value: '<th scope="row">third call</th>'
```
##### tr (149:5) => tableRow
```
type: 'html'
value: '<th scope="row">fourth call</th>'
```
##### table (113:1) => table
```
type: 'html'
value: '<tr><th scope="col"><code><var>callback</var></code></th><th scope="col"><code><var>accumulator</var></code></th><th scope="col"><code><var>currentValue</var></code></th><th scope="col"><code><var>index</var></code></th><th scope="col"><code><var>array</var></code></th><th scope="col">return value</th></tr>',type: 'html'
value: '<tr><th scope="row">first call</th><td><code>4</code></td><td><code>3</code></td><td><code>3</code></td><td><code>[0, 1, 2, 3, 4]</code></td><td><code>7</code></td></tr>',type: 'html'
value: '<tr><th scope="row">second call</th><td><code>7</code></td><td><code>2</code></td><td><code>2</code></td><td><code>[0, 1, 2, 3, 4]</code></td><td><code>9</code></td></tr>',type: 'html'
value: '<tr><th scope="row">third call</th><td><code>9</code></td><td><code>1</code></td><td><code>1</code></td><td><code>[0, 1, 2, 3, 4]</code></td><td><code>10</code></td></tr>',type: 'html'
value: '<tr><th scope="row">fourth call</th><td><code>10</code></td><td><code>0</code></td><td><code>0</code></td><td><code>[0, 1, 2, 3, 4]</code></td><td><code>10</code></td></tr>'
```
##### tr (173:5) => tableRow
```
type: 'html'
value: '<th scope="col"><code><var>callback</var></code></th>',type: 'html'
value: '<th scope="col"><code><var>accumulator</var></code></th>',type: 'html'
value: '<th scope="col"><code><var>currentValue</var></code></th>',type: 'html'
value: '<th scope="col"><code><var>index</var></code></th>',type: 'html'
value: '<th scope="col"><code><var>array</var></code></th>',type: 'html'
value: '<th scope="col">return value</th>'
```
##### tr (183:5) => tableRow
```
type: 'html'
value: '<th scope="row">first call</th>'
```
##### tr (191:5) => tableRow
```
type: 'html'
value: '<th scope="row">second call</th>'
```
##### tr (199:5) => tableRow
```
type: 'html'
value: '<th scope="row">third call</th>'
```
##### tr (207:5) => tableRow
```
type: 'html'
value: '<th scope="row">fourth call</th>'
```
##### tr (215:5) => tableRow
```
type: 'html'
value: '<th scope="row">fifth call</th>'
```
##### table (171:1) => table
```
type: 'html'
value: '<tr><th scope="col"><code><var>callback</var></code></th><th scope="col"><code><var>accumulator</var></code></th><th scope="col"><code><var>currentValue</var></code></th><th scope="col"><code><var>index</var></code></th><th scope="col"><code><var>array</var></code></th><th scope="col">return value</th></tr>',type: 'html'
value: '<tr><th scope="row">first call</th><td><code>10</code></td><td><code>4</code></td><td><code>4</code></td><td><code>[0, 1, 2, 3, 4]</code></td><td><code>14</code></td></tr>',type: 'html'
value: '<tr><th scope="row">second call</th><td><code>14</code></td><td><code>3</code></td><td><code>3</code></td><td><code>[0, 1, 2, 3, 4]</code></td><td><code>17</code></td></tr>',type: 'html'
value: '<tr><th scope="row">third call</th><td><code>17</code></td><td><code>2</code></td><td><code>2</code></td><td><code>[0, 1, 2, 3, 4]</code></td><td><code>19</code></td></tr>',type: 'html'
value: '<tr><th scope="row">fourth call</th><td><code>19</code></td><td><code>1</code></td><td><code>1</code></td><td><code>[0, 1, 2, 3, 4]</code></td><td><code>20</code></td></tr>',type: 'html'
value: '<tr><th scope="row">fifth call</th><td><code>20</code></td><td><code>0</code></td><td><code>0</code></td><td><code>[0, 1, 2, 3, 4]</code></td><td><code>20</code></td></tr>'
```
### Missing conversion rules
- th[scope="col"] (116:7)
- th[scope="col"] (117:7)
- th[scope="col"] (118:7)
- th[scope="col"] (119:7)
- th[scope="col"] (120:7)
- th[scope="col"] (121:7)
- th[scope="row"] (126:7)
- th[scope="row"] (134:7)
- th[scope="row"] (142:7)
- th[scope="row"] (150:7)
- th[scope="col"] (174:7)
- th[scope="col"] (175:7)
- th[scope="col"] (176:7)
- th[scope="col"] (177:7)
- th[scope="col"] (178:7)
- th[scope="col"] (179:7)
- th[scope="row"] (184:7)
- th[scope="row"] (192:7)
- th[scope="row"] (200:7)
- th[scope="row"] (208:7)
- th[scope="row"] (216:7)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/slice](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/slice)
#### Invalid AST transformations
##### code (53:26) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'arr'
```
##### code (56:6) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'arr'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/some](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/some)
#### Invalid AST transformations
##### code (115:8) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'fun'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/sort](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/sort)
#### Invalid AST transformations
##### dl (44:1) => paragraph
```
type: 'list'
spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'firstEl'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The first element for comparison.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'secondEl'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The second element for comparison.'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice)
#### Invalid AST transformations
##### code (44:47) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'n'
```
##### code (46:21) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'array'
```
##### code (47:5) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'array'
```
##### code (55:17) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'array'
```
##### code (62:7) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'item1'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/unshift](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/unshift)
#### Invalid AST transformations
##### code (31:7) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'N'
```
##### pre.brush:.js (59:1) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: '1, 2, 3'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/ArrayBuffer/ArrayBuffer](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/ArrayBuffer/ArrayBuffer)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'length'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/ArrayBuffer/isView](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/ArrayBuffer/isView)
#### Invalid AST transformations
##### pre.brush:.js (25:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'value'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/AsyncFunction](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/AsyncFunction)
#### Invalid AST transformations
##### code (34:7) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'N'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Atomics/add](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Atomics/add)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'typedArray'
```
##### code (45:4) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'typedArray'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Atomics/and](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Atomics/and)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'typedArray'
```
##### code (45:4) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'typedArray'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Atomics/compareExchange](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Atomics/compareExchange)
#### Invalid AST transformations
##### pre.brush:.js (26:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'typedArray'
```
##### code (49:4) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'typedArray'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Atomics/exchange](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Atomics/exchange)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'typedArray'
```
##### code (45:4) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'typedArray'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Atomics/or](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Atomics/or)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'typedArray'
```
##### code (45:4) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'typedArray'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Atomics/store](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Atomics/store)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'typedArray'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Atomics/sub](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Atomics/sub)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'typedArray'
```
##### code (44:4) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'typedArray'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/BigInt/asIntN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/BigInt/asIntN)
#### Invalid AST transformations
##### pre.brush:.js (22:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'bits'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/BigInt/asUintN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/BigInt/asUintN)
#### Invalid AST transformations
##### pre.brush:.js (22:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'bits'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/BigInt/BigInt](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/BigInt/BigInt)
#### Invalid AST transformations
##### pre.brush:.js (19:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'value'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/BigInt/toLocaleString](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/BigInt/toLocaleString)
#### Invalid AST transformations
##### pre.brush:.js (71:1) => text
```
type: 'element'
tagName: 'a'
properties: 
  href: 'https://en.wikipedia.org/wiki/Eastern_Arabic_numerals'
children: 
  type: 'text'
  value: 'Eastern Arabic'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/BigInt/valueOf](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/BigInt/valueOf)
#### Invalid AST transformations
##### pre.brush:.js (22:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'bigIntObj'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/BigInt64Array/BigInt64Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/BigInt64Array/BigInt64Array)
#### Invalid AST transformations
##### code (51:26) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/BigUint64Array/BigUint64Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/BigUint64Array/BigUint64Array)
#### Invalid AST transformations
##### code (50:26) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/DataView](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/DataView)
#### Invalid AST transformations
##### span.seoSummary (15:4) => text
```
type: 'element'
tagName: 'a'
properties: 
  href: '/en-US/docs/Glossary/Endianness'
children: 
  type: 'text'
  value: 'endianness'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/DataView/setBigInt64](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/DataView/setBigInt64)
#### Invalid AST transformations
##### code (39:5) => text
```
type: 'element'
tagName: 'span'
properties: 
  className: 
    'blob-code-inner'
    'blob-code-marker'
children: 
  type: 'text'
  value: '2n ** (64n -1n) - 1n'
```
### Missing conversion rules
- span.blob-code-inner.blob-code-marker (39:92)
- span.blob-code-inner.blob-code-marker (41:79)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/DataView/setBigUint64](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/DataView/setBigUint64)
#### Invalid AST transformations
##### code (39:5) => text
```
type: 'element'
tagName: 'span'
properties: 
  className: 
    'blob-code-inner'
    'blob-code-marker'
children: 
  type: 'text'
  value: '2n ** 64n - 1n'
```
### Missing conversion rules
- span.blob-code-inner.blob-code-marker (39:86)
- span.blob-code-inner.blob-code-marker (41:49)
- span.blob-code-inner.blob-code-marker (43:30)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/@@toPrimitive](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/@@toPrimitive)
#### Invalid AST transformations
##### pre.brush:.js (20:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'hint'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/Date)
#### Invalid AST transformations
##### dl (69:5) => paragraph
```
type: 'blockquote'
children: 
  type: 'paragraph'
  children: 
    type: 'strong'
    children: 
      type: 'text'
      value: 'Note:'
    type: 'text'
    value: ' Parsing of date strings with the '
    type: 'inlineCode'
    value: 'Date'
    type: 'text'
    value: '
constructor (and '
    type: 'inlineCode'
    value: 'Date.parse()'
    type: 'text'
    value: ', which works the same way) is
'
    type: 'emphasis'
    children: 
      type: 'text'
      value: 'strongly discouraged'
    type: 'text'
    value: ' due to browser differences and inconsistencies.'
  type: 'list'
  ordered: 'false'
  start: 

  spread: 'false'
  children: 
    type: 'listItem'
    spread: 'false'
    children: 
      type: 'paragraph'
      children: 
        type: 'text'
        value: 'Support for '
        type: 'link'
        title: 

        url: 'https://datatracker.ietf.org/doc/html/rfc2822'
        children: 
          type: 'text'
          value: 'RFC 2822'
        type: 'text'
        value: '
format strings is by convention only.'
    type: 'listItem'
    spread: 'false'
    children: 
      type: 'paragraph'
      children: 
        type: 'text'
        value: 'Support for ISO 8601 formats differs in that date-only strings (e.g.
'
        type: 'inlineCode'
        value: '"1970-01-01"'
        type: 'text'
        value: ') are treated as UTC, not local.'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/getTimezoneOffset](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/getTimezoneOffset)
#### Invalid AST transformations
##### code (29:4) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'date'
```
##### tr (37:3) => tableRow
```
type: 'html'
value: '<th scope="row">Current time zone</th>',type: 'html'
value: '<th scope="col">UTC-8</th>',type: 'html'
value: '<th scope="col">UTC</th>',type: 'html'
value: '<th scope="col">UTC+3</th>'
```
##### tr (45:3) => tableRow
```
type: 'html'
value: '<th scope="row">Return Value</th>'
```
##### table.standard-table (35:1) => table
```
type: 'html'
value: '<tr><th scope="row">Current time zone</th><th scope="col">UTC-8</th><th scope="col">UTC</th><th scope="col">UTC+3</th></tr>',type: 'html'
value: '<tr><th scope="row">Return Value</th><td>480</td><td>0</td><td>-180</td></tr>'
```
##### code (57:162) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'date1'
```
##### code (60:147) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'date2'
```
##### code (61:147) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'date3'
```
### Missing conversion rules
- var (25:40)
- var (29:97)
- var (29:152)
- th[scope="row"] (38:4)
- th[scope="col"] (39:4)
- th[scope="col"] (40:4)
- th[scope="col"] (41:4)
- th[scope="row"] (46:4)
- var (57:48)
- var (57:100)
- var (60:67)
- var (60:200)
- var (61:80)
- var (61:200)
- var (64:225)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date)
#### Invalid AST transformations
##### dl (50:1) => paragraph
```
type: 'blockquote'
children: 
  type: 'paragraph'
  children: 
    type: 'strong'
    children: 
      type: 'text'
      value: 'Note:'
    type: 'text'
    value: ' Parsing of strings with '
    type: 'inlineCode'
    value: 'Date.parse'
    type: 'text'
    value: ' is strongly discouraged due to browser differences and inconsistencies.'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/parse](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/parse)
#### Invalid AST transformations
##### pre.brush:.js (31:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'dateString'
```
##### pre.brush:.js (36:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'dateString'
```
##### code (249:5) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'dateString'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/setFullYear](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/setFullYear)
#### Invalid AST transformations
##### code (59:4) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'yearValue'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/setHours](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/setHours)
#### Invalid AST transformations
##### code (71:24) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'minutesValue'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/setMinutes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/setMinutes)
#### Invalid AST transformations
##### code (60:24) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'minutesValue'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/setUTCFullYear](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/setUTCFullYear)
#### Invalid AST transformations
##### code (59:4) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'yearValue'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/setUTCMinutes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/setUTCMinutes)
#### Invalid AST transformations
##### code (61:4) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'minutesValue'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/toISOString](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/toISOString)
#### Invalid AST transformations
##### code (20:4) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'YYYY'
```
##### code (22:3) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: '±'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/toLocaleDateString](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/toLocaleDateString)
#### Invalid AST transformations
##### pre.brush:.js (103:1) => text
```
type: 'element'
tagName: 'span'
properties: 
  dir: 'rtl'
children: 
  type: 'text'
  value: '٢٠‏/١٢‏/٢٠١٢'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/toLocaleString](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/toLocaleString)
#### Invalid AST transformations
##### pre.brush:.js (98:1) => text
```
type: 'element'
tagName: 'span'
properties: 
  dir: 'rtl'
children: 
  type: 'text'
  value: '٢٠‏/١٢‏/٢٠١٢ ٥:٠٠:٠٠ ص'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/toLocaleTimeString](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/toLocaleTimeString)
#### Invalid AST transformations
##### pre.brush:.js (102:1) => text
```
type: 'element'
tagName: 'span'
properties: 
  dir: 'rtl'
children: 
  type: 'text'
  value: '٧:٠٠:٠٠ م'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/toSource](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/toSource)
#### Invalid AST transformations
##### pre.brush:.js (20:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'dateObj'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/toUTCString](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/toUTCString)
#### Invalid AST transformations
##### code (38:3) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'Www'
```
##### tr (43:5) => tableRow
```
type: 'html'
value: '<th scope="col">Format String</th>',type: 'html'
value: '<th scope="col">Description</th>'
```
##### table.standard-table (41:1) => table
```
type: 'html'
value: '<tr><th scope="col">Format String</th><th scope="col">Description</th></tr>'
```
### Missing conversion rules
- th[scope="col"] (44:7)
- th[scope="col"] (45:7)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/UTC](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/UTC)
#### Invalid AST transformations
##### code (85:3) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'year'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/decodeURI](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/decodeURI)
#### Invalid AST transformations
##### pre.brush:.js (26:1) => text
```
type: 'element'
tagName: 'code'
properties: 

children: 
  type: 'text'
  value: 'decodeURI('
  type: 'element'
  tagName: 'var'
  properties: 

  children: 
    type: 'text'
    value: 'encodedURI'
  type: 'text'
  value: ')'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/decodeURIComponent](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/decodeURIComponent)
#### Invalid AST transformations
##### pre.brush:.js (21:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'encodedURI'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/encodeURI](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/encodeURI)
#### Invalid AST transformations
##### pre.brush:.js (27:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'URI'
```
##### pre.brush:.plain (58:1) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: 'Not Escaped'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/encodeURIComponent](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/encodeURIComponent)
#### Invalid AST transformations
##### pre.brush:.js (26:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'str'
```
##### pre.brush:.plain (43:1) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: 'Not Escaped'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Error/toSource](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Error/toSource)
#### Invalid AST transformations
##### pre.brush:.js (37:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'name'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/escape](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/escape)
#### Invalid AST transformations
##### code (32:27) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'HH'
```
##### code (33:42) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'HH'
```
##### pre.brush:.js (43:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'str'
```
##### code (62:41) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'xx'
```
##### code (63:44) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'xxxx'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Float32Array/Float32Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Float32Array/Float32Array)
#### Invalid AST transformations
##### code (52:26) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Float64Array/Float64Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Float64Array/Float64Array)
#### Invalid AST transformations
##### code (52:26) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/apply](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/apply)
#### Invalid AST transformations
##### code (59:283) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'func'
```
##### code (59:397) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'func'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/arguments](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/arguments)
#### Invalid AST transformations
##### code (15:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'function'
```
##### code (19:15) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'function'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/bind](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/bind)
#### Invalid AST transformations
##### code (47:7) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'arg1'
```
##### code (84:3) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'boundThis'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/call](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/call)
#### Invalid AST transformations
##### code (47:5) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'arg1'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/caller](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/caller)
#### Invalid AST transformations
##### code (14:16) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'function'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/displayName](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/displayName)
#### Invalid AST transformations
##### code (14:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'function'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/Function](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/Function)
#### Invalid AST transformations
##### code (35:7) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'arg1'
```
### Missing conversion rules
- span.seoSummary (14:4)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/toString](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/toString)
#### Invalid AST transformations
##### tr (71:9) => tableRow
```
type: 'html'
value: '<th scope="col">Function</th>',type: 'html'
value: '<th scope="col">Function.prototype.toString result</th>'
```
##### td (78:13) => tableCell
```
type: 'code'
lang: 'js'
meta: ''
value: 'function f(){}'
```
##### td (82:13) => tableCell
```
type: 'code'
lang: 'js'
meta: ''
value: '"function f(){}"'
```
##### tr (77:9) => tableRow
```
type: 'html'
value: '<td><pre class="brush: js">function f(){}</pre></td>',type: 'html'
value: '<td><pre class="brush: js">"function f(){}"</pre></td>'
```
##### td (88:13) => tableCell
```
type: 'code'
lang: 'js'
meta: ''
value: 'class A { a(){} }'
```
##### td (92:13) => tableCell
```
type: 'code'
lang: 'js'
meta: ''
value: '"class A { a(){} }"'
```
##### tr (87:9) => tableRow
```
type: 'html'
value: '<td><pre class="brush: js">class A { a(){} }</pre></td>',type: 'html'
value: '<td><pre class="brush: js">"class A { a(){} }"</pre></td>'
```
##### td (98:13) => tableCell
```
type: 'code'
lang: 'js'
meta: ''
value: 'function* g(){}'
```
##### td (102:13) => tableCell
```
type: 'code'
lang: 'js'
meta: ''
value: '"function* g(){}"'
```
##### tr (97:9) => tableRow
```
type: 'html'
value: '<td><pre class="brush: js">function* g(){}</pre></td>',type: 'html'
value: '<td><pre class="brush: js">"function* g(){}"</pre></td>'
```
##### td (108:13) => tableCell
```
type: 'code'
lang: 'js'
meta: ''
value: 'a => a'
```
##### td (112:13) => tableCell
```
type: 'code'
lang: 'js'
meta: ''
value: '"a => a"'
```
##### tr (107:9) => tableRow
```
type: 'html'
value: '<td><pre class="brush: js">a => a</pre></td>',type: 'html'
value: '<td><pre class="brush: js">"a => a"</pre></td>'
```
##### td (118:13) => tableCell
```
type: 'code'
lang: 'js'
meta: ''
value: '({ a(){} }.a)'
```
##### td (122:13) => tableCell
```
type: 'code'
lang: 'js'
meta: ''
value: '"a(){}"'
```
##### tr (117:9) => tableRow
```
type: 'html'
value: '<td><pre class="brush: js">({ a(){} }.a)</pre></td>',type: 'html'
value: '<td><pre class="brush: js">"a(){}"</pre></td>'
```
##### td (128:13) => tableCell
```
type: 'code'
lang: 'js'
meta: ''
value: '({ *a(){} }.a)'
```
##### td (132:13) => tableCell
```
type: 'code'
lang: 'js'
meta: ''
value: '"*a(){}"'
```
##### tr (127:9) => tableRow
```
type: 'html'
value: '<td><pre class="brush: js">({ *a(){} }.a)</pre></td>',type: 'html'
value: '<td><pre class="brush: js">"*a(){}"</pre></td>'
```
##### td (138:13) => tableCell
```
type: 'code'
lang: 'js'
meta: ''
value: '({ [0](){} }[0])'
```
##### td (142:13) => tableCell
```
type: 'code'
lang: 'js'
meta: ''
value: '"[0](){}"'
```
##### tr (137:9) => tableRow
```
type: 'html'
value: '<td><pre class="brush: js">({ [0](){} }[0])</pre></td>',type: 'html'
value: '<td><pre class="brush: js">"[0](){}"</pre></td>'
```
##### td (148:13) => tableCell
```
type: 'code'
lang: 'js'
meta: ''
value: 'Object.getOwnPropertyDescriptor({     get a(){} }, "a").get'
```
##### td (154:13) => tableCell
```
type: 'code'
lang: 'js'
meta: ''
value: '"get a(){}"'
```
##### tr (147:9) => tableRow
```
type: 'html'
value: '<td><pre class="brush: js">Object.getOwnPropertyDescriptor({
    get a(){}
}, "a").get</pre></td>',type: 'html'
value: '<td><pre class="brush: js">"get a(){}"</pre></td>'
```
##### td (160:13) => tableCell
```
type: 'code'
lang: 'js'
meta: ''
value: 'Object.getOwnPropertyDescriptor({     set a(x){} }, "a").set'
```
##### td (166:13) => tableCell
```
type: 'code'
lang: 'js'
meta: ''
value: '"set a(x){}"'
```
##### tr (159:9) => tableRow
```
type: 'html'
value: '<td><pre class="brush: js">Object.getOwnPropertyDescriptor({
    set a(x){}
}, "a").set</pre></td>',type: 'html'
value: '<td><pre class="brush: js">"set a(x){}"</pre></td>'
```
##### td (172:13) => tableCell
```
type: 'code'
lang: 'js'
meta: ''
value: 'Function.prototype.toString'
```
##### td (176:13) => tableCell
```
type: 'code'
lang: 'js'
meta: ''
value: '"function toString() { [native code] }"'
```
##### tr (171:9) => tableRow
```
type: 'html'
value: '<td><pre class="brush: js">Function.prototype.toString</pre></td>',type: 'html'
value: '<td><pre class="brush: js">"function toString() { [native code] }"</pre></td>'
```
##### td (182:13) => tableCell
```
type: 'code'
lang: 'js'
meta: ''
value: '(function f(){}.bind(0))'
```
##### td (186:13) => tableCell
```
type: 'code'
lang: 'js'
meta: ''
value: '"function () { [native code] }"'
```
##### tr (181:9) => tableRow
```
type: 'html'
value: '<td><pre class="brush: js">(function f(){}.bind(0))</pre></td>',type: 'html'
value: '<td><pre class="brush: js">"function () { [native code] }"</pre></td>'
```
##### td (192:13) => tableCell
```
type: 'code'
lang: 'js'
meta: ''
value: 'Function("a", "b")'
```
##### td (196:13) => tableCell
```
type: 'code'
lang: 'js'
meta: ''
value: '"function anonymous(a\n) {\nb\n}"'
```
##### tr (191:9) => tableRow
```
type: 'html'
value: '<td><pre class="brush: js">Function("a", "b")</pre></td>',type: 'html'
value: '<td><pre class="brush: js">"function anonymous(a\n) {\nb\n}"</pre></td>'
```
##### table.standard-table (69:1) => table
```
type: 'html'
value: '<tr><th scope="col">Function</th><th scope="col">Function.prototype.toString result</th></tr>',type: 'html'
value: '<tr><td><pre class="brush: js">function f(){}</pre></td><td><pre class="brush: js">"function f(){}"</pre></td></tr>',type: 'html'
value: '<tr><td><pre class="brush: js">class A { a(){} }</pre></td><td><pre class="brush: js">"class A { a(){} }"</pre></td></tr>',type: 'html'
value: '<tr><td><pre class="brush: js">function* g(){}</pre></td><td><pre class="brush: js">"function* g(){}"</pre></td></tr>',type: 'html'
value: '<tr><td><pre class="brush: js">a => a</pre></td><td><pre class="brush: js">"a => a"</pre></td></tr>',type: 'html'
value: '<tr><td><pre class="brush: js">({ a(){} }.a)</pre></td><td><pre class="brush: js">"a(){}"</pre></td></tr>',type: 'html'
value: '<tr><td><pre class="brush: js">({ *a(){} }.a)</pre></td><td><pre class="brush: js">"*a(){}"</pre></td></tr>',type: 'html'
value: '<tr><td><pre class="brush: js">({ [0](){} }[0])</pre></td><td><pre class="brush: js">"[0](){}"</pre></td></tr>',type: 'html'
value: '<tr><td><pre class="brush: js">Object.getOwnPropertyDescriptor({
    get a(){}
}, "a").get</pre></td><td><pre class="brush: js">"get a(){}"</pre></td></tr>',type: 'html'
value: '<tr><td><pre class="brush: js">Object.getOwnPropertyDescriptor({
    set a(x){}
}, "a").set</pre></td><td><pre class="brush: js">"set a(x){}"</pre></td></tr>',type: 'html'
value: '<tr><td><pre class="brush: js">Function.prototype.toString</pre></td><td><pre class="brush: js">"function toString() { [native code] }"</pre></td></tr>',type: 'html'
value: '<tr><td><pre class="brush: js">(function f(){}.bind(0))</pre></td><td><pre class="brush: js">"function () { [native code] }"</pre></td></tr>',type: 'html'
value: '<tr><td><pre class="brush: js">Function("a", "b")</pre></td><td><pre class="brush: js">"function anonymous(a\n) {\nb\n}"</pre></td></tr>'
```
### Missing conversion rules
- th[scope="col"] (72:13)
- th[scope="col"] (73:13)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Generator/next](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Generator/next)
#### Invalid AST transformations
##### code (33:17) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'variable'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Generator/return](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Generator/return)
#### Invalid AST transformations
##### pre.brush:.js (21:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'value'
```
##### code (53:7) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'value'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Generator/throw](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Generator/throw)
#### Invalid AST transformations
##### dl (36:1) => paragraph
```
type: 'list'
ordered: 'false'
start: 

spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'Has the value '
      type: 'inlineCode'
      value: 'true'
      type: 'text'
      value: ' if the iterator is past the end of the iterated
sequence. In this case '
      type: 'inlineCode'
      value: 'value'
      type: 'text'
      value: ' optionally specifies the '
      type: 'emphasis'
      children: 
        type: 'text'
        value: 'return
value'
      type: 'text'
      value: ' of the iterator.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'Has the value '
      type: 'inlineCode'
      value: 'false'
      type: 'text'
      value: ' if the iterator was able to produce the next
value in the sequence. This is equivalent of not specifying the '
      type: 'inlineCode'
      value: 'done'
      type: 'text'
      value: '
property altogether.'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/GeneratorFunction](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/GeneratorFunction)
#### Invalid AST transformations
##### code (37:7) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'N'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/globalThis](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/globalThis)
#### Invalid AST transformations
##### span.seoSummary (17:4) => text
```
type: 'element'
tagName: 'a'
properties: 
  href: '/en-US/docs/Glossary/Global_object'
children: 
  type: 'text'
  value: 'global object'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Int16Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Int16Array)
#### Invalid AST transformations
##### pre.brush:.js (116:1) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: '// From a length
var int16 = new Int16Array(2);
int16[0] = 42;
console.log(int16[0]); // 42
console.log(int16.length); // 2
console.log(int16.BYTES_PER_ELEMENT); // 2

// From an array
var arr = new Int16Array([21,31]);
console.log(arr[1]); // 31

// From another TypedArray
var x = new Int16Array([21, 31]);
var y = new Int16Array(x);
console.log(y[0]); // 21

// From an ArrayBuffer
var buffer = new ArrayBuffer(8);
var z = new Int16Array(buffer, 0, 4);

// From an iterable
var iterable = function*(){ yield* [1,2,3]; }();
var int16 = new Int16Array(iterable);
// Int16Array[1, 2, 3]
'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Int16Array/Int16Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Int16Array/Int16Array)
#### Invalid AST transformations
##### code (51:26) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Int32Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Int32Array)
#### Invalid AST transformations
##### code (51:26) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Int32Array/Int32Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Int32Array/Int32Array)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'length'
```
##### code (46:26) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Int8Array/Int8Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Int8Array/Int8Array)
#### Invalid AST transformations
##### code (49:26) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/Collator/Collator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/Collator/Collator)
#### Invalid AST transformations
##### dl (76:3) => paragraph
```
type: 'blockquote'
children: 
  type: 'paragraph'
  children: 
    type: 'strong'
    children: 
      type: 'text'
      value: 'Note:'
    type: 'text'
    value: ' This option can also be set through the '
    type: 'inlineCode'
    value: 'kn'
    type: 'text'
    value: ' Unicode
extension key; if both are provided, this '
    type: 'inlineCode'
    value: 'options'
    type: 'text'
    value: '
property takes precedence.'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/DateTimeFormat/DateTimeFormat](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/DateTimeFormat/DateTimeFormat)
#### Invalid AST transformations
##### dl (69:3) => paragraph
```
type: 'list'
ordered: 'false'
start: 

spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: '"'
      type: 'inlineCode'
      value: 'full'
      type: 'text'
      value: '"'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: '"'
      type: 'inlineCode'
      value: 'long'
      type: 'text'
      value: '"'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: '"'
      type: 'inlineCode'
      value: 'medium'
      type: 'text'
      value: '"'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: '"'
      type: 'inlineCode'
      value: 'short'
      type: 'text'
      value: '"',type: 'blockquote'
children: 
  type: 'paragraph'
  children: 
    type: 'strong'
    children: 
      type: 'text'
      value: 'Note:'
    type: 'text'
    value: ' '
    type: 'inlineCode'
    value: 'dateStyle'
    type: 'text'
    value: ' can be used with '
    type: 'inlineCode'
    value: 'timeStyle'
    type: 'text'
    value: ', but
not with other options (e.g. '
    type: 'inlineCode'
    value: 'weekday'
    type: 'text'
    value: ',
'
    type: 'inlineCode'
    value: 'hour'
    type: 'text'
    value: ', '
    type: 'inlineCode'
    value: 'month'
    type: 'text'
    value: ', etc.).'
```
##### dl (176:3) => paragraph
```
type: 'list'
ordered: 'false'
start: 

spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: '"'
      type: 'inlineCode'
      value: 'long'
      type: 'text'
      value: '" (e.g., '
      type: 'inlineCode'
      value: 'Thursday'
      type: 'text'
      value: ')'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: '"'
      type: 'inlineCode'
      value: 'short'
      type: 'text'
      value: '" (e.g., '
      type: 'inlineCode'
      value: 'Thu'
      type: 'text'
      value: ')'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: '"'
      type: 'inlineCode'
      value: 'narrow'
      type: 'text'
      value: '" (e.g., '
      type: 'inlineCode'
      value: 'T'
      type: 'text'
      value: '). Two weekdays may
have the same narrow style for some locales (e.g.
'
      type: 'inlineCode'
      value: 'Tuesday'
      type: 'text'
      value: ''s narrow style is also '
      type: 'inlineCode'
      value: 'T'
      type: 'text'
      value: ').'
```
### Missing conversion rules
- p.noinclude (253:3)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/DateTimeFormat](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/DateTimeFormat)
#### Invalid AST transformations
##### pre.brush:.js (69:1) => text
```
type: 'element'
tagName: 'span'
properties: 
  dir: 'rtl'
children: 
  type: 'text'
  value: '‏/١٢‏/٢٠١٢'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/DisplayNames/DisplayNames](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/DisplayNames/DisplayNames)
#### Invalid AST transformations
##### dl (59:3) => paragraph
```
type: 'list'
ordered: 'false'
start: 

spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: '"'
      type: 'inlineCode'
      value: 'narrow'
      type: 'text'
      value: '"'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: '"'
      type: 'inlineCode'
      value: 'short'
      type: 'text'
      value: '"'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: '"'
      type: 'inlineCode'
      value: 'long'
      type: 'text'
      value: '"'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/DisplayNames/of](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/DisplayNames/of)
#### Invalid AST transformations
##### dl (31:1) => paragraph
```
type: 'list'
ordered: 'false'
start: 

spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'If the type is "region", code should be either an '
      type: 'link'
      title: 

      url: 'https://www.iso.org/iso-3166-country-codes.html'
      children: 
        type: 'text'
        value: 'ISO-3166 two letters region code'
      type: 'text'
      value: ', or a '
      type: 'link'
      title: 

      url: 'https://unstats.un.org/unsd/methodology/m49/'
      children: 
        type: 'text'
        value: 'three digits UN M49 Geographic Regions'
      type: 'text'
      value: '.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'If the type is "script", code should be an '
      type: 'link'
      title: 

      url: 'http://unicode.org/iso15924/iso15924-codes.html'
      children: 
        type: 'text'
        value: 'ISO-15924 four letters script code'
      type: 'text'
      value: '.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'If the type is "language", code should be a '
      type: 'emphasis'
      children: 
        type: 'text'
        value: 'languageCode'
      type: 'text'
      value: ' ["-"
'
      type: 'emphasis'
      children: 
        type: 'text'
        value: 'scriptCode'
      type: 'text'
      value: '] ["-" '
      type: 'emphasis'
      children: 
        type: 'text'
        value: 'regionCode'
      type: 'text'
      value: ' ] *("-" '
      type: 'emphasis'
      children: 
        type: 'text'
        value: 'variant'
      type: 'text'
      value: ' )
subsequence of the unicode_language_id grammar in '
      type: 'link'
      title: 

      url: 'http://unicode.org/reports/tr35/#Unicode_language_identifier'
      children: 
        type: 'text'
        value: 'UTS 35's Unicode Language and Locale Identifiers
grammar'
      type: 'text'
      value: '. '
      type: 'emphasis'
      children: 
        type: 'text'
        value: 'languageCode'
      type: 'text'
      value: ' is either a two letters ISO 639-1
language code or a three letters ISO 639-2 language code.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'If the type is "currency", code should be a '
      type: 'link'
      title: 

      url: 'https://www.iso.org/iso-4217-currency-codes.html'
      children: 
        type: 'text'
        value: '3-letter ISO 4217 currency code'
      type: 'text'
      value: '.'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/getCanonicalLocales](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/getCanonicalLocales)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'locales'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/ListFormat/resolvedOptions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/ListFormat/resolvedOptions)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'listFormat'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/Locale/calendar](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/Locale/calendar)
#### Invalid AST transformations
##### tr (29:3) => tableRow
```
type: 'html'
value: '<th scope="col">Calendar key (name)</th>',type: 'html'
value: '<th scope="col">Description</th>'
```
##### td (108:4) => tableCell
```
type: 'blockquote'
children: 
  type: 'paragraph'
  children: 
    type: 'strong'
    children: 
      type: 'text'
      value: 'Warning:'
    type: 'text'
    value: ' The '
    type: 'inlineCode'
    value: 'islamicc'
    type: 'text'
    value: ' calendar key has been deprecated. Please use '
    type: 'inlineCode'
    value: 'islamic-civil'
    type: 'text'
    value: '.',type: 'paragraph'
summary: 'The Intl.Locale.prototype.calendar property is an accessor property which returns the type of calendar used in the Locale.'
shouldWrap: 'true'
children: 
  type: 'inlineCode'
  value: 'islamicc'
```
##### tr (107:3) => tableRow
```
type: 'html'
value: '<td><div class="notecard warning"><p><strong>Warning:</strong> The <code>islamicc</code> calendar key has been deprecated. Please use <code>islamic-civil</code>.</p></div><p><code>islamicc</code></p></td>'
```
##### table.standard-table (26:1) => table
```
type: 'text'
value: 'Unicode calendar keys',type: 'html'
value: '<tr><th scope="col">Calendar key (name)</th><th scope="col">Description</th></tr>',type: 'html'
value: '<tr><td><div class="notecard warning"><p><strong>Warning:</strong> The <code>islamicc</code> calendar key has been deprecated. Please use <code>islamic-civil</code>.</p></div><p><code>islamicc</code></p></td><td>Civil (algorithmic) Arabic calendar</td></tr>'
```
### Missing conversion rules
- th[scope="col"] (30:4)
- th[scope="col"] (31:4)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/Locale/caseFirst](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/Locale/caseFirst)
#### Invalid AST transformations
##### tr (30:3) => tableRow
```
type: 'html'
value: '<th scope="col">Value</th>',type: 'html'
value: '<th scope="col">Description</th>'
```
##### table.standard-table (28:1) => table
```
type: 'html'
value: '<tr><th scope="col">Value</th><th scope="col">Description</th></tr>'
```
### Missing conversion rules
- th[scope="col"] (31:4)
- th[scope="col"] (32:4)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/Locale/collation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/Locale/collation)
#### Invalid AST transformations
##### span.seoSummary (18:4) => text
```
type: 'element'
tagName: 'a'
properties: 
  href: 'https://www.unicode.org/reports/tr35/tr35-collation.html#CLDR_Collation'
children: 
  type: 'text'
  value: 'collation type'
```
##### tr (30:3) => tableRow
```
type: 'html'
value: '<th scope="col">Collation Type</th>',type: 'html'
value: '<th scope="col">Description</th>'
```
##### td (49:4) => tableCell
```
type: 'blockquote'
children: 
  type: 'paragraph'
  children: 
    type: 'strong'
    children: 
      type: 'text'
      value: 'Warning:'
    type: 'text'
    value: ' The '
    type: 'inlineCode'
    value: 'direct'
    type: 'text'
    value: ' collation type has been deprected. Do not use.',type: 'paragraph'
summary: 'The Intl.Locale.prototype.collation property is an accessor property that returns the collation type for the Locale, which is used to order strings according to the locale's rules.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'direct'
```
##### tr (48:3) => tableRow
```
type: 'html'
value: '<td><div class="notecard warning"><p><strong>Warning:</strong> The <code>direct</code> collation type has been deprected. Do not use.</p></div><p>direct</p></td>'
```
##### td (115:4) => tableCell
```
type: 'paragraph'
summary: 'The Intl.Locale.prototype.collation property is an accessor property that returns the collation type for the Locale, which is used to order strings according to the locale's rules.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Pinyin ordering for Latin, zhuyin order for Bopomofo and CJK characters (used in Chinese)'
```
##### tr (113:3) => tableRow
```
type: 'html'
value: '<td><p>Pinyin ordering for Latin, zhuyin order for Bopomofo and CJK characters (used in Chinese)</p></td>'
```
##### table.standard-table (28:1) => table
```
type: 'html'
value: '<tr><th scope="col">Collation Type</th><th scope="col">Description</th></tr>',type: 'html'
value: '<tr><td><div class="notecard warning"><p><strong>Warning:</strong> The <code>direct</code> collation type has been deprected. Do not use.</p></div><p>direct</p></td><td>Binary code point order (used in Hindi)</td></tr>',type: 'html'
value: '<tr><td>zhuyin</td><td><p>Pinyin ordering for Latin, zhuyin order for Bopomofo and CJK characters (used in Chinese)</p></td></tr>'
```
### Missing conversion rules
- th[scope="col"] (31:4)
- th[scope="col"] (32:4)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/Locale/hourCycle](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/Locale/hourCycle)
#### Invalid AST transformations
##### tr (28:3) => tableRow
```
type: 'html'
value: '<th scope="col">Hour cycle type</th>',type: 'html'
value: '<th scope="col">Description</th>'
```
##### table.standard-table (26:1) => table
```
type: 'html'
value: '<tr><th scope="col">Hour cycle type</th><th scope="col">Description</th></tr>'
```
### Missing conversion rules
- th[scope="col"] (29:4)
- th[scope="col"] (30:4)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/Locale/maximize](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/Locale/maximize)
### Missing conversion rules
- span.seoSummary (17:4)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/Locale/minimize](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/Locale/minimize)
### Missing conversion rules
- span.seoSummary (16:4)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/Locale/numberingSystem](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/Locale/numberingSystem)
#### Invalid AST transformations
##### span.seoSummary (18:4) => text
```
type: 'element'
tagName: 'a'
properties: 
  href: 'https://en.wikipedia.org/wiki/Numeral_system'
children: 
  type: 'text'
  value: 'numeral system'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/Locale/toString](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/Locale/toString)
#### Invalid AST transformations
##### span.seoSummary (17:4) => text
```
type: 'element'
tagName: 'a'
properties: 
  href: 'https://www.unicode.org/reports/tr35/#Unicode_locale_identifier'
children: 
  type: 'text'
  value: 'locale
identifier string'
```
### Missing conversion rules
- var (32:8)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/NumberFormat/NumberFormat](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/NumberFormat/NumberFormat)
#### Invalid AST transformations
##### dl (76:3) => paragraph
```
type: 'list'
ordered: 'false'
start: 

spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: '"'
      type: 'inlineCode'
      value: 'symbol'
      type: 'text'
      value: '" to use a localized currency symbol such as
€, this is the default value,'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: '"'
      type: 'inlineCode'
      value: 'narrowSymbol'
      type: 'text'
      value: '" to use a narrow format symbol ("$100"
rather than "US$100"),'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: '"'
      type: 'inlineCode'
      value: 'code'
      type: 'text'
      value: '" to use the ISO currency code,'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: '"'
      type: 'inlineCode'
      value: 'name'
      type: 'text'
      value: '" to use a localized currency name such as
"'
      type: 'inlineCode'
      value: 'dollar'
      type: 'text'
      value: '",'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/PluralRules/PluralRules](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/PluralRules/PluralRules)
#### Invalid AST transformations
##### dl (41:3) => paragraph
```
type: 'list'
ordered: 'false'
start: 

spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: '"'
      type: 'inlineCode'
      value: 'cardinal'
      type: 'text'
      value: '" for cardinal numbers (refering to the
quantity of things). This is the default value.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: '"'
      type: 'inlineCode'
      value: 'ordinal'
      type: 'text'
      value: '" for ordinal number (refering to the
ordering or ranking of things, e.g. "1st", "2nd", "3rd" in
English).'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/RelativeTimeFormat/RelativeTimeFormat](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/RelativeTimeFormat/RelativeTimeFormat)
#### Invalid AST transformations
##### dl (39:3) => paragraph
```
type: 'list'
ordered: 'false'
start: 

spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: '"'
      type: 'inlineCode'
      value: 'always'
      type: 'text'
      value: '" (default, e.g., '
      type: 'inlineCode'
      value: '1 day ago'
      type: 'text'
      value: '),'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'or "'
      type: 'inlineCode'
      value: 'auto'
      type: 'text'
      value: '" (e.g., '
      type: 'inlineCode'
      value: 'yesterday'
      type: 'text'
      value: '). The "'
      type: 'inlineCode'
      value: 'auto'
      type: 'text'
      value: '" value allows to not always have to use numeric values in the output.'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/RelativeTimeFormat/resolvedOptions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/RelativeTimeFormat/resolvedOptions)
#### Invalid AST transformations
##### dl (36:1) => paragraph
```
type: 'list'
ordered: 'false'
start: 

spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: '"'
      type: 'inlineCode'
      value: 'long'
      type: 'text'
      value: '" (default, e.g., '
      type: 'inlineCode'
      value: 'in 1 month'
      type: 'text'
      value: ')'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: '"'
      type: 'inlineCode'
      value: 'short'
      type: 'text'
      value: '" (e.g., '
      type: 'inlineCode'
      value: 'in 1 mo.'
      type: 'text'
      value: '),'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'or "'
      type: 'inlineCode'
      value: 'narrow'
      type: 'text'
      value: '" (e.g., '
      type: 'inlineCode'
      value: 'in 1 mo.'
      type: 'text'
      value: '). The narrow style could be similar to the short style for some locales.'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/isFinite](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/isFinite)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'testValue'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON)
#### Invalid AST transformations
##### span.seoSummary (15:4) => text
```
type: 'element'
tagName: 'a'
properties: 
  href: 'https://json.org/'
children: 
  type: 'text'
  value: 'JavaScript Object
Notation'
```
##### pre.brush:.js (64:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'JSON'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/stringify](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/stringify)
#### Invalid AST transformations
##### dl (34:1) => paragraph
```
type: 'paragraph'
summary: 'The JSON.stringify() method converts a JavaScript object
  or value to a JSON string, optionally replacing values if a replacer function is
  specified or optionally including only the specified properties if a replacer array is
  specified.'
children: 
  type: 'text'
  value: 'If this is a '
  type: 'inlineCode'
  value: 'Number'
  type: 'text'
  value: ', it indicates the number of space characters to
use as white space; this number is capped at 10 (if it is greater, the value is just
'
  type: 'inlineCode'
  value: '10'
  type: 'text'
  value: '). Values less than 1 indicate that no space should be used.',type: 'paragraph'
summary: 'The JSON.stringify() method converts a JavaScript object
  or value to a JSON string, optionally replacing values if a replacer function is
  specified or optionally including only the specified properties if a replacer array is
  specified.'
children: 
  type: 'text'
  value: 'If this is a '
  type: 'inlineCode'
  value: 'String'
  type: 'text'
  value: ', the string (or the first 10 characters of the
string, if it's longer than that) is used as white space. If this parameter is not
provided (or is {{SlN4UmVmKCJudWxsIik=}}), no white space is used.'
```
### Missing conversion rules
- var (169:65)
- var (170:3)
- var (218:47)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map/@@iterator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map/@@iterator)
#### Invalid AST transformations
##### pre.brush:.js (26:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'myMap'
```
### Missing conversion rules
- p.seoSummary (17:1)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map)
#### Invalid AST transformations
##### code (25:3) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'key'
```
##### tr (54:5) => tableRow
```
type: 'html'
value: '<th scope="row"></th>',type: 'html'
value: '<th scope="col">Map</th>',type: 'html'
value: '<th scope="col">Object</th>'
```
##### td (65:7) => tableCell
```
type: 'paragraph'
summary: 'The Map object holds key-value
    pairs and remembers the original insertion order of the keys. Any value (both
  objects and {{Z2xvc3NhcnkoIlByaW1pdGl2ZSIsICJwcmltaXRpdmUgdmFsdWVzIik=}}) may be used as either a key
  or a value.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'An '
  type: 'inlineCode'
  value: 'Object'
  type: 'text'
  value: ' has a prototype, so it contains default keys that could collide with your own keys if you're not careful.',type: 'blockquote'
children: 
  type: 'paragraph'
  children: 
    type: 'strong'
    children: 
      type: 'text'
      value: 'Note:'
    type: 'text'
    value: ' As of ES5, this can be bypassed by using {{anN4cmVmKCJPYmplY3QuY3JlYXRlIiwgIk9iamVjdC5jcmVhdGUobnVsbCkiKQ==}}, but this is seldom done.'
```
##### tr (61:5) => tableRow
```
type: 'html'
value: '<th scope="row">Accidental Keys</th>',type: 'html'
value: '<td><p>An <code>Object</code> has a prototype, so it contains default keys that could
collide with your own keys if you're not careful.</p><div class="notecard note"><p><strong>Note:</strong> As of ES5, this can be bypassed by using
{{anN4cmVmKCJPYmplY3QuY3JlYXRlIiwgIk9iamVjdC5jcmVhdGUobnVsbCkiKQ==}}, but this is seldom done.</p></div></td>'
```
##### tr (76:5) => tableRow
```
type: 'html'
value: '<th scope="row">Key Types</th>'
```
##### td (85:7) => tableCell
```
type: 'paragraph'
summary: 'The Map object holds key-value
    pairs and remembers the original insertion order of the keys. Any value (both
  objects and {{Z2xvc3NhcnkoIlByaW1pdGl2ZSIsICJwcmltaXRpdmUgdmFsdWVzIik=}}) may be used as either a key
  or a value.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'The keys in '
  type: 'inlineCode'
  value: 'Map'
  type: 'text'
  value: ' are ordered in a simple, straightforward way: A '
  type: 'inlineCode'
  value: 'Map'
  type: 'text'
  value: ' object iterates entries, keys, and values in the order of entry insertion.'
```
##### td (90:7) => tableCell
```
type: 'paragraph'
summary: 'The Map object holds key-value
    pairs and remembers the original insertion order of the keys. Any value (both
  objects and {{Z2xvc3NhcnkoIlByaW1pdGl2ZSIsICJwcmltaXRpdmUgdmFsdWVzIik=}}) may be used as either a key
  or a value.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Although the keys of an ordinary '
  type: 'inlineCode'
  value: 'Object'
  type: 'text'
  value: ' are ordered now, this was not always the case, and the order is complex. As a result, it's best not to rely on property order.',type: 'paragraph'
summary: 'The Map object holds key-value
    pairs and remembers the original insertion order of the keys. Any value (both
  objects and {{Z2xvc3NhcnkoIlByaW1pdGl2ZSIsICJwcmltaXRpdmUgdmFsdWVzIik=}}) may be used as either a key
  or a value.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'The order was first defined for own properties only in ECMAScript 2015; ECMAScript 2020 defines order for inherited properties as well. See the '
  type: 'link'
  title: 

  url: 'https://tc39.es/ecma262/#sec-ordinaryownpropertykeys'
  children: 
    type: 'text'
    value: 'OrdinaryOwnPropertyKeys'
  type: 'text'
  value: ' and '
  type: 'link'
  title: 

  url: 'https://tc39.es/ecma262/#sec-enumerate-object-properties'
  children: 
    type: 'text'
    value: 'EnumerateObjectProperties'
  type: 'text'
  value: ' abstract specification operations. But note that no single mechanism iterates '
  type: 'strong'
  children: 
    type: 'text'
    value: 'all'
  type: 'text'
  value: ' of an object's properties; the various mechanisms each include different subsets of properties. ({{anN4cmVmKCJTdGF0ZW1lbnRzL2Zvci4uLmluIiwKICAgICAgICAgICJmb3ItaW4iKQ==}} includes only enumerable string-keyed properties; {{anN4cmVmKCJPYmplY3Qua2V5cyIp}} includes only own, enumerable, string-keyed properties; {{anN4cmVmKCJPYmplY3QuZ2V0T3duUHJvcGVydHlOYW1lcyIp}} includes own, string-keyed properties even if non-enumerable; {{anN4cmVmKCJPYmplY3QuZ2V0T3duUHJvcGVydHlTeW1ib2xzIik=}} does the same for just '
  type: 'inlineCode'
  value: 'Symbol'
  type: 'text'
  value: '-keyed properties, etc.)'
```
##### tr (83:5) => tableRow
```
type: 'html'
value: '<th scope="row">Key Order</th>',type: 'html'
value: '<td><p>The keys in <code>Map</code> are ordered in a simple, straightforward way: A
<code>Map</code> object iterates entries, keys, and values in the order of entry
insertion.</p></td>',type: 'html'
value: '<td><p>Although the keys of an ordinary <code>Object</code> are ordered now, this was not always the case, and the order is complex. As a result, it's best not to rely
on property order.</p><p>The order was first defined for own properties only in ECMAScript 2015;
ECMAScript 2020 defines order for inherited properties as well. See the <a href="https://tc39.es/ecma262/#sec-ordinaryownpropertykeys">OrdinaryOwnPropertyKeys</a>
and <a href="https://tc39.es/ecma262/#sec-enumerate-object-properties">EnumerateObjectProperties</a>
abstract specification operations. But note that no single mechanism iterates
<strong>all</strong> of an object's properties; the various mechanisms each
include different subsets of properties. ({{anN4cmVmKCJTdGF0ZW1lbnRzL2Zvci4uLmluIiwKICAgICAgICAgICJmb3ItaW4iKQ==}} includes only enumerable string-keyed properties;
{{anN4cmVmKCJPYmplY3Qua2V5cyIp}} includes only own, enumerable, string-keyed
properties; {{anN4cmVmKCJPYmplY3QuZ2V0T3duUHJvcGVydHlOYW1lcyIp}} includes own, string-keyed
properties even if non-enumerable; {{anN4cmVmKCJPYmplY3QuZ2V0T3duUHJvcGVydHlTeW1ib2xzIik=}}
does the same for just <code>Symbol</code>-keyed properties, etc.)</p></td>'
```
##### tr (108:5) => tableRow
```
type: 'html'
value: '<th scope="row"><p>Size</p></th>'
```
##### td (121:7) => tableCell
```
type: 'paragraph'
summary: 'The Map object holds key-value
    pairs and remembers the original insertion order of the keys. Any value (both
  objects and {{Z2xvc3NhcnkoIlByaW1pdGl2ZSIsICJwcmltaXRpdmUgdmFsdWVzIik=}}) may be used as either a key
  or a value.'
shouldWrap: 'true'
children: 
  type: 'inlineCode'
  value: 'Object'
  type: 'text'
  value: ' does not implement an '
  type: 'link'
  title: 

  url: '/en-US/docs/Web/JavaScript/Reference/Iteration_protocols#the_iterable_protocol'
  children: 
    type: 'text'
    value: 'iteration protocol'
  type: 'text'
  value: ', and so objects are not directly iterable using the JavaScript '
  type: 'link'
  title: 

  url: '/en-US/docs/Web/JavaScript/Reference/Statements/for...of'
  children: 
    type: 'text'
    value: 'for...of'
  type: 'text'
  value: ' statement (by default).',type: 'blockquote'
children: 
  type: 'paragraph'
  children: 
    type: 'strong'
    children: 
      type: 'text'
      value: 'Note:'
  type: 'list'
  ordered: 'false'
  start: 

  spread: 'false'
  children: 
    type: 'listItem'
    spread: 'false'
    children: 
      type: 'paragraph'
      children: 
        type: 'text'
        value: 'An object can implement the iteration protocol, or you can get an iterable for an object using '
        type: 'link'
        title: 

        url: '/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys'
        children: 
          type: 'inlineCode'
          value: 'Object.keys'
        type: 'text'
        value: ' or '
        type: 'link'
        title: 

        url: '/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/entries'
        children: 
          type: 'inlineCode'
          value: 'Object.entries'
        type: 'text'
        value: '.'
    type: 'listItem'
    spread: 'false'
    children: 
      type: 'paragraph'
      children: 
        type: 'text'
        value: 'The '
        type: 'link'
        title: 

        url: '/en-US/docs/Web/JavaScript/Reference/Statements/for...in'
        children: 
          type: 'text'
          value: 'for...in'
        type: 'text'
        value: ' statement allows you to iterate over the '
        type: 'emphasis'
        children: 
          type: 'text'
          value: 'enumerable'
        type: 'text'
        value: ' properties of an object.'
```
##### tr (116:5) => tableRow
```
type: 'html'
value: '<th scope="row">Iteration</th>',type: 'html'
value: '<td><p><code>Object</code> does not implement an <a href="/en-US/docs/Web/JavaScript/Reference/Iteration_protocols#the_iterable_protocol">iteration
protocol</a>, and so objects are not directly iterable using the JavaScript <a href="/en-US/docs/Web/JavaScript/Reference/Statements/for...of">for...of</a>
statement (by default).</p><div class="notecard note"><p><strong>Note:</strong></p><ul><li>An object can implement the iteration protocol, or you can get an iterable
for an object using <a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys"><code>Object.keys</code></a> or <a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/entries"><code>Object.entries</code></a>.</li><li>The <a href="/en-US/docs/Web/JavaScript/Reference/Statements/for...in">for...in</a>
statement allows you to iterate over the <em>enumerable</em> properties of
an object.</li></ul></div></td>'
```
##### td (147:7) => tableCell
```
type: 'paragraph'
summary: 'The Map object holds key-value
    pairs and remembers the original insertion order of the keys. Any value (both
  objects and {{Z2xvc3NhcnkoIlByaW1pdGl2ZSIsICJwcmltaXRpdmUgdmFsdWVzIik=}}) may be used as either a key
  or a value.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Performs better in scenarios involving frequent additions and removals of key-value pairs.'
```
##### td (151:7) => tableCell
```
type: 'paragraph'
summary: 'The Map object holds key-value
    pairs and remembers the original insertion order of the keys. Any value (both
  objects and {{Z2xvc3NhcnkoIlByaW1pdGl2ZSIsICJwcmltaXRpdmUgdmFsdWVzIik=}}) may be used as either a key
  or a value.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Not optimized for frequent additions and removals of key-value pairs.'
```
##### tr (145:5) => tableRow
```
type: 'html'
value: '<th scope="row">Performance</th>',type: 'html'
value: '<td><p>Performs better in scenarios involving frequent additions and removals of
key-value pairs.</p></td>',type: 'html'
value: '<td><p>Not optimized for frequent additions and removals of key-value pairs.</p></td>'
```
##### td (157:7) => tableCell
```
type: 'paragraph'
summary: 'The Map object holds key-value
    pairs and remembers the original insertion order of the keys. Any value (both
  objects and {{Z2xvc3NhcnkoIlByaW1pdGl2ZSIsICJwcmltaXRpdmUgdmFsdWVzIik=}}) may be used as either a key
  or a value.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'No native support for serialization or parsing.',type: 'paragraph'
summary: 'The Map object holds key-value
    pairs and remembers the original insertion order of the keys. Any value (both
  objects and {{Z2xvc3NhcnkoIlByaW1pdGl2ZSIsICJwcmltaXRpdmUgdmFsdWVzIik=}}) may be used as either a key
  or a value.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: '(But you can build your own serialization and parsing support for '
  type: 'inlineCode'
  value: 'Map'
  type: 'text'
  value: ' by using {{anN4cmVmKCJKU09OLnN0cmluZ2lmeSgpIik=}} with its '
  type: 'emphasis'
  children: 
    type: 'text'
    value: 'replacer'
  type: 'text'
  value: ' argument, and by using {{anN4cmVmKCJKU09OLnBhcnNlKCkiKQ==}} with its '
  type: 'emphasis'
  children: 
    type: 'text'
    value: 'reviver'
  type: 'text'
  value: ' argument. See the Stack Overflow question '
  type: 'link'
  title: 

  url: 'https://stackoverflow.com/q/29085197/'
  children: 
    type: 'text'
    value: 'How do you JSON.stringify an ES6 Map?'
  type: 'text'
  value: ').'
```
##### td (161:7) => tableCell
```
type: 'paragraph'
summary: 'The Map object holds key-value
    pairs and remembers the original insertion order of the keys. Any value (both
  objects and {{Z2xvc3NhcnkoIlByaW1pdGl2ZSIsICJwcmltaXRpdmUgdmFsdWVzIik=}}) may be used as either a key
  or a value.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Native support for serialization from {{anN4cmVmKCJPYmplY3QiKQ==}} to JSON, using {{anN4cmVmKCJKU09OLnN0cmluZ2lmeSgpIik=}}.',type: 'paragraph'
summary: 'The Map object holds key-value
    pairs and remembers the original insertion order of the keys. Any value (both
  objects and {{Z2xvc3NhcnkoIlByaW1pdGl2ZSIsICJwcmltaXRpdmUgdmFsdWVzIik=}}) may be used as either a key
  or a value.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'Native support for parsing from JSON to {{anN4cmVmKCJPYmplY3QiKQ==}}, using {{anN4cmVmKCJKU09OLnBhcnNlKCkiKQ==}}.'
```
##### tr (155:5) => tableRow
```
type: 'html'
value: '<th scope="row">Serialization and parsing</th>',type: 'html'
value: '<td><p>No native support for serialization or parsing.</p><p>(But you can build your own serialization and parsing support for <code>Map</code> by using {{anN4cmVmKCJKU09OLnN0cmluZ2lmeSgpIik=}} with its <em>replacer</em> argument, and by using {{anN4cmVmKCJKU09OLnBhcnNlKCkiKQ==}} with its <em>reviver</em> argument. See the Stack Overflow question <a href="https://stackoverflow.com/q/29085197/">How do you JSON.stringify an ES6 Map?</a>).</p></td>',type: 'html'
value: '<td><p>Native support for serialization from {{anN4cmVmKCJPYmplY3QiKQ==}} to JSON, using {{anN4cmVmKCJKU09OLnN0cmluZ2lmeSgpIik=}}.</p><p>Native support for parsing from JSON to {{anN4cmVmKCJPYmplY3QiKQ==}}, using {{anN4cmVmKCJKU09OLnBhcnNlKCkiKQ==}}.</p></td>'
```
##### table.standard-table (52:1) => table
```
type: 'html'
value: '<tr><th scope="row"></th><th scope="col">Map</th><th scope="col">Object</th></tr>',type: 'html'
value: '<tr><th scope="row">Accidental Keys</th><td>A <code>Map</code> does not contain any keys by default. It only contains what
is explicitly put into it.</td><td><p>An <code>Object</code> has a prototype, so it contains default keys that could
collide with your own keys if you're not careful.</p><div class="notecard note"><p><strong>Note:</strong> As of ES5, this can be bypassed by using
{{anN4cmVmKCJPYmplY3QuY3JlYXRlIiwgIk9iamVjdC5jcmVhdGUobnVsbCkiKQ==}}, but this is seldom done.</p></div></td></tr>',type: 'html'
value: '<tr><th scope="row">Key Types</th><td>A <code>Map</code>'s keys can be any value (including functions, objects, or any
primitive).</td><td>The keys of an <code>Object</code> must be either a {{anN4cmVmKCJTdHJpbmciKQ==}} or a
{{anN4cmVmKCJTeW1ib2wiKQ==}}.</td></tr>',type: 'html'
value: '<tr><th scope="row">Key Order</th><td><p>The keys in <code>Map</code> are ordered in a simple, straightforward way: A
<code>Map</code> object iterates entries, keys, and values in the order of entry
insertion.</p></td><td><p>Although the keys of an ordinary <code>Object</code> are ordered now, this was not always the case, and the order is complex. As a result, it's best not to rely
on property order.</p><p>The order was first defined for own properties only in ECMAScript 2015;
ECMAScript 2020 defines order for inherited properties as well. See the <a href="https://tc39.es/ecma262/#sec-ordinaryownpropertykeys">OrdinaryOwnPropertyKeys</a>
and <a href="https://tc39.es/ecma262/#sec-enumerate-object-properties">EnumerateObjectProperties</a>
abstract specification operations. But note that no single mechanism iterates
<strong>all</strong> of an object's properties; the various mechanisms each
include different subsets of properties. ({{anN4cmVmKCJTdGF0ZW1lbnRzL2Zvci4uLmluIiwKICAgICAgICAgICJmb3ItaW4iKQ==}} includes only enumerable string-keyed properties;
{{anN4cmVmKCJPYmplY3Qua2V5cyIp}} includes only own, enumerable, string-keyed
properties; {{anN4cmVmKCJPYmplY3QuZ2V0T3duUHJvcGVydHlOYW1lcyIp}} includes own, string-keyed
properties even if non-enumerable; {{anN4cmVmKCJPYmplY3QuZ2V0T3duUHJvcGVydHlTeW1ib2xzIik=}}
does the same for just <code>Symbol</code>-keyed properties, etc.)</p></td></tr>',type: 'html'
value: '<tr><th scope="row"><p>Size</p></th><td>The number of items in a <code>Map</code> is easily retrieved from its
{{anN4cmVmKCJNYXAucHJvdG90eXBlLnNpemUiLCAic2l6ZSIp}} property.</td><td>The number of items in an <code>Object</code> must be determined manually.</td></tr>',type: 'html'
value: '<tr><th scope="row">Iteration</th><td>A <code>Map</code> is an <a href="/en-US/docs/Web/JavaScript/Reference/Iteration_protocols">iterable</a>, so it can be
directly iterated.</td><td><p><code>Object</code> does not implement an <a href="/en-US/docs/Web/JavaScript/Reference/Iteration_protocols#the_iterable_protocol">iteration
protocol</a>, and so objects are not directly iterable using the JavaScript <a href="/en-US/docs/Web/JavaScript/Reference/Statements/for...of">for...of</a>
statement (by default).</p><div class="notecard note"><p><strong>Note:</strong></p><ul><li>An object can implement the iteration protocol, or you can get an iterable
for an object using <a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys"><code>Object.keys</code></a> or <a href="/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/entries"><code>Object.entries</code></a>.</li><li>The <a href="/en-US/docs/Web/JavaScript/Reference/Statements/for...in">for...in</a>
statement allows you to iterate over the <em>enumerable</em> properties of
an object.</li></ul></div></td></tr>',type: 'html'
value: '<tr><th scope="row">Performance</th><td><p>Performs better in scenarios involving frequent additions and removals of
key-value pairs.</p></td><td><p>Not optimized for frequent additions and removals of key-value pairs.</p></td></tr>',type: 'html'
value: '<tr><th scope="row">Serialization and parsing</th><td><p>No native support for serialization or parsing.</p><p>(But you can build your own serialization and parsing support for <code>Map</code> by using {{anN4cmVmKCJKU09OLnN0cmluZ2lmeSgpIik=}} with its <em>replacer</em> argument, and by using {{anN4cmVmKCJKU09OLnBhcnNlKCkiKQ==}} with its <em>reviver</em> argument. See the Stack Overflow question <a href="https://stackoverflow.com/q/29085197/">How do you JSON.stringify an ES6 Map?</a>).</p></td><td><p>Native support for serialization from {{anN4cmVmKCJPYmplY3QiKQ==}} to JSON, using {{anN4cmVmKCJKU09OLnN0cmluZ2lmeSgpIik=}}.</p><p>Native support for parsing from JSON to {{anN4cmVmKCJPYmplY3QiKQ==}}, using {{anN4cmVmKCJKU09OLnBhcnNlKCkiKQ==}}.</p></td></tr>'
```
##### code (193:3) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'key'
```
##### code (236:5) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'key'
```
##### code (254:7) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'key'
```
##### code (264:7) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'key'
```
### Missing conversion rules
- th[scope="row"] (55:7)
- th[scope="col"] (56:7)
- th[scope="col"] (57:7)
- th[scope="row"] (62:7)
- th[scope="row"] (77:7)
- th[scope="row"] (84:7)
- th[scope="row"] (109:7)
- th[scope="row"] (117:7)
- th[scope="row"] (146:7)
- th[scope="row"] (156:7)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/abs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/abs)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'x'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/acos](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/acos)
#### Invalid AST transformations
##### pre.brush:.js (77:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'x'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/acosh](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/acosh)
#### Invalid AST transformations
##### pre.brush:.js (66:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'x'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/asin](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/asin)
### Missing conversion rules
- var (124:23)
- var (124:70)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/atan](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/atan)
#### Invalid AST transformations
##### pre.brush:.js (119:1) => text
```
type: 'element'
tagName: 'span'
properties: 
  className: 
    'objectBox'
    'objectBox-number'
children: 
  type: 'text'
  value: '  //  1.5707963267948966
Math.atan(-Infinity);  // -1.5707963267948966

'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/atan2](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/atan2)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'y'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/cbrt](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/cbrt)
### Missing conversion rules
- var (71:7)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/clz32](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/clz32)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'x'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/cos](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/cos)
#### Invalid AST transformations
##### pre.brush:.js (27:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'x'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/cosh](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/cosh)
#### Invalid AST transformations
##### pre.brush:.js (53:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'x'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/exp](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/exp)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### code (35:26) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'x'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/expm1](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/expm1)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'x'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/floor](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/floor)
#### Invalid AST transformations
##### pre.brush:.js (22:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'x'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/hypot](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/hypot)
#### Invalid AST transformations
##### code (108:7) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'value1'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math)
#### Invalid AST transformations
##### code (20:225) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### code (79:14) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: '^x'
```
##### code (81:46) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### code (93:63) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### code (103:103) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'x'
```
### Missing conversion rules
- sub (91:38)
- sub (93:38)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/log](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/log)
#### Invalid AST transformations
##### pre.brush:.js (65:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'x'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/log10](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/log10)
#### Invalid AST transformations
##### pre.brush:.js (67:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'x'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/log2](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/log2)
#### Invalid AST transformations
##### pre.brush:.js (67:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'x'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/max](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/max)
#### Invalid AST transformations
##### code (40:7) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'value1'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/min](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/min)
#### Invalid AST transformations
##### code (40:7) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'value1'
```
### Missing conversion rules
- span.seoSummary (21:4)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/pow](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/pow)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'base'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/round](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/round)
#### Invalid AST transformations
##### pre.brush:.js (22:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'x'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/sign](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/sign)
#### Invalid AST transformations
##### pre.brush:.js (26:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'x'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/sin](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/sin)
#### Invalid AST transformations
##### pre.brush:.js (21:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'x'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/sinh](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/sinh)
#### Invalid AST transformations
##### pre.brush:.js (54:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'x'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/sqrt](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/sqrt)
#### Invalid AST transformations
##### pre.brush:.js (71:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'x'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/tanh](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/tanh)
#### Invalid AST transformations
##### pre.brush:.js (101:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'x'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/trunc](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/trunc)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'x'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)
### Missing conversion rules
- var (103:74)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/isFinite](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/isFinite)
#### Invalid AST transformations
##### pre.brush:.js (25:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'value'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/isInteger](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/isInteger)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'value'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/isNaN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/isNaN)
#### Invalid AST transformations
##### pre.brush:.js (25:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'value'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/isSafeInteger](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/isSafeInteger)
### Missing conversion rules
- dfn (16:40)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/Number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/Number)
#### Invalid AST transformations
##### pre.brush:.js (19:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'value'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/parseFloat](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/parseFloat)
#### Invalid AST transformations
##### pre.brush:.js (22:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'string'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/parseInt](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/parseInt)
#### Invalid AST transformations
##### dl (29:1) => paragraph
```
type: 'paragraph'
summary: 'The Number.parseInt() method parses a string argument and
  returns an integer of the specified radix or base.'
children: 
  type: 'text'
  value: 'If '
  type: 'inlineCode'
  value: 'radix'
  type: 'text'
  value: ' is undefined or '
  type: 'inlineCode'
  value: '0'
  type: 'text'
  value: ', it is assumed to be '
  type: 'inlineCode'
  value: '10'
  type: 'text'
  value: ' except when the number begins with the code unit pairs '
  type: 'inlineCode'
  value: '0x'
  type: 'text'
  value: ' or '
  type: 'inlineCode'
  value: '0X'
  type: 'text'
  value: ', in which case a radix of '
  type: 'inlineCode'
  value: '16'
  type: 'text'
  value: ' is assumed.'
```
### Missing conversion rules
- var (34:36)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/toLocaleString](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/toLocaleString)
#### Invalid AST transformations
##### pre.brush:.js (103:1) => text
```
type: 'element'
tagName: 'a'
properties: 
  href: 'https://en.wikipedia.org/wiki/Eastern_Arabic_numerals'
children: 
  type: 'text'
  value: 'Eastern Arabic'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/__defineSetter__](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/__defineSetter__)
#### Invalid AST transformations
##### pre.brush:.js (40:5) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'val'
```
##### dl (34:1) => paragraph
```
type: 'list'
spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'val'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'An alias for the variable that holds the value attempted to be assigned to
'
          type: 'inlineCode'
          value: 'prop'
          type: 'text'
          value: '.'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/assign](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/assign)
#### Invalid AST transformations
##### pre.brush:.js (27:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'target'
```
### Missing conversion rules
- span.seoSummary (16:4)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/constructor](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/constructor)
#### Invalid AST transformations
##### pre.brush:.js (63:1) => text
```
type: 'element'
tagName: 'span'
properties: 
  className: 
    'message-body-wrapper'
children: 
  type: 'element'
  tagName: 'span'
  properties: 
    className: 
      'message-flex-body'
  children: 
    type: 'element'
    tagName: 'span'
    properties: 
      className: 
        'devtools-monospace'
        'message-body'
    children: 
      type: 'element'
      tagName: 'span'
      properties: 
        className: 
          'objectBox-stackTrace'
          'reps-custom-format'
      children: 
        type: 'text'
        value: 'TypeError: '
        type: 'element'
        tagName: 'span'
        properties: 
          className: 
            'objectBox'
            'objectBox-string'
        children: 
          type: 'text'
          value: 'var is null'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/defineProperties](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/defineProperties)
#### Invalid AST transformations
##### pre.brush:.js (22:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'obj'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/defineProperty](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/defineProperty)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'obj'
```
### Missing conversion rules
- dfn (53:31)
- dfn (54:51)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/entries](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/entries)
#### Invalid AST transformations
##### code (17:3) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'key'
```
##### pre.brush:.js (31:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'obj'
```
##### code (38:5) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'key'
```
##### code (44:3) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'key'
```
##### code (49:43) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'key'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/freeze](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/freeze)
#### Invalid AST transformations
##### pre.brush:.js (34:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'obj'
```
##### pre.brush:.js (77:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'Uint8Array'
```
##### code (194:26) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'object'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/fromEntries](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/fromEntries)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'iterable'
```
### Missing conversion rules
- var (43:3)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyDescriptor](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyDescriptor)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'obj'
```
### Missing conversion rules
- dfn (45:3)
- dfn (50:6)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyDescriptors](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyDescriptors)
#### Invalid AST transformations
##### pre.brush:.js (21:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'obj'
```
### Missing conversion rules
- dfn (38:13)
- dfn (43:6)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyNames](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyNames)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'obj'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertySymbols](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertySymbols)
#### Invalid AST transformations
##### pre.brush:.js (22:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'obj'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getPrototypeOf](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getPrototypeOf)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'obj'
```
### Missing conversion rules
- var (49:78)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/hasOwnProperty](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/hasOwnProperty)
### Missing conversion rules
- var (29:7)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/isExtensible](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/isExtensible)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'obj'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/isFrozen](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/isFrozen)
#### Invalid AST transformations
##### pre.brush:.js (22:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'obj'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/isSealed](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/isSealed)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'obj'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys)
#### Invalid AST transformations
##### pre.brush:.js (25:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'obj'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/Object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/Object)
#### Invalid AST transformations
##### pre.brush:.js (30:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'value'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/preventExtensions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/preventExtensions)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'obj'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/seal](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/seal)
#### Invalid AST transformations
##### pre.brush:.js (26:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'obj'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/setPrototypeOf](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/setPrototypeOf)
#### Invalid AST transformations
##### pre.brush:.js (38:1) => text
```
type: 'element'
tagName: 'code'
properties: 

children: 
  type: 'text'
  value: 'Object.setPrototypeOf('
  type: 'element'
  tagName: 'var'
  properties: 

  children: 
    type: 'text'
    value: 'obj'
  type: 'text'
  value: ', '
  type: 'element'
  tagName: 'var'
  properties: 

  children: 
    type: 'text'
    value: 'prototype'
  type: 'text'
  value: ')'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/toString](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/toString)
#### Invalid AST transformations
##### code (36:4) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'type'
```
##### code (45:41) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'Null'
```
##### code (46:46) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'Undefined'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/valueOf](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/valueOf)
#### Invalid AST transformations
##### pre.brush:.js (71:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'myNumberType'
```
##### code (78:6) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'type'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/values](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/values)
#### Invalid AST transformations
##### pre.brush:.js (25:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'obj'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/parseFloat](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/parseFloat)
#### Invalid AST transformations
##### pre.brush:.js (22:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'string'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/parseInt](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/parseInt)
#### Invalid AST transformations
##### code (119:3) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'thatNumber'
```
### Missing conversion rules
- var (36:36)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/all](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/all)
#### Invalid AST transformations
##### pre.brush:.js (26:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'iterable'
```
### Missing conversion rules
- var (41:5)
- var (43:5)
- var (47:56)
- var (69:57)
- var (73:19)
- var (104:11)
- var (130:3)
- var (169:7)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/allSettled](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/allSettled)
#### Invalid AST transformations
##### pre.brush:.js (33:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'Promise'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/any](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/any)
### Missing conversion rules
- var (33:79)
- var (34:86)
- var (35:232)
- var (46:115)
- var (57:18)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/catch](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/catch)
#### Invalid AST transformations
##### pre.brush:.js (28:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'p'
```
##### dl (37:1) => paragraph
```
type: 'list'
spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'reason'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The rejection reason.'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/finally](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/finally)
#### Invalid AST transformations
##### pre.brush:.js (27:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'p'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)
#### Invalid AST transformations
##### code (42:456) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'expression'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/Promise)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'executor'
```
##### pre.brush:.js (34:5) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'resolutionFunc'
```
##### pre.brush:.js (68:5) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'rejected'
```
##### dl (28:1) => paragraph
```
type: 'paragraph'
summary: 'The Promise constructor is primarily used to wrap
  functions that do not already support promises.'
children: 
  type: 'text'
  value: 'At the time when the constructor generates the new '
  type: 'inlineCode'
  value: 'Promise'
  type: 'text'
  value: ' object, it
also generates a corresponding pair of functions for
'
  type: 'inlineCode'
  value: 'resolutionFunc'
  type: 'text'
  value: ' and '
  type: 'inlineCode'
  value: 'rejectionFunc'
  type: 'text'
  value: ';
these are "tethered" to the '
  type: 'inlineCode'
  value: 'Promise'
  type: 'text'
  value: ' object. Therefore, the code within
the '
  type: 'inlineCode'
  value: 'executor'
  type: 'text'
  value: ' has the opportunity to perform some operation
and then reflect the operation's outcome (If the value is not another Promise
object) as either "fulfilled" or "rejected" by terminating with an invocation of
either the '
  type: 'inlineCode'
  value: 'resolutionFunc'
  type: 'text'
  value: ' or the
'
  type: 'inlineCode'
  value: 'rejectionFunc'
  type: 'text'
  value: ', respectively.',type: 'paragraph'
summary: 'The Promise constructor is primarily used to wrap
  functions that do not already support promises.'
children: 
  type: 'text'
  value: 'The '
  type: 'inlineCode'
  value: 'executor'
  type: 'text'
  value: ' has no meaningful return value. It
communicates via the side-effect caused by '
  type: 'inlineCode'
  value: 'resolutionFunc'
  type: 'text'
  value: ' or
'
  type: 'inlineCode'
  value: 'rejectionFunc'
  type: 'text'
  value: '. The side-effect is that the
'
  type: 'inlineCode'
  value: 'Promise'
  type: 'text'
  value: ' object becomes "resolved."',type: 'paragraph'
summary: 'The Promise constructor is primarily used to wrap
  functions that do not already support promises.'
children: 
  type: 'text'
  value: 'Typically, it works like this: The operation within
'
  type: 'inlineCode'
  value: 'executor'
  type: 'text'
  value: ' is asynchronous and provides a callback. The
callback is defined within the '
  type: 'inlineCode'
  value: 'executor'
  type: 'text'
  value: ' code. The callback
terminates by invoking '
  type: 'inlineCode'
  value: 'resolutionFunc'
  type: 'text'
  value: '. The invocation of
'
  type: 'inlineCode'
  value: 'resolutionFunc'
  type: 'text'
  value: ' includes a '
  type: 'inlineCode'
  value: 'value'
  type: 'text'
  value: ' parameter. The
'
  type: 'inlineCode'
  value: 'value'
  type: 'text'
  value: ' is passed back to the tethered '
  type: 'inlineCode'
  value: 'Promise'
  type: 'text'
  value: ' object. The
'
  type: 'inlineCode'
  value: 'Promise'
  type: 'text'
  value: ' object (asynchronously) invokes any '
  type: 'inlineCode'
  value: '.then()'
  type: 'text'
  value: '
associated with it. The '
  type: 'inlineCode'
  value: 'value'
  type: 'text'
  value: ' received by '
  type: 'inlineCode'
  value: '.then()'
  type: 'text'
  value: ' is
passed to the invocation of '
  type: 'inlineCode'
  value: 'handleFulfilled'
  type: 'text'
  value: ' as an input parameter (See
"Chained Promises" section).',type: 'paragraph'
summary: 'The Promise constructor is primarily used to wrap
  functions that do not already support promises.'
children: 
  type: 'text'
  value: 'The '
  type: 'inlineCode'
  value: 'executor'
  type: 'text'
  value: ' might also include a
'
  type: 'inlineCode'
  value: 'try{} catch()'
  type: 'text'
  value: ' block that invokes '
  type: 'inlineCode'
  value: 'rejectionFunc'
  type: 'text'
  value: '
upon error.',type: 'paragraph'
summary: 'The Promise constructor is primarily used to wrap
  functions that do not already support promises.'
children: 
  type: 'text'
  value: 'The signatures of these two functions are simple, they accept a single parameter of
any type. Of course, the actual names of these functions can be whatever is desired,
i.e. they are named as the parameters of '
  type: 'inlineCode'
  value: 'executor'
  type: 'text'
  value: '. Each
function is used by calling it when appropriate.',type: 'paragraph'
summary: 'The Promise constructor is primarily used to wrap
  functions that do not already support promises.'
children: 
  type: 'text'
  value: 'The returned '
  type: 'inlineCode'
  value: 'value'
  type: 'text'
  value: ' can be another promise object, in which case the
promise gets dynamically inserted into the chain.'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/race](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/race)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'iterable'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/reject](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/reject)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'reason'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/resolve](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/resolve)
#### Invalid AST transformations
##### pre.brush:.js (25:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'value'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/then](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/then)
#### Invalid AST transformations
##### pre.brush:.js (33:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'p.then(onFulfilled[, onRejected])'
```
##### pre.brush:.js (238:1) => text
```
type: 'element'
tagName: 'a'
properties: 
  href: '/en-US/docs/Web/API/GlobalFetch/fetch'
children: 
  type: 'text'
  value: 'fetch'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/Proxy/apply](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/Proxy/apply)
#### Invalid AST transformations
##### pre.brush:.js (22:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'p'
```
##### code (56:7) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'proxy'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/Proxy/construct](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/Proxy/construct)
#### Invalid AST transformations
##### pre.brush:.js (21:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'p'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/Proxy/defineProperty](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/Proxy/defineProperty)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'p'
```
##### code (75:5) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'target'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/Proxy/deleteProperty](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/Proxy/deleteProperty)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'target'
```
##### code (56:26) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'proxy'
```
##### code (57:5) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'proxy'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/Proxy/get](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/Proxy/get)
#### Invalid AST transformations
##### pre.brush:.js (22:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'p'
```
##### code (56:24) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'proxy'
```
##### code (57:5) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'proxy'
```
##### code (59:5) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'proxy'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/Proxy/getOwnPropertyDescriptor](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/Proxy/getOwnPropertyDescriptor)
#### Invalid AST transformations
##### pre.brush:.js (21:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'p'
```
##### code (65:20) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'target'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/Proxy/getPrototypeOf](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/Proxy/getPrototypeOf)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'p'
```
##### code (68:9) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'proxy'
```
##### code (69:18) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'target'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/Proxy/has](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/Proxy/has)
#### Invalid AST transformations
##### pre.brush:.js (22:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'p'
```
##### code (54:23) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'foo'
```
##### code (55:33) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'proxy'
```
##### code (56:32) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'proxy'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/Proxy](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/Proxy)
#### Invalid AST transformations
##### pre.brush:.js (19:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'target'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/Proxy/isExtensible](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/Proxy/isExtensible)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'p'
```
##### code (63:7) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'proxy'
```
##### code (64:5) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'target'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/Proxy/ownKeys](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/Proxy/ownKeys)
#### Invalid AST transformations
##### pre.brush:.js (21:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'p'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/Proxy/preventExtensions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/Proxy/preventExtensions)
#### Invalid AST transformations
##### pre.brush:.js (21:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'p'
```
##### code (58:6) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'proxy'
```
##### code (58:96) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'proxy'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/Proxy/set](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/Proxy/set)
#### Invalid AST transformations
##### pre.brush:.js (22:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'p'
```
##### code (46:9) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'obj'
```
##### code (73:28) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'proxy'
```
##### code (74:9) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'proxy'
```
##### code (76:5) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'proxy'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/Proxy/setPrototypeOf](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/Proxy/setPrototypeOf)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'p'
```
##### code (68:5) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'target'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/revocable](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/revocable)
#### Invalid AST transformations
##### pre.brush:.js (19:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'target'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect/apply](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect/apply)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'target'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect/Comparing_Reflect_and_Object_methods](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect/Comparing_Reflect_and_Object_methods)
#### Invalid AST transformations
##### tr (22:3) => tableRow
```
type: 'html'
value: '<th scope="col">Method Name</th>',type: 'html'
value: '<th scope="col"><code>Object</code></th>',type: 'html'
value: '<th scope="col"><code>Reflect</code></th>'
```
##### td (77:4) => tableCell
```
type: 'paragraph'
summary: 'The {{anN4cmVmKCJSZWZsZWN0Iik=}} object, introduced in ES2015, is a built-in object that provides methods to interface with JavaScript objects. Some of the static functions that exist on Reflect also correspond to methods available on {{anN4cmVmKCJPYmplY3QiKQ==}}, which predates ES2015. Although some of the methods appear to be similar in their behavior, there are often subtle differences between them.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: '{{anN4cmVmKCJSZWZsZWN0LmlzRXh0ZW5zaWJsZSgpIik=}} returns '
  type: 'inlineCode'
  value: 'true'
  type: 'text'
  value: ' if the object is extensible, and '
  type: 'inlineCode'
  value: 'false'
  type: 'text'
  value: ' if it is not. Throws a '
  type: 'inlineCode'
  value: 'TypeError'
  type: 'text'
  value: ' if the first argument is not an object (a primitive).'
```
##### tr (74:3) => tableRow
```
type: 'html'
value: '<td><p>{{anN4cmVmKCJSZWZsZWN0LmlzRXh0ZW5zaWJsZSgpIik=}} returns <code>true</code> if the object is extensible, and <code>false</code> if it is not. Throws a <code>TypeError</code> if the first argument is not an object (a primitive).</p></td>'
```
##### td (83:4) => tableCell
```
type: 'paragraph'
summary: 'The {{anN4cmVmKCJSZWZsZWN0Iik=}} object, introduced in ES2015, is a built-in object that provides methods to interface with JavaScript objects. Some of the static functions that exist on Reflect also correspond to methods available on {{anN4cmVmKCJPYmplY3QiKQ==}}, which predates ES2015. Although some of the methods appear to be similar in their behavior, there are often subtle differences between them.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: '{{anN4cmVmKCJPYmplY3QucHJldmVudEV4dGVuc2lvbnMoKSIp}} returns the object that is being made non-extensible. Throws a '
  type: 'inlineCode'
  value: 'TypeError'
  type: 'text'
  value: 'in ES5 if the argument is not an object (a primitive). In ES2015, treats the argument as a non-extensible, ordinary object and returns the object itself.'
```
##### tr (81:3) => tableRow
```
type: 'html'
value: '<td><p>{{anN4cmVmKCJPYmplY3QucHJldmVudEV4dGVuc2lvbnMoKSIp}} returns the object that is being made non-extensible. Throws a <code>TypeError</code>in ES5 if the argument is not an object (a primitive). In ES2015, treats the argument as a non-extensible, ordinary object and returns the object itself.</p></td>'
```
##### table.standard-table (20:1) => table
```
type: 'html'
value: '<tr><th scope="col">Method Name</th><th scope="col"><code>Object</code></th><th scope="col"><code>Reflect</code></th></tr>',type: 'html'
value: '<tr><td><code>isExtensible()</code></td><td>{{anN4cmVmKCJPYmplY3QuaXNFeHRlbnNpYmxlKCkiKQ==}} returns <code>true</code> if the object is extensible, and <code>false</code> if it is not. Throws a <code>TypeError</code> in ES5 if the first argument is not an object (a primitive). In ES2015, it will be coerced into a non-extensible, ordinary object and will return <code>false</code>.</td><td><p>{{anN4cmVmKCJSZWZsZWN0LmlzRXh0ZW5zaWJsZSgpIik=}} returns <code>true</code> if the object is extensible, and <code>false</code> if it is not. Throws a <code>TypeError</code> if the first argument is not an object (a primitive).</p></td></tr>',type: 'html'
value: '<tr><td><code>preventExtensions()</code></td><td><p>{{anN4cmVmKCJPYmplY3QucHJldmVudEV4dGVuc2lvbnMoKSIp}} returns the object that is being made non-extensible. Throws a <code>TypeError</code>in ES5 if the argument is not an object (a primitive). In ES2015, treats the argument as a non-extensible, ordinary object and returns the object itself.</p></td><td>{{anN4cmVmKCJSZWZsZWN0LnByZXZlbnRFeHRlbnNpb25zKCkiKQ==}} returns <code>true</code> if the object has been made non-extensible, and <code>false</code> if it has not. Throws a <code>TypeError</code> if the argument is not an object (a primitive).</td></tr>'
```
### Missing conversion rules
- th[scope="col"] (23:4)
- th[scope="col"] (24:4)
- th[scope="col"] (25:4)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect/construct](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect/construct)
#### Invalid AST transformations
##### pre.brush:.js (65:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'args'
```
##### pre.brush:.js (123:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'args'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect/defineProperty](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect/defineProperty)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'target'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect/deleteProperty](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect/deleteProperty)
#### Invalid AST transformations
##### pre.brush:.js (26:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'target'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect/getOwnPropertyDescriptor](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect/getOwnPropertyDescriptor)
#### Invalid AST transformations
##### pre.brush:.js (27:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'target'
```
### Missing conversion rules
- span.seoSummary (16:4)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect/getPrototypeOf](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect/getPrototypeOf)
#### Invalid AST transformations
##### pre.brush:.js (25:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'target'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect/has](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect/has)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'target'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect)
#### Invalid AST transformations
##### span.seoSummary (15:4) => text
```
type: 'element'
tagName: 'a'
properties: 
  href: '/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy/handler'
children: 
  type: 'text'
  value: 'proxy handlers'
```
##### code (31:138) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'target'
```
##### code (35:144) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'target'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect/isExtensible](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect/isExtensible)
#### Invalid AST transformations
##### span.seoSummary (16:4) => text
```
type: 'element'
tagName: 'a'
properties: 
  href: '#Difference_to_Object.isExtensible'
children: 
  type: 'text'
  value: 'differences'
```
##### pre.brush:.js (27:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'target'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect/ownKeys](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect/ownKeys)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'target'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect/preventExtensions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect/preventExtensions)
#### Invalid AST transformations
##### pre.brush:.js (27:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'target'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect/setPrototypeOf](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect/setPrototypeOf)
#### Invalid AST transformations
##### pre.brush:.js (28:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'target'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/@@match](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/@@match)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'regexp'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/@@matchAll](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/@@matchAll)
#### Invalid AST transformations
##### pre.brush:.js (26:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'regexp'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/@@replace](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/@@replace)
#### Invalid AST transformations
##### pre.brush:.js (27:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'regexp'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/@@search](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/@@search)
#### Invalid AST transformations
##### pre.brush:.js (25:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'regexp'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/@@split](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/@@split)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'regexp'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/exec](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/exec)
#### Invalid AST transformations
##### tr (76:5) => tableRow
```
type: 'html'
value: '<th scope="col">Property/Index</th>',type: 'html'
value: '<th scope="col">Description</th>',type: 'html'
value: '<th scope="col">Example</th>'
```
##### code (89:11) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'n'
```
##### td (90:7) => tableCell
```
type: 'paragraph'
summary: 'The exec() method executes a
    search for a match in a specified string. Returns a result array, or
    {{anN4cmVmKCJudWxsIik=}}.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'The parenthesized substring matches, if any.',type: 'paragraph'
summary: 'The exec() method executes a
    search for a match in a specified string. Returns a result array, or
    {{anN4cmVmKCJudWxsIik=}}.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'The number of possible parenthesized substrings is unlimited.'
```
##### td (95:7) => tableCell
```
type: 'paragraph'
summary: 'The exec() method executes a
    search for a match in a specified string. Returns a result array, or
    {{anN4cmVmKCJudWxsIik=}}.'
shouldWrap: 'true'
children: 
  type: 'inlineCode'
  value: 'result[1] === "Brown"',type: 'paragraph'
summary: 'The exec() method executes a
    search for a match in a specified string. Returns a result array, or
    {{anN4cmVmKCJudWxsIik=}}.'
shouldWrap: 'true'
children: 
  type: 'inlineCode'
  value: 'result[2] === "Jumps"'
```
##### tr (88:5) => tableRow
```
type: 'html'
value: '<td><p>The parenthesized substring matches, if any.</p><p>The number of possible parenthesized substrings is unlimited.</p></td>',type: 'html'
value: '<td><p><code>result[1] === "Brown"</code></p><p><code>result[2] === "Jumps"</code></p></td>'
```
##### td (118:7) => tableCell
```
type: 'paragraph'
summary: 'The exec() method executes a
    search for a match in a specified string. Returns a result array, or
    {{anN4cmVmKCJudWxsIik=}}.'
shouldWrap: 'true'
children: 
  type: 'inlineCode'
  value: 'indices[0] === Array [ 4, 25 ]',type: 'paragraph'
summary: 'The exec() method executes a
    search for a match in a specified string. Returns a result array, or
    {{anN4cmVmKCJudWxsIik=}}.'
shouldWrap: 'true'
children: 
  type: 'inlineCode'
  value: 'indices[1] === Array [ 10, 15 ]',type: 'paragraph'
summary: 'The exec() method executes a
    search for a match in a specified string. Returns a result array, or
    {{anN4cmVmKCJudWxsIik=}}.'
shouldWrap: 'true'
children: 
  type: 'inlineCode'
  value: 'indices[2] === Array [ 20, 25 ]',type: 'paragraph'
summary: 'The exec() method executes a
    search for a match in a specified string. Returns a result array, or
    {{anN4cmVmKCJudWxsIik=}}.'
shouldWrap: 'true'
children: 
  type: 'inlineCode'
  value: 'indices.groups === undefined',type: 'paragraph'
summary: 'The exec() method executes a
    search for a match in a specified string. Returns a result array, or
    {{anN4cmVmKCJudWxsIik=}}.'
shouldWrap: 'true'
children: 
  type: 'inlineCode'
  value: 'indices.length === 3'
```
##### tr (106:5) => tableRow
```
type: 'html'
value: '<td><p><code>indices[0] === Array [ 4, 25 ]</code></p><p><code>indices[1] === Array [ 10, 15 ]</code></p><p><code>indices[2] === Array [ 20, 25 ]</code></p><p><code>indices.groups === undefined</code></p><p><code>indices.length === 3</code></p></td>'
```
##### table.standard-table (74:1) => table
```
type: 'html'
value: '<tr><th scope="col">Property/Index</th><th scope="col">Description</th><th scope="col">Example</th></tr>',type: 'html'
value: '<tr><td><code>[1], ...[<var>n</var>]</code></td><td><p>The parenthesized substring matches, if any.</p><p>The number of possible parenthesized substrings is unlimited.</p></td><td><p><code>result[1] === "Brown"</code></p><p><code>result[2] === "Jumps"</code></p></td></tr>',type: 'html'
value: '<tr><td><code>indices</code></td><td>An array where each entry represents a substring match.
Each substring match itself is an array where the first entry
represents its start index and the second entry its end index.<br>The <code>indices</code> array additionally has a <code>groups</code>
property which holds an object of all named capturing groups. The keys
are the names of the capturing groups and each value is an array with
the first item being the start entry and the second entry being the
end index of the capturing group. If the regular expression doesn't
contain any capturing groups, <code>groups</code> is <code>undefined</code>.</td><td><p><code>indices[0] === Array [ 4, 25 ]</code></p><p><code>indices[1] === Array [ 10, 15 ]</code></p><p><code>indices[2] === Array [ 20, 25 ]</code></p><p><code>indices.groups === undefined</code></p><p><code>indices.length === 3</code></p></td></tr>'
```
##### tr (138:5) => tableRow
```
type: 'html'
value: '<th scope="col">Property/Index</th>',type: 'html'
value: '<th scope="col">Description</th>',type: 'html'
value: '<th scope="col">Example</th>'
```
##### td (147:7) => tableCell
```
type: 'paragraph'
summary: 'The exec() method executes a
    search for a match in a specified string. Returns a result array, or
    {{anN4cmVmKCJudWxsIik=}}.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'The index at which to start the next match.',type: 'paragraph'
summary: 'The exec() method executes a
    search for a match in a specified string. Returns a result array, or
    {{anN4cmVmKCJudWxsIik=}}.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'If '
  type: 'inlineCode'
  value: 'g'
  type: 'text'
  value: ' is absent, this will always be '
  type: 'inlineCode'
  value: '0'
  type: 'text'
  value: '.'
```
##### tr (145:5) => tableRow
```
type: 'html'
value: '<td><p>The index at which to start the next match.</p><p>If <code>g</code> is absent, this will always be <code>0</code>.</p></td>'
```
##### table.standard-table (136:1) => table
```
type: 'html'
value: '<tr><th scope="col">Property/Index</th><th scope="col">Description</th><th scope="col">Example</th></tr>',type: 'html'
value: '<tr><td><code>lastIndex</code></td><td><p>The index at which to start the next match.</p><p>If <code>g</code> is absent, this will always be <code>0</code>.</p></td><td><code>25</code></td></tr>'
```
### Missing conversion rules
- th[scope="col"] (77:7)
- th[scope="col"] (78:7)
- th[scope="col"] (79:7)
- th[scope="col"] (139:7)
- th[scope="col"] (140:7)
- th[scope="col"] (141:7)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp)
#### Invalid AST transformations
##### code (188:77) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'hhhh'
```
##### code (243:40) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: '$N'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/RegExp](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/RegExp)
#### Invalid AST transformations
##### pre.brush:.js (29:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'pattern'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/test](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/test)
#### Invalid AST transformations
##### code (88:21) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'str'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set/@@iterator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set/@@iterator)
#### Invalid AST transformations
##### pre.brush:.js (25:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'mySet'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set)
#### Invalid AST transformations
##### code (59:158) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'value'
```
##### code (75:69) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'value'
```
##### pre.brush:.js (119:1) => text
```
type: 'element'
tagName: 'a'
properties: 
  href: '/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/from'
children: 
  type: 'text'
  value: 'Array.from'
```
### Missing conversion rules
- pre.brush:.js[dir="ltr"] (260:1)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set/Set](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set/Set)
#### Invalid AST transformations
##### span.seoSummary (15:4) => text
```
type: 'element'
tagName: 'a'
properties: 
  href: '/en-US/docs/Glossary/Primitive'
children: 
  type: 'text'
  value: 'primitive values'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/@@iterator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/@@iterator)
#### Invalid AST transformations
##### pre.brush:.js (27:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'str'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/anchor](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/anchor)
#### Invalid AST transformations
##### code (43:31) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'name'
```
### Missing conversion rules
- var (44:17)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/charAt](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/charAt)
#### Invalid AST transformations
##### code (30:45) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'str'
```
##### code (46:41) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'stringName'
```
### Missing conversion rules
- span.seoSummary (15:4)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/charCodeAt](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/charCodeAt)
#### Invalid AST transformations
##### code (64:36) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'i'
```
##### code (65:5) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'i'
```
##### code (66:25) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'i'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/endsWith](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/endsWith)
#### Invalid AST transformations
##### code (37:5) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'str'
```
### Missing conversion rules
- span.seoSummary (16:4)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/fromCharCode](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/fromCharCode)
#### Invalid AST transformations
##### code (33:7) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'N'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/fromCodePoint](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/fromCodePoint)
#### Invalid AST transformations
##### code (34:7) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'num1'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)
#### Invalid AST transformations
##### tr (149:5) => tableRow
```
type: 'html'
value: '<th scope="col">Escape sequence</th>',type: 'html'
value: '<th scope="col">Unicode code point</th>'
```
##### code (196:11) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'XXXX'
```
##### code (201:11) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'X'
```
##### code (201:41) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'XXXXXX'
```
##### code (206:11) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'XX'
```
##### table.standard-table (147:1) => table
```
type: 'html'
value: '<tr><th scope="col">Escape sequence</th><th scope="col">Unicode code point</th></tr>'
```
### Missing conversion rules
- kbd (44:48)
- th[scope="col"] (150:7)
- th[scope="col"] (151:7)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/indexOf](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/indexOf)
#### Invalid AST transformations
##### code (57:12) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'str'
```
##### code (58:11) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'str'
```
##### code (101:41) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'stringName'
```
### Missing conversion rules
- span.seoSummary (15:4)
- var (41:61)
- var (51:7)
- var (56:12)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/lastIndexOf](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/lastIndexOf)
#### Invalid AST transformations
##### code (41:5) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'fromIndex'
```
##### code (42:18) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'fromIndex'
```
##### code (55:3) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'str'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/localeCompare](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/localeCompare)
#### Invalid AST transformations
##### pre.brush:.js (159:1) => text
```
type: 'element'
tagName: 'span'
properties: 
  className: 
    'message-body-wrapper'
children: 
  type: 'element'
  tagName: 'span'
  properties: 
    className: 
      'message-flex-body'
  children: 
    type: 'element'
    tagName: 'span'
    properties: 
      className: 
        'devtools-monospace'
        'message-body'
    children: 
      type: 'text'
      value: '"2".localeCompare("10")'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/match](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/match)
#### Invalid AST transformations
##### code (36:5) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'regexp'
```
##### code (163:3) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'regexp'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/matchAll](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/matchAll)
#### Invalid AST transformations
##### code (40:7) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'obj'
```
### Missing conversion rules
- var (18:14)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/normalize](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/normalize)
#### Invalid AST transformations
##### code (163:5) => text
```
type: 'element'
tagName: 'span'
properties: 
  className: 
    'message-body-wrapper'
children: 
  type: 'element'
  tagName: 'span'
  properties: 
    className: 
      'message-flex-body'
  children: 
    type: 'element'
    tagName: 'span'
    properties: 
      className: 
        'devtools-monospace'
        'message-body'
    children: 
      type: 'element'
      tagName: 'span'
      properties: 
        className: 
          'cm-string'
      children: 
        type: 'text'
        value: '"Ⓓ"'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/padEnd](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/padEnd)
#### Invalid AST transformations
##### code (35:45) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'str.'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/padStart](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/padStart)
#### Invalid AST transformations
##### code (38:44) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'str.'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/raw](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/raw)
#### Invalid AST transformations
##### pre.brush:.js (29:1) => text
```
type: 'element'
tagName: 'code'
properties: 

children: 
  type: 'text'
  value: 'String.raw('
  type: 'element'
  tagName: 'var'
  properties: 

  children: 
    type: 'text'
    value: 'callSite'
  type: 'text'
  value: ', '
  type: 'element'
  tagName: 'var'
  properties: 

  children: 
    type: 'text'
    value: '...substitutions'
  type: 'text'
  value: ')

String.raw`'
  type: 'element'
  tagName: 'var'
  properties: 

  children: 
    type: 'text'
    value: 'templateString'
  type: 'text'
  value: '`
'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/replace](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/replace)
#### Invalid AST transformations
##### tr (81:5) => tableRow
```
type: 'html'
value: '<th class="header" scope="col">Pattern</th>',type: 'html'
value: '<th class="header" scope="col">Inserts</th>'
```
##### code (104:11) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'n'
```
##### table.standard-table (79:1) => table
```
type: 'html'
value: '<tr><th class="header" scope="col">Pattern</th><th class="header" scope="col">Inserts</th></tr>'
```
##### tr (136:5) => tableRow
```
type: 'html'
value: '<th class="header" scope="col">Possible name</th>',type: 'html'
value: '<th class="header" scope="col">Supplied value</th>'
```
##### table.standard-table (134:1) => table
```
type: 'html'
value: '<tr><th class="header" scope="col">Possible name</th><th class="header" scope="col">Supplied value</th></tr>'
```
### Missing conversion rules
- th.header[scope="col"] (82:7)
- th.header[scope="col"] (83:7)
- th.header[scope="col"] (137:7)
- th.header[scope="col"] (138:7)
- var (148:15)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/replaceAll](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/replaceAll)
#### Invalid AST transformations
##### tr (84:5) => tableRow
```
type: 'html'
value: '<th class="header" scope="col">Pattern</th>',type: 'html'
value: '<th class="header" scope="col">Inserts</th>'
```
##### code (107:11) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'n'
```
##### table.standard-table (82:1) => table
```
type: 'html'
value: '<tr><th class="header" scope="col">Pattern</th><th class="header" scope="col">Inserts</th></tr>'
```
##### tr (129:5) => tableRow
```
type: 'html'
value: '<th class="header" scope="col">Possible name</th>',type: 'html'
value: '<th class="header" scope="col">Supplied value</th>'
```
##### table.standard-table (127:1) => table
```
type: 'html'
value: '<tr><th class="header" scope="col">Possible name</th><th class="header" scope="col">Supplied value</th></tr>'
```
### Missing conversion rules
- var (38:43)
- th.header[scope="col"] (85:7)
- th.header[scope="col"] (86:7)
- th.header[scope="col"] (130:7)
- th.header[scope="col"] (131:7)
- var (141:15)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/search](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/search)
#### Invalid AST transformations
##### code (34:54) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'regexp'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/slice](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/slice)
#### Invalid AST transformations
##### code (33:7) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'str'
```
##### code (35:7) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'str'
```
##### code (40:7) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'str'
```
##### code (48:7) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'str'
```
##### code (50:7) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'str'
```
##### code (52:7) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'str'
```
##### code (53:7) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'endIndex'
```
##### code (74:3) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'str'
```
##### code (77:19) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'str'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/String)
#### Invalid AST transformations
##### pre.brush:.js (21:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'thing'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/substr](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/substr)
#### Invalid AST transformations
##### code (50:53) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'str'
```
##### code (54:5) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'str'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/trimEnd](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/trimEnd)
### Missing conversion rules
- pre.brush:.js.highlight:.[5] (51:1)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/trimStart](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/trimStart)
### Missing conversion rules
- pre.brush:.js.highlight:.[5] (51:1)
- pre.brush:.js.highlight:.[5] (62:1)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol/@@toPrimitive](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol/@@toPrimitive)
#### Invalid AST transformations
##### pre.brush:.js (20:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'hint'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol/for](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol/for)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'key'
```
##### table.standard-table (52:1) => table
```
type: 'text'
value: 'A record in the global symbol registry'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol)
#### Invalid AST transformations
##### code (140:9) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'sym'
```
##### code (140:41) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'sym'
```
##### code (141:33) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'sym'
```
##### code (143:105) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'sym'
```
##### code (143:262) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'sym'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol/keyFor](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol/keyFor)
#### Invalid AST transformations
##### pre.brush:.js (21:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'sym'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray/every](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray/every)
#### Invalid AST transformations
##### dl (48:1) => paragraph
```
type: 'list'
spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'element'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The current element being processed in the typed array.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'index'
      type: 'text'
      value: ' {{T3B0aW9uYWxfaW5saW5l}}'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The index of the current element being processed in the typed array.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'array'
      type: 'text'
      value: ' {{T3B0aW9uYWxfaW5saW5l}}'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The typed array '
          type: 'inlineCode'
          value: 'every'
          type: 'text'
          value: ' was called upon.'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray/filter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray/filter)
#### Invalid AST transformations
##### code (51:5) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'element'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray/find](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray/find)
#### Invalid AST transformations
##### dl (52:1) => paragraph
```
type: 'list'
spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'element'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The current element being processed in the typed array.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'index'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The index of the current element being processed in the typed array.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'array'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The array '
          type: 'inlineCode'
          value: 'find()'
          type: 'text'
          value: ' was called upon.'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray/findIndex](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray/findIndex)
#### Invalid AST transformations
##### dl (49:1) => paragraph
```
type: 'list'
spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'element'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The current element being processed in the typed array.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'index'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The index of the current element being processed in the typed array.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'array'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The typed array '
          type: 'inlineCode'
          value: 'findIndex()'
          type: 'text'
          value: ' was called upon.'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray/forEach](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray/forEach)
#### Invalid AST transformations
##### dl (45:1) => paragraph
```
type: 'list'
spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'element'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The current element being processed in the typed array.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'index'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The index of the current element being processed in the array.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'array'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The array '
          type: 'inlineCode'
          value: 'forEach()'
          type: 'text'
          value: ' was called upon.'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray/from](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray/from)
#### Invalid AST transformations
##### code (17:16) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
##### code (80:4) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
##### code (90:4) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
##### code (97:9) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
##### code (99:9) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
##### code (109:5) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
##### code (113:9) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
##### code (114:9) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
##### code (117:9) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
##### code (123:9) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
##### code (129:25) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray)
#### Invalid AST transformations
##### code (36:4) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
##### code (50:14) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
##### tr (57:5) => tableRow
```
type: 'html'
value: '<th class="header" scope="col">Type</th>',type: 'html'
value: '<th class="header" scope="col">Value Range</th>',type: 'html'
value: '<th class="header" scope="col">Size in bytes</th>',type: 'html'
value: '<th class="header" scope="col">Description</th>',type: 'html'
value: '<th class="header" scope="col">Web IDL type</th>',type: 'html'
value: '<th class="header" scope="col">Equivalent C type</th>'
```
##### table.standard-table (55:1) => table
```
type: 'html'
value: '<tr><th class="header" scope="col">Type</th><th class="header" scope="col">Value Range</th><th class="header" scope="col">Size in bytes</th><th class="header" scope="col">Description</th><th class="header" scope="col">Web IDL type</th><th class="header" scope="col">Equivalent C type</th></tr>'
```
##### code (198:26) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
### Missing conversion rules
- th.header[scope="col"] (58:7)
- th.header[scope="col"] (59:7)
- th.header[scope="col"] (60:7)
- th.header[scope="col"] (61:7)
- th.header[scope="col"] (62:7)
- th.header[scope="col"] (63:7)
- var (180:10)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray/name](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray/name)
#### Invalid AST transformations
##### code (14:8) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray/of](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray/of)
#### Invalid AST transformations
##### code (16:16) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
##### code (53:7) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'N'
```
##### code (64:3) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
##### code (67:48) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
##### code (68:24) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
##### code (71:7) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray/reduce](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray/reduce)
#### Invalid AST transformations
##### dl (49:1) => paragraph
```
type: 'list'
spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'accumulator'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The value previously returned in the last invocation of the callback, or
'
          type: 'inlineCode'
          value: 'initialValue'
          type: 'text'
          value: ', if supplied (see below).'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'currentValue'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The current element being processed in the typed array.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'index'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The index of the current element being processed in the typed array.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'array'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The typed array '
          type: 'inlineCode'
          value: 'reduce()'
          type: 'text'
          value: ' was called upon.'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray/reduceRight](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray/reduceRight)
#### Invalid AST transformations
##### dl (46:1) => paragraph
```
type: 'list'
spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'accumulator'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The value previously returned in the last invocation of the callback, or
'
          type: 'inlineCode'
          value: 'initialValue'
          type: 'text'
          value: ', if supplied (see below).'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'currentValue'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The current element being processed in the typed array.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'index'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The index of the current element being processed in the typed array.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'array'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The typed array '
          type: 'inlineCode'
          value: 'reduceRight()'
          type: 'text'
          value: ' was called upon.'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray/some](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray/some)
#### Invalid AST transformations
##### dl (47:1) => paragraph
```
type: 'list'
spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'element'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The current element being processed in the typed array.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'index'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The index of the current element being processed in the typed array.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'array'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The typed array '
          type: 'inlineCode'
          value: 'some'
          type: 'text'
          value: ' was called upon.'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Uint16Array/Uint16Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Uint16Array/Uint16Array)
#### Invalid AST transformations
##### code (47:26) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Uint32Array/Uint32Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Uint32Array/Uint32Array)
#### Invalid AST transformations
##### code (51:26) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Uint8Array/Uint8Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Uint8Array/Uint8Array)
#### Invalid AST transformations
##### code (49:26) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Uint8ClampedArray/Uint8ClampedArray](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Uint8ClampedArray/Uint8ClampedArray)
#### Invalid AST transformations
##### code (51:26) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'TypedArray'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/unescape](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/unescape)
#### Invalid AST transformations
##### pre.brush:.js (35:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'str'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/uneval](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/uneval)
#### Invalid AST transformations
##### pre.brush:.js (22:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'object'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/WeakMap/clear](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WeakMap/clear)
### Missing conversion rules
- pre.brush:.js;highlight:[10].example-bad (27:1)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/WeakMap](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WeakMap)
#### Invalid AST transformations
##### code (50:71) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'key'
```
### Missing conversion rules
- var (31:32)
- var (31:67)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/WeakSet](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WeakSet)
#### Invalid AST transformations
##### code (83:75) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'value'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/WeakSet/WeakSet](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WeakSet/WeakSet)
### Missing conversion rules
- var (29:7)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/WebAssembly/Global/Global](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WebAssembly/Global/Global)
#### Invalid AST transformations
##### dl (25:1) => paragraph
```
type: 'list'
ordered: 'false'
start: 

spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'value'
      type: 'text'
      value: ': A '
      type: 'link'
      title: 

      url: '/en-US/docs/Web/API/USVString'
      children: 
        type: 'inlineCode'
        value: 'USVString'
      type: 'text'
      value: ' representing the
data type of the global. This can be one of '
      type: 'inlineCode'
      value: 'i32'
      type: 'text'
      value: ', '
      type: 'inlineCode'
      value: 'i64'
      type: 'text'
      value: ',
'
      type: 'inlineCode'
      value: 'f32'
      type: 'text'
      value: ', and '
      type: 'inlineCode'
      value: 'f64'
      type: 'text'
      value: '. USVString corresponds to the set of all
possible sequences of unicode scalar values. USVString maps to a String when
returned in JavaScript; it's generally only used for APIs that perform text
processing and need a string of unicode scalar values to operate on. USVString is
equivalent to DOMString except for not allowing unpaired surrogate codepoints.
Unpaired surrogate codepoints present in USVString are converted by the browser to
Unicode 'replacement character' U+FFFD, (�).'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'mutable'
      type: 'text'
      value: ': A boolean value that determines whether the global is
mutable or not. By default, this is '
      type: 'inlineCode'
      value: 'false'
      type: 'text'
      value: '.'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/WebAssembly/Memory/Memory](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WebAssembly/Memory/Memory)
#### Invalid AST transformations
##### dl (30:1) => paragraph
```
type: 'list'
spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'emphasis'
      children: 
        type: 'text'
        value: 'initial'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The initial size of the WebAssembly Memory, in units of WebAssembly pages.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'emphasis'
      children: 
        type: 'text'
        value: 'maximum {{b3B0aW9uYWxfaW5saW5l}}'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The maximum size the WebAssembly Memory is allowed to grow to, in units of
WebAssembly pages. When present, the '
          type: 'inlineCode'
          value: 'maximum'
          type: 'text'
          value: ' parameter acts as a hint
to the engine to reserve memory up front. However, the engine may ignore or clamp
this reservation request. Unshared WebAssembly memories don't need to set a
'
          type: 'inlineCode'
          value: 'maximum'
          type: 'text'
          value: ', but shared memories do.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'text'
      value: 'shared '
      type: 'emphasis'
      children: 
        type: 'text'
        value: '{{b3B0aW9uYWxfaW5saW5l}}'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'A boolean value that defines whether the memory is a shared memory or not. If
set to '
          type: 'inlineCode'
          value: 'true'
          type: 'text'
          value: ', it is a shared memory. The default is
'
          type: 'inlineCode'
          value: 'false'
          type: 'text'
          value: '.'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/WebAssembly/Module](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WebAssembly/Module)
#### Invalid AST transformations
##### span.seoSummary (15:4) => text
```
type: 'element'
tagName: 'a'
properties: 
  href: '/en-US/docs/Web/API/Worker/postMessage'
children: 
  type: 'text'
  value: 'shared with Workers'
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/WebAssembly/Table/Table](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WebAssembly/Table/Table)
#### Invalid AST transformations
##### dl (23:1) => paragraph
```
type: 'list'
spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'emphasis'
      children: 
        type: 'text'
        value: 'element'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'A string representing the type of value to be stored in the table. At the moment
this can only have a value of '
          type: 'inlineCode'
          value: '"anyfunc"'
          type: 'text'
          value: ' (functions).'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'emphasis'
      children: 
        type: 'text'
        value: 'initial'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The initial number of elements of the WebAssembly Table.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'emphasis'
      children: 
        type: 'text'
        value: 'maximum {{b3B0aW9uYWxfaW5saW5l}}'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'The maximum number of elements the WebAssembly Table is allowed to grow to.'
```
### [/en-US/docs/Web/JavaScript/Reference/Iteration_protocols](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Iteration_protocols)
#### Invalid AST transformations
##### tr (28:3) => tableRow
```
type: 'html'
value: '<th scope="col">Property</th>',type: 'html'
value: '<th scope="col">Value</th>'
```
##### table.standard-table (26:1) => table
```
type: 'html'
value: '<tr><th scope="col">Property</th><th scope="col">Value</th></tr>'
```
##### tr (55:3) => tableRow
```
type: 'html'
value: '<th scope="col">Property</th>',type: 'html'
value: '<th scope="col">Value</th>'
```
##### td (63:4) => tableCell
```
type: 'paragraph'
summary: 'As a couple of additions to ECMAScript 2015, Iteration protocols aren't new built-ins or syntax, but protocols. These protocols can be implemented by any object by following some conventions.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'A zero-argument function that returns an object with at least the following two properties:',type: 'list'
spread: 'false'
children: 
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'done'
      type: 'text'
      value: ' (boolean)'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        summary: 'As a couple of additions to ECMAScript 2015, Iteration protocols aren't new built-ins or syntax, but protocols. These protocols can be implemented by any object by following some conventions.'
        shouldWrap: 'true'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'Has the value '
          type: 'inlineCode'
          value: 'false'
          type: 'text'
          value: ' if the iterator was able to produce the next value in the sequence. (This is equivalent to not specifying the '
          type: 'inlineCode'
          value: 'done'
          type: 'text'
          value: ' property altogether.)'
        type: 'paragraph'
        summary: 'As a couple of additions to ECMAScript 2015, Iteration protocols aren't new built-ins or syntax, but protocols. These protocols can be implemented by any object by following some conventions.'
        shouldWrap: 'true'
        children: 
          type: 'text'
          value: 'Has the value '
          type: 'inlineCode'
          value: 'true'
          type: 'text'
          value: ' if the iterator has completed its sequence. In this case, '
          type: 'inlineCode'
          value: 'value'
          type: 'text'
          value: ' optionally specifies the return value of the iterator.'
  type: 'listItem'
  spread: 'false'
  children: 
    type: 'paragraph'
    children: 
      type: 'inlineCode'
      value: 'value'
    type: 'list'
    spread: 'false'
    children: 
      type: 'listItem'
      spread: 'false'
      children: 
        type: 'paragraph'
        children: 
          type: 'text'
          value: ': '
          type: 'text'
          value: 'Any JavaScript value returned by the iterator. Can be omitted when '
          type: 'inlineCode'
          value: 'done'
          type: 'text'
          value: ' is '
          type: 'inlineCode'
          value: 'true'
          type: 'text'
          value: '.',type: 'paragraph'
summary: 'As a couple of additions to ECMAScript 2015, Iteration protocols aren't new built-ins or syntax, but protocols. These protocols can be implemented by any object by following some conventions.'
shouldWrap: 'true'
children: 
  type: 'text'
  value: 'The '
  type: 'inlineCode'
  value: 'next()'
  type: 'text'
  value: ' method must always return an object with appropriate properties including '
  type: 'inlineCode'
  value: 'done'
  type: 'text'
  value: ' and '
  type: 'inlineCode'
  value: 'value'
  type: 'text'
  value: '. If a non-object value gets returned (such as '
  type: 'inlineCode'
  value: 'false'
  type: 'text'
  value: ' or '
  type: 'inlineCode'
  value: 'undefined'
  type: 'text'
  value: '), a {{anN4cmVmKCJUeXBlRXJyb3IiKQ==}} ('
  type: 'inlineCode'
  value: '"iterator.next() returned a non-object value"'
  type: 'text'
  value: ') will be thrown.'
```
##### tr (61:3) => tableRow
```
type: 'html'
value: '<td><p>A zero-argument function that returns an object with at least the following two properties:</p><dl><dt><code>done</code> (boolean)</dt><dd><p>Has the value <code>false</code> if the iterator was able to produce the next value in the sequence. (This is equivalent to not specifying the <code>done</code> property altogether.)</p><p>Has the value <code>true</code> if the iterator has completed its sequence. In this case, <code>value</code> optionally specifies the return value of the iterator.</p></dd><dt><code>value</code></dt><dd>Any JavaScript value returned by the iterator. Can be omitted when <code>done</code> is <code>true</code>.</dd></dl><p>The <code>next()</code> method must always return an object with appropriate properties including <code>done</code> and <code>value</code>. If a non-object value gets returned (such as <code>false</code> or <code>undefined</code>), a {{anN4cmVmKCJUeXBlRXJyb3IiKQ==}} (<code>"iterator.next() returned a non-object value"</code>) will be thrown.</p></td>'
```
##### table.standard-table (53:1) => table
```
type: 'html'
value: '<tr><th scope="col">Property</th><th scope="col">Value</th></tr>',type: 'html'
value: '<tr><td><code>next()</code></td><td><p>A zero-argument function that returns an object with at least the following two properties:</p><dl><dt><code>done</code> (boolean)</dt><dd><p>Has the value <code>false</code> if the iterator was able to produce the next value in the sequence. (This is equivalent to not specifying the <code>done</code> property altogether.)</p><p>Has the value <code>true</code> if the iterator has completed its sequence. In this case, <code>value</code> optionally specifies the return value of the iterator.</p></dd><dt><code>value</code></dt><dd>Any JavaScript value returned by the iterator. Can be omitted when <code>done</code> is <code>true</code>.</dd></dl><p>The <code>next()</code> method must always return an object with appropriate properties including <code>done</code> and <code>value</code>. If a non-object value gets returned (such as <code>false</code> or <code>undefined</code>), a {{anN4cmVmKCJUeXBlRXJyb3IiKQ==}} (<code>"iterator.next() returned a non-object value"</code>) will be thrown.</p></td></tr>'
```
### Missing conversion rules
- th[scope="col"] (29:4)
- th[scope="col"] (30:4)
- th[scope="col"] (56:4)
- th[scope="col"] (57:4)
### [/en-US/docs/Web/JavaScript/Reference/Lexical_grammar](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Lexical_grammar)
#### Invalid AST transformations
##### table.standard-table (21:1) => table
```
type: 'text'
value: 'Unicode format-control characters'
```
##### table.standard-table (57:1) => table
```
type: 'text'
value: 'White space characters'
```
##### table.standard-table (120:1) => table
```
type: 'text'
value: 'Line terminator characters'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Addition](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Addition)
#### Invalid AST transformations
##### pre.brush:.js (21:1) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: 'Operator:'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Addition_assignment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Addition_assignment)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: 'Operator:'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Assignment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Assignment)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: 'Operator:'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/async_function](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/async_function)
#### Invalid AST transformations
##### pre.brush:.js (25:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'name'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/await](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/await)
#### Invalid AST transformations
##### pre.brush:.js (19:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'rv'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_AND](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_AND)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'code'
properties: 

children: 
  type: 'element'
  tagName: 'var'
  properties: 

  children: 
    type: 'text'
    value: 'a'
  type: 'text'
  value: ' & '
  type: 'element'
  tagName: 'var'
  properties: 

  children: 
    type: 'text'
    value: 'b'
```
##### tr (47:5) => tableRow
```
type: 'html'
value: '<th class="header" scope="col">a</th>',type: 'html'
value: '<th class="header" scope="col">b</th>',type: 'html'
value: '<th class="header" scope="col">a AND b</th>'
```
##### table.standard-table (45:1) => table
```
type: 'html'
value: '<tr><th class="header" scope="col">a</th><th class="header" scope="col">b</th><th class="header" scope="col">a AND b</th></tr>'
```
### Missing conversion rules
- th.header[scope="col"] (48:7)
- th.header[scope="col"] (49:7)
- th.header[scope="col"] (50:7)
### [/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_AND_assignment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_AND_assignment)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: 'Operator:'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_NOT](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_NOT)
#### Invalid AST transformations
##### pre.brush:.js (21:1) => text
```
type: 'element'
tagName: 'code'
properties: 

children: 
  type: 'element'
  tagName: 'var'
  properties: 

  children: 
    type: 'text'
    value: '~a'
```
##### tr (45:5) => tableRow
```
type: 'html'
value: '<th class="header" scope="col">a</th>',type: 'html'
value: '<th class="header" scope="col">NOT a</th>'
```
##### table.standard-table (43:1) => table
```
type: 'html'
value: '<tr><th class="header" scope="col">a</th><th class="header" scope="col">NOT a</th></tr>'
```
### Missing conversion rules
- th.header[scope="col"] (46:7)
- th.header[scope="col"] (47:7)
### [/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_OR](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_OR)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'code'
properties: 

children: 
  type: 'element'
  tagName: 'var'
  properties: 

  children: 
    type: 'text'
    value: 'a'
  type: 'text'
  value: ' | '
  type: 'element'
  tagName: 'var'
  properties: 

  children: 
    type: 'text'
    value: 'b'
```
##### tr (47:5) => tableRow
```
type: 'html'
value: '<th class="header" scope="col">a</th>',type: 'html'
value: '<th class="header" scope="col">b</th>',type: 'html'
value: '<th class="header" scope="col">a OR b</th>'
```
##### table.standard-table (45:1) => table
```
type: 'html'
value: '<tr><th class="header" scope="col">a</th><th class="header" scope="col">b</th><th class="header" scope="col">a OR b</th></tr>'
```
### Missing conversion rules
- th.header[scope="col"] (48:7)
- th.header[scope="col"] (49:7)
- th.header[scope="col"] (50:7)
### [/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_OR_assignment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_OR_assignment)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: 'Operator:'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_XOR](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_XOR)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'code'
properties: 

children: 
  type: 'element'
  tagName: 'var'
  properties: 

  children: 
    type: 'text'
    value: 'a'
  type: 'text'
  value: ' ^ '
  type: 'element'
  tagName: 'var'
  properties: 

  children: 
    type: 'text'
    value: 'b'
```
##### tr (48:5) => tableRow
```
type: 'html'
value: '<th class="header" scope="col">a</th>',type: 'html'
value: '<th class="header" scope="col">b</th>',type: 'html'
value: '<th class="header" scope="col">a XOR b</th>'
```
##### table.standard-table (46:1) => table
```
type: 'html'
value: '<tr><th class="header" scope="col">a</th><th class="header" scope="col">b</th><th class="header" scope="col">a XOR b</th></tr>'
```
### Missing conversion rules
- th.header[scope="col"] (49:7)
- th.header[scope="col"] (50:7)
- th.header[scope="col"] (51:7)
### [/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_XOR_assignment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_XOR_assignment)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: 'Operator:'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/class](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/class)
#### Invalid AST transformations
##### pre.brush:.js (28:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'MyClass'
```
##### pre.brush:.js (52:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'declarations'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Comma_Operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comma_Operator)
#### Invalid AST transformations
##### pre.brush:.js (29:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'expr1'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Conditional_Operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Conditional_Operator)
#### Invalid AST transformations
##### pre.brush:.js (34:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'condition'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Decrement](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Decrement)
#### Invalid AST transformations
##### pre.brush:.js (21:1) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: 'Operator:'
```
##### code (27:3) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### code (31:3) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'x'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/delete](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/delete)
#### Invalid AST transformations
##### pre.brush:.js (27:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'expression'
```
##### pre.brush:.js (32:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'object'
```
##### pre.brush:.js (127:1) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: 'configurable: false'
```
##### pre.brush:.js (191:1) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: '//'
```
### Missing conversion rules
- span.seoSummary (19:4)
### [/en-US/docs/Web/JavaScript/Reference/Operators/Division](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Division)
#### Invalid AST transformations
##### pre.brush:.js (21:1) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: 'Operator:'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Division_assignment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Division_assignment)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: 'Operator:'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Exponentiation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Exponentiation)
#### Invalid AST transformations
##### pre.brush:.js (22:1) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: 'Operator:'
```
##### code (28:22) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'a'
```
##### code (29:3) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'a'
```
### Missing conversion rules
- kbd (49:62)
### [/en-US/docs/Web/JavaScript/Reference/Operators/Exponentiation_assignment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Exponentiation_assignment)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: 'Operator:'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/function](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/function)
#### Invalid AST transformations
##### pre.brush:.js (28:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'name'
```
### Missing conversion rules
- u (74:39)
### [/en-US/docs/Web/JavaScript/Reference/Operators/function*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/function*)
#### Invalid AST transformations
##### pre.brush:.js (25:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'name'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/in](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/in)
#### Invalid AST transformations
##### pre.brush:.js (22:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'prop'
```
### Missing conversion rules
- span.seoSummary (14:4)
- span.short_text[lang="en"] (31:54)
### [/en-US/docs/Web/JavaScript/Reference/Operators/Increment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Increment)
#### Invalid AST transformations
##### pre.brush:.js (21:1) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: 'Operator:'
```
##### code (27:3) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'x'
```
##### code (31:3) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'x'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/instanceof](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/instanceof)
#### Invalid AST transformations
##### pre.brush:.js (25:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'object'
```
##### code (91:24) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'myObj'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Left_shift](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Left_shift)
#### Invalid AST transformations
##### pre.brush:.js (22:1) => text
```
type: 'element'
tagName: 'code'
properties: 

children: 
  type: 'element'
  tagName: 'var'
  properties: 

  children: 
    type: 'text'
    value: 'a'
  type: 'text'
  value: ' << '
  type: 'element'
  tagName: 'var'
  properties: 

  children: 
    type: 'text'
    value: 'b'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Left_shift_assignment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Left_shift_assignment)
#### Invalid AST transformations
##### pre.brush:.js (21:1) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: 'Operator:'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Logical_AND](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_AND)
#### Invalid AST transformations
##### pre.brush:.js (27:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'expr1'
```
##### code (65:4) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'expr'
```
##### code (68:33) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'expr'
```
##### code (70:3) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'expr'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Logical_AND_assignment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_AND_assignment)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'expr1'
```
##### code (37:33) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'expr'
```
##### code (39:3) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'expr'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Logical_NOT](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_NOT)
#### Invalid AST transformations
##### pre.brush:.js (25:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'expr'
```
##### pre.brush:.js (78:1) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: 'any'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Logical_nullish_assignment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_nullish_assignment)
#### Invalid AST transformations
##### pre.brush:.js (26:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'expr1'
```
##### code (42:33) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'expr'
```
##### code (44:3) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'expr'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Logical_OR](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_OR)
#### Invalid AST transformations
##### pre.brush:.js (27:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'expr1'
```
##### code (63:4) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'expr'
```
##### code (66:33) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'expr'
```
##### code (68:3) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'expr'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Logical_OR_assignment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_OR_assignment)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'expr1'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Multiplication](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Multiplication)
#### Invalid AST transformations
##### pre.brush:.js (20:1) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: 'Operator:'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Multiplication_assignment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Multiplication_assignment)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: 'Operator:'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/new](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/new)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'constructor'
```
##### code (72:18) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'Foo'
```
##### code (76:48) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'Foo'
```
##### code (77:32) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'Foo'
```
##### code (80:40) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'Foo'
```
##### code (81:5) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'Foo'
```
##### code (82:5) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'Foo'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/new.target](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/new.target)
### Missing conversion rules
- p.summary (89:1)
### [/en-US/docs/Web/JavaScript/Reference/Operators/Nullish_coalescing_operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Nullish_coalescing_operator)
#### Invalid AST transformations
##### pre.brush:.js (41:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'leftExpr'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Object_initializer](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Object_initializer)
#### Invalid AST transformations
##### pre.brush:.js (27:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'property: function '
```
##### pre.brush:.js (44:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'property'
```
##### pre.brush:.js (158:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'property: function '
```
##### pre.brush:.js (166:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'property'
```
##### pre.brush:.js (173:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'generator'
```
##### pre.brush:.js (181:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: ': function* '
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Operator_Precedence](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Operator_Precedence)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'sub'
properties: 

children: 
  type: 'text'
  value: '1'
```
##### code (26:7) => text
```
type: 'element'
tagName: 'sub'
properties: 

children: 
  type: 'text'
  value: '1'
```
##### code (26:39) => text
```
type: 'element'
tagName: 'sub'
properties: 

children: 
  type: 'text'
  value: '2'
```
##### code (38:5) => text
```
type: 'element'
tagName: 'sub'
properties: 

children: 
  type: 'text'
  value: '1'
```
##### code (40:5) => text
```
type: 'element'
tagName: 'sub'
properties: 

children: 
  type: 'text'
  value: '1'
```
##### td (63:13) => tableCell
```
type: 'code'
lang: 'js'
meta: ''
value: 'function echo(name, num) {     console.log("Evaluating the " + name + " side");     return num; } // Notice the division operator (/) console.log(echo("left", 6) / echo("right", 2)); '
```
##### td (73:13) => tableCell
```
type: 'code'
lang: 'plain'
meta: ''
value: 'Evaluating the left side Evaluating the right side 3 '
```
##### tr (62:9) => tableRow
```
type: 'html'
value: '<td><pre class="brush: js">function echo(name, num) {
    console.log("Evaluating the " + name + " side");
    return num;
}
// Notice the division operator (/)
console.log(echo("left", 6) / echo("right", 2));
</pre></td>',type: 'html'
value: '<td><pre class="brush: plain">Evaluating the left side
Evaluating the right side
3
</pre></td>'
```
##### td (82:13) => tableCell
```
type: 'code'
lang: 'js'
meta: ''
value: 'function echo(name, num) {     console.log("Evaluating the " + name + " side");     return num; } // Notice the exponentiation operator (**) console.log(echo("left", 2) ** echo("right", 3));'
```
##### td (91:13) => tableCell
```
type: 'code'
lang: 'plain'
meta: ''
value: 'Evaluating the left side Evaluating the right side 8'
```
##### tr (81:9) => tableRow
```
type: 'html'
value: '<td><pre class="brush: js">function echo(name, num) {
    console.log("Evaluating the " + name + " side");
    return num;
}
// Notice the exponentiation operator (**)
console.log(echo("left", 2) ** echo("right", 3));</pre></td>',type: 'html'
value: '<td><pre class="brush: plain">Evaluating the left side
Evaluating the right side
8</pre></td>'
```
##### table.standard-table (56:1) => table
```
type: 'html'
value: '<tr><td><pre class="brush: js">function echo(name, num) {
    console.log("Evaluating the " + name + " side");
    return num;
}
// Notice the division operator (/)
console.log(echo("left", 6) / echo("right", 2));
</pre></td><td><pre class="brush: plain">Evaluating the left side
Evaluating the right side
3
</pre></td></tr>',type: 'html'
value: '<tr><td><pre class="brush: js">function echo(name, num) {
    console.log("Evaluating the " + name + " side");
    return num;
}
// Notice the exponentiation operator (**)
console.log(echo("left", 2) ** echo("right", 3));</pre></td><td><pre class="brush: plain">Evaluating the left side
Evaluating the right side
8</pre></td></tr>'
```
##### td (114:13) => tableCell
```
type: 'code'
lang: 'js'
meta: ''
value: 'function echo(name, num) {     console.log("Evaluating the " + name + " side");     return num; } // Notice the division operator (/) console.log(echo("left", 6) / echo("middle", 2) / echo("right", 3)); '
```
##### td (124:13) => tableCell
```
type: 'code'
lang: 'plain'
meta: ''
value: 'Evaluating the left side Evaluating the middle side Evaluating the right side 1 '
```
##### tr (113:9) => tableRow
```
type: 'html'
value: '<td><pre class="brush: js">function echo(name, num) {
    console.log("Evaluating the " + name + " side");
    return num;
}
// Notice the division operator (/)
console.log(echo("left", 6) / echo("middle", 2) / echo("right", 3));
</pre></td>',type: 'html'
value: '<td><pre class="brush: plain">Evaluating the left side
Evaluating the middle side
Evaluating the right side
1
</pre></td>'
```
##### td (134:13) => tableCell
```
type: 'code'
lang: 'js'
meta: ''
value: 'function echo(name, num) {     console.log("Evaluating the " + name + " side");     return num; } // Notice the exponentiation operator (**) console.log(echo("left", 2) ** echo("middle", 3) ** echo("right", 2)); '
```
##### td (144:13) => tableCell
```
type: 'code'
lang: 'plain'
meta: ''
value: 'Evaluating the left side Evaluating the middle side Evaluating the right side 512 '
```
##### tr (133:9) => tableRow
```
type: 'html'
value: '<td><pre class="brush: js">function echo(name, num) {
    console.log("Evaluating the " + name + " side");
    return num;
}
// Notice the exponentiation operator (**)
console.log(echo("left", 2) ** echo("middle", 3) ** echo("right", 2));
</pre></td>',type: 'html'
value: '<td><pre class="brush: plain">Evaluating the left side
Evaluating the middle side
Evaluating the right side
512
</pre></td>'
```
##### td (154:13) => tableCell
```
type: 'code'
lang: 'js'
meta: ''
value: 'function echo(name, num) {     console.log("Evaluating the " + name + " side");     return num; } // Notice the parentheses around the left and middle exponentiation console.log((echo("left", 2) ** echo("middle", 3)) ** echo("right", 2));'
```
##### td (163:13) => tableCell
```
type: 'code'
lang: 'plain'
meta: ''
value: 'Evaluating the left side Evaluating the middle side Evaluating the right side 64'
```
##### tr (153:9) => tableRow
```
type: 'html'
value: '<td><pre class="brush: js">function echo(name, num) {
    console.log("Evaluating the " + name + " side");
    return num;
}
// Notice the parentheses around the left and middle exponentiation
console.log((echo("left", 2) ** echo("middle", 3)) ** echo("right", 2));</pre></td>',type: 'html'
value: '<td><pre class="brush: plain">Evaluating the left side
Evaluating the middle side
Evaluating the right side
64</pre></td>'
```
##### table.standard-table (107:1) => table
```
type: 'html'
value: '<tr><td><pre class="brush: js">function echo(name, num) {
    console.log("Evaluating the " + name + " side");
    return num;
}
// Notice the division operator (/)
console.log(echo("left", 6) / echo("middle", 2) / echo("right", 3));
</pre></td><td><pre class="brush: plain">Evaluating the left side
Evaluating the middle side
Evaluating the right side
1
</pre></td></tr>',type: 'html'
value: '<tr><td><pre class="brush: js">function echo(name, num) {
    console.log("Evaluating the " + name + " side");
    return num;
}
// Notice the exponentiation operator (**)
console.log(echo("left", 2) ** echo("middle", 3) ** echo("right", 2));
</pre></td><td><pre class="brush: plain">Evaluating the left side
Evaluating the middle side
Evaluating the right side
512
</pre></td></tr>',type: 'html'
value: '<tr><td><pre class="brush: js">function echo(name, num) {
    console.log("Evaluating the " + name + " side");
    return num;
}
// Notice the parentheses around the left and middle exponentiation
console.log((echo("left", 2) ** echo("middle", 3)) ** echo("right", 2));</pre></td><td><pre class="brush: plain">Evaluating the left side
Evaluating the middle side
Evaluating the right side
64</pre></td></tr>'
```
### Missing conversion rules
- sub (22:7)
- sub (22:26)
- table.fullwidth-table (223:1)
### [/en-US/docs/Web/JavaScript/Reference/Operators/Optional_chaining](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Optional_chaining)
#### Invalid AST transformations
##### pre.brush:.js (39:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'obj.val'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Pipeline_operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Pipeline_operator)
#### Invalid AST transformations
##### pre.brush:.js (30:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'expression'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Property_Accessors](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Property_Accessors)
#### Invalid AST transformations
##### pre.brush:.js (22:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'object'
```
##### code (46:3) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'object'
```
##### code (46:53) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'object'
```
##### pre.brush:.js (49:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'object'
```
##### pre.brush:.js (93:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'object'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Remainder](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Remainder)
#### Invalid AST transformations
##### pre.brush:.js (28:1) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: 'Operator:'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Remainder_assignment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Remainder_assignment)
#### Invalid AST transformations
##### pre.brush:.js (22:1) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: 'Operator:'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Right_shift](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Right_shift)
#### Invalid AST transformations
##### pre.brush:.js (26:1) => text
```
type: 'element'
tagName: 'code'
properties: 

children: 
  type: 'element'
  tagName: 'var'
  properties: 

  children: 
    type: 'text'
    value: 'a'
  type: 'text'
  value: ' >> '
  type: 'element'
  tagName: 'var'
  properties: 

  children: 
    type: 'text'
    value: 'b'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Right_shift_assignment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Right_shift_assignment)
#### Invalid AST transformations
##### pre.brush:.js (22:1) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: 'Operator:'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax)
#### Invalid AST transformations
##### pre.brush:.js (63:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'myFunction'
```
##### pre.brush:.js (68:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'iterableObj'
```
##### pre.brush:.js (73:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'objClone'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Subtraction](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Subtraction)
#### Invalid AST transformations
##### pre.brush:.js (21:1) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: 'Operator:'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Subtraction_assignment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Subtraction_assignment)
#### Invalid AST transformations
##### pre.brush:.js (22:1) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: 'Operator:'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/typeof](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/typeof)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'operand'
```
##### tr (46:5) => tableRow
```
type: 'html'
value: '<th scope="col">Type</th>',type: 'html'
value: '<th scope="col">Result</th>'
```
##### table.standard-table (44:1) => table
```
type: 'html'
value: '<tr><th scope="col">Type</th><th scope="col">Result</th></tr>'
```
##### pre.brush:.js (105:1) => text
```
type: 'element'
tagName: 'a'
properties: 
  href: '/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/isArray'
children: 
  type: 'text'
  value: 'Array.isArray'
```
### Missing conversion rules
- th[scope="col"] (47:7)
- th[scope="col"] (48:7)
### [/en-US/docs/Web/JavaScript/Reference/Operators/Unary_negation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Unary_negation)
#### Invalid AST transformations
##### pre.brush:.js (21:1) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: 'Operator:'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Unary_plus](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Unary_plus)
#### Invalid AST transformations
##### pre.brush:.js (21:1) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: 'Operator:'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Unsigned_right_shift](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Unsigned_right_shift)
#### Invalid AST transformations
##### pre.brush:.js (27:1) => text
```
type: 'element'
tagName: 'code'
properties: 

children: 
  type: 'element'
  tagName: 'var'
  properties: 

  children: 
    type: 'text'
    value: 'a'
  type: 'text'
  value: ' >>> '
  type: 'element'
  tagName: 'var'
  properties: 

  children: 
    type: 'text'
    value: 'b'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/Unsigned_right_shift_assignment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Unsigned_right_shift_assignment)
#### Invalid AST transformations
##### pre.brush:.js (25:1) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: 'Operator:'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/void](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/void)
#### Invalid AST transformations
##### code (16:3) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'expression'
```
##### pre.brush:.js (22:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'expression'
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/yield](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/yield)
#### Invalid AST transformations
##### pre.brush:.js (26:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'rv'
```
### Missing conversion rules
- var (116:32)
- var (117:4)
### [/en-US/docs/Web/JavaScript/Reference/Operators/yield*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/yield*)
#### Invalid AST transformations
##### pre.brush:.js (26:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'expression'
```
### [/en-US/docs/Web/JavaScript/Reference/Statements/async_function](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'name'
```
##### pre.brush:.js (69:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'foo'
```
##### pre.brush:.js (76:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'foo'
```
##### pre.brush:.js (110:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'foo'
```
##### pre.brush:.js (117:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'foo'
```
##### pre.brush:.js (148:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'foo'
```
##### pre.brush:.js (164:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'foo'
```
### Missing conversion rules
- div.notecard.note (81:1)
### [/en-US/docs/Web/JavaScript/Reference/Statements/block](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/block)
#### Invalid AST transformations
##### pre.brush:.js (25:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'StatementList'
```
##### pre.brush:.js (32:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'LabelIdentifier'
```
### [/en-US/docs/Web/JavaScript/Reference/Statements/break](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/break)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'label'
```
### [/en-US/docs/Web/JavaScript/Reference/Statements/class](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/class)
#### Invalid AST transformations
##### pre.brush:.js (31:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'name'
```
### [/en-US/docs/Web/JavaScript/Reference/Statements/const](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/const)
#### Invalid AST transformations
##### pre.brush:.js (26:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'name1'
```
##### pre.brush:.js (42:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: '{ bar }'
```
### [/en-US/docs/Web/JavaScript/Reference/Statements/continue](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/continue)
#### Invalid AST transformations
##### pre.brush:.js (22:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'label'
```
### [/en-US/docs/Web/JavaScript/Reference/Statements/do...while](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/do...while)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'statement'
```
##### code (29:7) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'statement'
```
##### code (34:7) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'condition'
```
### [/en-US/docs/Web/JavaScript/Reference/Statements/export](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/export)
#### Invalid AST transformations
##### pre.brush:.js (38:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'name1'
```
##### pre.brush:.js (117:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'myFunction'
```
### [/en-US/docs/Web/JavaScript/Reference/Statements/for](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for)
#### Invalid AST transformations
##### pre.brush:.js (27:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'initialization'
```
### [/en-US/docs/Web/JavaScript/Reference/Statements/for-await...of](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for-await...of)
#### Invalid AST transformations
##### pre.brush:.js (27:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'variable'
```
### [/en-US/docs/Web/JavaScript/Reference/Statements/for...in](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...in)
#### Invalid AST transformations
##### pre.brush:.js (23:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'variable'
```
### [/en-US/docs/Web/JavaScript/Reference/Statements/for...of](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...of)
#### Invalid AST transformations
##### pre.brush:.js (28:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'variable'
```
### [/en-US/docs/Web/JavaScript/Reference/Statements/function](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/function)
#### Invalid AST transformations
##### pre.brush:.js (25:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'name'
```
### [/en-US/docs/Web/JavaScript/Reference/Statements/function*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/function*)
#### Invalid AST transformations
##### pre.brush:.js (27:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'name'
```
### [/en-US/docs/Web/JavaScript/Reference/Statements/if...else](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)
#### Invalid AST transformations
##### pre.brush:.js (25:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'condition'
```
##### pre.brush:.js (57:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'condition1'
```
##### pre.brush:.js (71:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'condition1'
```
##### pre.brush:.js (86:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'condition'
```
### Missing conversion rules
- var (38:37)
### [/en-US/docs/Web/JavaScript/Reference/Statements/import](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/import)
#### Invalid AST transformations
##### pre.brush:.js (36:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'defaultExport'
```
##### pre.brush:.js (78:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'myModule'
```
### [/en-US/docs/Web/JavaScript/Reference/Statements/label](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/label)
#### Invalid AST transformations
##### pre.brush:.js (21:1) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'label'
```
##### code (26:7) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'label'
```
##### code (28:7) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'statement'
```
### [/en-US/docs/Web/JavaScript/Reference/Statements/let](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/let)
#### Invalid AST transformations
##### pre.brush:.js (25:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'name1'
```
##### pre.brush:.js (43:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: '{ bar }'
```
### [/en-US/docs/Web/JavaScript/Reference/Statements/return](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/return)
#### Invalid AST transformations
##### pre.brush:.js (21:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'expression'
```
### [/en-US/docs/Web/JavaScript/Reference/Statements/switch](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/switch)
#### Invalid AST transformations
##### span.seoSummary (15:4) => text
```
type: 'element'
tagName: 'a'
properties: 
  href: '/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators'
children: 
  type: 'text'
  value: 'expression'
```
##### pre.brush:.js (27:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'expression'
```
##### code (50:7) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'valueN'
```
##### tr (240:5) => tableRow
```
type: 'html'
value: '<th scope="col">Value</th>',type: 'html'
value: '<th scope="col">Log text</th>'
```
##### table.standard-table (238:1) => table
```
type: 'html'
value: '<tr><th scope="col">Value</th><th scope="col">Log text</th></tr>'
```
##### pre.brush:.js (315:1) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: '{ // added brackets'
```
### Missing conversion rules
- th[scope="col"] (241:7)
- th[scope="col"] (242:7)
### [/en-US/docs/Web/JavaScript/Reference/Statements/throw](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/throw)
#### Invalid AST transformations
##### pre.brush:.js (26:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'expression'
```
### [/en-US/docs/Web/JavaScript/Reference/Statements/try...catch](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/try...catch)
#### Invalid AST transformations
##### code (34:7) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'try_statements'
```
##### code (37:7) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'catch_statements'
```
##### code (41:7) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'exception_var'
```
##### code (45:7) => text
```
type: 'element'
tagName: 'em'
properties: 

children: 
  type: 'text'
  value: 'finally_statements'
```
### [/en-US/docs/Web/JavaScript/Reference/Statements/var](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/var)
#### Invalid AST transformations
##### pre.brush:.js (22:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'varname1'
```
##### code (26:7) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: 'N'
```
##### code (28:7) => text
```
type: 'element'
tagName: 'strong'
properties: 

children: 
  type: 'text'
  value: 'N'
```
##### pre.brush:.js (37:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: '{ bar }'
```
### Missing conversion rules
- dfn (43:28)
- dfn (148:38)
### [/en-US/docs/Web/JavaScript/Reference/Statements/while](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/while)
#### Invalid AST transformations
##### pre.brush:.js (22:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'condition'
```
### [/en-US/docs/Web/JavaScript/Reference/Statements/with](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/with)
#### Invalid AST transformations
##### pre.brush:.js (24:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'expression'
```
### [/en-US/docs/Web/JavaScript/Reference/Template_literals](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals)
#### Invalid AST transformations
##### pre.brush:.js (27:1) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'expression'
```
##### code (44:17) => text
```
type: 'element'
tagName: 'var'
properties: 

children: 
  type: 'text'
  value: 'expression'
```
### Missing conversion rules
- dfn (49:12)
### [/en-US/docs/Web/JavaScript/Typed_arrays](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Typed_arrays)
#### Invalid AST transformations
##### tr (33:3) => tableRow
```
type: 'html'
value: '<th class="header" scope="col">Type</th>',type: 'html'
value: '<th class="header" scope="col">Value Range</th>',type: 'html'
value: '<th class="header" scope="col">Size in bytes</th>',type: 'html'
value: '<th class="header" scope="col">Description</th>',type: 'html'
value: '<th class="header" scope="col">Web IDL type</th>',type: 'html'
value: '<th class="header" scope="col">Equivalent C type</th>'
```
##### table.standard-table (31:1) => table
```
type: 'html'
value: '<tr><th class="header" scope="col">Type</th><th class="header" scope="col">Value Range</th><th class="header" scope="col">Size in bytes</th><th class="header" scope="col">Description</th><th class="header" scope="col">Web IDL type</th><th class="header" scope="col">Equivalent C type</th></tr>'
```
### Missing conversion rules
- th.header[scope="col"] (34:4)
- th.header[scope="col"] (35:4)
- th.header[scope="col"] (36:4)
- th.header[scope="col"] (37:4)
- th.header[scope="col"] (38:4)
- th.header[scope="col"] (39:4)