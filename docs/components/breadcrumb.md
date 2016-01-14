---
layout: docs
title: Breadcrumb
group: components
---

[//]: # DO NOT EDIT IT WILL BE OVERWRITTEN - copy of bootstrap documentation generated by grunt docs-copy-bootstrap-docs

{% callout info %}
**Bootstrap Reference Documentation** 
This is a part of the reference documentation from <a href="http://getbootstrap.com">Bootstrap</a>. 
It is included here to demonstrate rendering with Material Design for Bootstrap default styling. 
See the <a href="/material-design/buttons">Material Design</a> section for more elements and customization options.
{% endcallout %}



Indicate the current page's location within a navigational hierarchy. Separators are automatically added in CSS through [`::before`](https://developer.mozilla.org/en-US/docs/Web/CSS/::before) and [`content`](https://developer.mozilla.org/en-US/docs/Web/CSS/content).

{% example html %}
<ol class="breadcrumb">
  <li class="breadcrumb-item active">Home</li>
</ol>
<ol class="breadcrumb">
  <li class="breadcrumb-item"><a href="#">Home</a></li>
  <li class="breadcrumb-item active">Library</li>
</ol>
<ol class="breadcrumb">
  <li class="breadcrumb-item"><a href="#">Home</a></li>
  <li class="breadcrumb-item"><a href="#">Library</a></li>
  <li class="breadcrumb-item active">Data</li>
</ol>
{% endexample %}

Similar to our navigation components, breadcrumbs work fine with or without the usage of list markup.

{% example html %}
<nav class="breadcrumb">
  <a class="breadcrumb-item" href="#">Home</a>
  <a class="breadcrumb-item" href="#">Library</a>
  <a class="breadcrumb-item" href="#">Data</a>
  <span class="breadcrumb-item active">Bootstrap</span>
</nav>
{% endexample %}