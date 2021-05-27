---
title: Promise() constructor
slug: Web/JavaScript/Reference/Global_Objects/Promise/Promise
tags:
- Constructor
- JavaScript
- Promise
- Reference
- Polyfill
browser-compat: javascript.builtins.Promise.Promise
---
{{JSRef}}

The **`Promise`** constructor is primarily used to wrap functions that do not
already support promises.

{{EmbedInteractiveExample("pages/js/promise-constructor.html", "taller")}}

## Syntax

<pre class="brush: js">new Promise(<var>executor</var>)
</pre>

### Parameters

<dl><dt><code><var>executor</var></code></dt><dd>A {{jsxref("function")}} to be executed by the constructor, during the process of
constructing the new <code>Promise</code> object. The <code><var>executor</var></code>
is custom code that ties an outcome to a promise. You, the programmer, write the
<code><var>executor</var></code>. The signature of this function is expected to be:<pre class="brush: js">function(<var>resolutionFunc</var>, <var>rejectionFunc</var>){
    // typically, some asynchronous operation.
}
</pre><p>At the time when the constructor generates the new <code>Promise</code> object, it
also generates a corresponding pair of functions for
<code><var>resolutionFunc</var></code> and <code><var>rejectionFunc</var></code>;
these are "tethered" to the <code>Promise</code> object. Therefore, the code within
the <code><var>executor</var></code> has the opportunity to perform some operation
and then reflect the operation's outcome (If the value is not another Promise
object) as either "fulfilled" or "rejected" by terminating with an invocation of
either the <code><var>resolutionFunc</var></code> or the
<code><var>rejectionFunc</var></code>, respectively.</p><p>The <code><var>executor</var></code> has no meaningful return value. It
communicates via the side-effect caused by <code><var>resolutionFunc</var></code> or
<code><var>rejectionFunc</var></code>. The side-effect is that the
<code>Promise</code> object becomes "resolved."</p><p>Typically, it works like this: The operation within
<code><var>executor</var></code> is asynchronous and provides a callback. The
callback is defined within the <code><var>executor</var></code> code. The callback
terminates by invoking <code><var>resolutionFunc</var></code>. The invocation of
<code><var>resolutionFunc</var></code> includes a <code>value</code> parameter. The
<code>value</code> is passed back to the tethered <code>Promise</code> object. The
<code>Promise</code> object (asynchronously) invokes any <code>.then()</code>
associated with it. The <code>value</code> received by <code>.then()</code> is
passed to the invocation of <code>handleFulfilled</code> as an input parameter (See
"Chained Promises" section).</p><p>The <code><var>executor</var></code> might also include a
<code>try{} catch()</code> block that invokes <code><var>rejectionFunc</var></code>
upon error.</p><p>The signatures of these two functions are simple, they accept a single parameter of
any type. Of course, the actual names of these functions can be whatever is desired,
i.e. they are named as the parameters of <code><var>executor</var></code>. Each
function is used by calling it when appropriate.</p><pre class="brush: js">resolutionFunc(value) // call on fulfilled
rejectionFunc(reason) // call on <em>rejected</em></pre><p>The returned <code>value</code> can be another promise object, in which case the
promise gets dynamically inserted into the chain.</p></dd></dl>

### Return value

When called via `new`, the `Promise` constructor returns a promise object. The
promise object will become "resolved" when either of the functions
`resolutionFunc` or `rejectionFunc` are invoked. Note that if you call
`resolutionFunc` or `rejectionFunc` and pass another Promise object as an
argument, you can say that it is "resolved", but still cannot be said to be
"settled".

## Examples

### Creating a new Promise

A `Promise` object is created using the `new` keyword and its constructor. This
constructor takes a function, called the "executor function", as its parameter.
This function should take two functions as parameters. The first of these
functions (`resolve`) is called when the asynchronous task completes
successfully and returns the results of the task as a value. The second
(`reject`) is called when the task fails, and returns the reason for failure,
which is typically an error object.

```js
const myFirstPromise = new Promise((resolve, reject) => {
  // do something asynchronous which eventually calls either:
  //
  //   resolve(someValue)        // fulfilled
  // or
  //   reject("failure reason")  // rejected
});
```

### Making functions return a Promise

To provide a function with promise functionality, have it return a promise:

```js
function myAsyncFunction(url) {
  return new Promise((resolve, reject) => {
    const xhr = new XMLHttpRequest()
    xhr.open("GET", url)
    xhr.onload = () => resolve(xhr.responseText)
    xhr.onerror = () => reject(xhr.statusText)
    xhr.send()
  });
}
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- A polyfill of `Promise` is available in
  [`core-js`](https://github.com/zloirock/core-js#ecmascript-promise)
- [Using Promises](/en-US/docs/Web/JavaScript/Guide/Using_promises)
