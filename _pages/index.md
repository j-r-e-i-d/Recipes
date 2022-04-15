---
layout: page
title: Home
id: home
permalink: /
---

# My recipe collection

{% for dinner in site.dinner %}
  <h3>
    <a href="{{ dinner.url }}">
      {{ dinner.title }} by {{ dinner.chef }}
    </a>
  </h3>
{% endfor %}

<style>
  .wrapper {
    max-width: 46em;
  }
</style>
