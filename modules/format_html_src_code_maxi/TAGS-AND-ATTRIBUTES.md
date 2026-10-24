# HTML Source Code: Maxi Format

A text filter supporting a large number of tags and attributes. The filter may open the site to
security risks if misused. Only the most trusted users with a good knowledge of HTML, tag attributes
and CSS should be given permissions for it's usage.

## Tags

### HTML Tags

| Tag                                         | Attributes                                 | ✅❌❔ |
| ------------------------------------------- | ------------------------------------------ | ------ |
| \<a>                                        | aria-label, class, dir, href, hreflang     | ✅     |
| \<abbr>                                     | class, dir, lang                           | ✅     |
| \<address>                                  | class , dir, lang                          |   ❌   |
| \<area>                                     |                                            |   ❌   |
| \<article><sup>[forms](#forms)</sup>        |                                            |   ❌   |
| \<aside>                                    | class, dir, lang                           | ✅  ❔ |
| \<audio>                                    |                                            |   ❌   |
| \<b>                                        |                                            | ✅     |
| \<base>                                     |                                            |   ❌   |
| \<bdi>                                      |                                            |   ❌   |
| \<bdo>                                      |                                            |   ❌   |
| \<blockquote>                               | cite, class, dir, lang                     | ✅     |
| \<body>                                     |                                            |   ❌   |
| \<br>                                       |                                            | ✅     |
| \<button>                                   |                                            |   ❌   |
| \<canvas>                                   |                                            |   ❌   |
| \<caption>                                  | class, dir, lang                           | ✅     |
| \<cite>                                     | class, dir, lang                           | ✅     |
| \<code>                                     | class, dir, lang                           | ✅     |
| \<col>                                      |                                            | ✅     |
| \<colgroup>                                 |                                            | ✅     |
| \<data>                                     |                                            |   ❌   |
| \<datalist>                                 |                                            |   ❌   |
| \<dd>                                       |                                            | ✅     |
| \<del>                                      |                                            | ✅     |
| \<details>                                  |                                            |   ❌   |
| \<dfn>                                      | class, dir, lang                           | ✅     |
| \<dialogue>                                 |                                            |   ❌   |
| \<div>                                      | class, dir, lang                           | ✅  ❔ |
| \<dl>                                       | class, dir, lang                           | ✅     |
| \<dt>                                       | class, dir, lang                           | ✅     |
| \<em>                                       |                                            | ✅     |
| \<embed>                                    |                                            |   ❌   |
| \<fieldset>                                 |                                            |   ❌   |
| \<figcaption>                               | class, dir, lang                           | ✅     |
| \<figure>                                   | class, dir, lang                           | ✅     |
| \<footer>                                   |                                            |   ❌   |
| \<form>                                     |                                            |   ❌   |
| \<head>                                     |                                            |   ❌   |
| \<header>                                   |                                            |   ❌   |
| \<hgroup>                                   | class, dir, lang                           | ✅  ❔ |
| \<h1>                                       |                                            |   ❌   |
| \<h2>                                       | class, dir, id, lang                       | ✅     |
| \<h3>                                       | class, dir, id, lang                       | ✅     |
| \<h4>                                       | class, dir, id, lang                       | ✅     |
| \<h5>                                       | class, dir, id, lang                       | ✅     |
| \<h6>                                       | class, dir, id, lang                       | ✅     |
| \<hr>                                       |                                            | ✅     |
| \<html>                                     |                                            |   ❌   |
| \<i>                                        |                                            | ✅     |
| \<iframe>                                   |                                            |   ❌   |
| \<img>                                      |                                            |   ❌   |
| \<ins>                                      | class, dir, lang                           | ✅     |
| \<kbd>                                      |                                            |   ❌   |
| \<keygen>                                   |                                            |   ❌   |
| \<label>                                    |                                            |   ❌   |
| \<legend>                                   |                                            |   ❌   |
| \<li>                                       | class, dir, lang                           | ✅     |
| \<link>                                     |                                            |   ❌   |
| \<main>                                     |                                            |   ❌   |
| \<map>                                      |                                            |   ❌   |
| \<mark>                                     | class, dir, lang                           | ✅     |
| \<menu>                                     |                                            |   ❌   |
| \<menuitem>                                 |                                            |   ❌   |
| \<meta>                                     |                                            |   ❌   |
| \<meter>                                    | class, dir, lang                           | ✅     |
| \<nav>                                      |                                            |   ❌   |
| \<noscript>                                 |                                            |   ❌   |
| \<object>                                   |                                            |   ❌   |
| \<ol>                                       | class, dir, lang, start, type              | ✅     |
| \<optgroup>                                 |                                            |   ❌   |
| \<option>                                   |                                            |   ❌   |
| \<output>                                   |                                            |   ❌   |
| \<p>                                        | class, dir, lang                           | ✅     |
| \<param>                                    |                                            |   ❌   |
| \<picture>                                  |                                            |   ❌   |
| \<pre>                                      | class, dir, lang                           | ✅     |
| \<progress>                                 |                                            |   ❌   |
| \<q>                                        | class, dir, lang                           | ✅     |
| \<rp>                                       |                                            |   ❌   |
| \<rt>                                       |                                            |   ❌   |
| \<ruby>                                     |                                            |   ❌   |
| \<s>                                        | class, dir, lang                           | ✅     |
| \<samp>                                     | class, dir, lang                           | ✅     |
| \<script>                                   |                                            |   ❌   |
| \<section>                                  | class, dir, lang                           | ✅  ❔ |
| \<select>                                   |                                            |   ❌   |
| \<small>                                    | class, dir, lang                           | ✅     |
| \<source>                                   |                                            |   ❌   |
| \<span>                                     | class, dir, lang                           | ✅     |
| \<strong>                                   | class, dir, lang                           | ✅     |
| \<style>                                    |                                            |   ❌   |
| \<sub>                                      | class, dir, lang                           | ✅     |
| \<summary>                                  |                                            |   ❌   |
| \<sup>                                      | class, dir, lang                           | ✅     |
| \<svg>                                      |                                            |   ❌   |
| \<table>                                    | class, dir, lang                           | ✅     |
| \<tbody>                                    | class, dir, lang                           | ✅     |
| \<td>                                       | class, dir, lang                           | ✅     |
| \<template>                                 |                                            |   ❌   |
| \<textarea>                                 |                                            |   ❌   |
| \<tfoot>                                    | class, dir, lang                           | ✅     |
| \<th>                                       | class, dir, lang                           | ✅     |
| \<thead>                                    | class, dir, lang                           | ✅     |
| \<time>                                     | class, dir, lang                           | ✅     |
| \<title>                                    |                                            |   ❌   |
| \<tr>                                       | class, dir, lang                           | ✅     |
| \<track>                                    |                                            |   ❌   |
| \<u>                                        | class, dir, lang                           | ✅     |
| \<ul>                                       | class, dir, lang                           | ✅     |
| \<var>                                      | class, dir, lang                           | ✅     |
| \<video>                                    |                                            |   ❌   |
| \<wbr>                                      | class, dir, lang                           | ✅     |

### Drupal Specific Tags

|   Tag              | Attributes                           | ✅❌❔ |
| ------------------ | ------------------------------------ | ------ |
| \<drupal-media>    | data-entity-type, data-entity-uuid   | ✅     |

***

## Thoughts and Reasoning

### Forms

- Unnecessary for content editors.
- Dangerous for use in site content.
- Forms should only be created and managed by those with higher privileges such as site
  administrators.
- Drupal provides a safer, more manageable way to create and consume forms.

### Structural

- Drupal core handles structural tags through the Twig template engine.
- Drupal modules add additional handling of structural tags through the Twig template engine.
- Use of structural tags may confuse semantic markup and therefore result in failures to achieve a
  good standard of accessibility.

### Media

- Drupal provides a more rounded way of handling of this type of content through the core media
  module.
- Links and changes are managed through the media module.
