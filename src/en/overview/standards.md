# Standards


While Nirvarnia CSS and Nirvarnia JS are intended to have very good support for the long tail of web clients, they assume that the application itself is built to current web standards. No effort is made to deal with HTML elements that have been deprecated from the HTML5 specification, things like `<acronym>`, `<center>` and `<hgroup>`. New HTML elements that have been recently added to web standards but are not yet widely supported – things like `<menu>` – are also not supported.

In effect, the Nirvarnia project supports a subset of standard HTML markup. Specifically, the following element types are supported:

```
<a>                          <address>                    <article>
<aside>                      <audio>                      <b>
<br>                         <button type="button">       <button type="submit">
<code>                       <col>                        <colgroup>
<div>                        <em>                         <embed>
<fieldset>                   <figcaption>                 <figure>
<footer>                     <form>                       <h1>
<h2>                         <h3>                         <header>
<i>                          <iframe>                     <img>
<input type="checkbox">      <input type="email">         <input type="file">
<input type="hidden">        <input type="number">        <input type="password">
<input type="radio">         <input type="search">        <input type="tel">
<input type="text">          <input type="url">           <label>
<legend>                     <li>                         <main>
<mark>                       <nav>                        <object>
<ol>                         <optgroup>                   <option>
<p>                          <param>                      <pre>
<section>                    <select>                     <small>
<span>                       <strong>                     <sub>
<sup>                        <table>                      <tbody>
<td>                         <textarea>                   <tfoot>
<th>                         <thead>                      <tr>
<ul>                         <video>
```

In addition, SVG graphics may be embedded using the `<svg>` element, and the `<script>` tag may be repurposed to hold in stasis fragments of markup that may be needed later for dynamic rendering of parts of the GUI.

There are many other standard HTML elements in existence but only those listed above have been so far accommodated in our the Nirvarnia design system, as they have proven to provide consistent results across all of our target browsers.
