# HTML Source Code: Maxi Format

A text filter supporting a large number of tags and attributes. The filter may open the site to
security risks if misused. Only the most trusted users with a good knowledge of HTML, tag attributes
and CSS should be given permissions for it's usage.

## Tags

### HTML Tags

| Tag                                         | Attributes                                                                                                | ✅❌❔ |
| ------------------------------------------- | --------------------------------------------------------------------------------------------------------- | ------ |
| \<a>                                        | aria-label, class, href, data-entity-metadata, data-entity-type, data-entity-uuid, id, rel, target, title | ✅     |
| \<abbr>                                     | class                                                                                                     | ✅     |
| \<address><sup>[provided](#provided)</sup>  |                                                                                                           |   ❌❔ |
| \<area><sup>[media](#media)</sup>           |                                                                                                           |   ❌   |
| \<article><sup>[semantic](#semantic)</sup>  |                                                                                                           |   ❌   |
| \<aside><sup>[semantic](#semantic)</sup>    |                                                                                                           |   ❌❔ |
| \<audio><sup>[media](#media)</sup>          |                                                                                                           |   ❌   |
| \<b><sup>[b](#b)</sup>                      |                                                                                                           |   ❌❔ |
| \<base><sup>[head](#head)</sup>             |                                                                                                           |   ❌   |
| \<bdi>                                      | class                                                                                                     | ✅  ❔ |
| \<bdo>                                      |                                                                                                           |   ❌❔ |
| \<blockquote>                               | cite, class                                                                                               | ✅     |
| \<body><sup>[doc](doc)</sup>                |                                                                                                           |   ❌   |
| \<br>                                       | class                                                                                                     | ✅     |
| \<button><sup>[forms](#forms)</sup>         |                                                                                                           |   ❌   |
| \<canvas><sup>[danger](#danger)</sup>       |                                                                                                           |   ❌   |
| \<caption>                                  | class                                                                                                     | ✅     |
| \<cite>                                     | class                                                                                                     | ✅     |
| \<code>                                     | class                                                                                                     | ✅     |
| \<col>                                      | class                                                                                                     | ✅     |
| \<colgroup>                                 | class                                                                                                     | ✅     |
| \<data>                                     | class                                                                                                     | ✅  ❔ |
| \<datalist><sup>[forms](#forms)</sup>       |                                                                                                           |   ❌   |
| \<dd>                                       | class                                                                                                     | ✅     |
| \<del>                                      | cite, class, datetime                                                                                     | ✅     |
| \<details>                                  | class                                                                                                     | ✅     |
| \<dfn>                                      | class, id, title                                                                                          | ✅     |
| \<dialogue><sup>[forms](#forms)</sup>       |                                                                                                           |   ❌   |
| \<div>                                      | class                                                                                                     | ✅  ❔ |
| \<dl>                                       | class                                                                                                     | ✅     |
| \<dt>                                       | class                                                                                                     | ✅     |
| \<em>                                       |                                                                                                           | ✅     |
| \<embed><sup>[danger](#danger)</sup>        |                                                                                                           |   ❌   |
| \<fieldset><sup>[forms](#forms)</sup>       |                                                                                                           |   ❌   |
| \<figcaption>                               | class                                                                                                     | ✅     |
| \<figure>                                   | class, id                                                                                                 | ✅     |
| \<footer><sup>[semantic](#semantic)</sup>   |                                                                                                           |   ❌   |
| \<form><sup>[forms](#forms)</sup>           |                                                                                                           |   ❌   |
| \<head><sup>[doc](doc)</sup>                |                                                                                                           |   ❌   |
| \<header><sup>[semantic](#semantic)</sup>   |                                                                                                           |   ❌   |
| \<hgroup>                                   | class, id                                                                                                 | ✅  ❔ |
| \<h1><sup>[semantic](#semantic)             |                                                                                                           |   ❌   |
| \<h2>                                       | class, id                                                                                                 | ✅     |
| \<h3>                                       | class, id                                                                                                 | ✅     |
| \<h4>                                       | class, id                                                                                                 | ✅     |
| \<h5>                                       | class, id                                                                                                 | ✅     |
| \<h6>                                       | class, id                                                                                                 | ✅     |
| \<hr>                                       |                                                                                                           | ✅     |
| \<html><sup>[doc](doc)</sup>                |                                                                                                           |   ❌   |
| \<i><sup>[em](em)</sup>                     |                                                                                                           | ✅     |
| \<iframe><sup>[danger](#danger)</sup>       |                                                                                                           |   ❌   |
| \<img><sup>[media](#media)</sup>            |                                                                                                           |   ❌   |
| \<input><sup>[forms](#forms)</sup>          |                                                                                                           |   ❌   |
| \<ins>                                      | cite, class, datetime, id                                                                                 | ✅     |
| \<kbd>                                      | class                                                                                                     | ✅     |
| \<label><sup>[forms](#forms)</sup>          |                                                                                                           |   ❌   |
| \<legend><sup>[forms](#forms)</sup>         |                                                                                                           |   ❌   |
| \<li>                                       | class                                                                                                     | ✅     |
| \<link><sup>[head](#head)</sup>             |                                                                                                           |   ❌   |
| \<main><sup>[semantic](#semantic)</sup>     |                                                                                                           |   ❌   |
| \<map><sup>[media](#media)</sup>            |                                                                                                           |   ❌   |
| \<mark>                                     | class                                                                                                     | ✅     |
| \<menu><sup>[danger](#danger)</sup>         |                                                                                                           |   ❌   |
| \<menuitem><sup>[danger](#danger)</sup>     |                                                                                                           |   ❌   |
| \<meta><sup>[doc](doc)</sup>                |                                                                                                           |   ❌   |
| \<meter>                                    | class                                                                                                     | ✅     |
| \<nav><sup>[semantic](#semantic)</sup>      |                                                                                                           |   ❌   |
| \<noscript>                                 |                                                                                                           |   ❌   |
| \<object><sup>[danger](#danger)</sup>       |                                                                                                           |   ❌   |
| \<ol>                                       | class, id, start, type                                                                                    | ✅     |
| \<optgroup><sup>[forms](#forms)</sup>       |                                                                                                           |   ❌   |
| \<option><sup>[forms](#forms)</sup>         |                                                                                                           |   ❌   |
| \<output><sup>[forms](#forms)</sup>         |                                                                                                           |   ❌   |
| \<p>                                        | class                                                                                                     | ✅     |
| \<param><sup>[danger](#danger)</sup>        |                                                                                                           |   ❌   |
| \<picture><sup>[media](#media)</sup>        |                                                                                                           |   ❌   |
| \<pre>                                      | class                                                                                                     | ✅     |
| \<progress><sup>[forms](#forms)</sup>       |                                                                                                           |   ❌   |
| \<q>                                        | class                                                                                                     | ✅     |
| \<rp>                                       |                                                                                                           |   ❌   |
| \<rt>                                       |                                                                                                           |   ❌   |
| \<ruby>                                     |                                                                                                           |   ❌   |
| \<s>                                        | class                                                                                                     | ✅     |
| \<samp>                                     | class                                                                                                     | ✅     |
| \<script><sup>[danger](#danger)</sup>       |                                                                                                           |   ❌   |
| \<section>                                  | class, id                                                                                                 | ✅  ❔ |
| \<select><sup>[forms](#forms)</sup>         |                                                                                                           |   ❌   |
| \<small>                                    | class                                                                                                     | ✅     |
| \<source><sup>[media](#media)</sup>         |                                                                                                           |   ❌   |
| \<span>                                     | class                                                                                                     | ✅     |
| \<strong>                                   |                                                                                                           | ✅     |
| \<style><sup>[head](#head)</sup>            |                                                                                                           |   ❌❔ |
| \<sub>                                      | class                                                                                                     | ✅     |
| \<summary><sup>[provided](#provided)</sup>  |                                                                                                           |   ❌   |
| \<sup>                                      | class                                                                                                     | ✅     |
| \<svg><sup>[media](#media)</sup>            |                                                                                                           |   ❌❔ |
| \<table>                                    | class, id                                                                                                 | ✅     |
| \<tbody>                                    | class                                                                                                     | ✅     |
| \<td>                                       | class, colspan, headers, rowspan                                                                          | ✅     |
| \<template>                                 |                                                                                                           |   ❌   |
| \<textarea><sup>[forms](#forms)</sup>       |                                                                                                           |   ❌   |
| \<tfoot>                                    | class                                                                                                     | ✅     |
| \<th>                                       | abbr, class, colspan, rowspan, scope                                                                      | ✅     |
| \<thead>                                    | class                                                                                                     | ✅     |
| \<time>                                     | class                                                                                                     | ✅     |
| \<title><sup>[head](#head)</sup>            |                                                                                                           |   ❌   |
| \<tr>                                       | class                                                                                                     | ✅     |
| \<track><sup>[media](#media)</sup>          |                                                                                                           |   ❌   |
| \<u>                                        | class                                                                                                     | ✅     |
| \<ul>                                       | class, type                                                                                               | ✅     |
| \<var>                                      | class                                                                                                     | ✅     |
| \<video><sup>[media](#media)</sup>          |                                                                                                           |   ❌   |
| \<wbr>                                      | class                                                                                                     | ✅     |

### Drupal Specific Tags

|   Tag           | Attributes                                                                                                                                                           | ✅❌❔ |
| --------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| \<drupal-media> | alt, class data-align, data-caption, data-entity-type, data-link-entity-metadata, data-link-entity-type, data-link-entity-uuid, data-entity-uuid, data-view-mode, id | ✅     |

***

## Thoughts and Reasoning

### b

  - Use \<strong> instead.

### Danger

One or more of the following may apply:

### Doc

One or more of the following may apply:

  - The tag forms part of overall document body.
  - The tag is handled through Drupal Core.
  - The tag and it's attributes are created through Twig Templates.

### Forms

One or more of the following may apply:

  - Unnecessary for content editors.
  - Unworkable in the context of content editing.
  - Dangerous for use in site content.
  - Forms should only be created and managed by those with higher privileges such as site
    administrators.
  - Drupal provides a safer, more manageable way to create and consume forms.

### Head

One or more of the following may apply:

  - The tag is contained within the head element of the document and is not useable within the
    document body

### i

  - Use \<em> instead.

### Media

One or more of the following may apply:

  - Drupal provides a more rounded way of handling of this type of content through the core media
    module.
  - Links and changes are managed through the media module.
  - A contributed module provides a safer, more rounded way of managing this tag and it's contents.

### Page

One or more of the following may apply:

### Provided

One or more of the following may apply:

  - Drupal core handles the display of this tag or component and attributes.
  - A frequently used Drupal contrib module may handle the tag or attributes more roundly that the
    HTML Tag

### Semantic

One or more of the following may apply:

  - Drupal core handles semantic tags through the Twig template engine.
  - Drupal contrib modules add additional handling of semantic tags through the Twig template engine.
  - Use of structural tags may confuse semantic markup in Twig templates and therefore result in
    failures to achieve a good standard of accessibility.
