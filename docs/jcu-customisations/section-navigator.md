---
layout: docs
title: Section Navigator
group: jcu-customisations
---

*Section Navigator* is an amalgam of a navbar, consisting of the current
site or section's navigation, and breadcrumbs.  This is typically used
CMS-style pages.

## Contents

* Will be replaced with the ToC, excluding the "Contents" header
{:toc}

## Examples

### Worked example

See the [Content Page example]({{ site.baseurl }}/examples/jcu-content-page/)
for a fully-worked, living example.

### Basic example

<style type="text/css">
.jcu-section-navigator {
  margin-top: 0;
}
</style>

{% example html %}
<div class="jcu-section-navigator">
  <div class="container-fluid container-fluid--max-width hidden-print">
    <nav class="navbar navbar-dark bg-inverse">
      <ul class="nav navbar-nav">
        <li class="nav-item active">
          <a class="nav-link" href="#">About JCU</a>
        </li>
        <li class="nav-item dropdown dropdown--open-on-hover">
          <a class="nav-link dropdown-toggle" href="#">Campuses</a>
          <div class="dropdown-menu">
            <a class="dropdown-item" href="#">Townsville</a>
            <a class="dropdown-item" href="#">Cairns</a>
            <a class="dropdown-item" href="#">Singapore</a>
            <a class="dropdown-item" href="#">Brisbane</a>
            <a class="dropdown-item" href="#">Mackay</a>
            <a class="dropdown-item" href="#">Mount Isa</a>
            <a class="dropdown-item" href="#">Thursday Island</a>
          </div>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">History</a>
        </li>
      </ul>
    </nav>
  </div>
  <nav class="container-fluid jcu-section-navigator__breadcrumb">
    <ol class="breadcrumb">
      <li><a href="#">About JCU</a></li>
      <li><a href="#">History and Information</a></li>
      <li class="active">About</li>
    </ol>
  </nav>
</div>
{% endexample %}