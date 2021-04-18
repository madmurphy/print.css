print.css
=========

The universal CSS to carry around in every website to make it adaptable to the
printed page

Besides the page itself, this CSS affects the printed layout of the following
elements: `<a>`, `<abbr>`, `<address>`, `<article>`, `<blockquote>`,
`<button>`, `<cite>`, `<code>`, `<data>`, `<dd>`, `<del>`, `<details>`, `<dt>`,
`<em>`, `<fieldset>`, `<figure>`, `<footer>`, `<h1>`, `<h2>`, `<h3>`, `<h4>`,
`<h5>`, `<h6>`, `<hr>`, `<i>`, `<iframe>`, `<img>`, `<input>`, `<ins>`,
`<legend>`, `<li>`, `<mark>`, `<nav>`, `<output>`, `<p>`, `<pre>`, `<q>`,
`<section>`, `<select>`, `<summary>`, `<textarea>`, `<time>`, `<thead>`,
`<tr>`.


Available classes:

<dl>
<dt><code>"new-page"</code></dt>
<dd>Print the element in a new page</dd>
<dt><code>"non-printable"</code></dt>
<dd>Do not print the element</dd>
<dt><code>"obvious"</code></dt>
<dd>Prevent the expansion of attributes (such as <code>href</code>,
<code>title</code>, etc.) &ndash; useful when the content makes them
redundant</dd>
<dt><code>"printable"</code></dt>
<dd>Print the element &ndash; useful for elements that would not be printed
otherwise, such as <code>&lt;nav&gt;</code> containers, form buttons, etc.</dd>
<dt><code>"trackable"</code></dt>
<dd>Expand the content of the <code>value</code> attributes assigned to
(nested) <code>&lt;data&gt;</code> elements and the <code>datetime</code>
attributes assigned to (nested) <code>&lt;time&gt;</code> elements</dd>
</dl>


Free software
-------------

This CSS is free software. You can redistribute it and/or modify it under the
terms of the GPL license version 3 or any later version. See [COPYING][1] for
details.


  [1]: https://github.com/madmurphy/print.css/blob/master/COPYING

