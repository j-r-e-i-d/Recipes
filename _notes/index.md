---
title: Index
---

# Jon's Recipe Collection

### Dinners
* [[Baked Rice with Confit Tomatoes and Garlic]]
* [[Baked Minty Rice with Feta and Pomegranate Relish]]


#### New section below

{% for dinner in site.dinner %}
  <h3>
    <a href="{{ dinner.url }}">
      {{ dinner.title }} by {{ dinner.chef }}
    </a>
  </h3>
{% endfor %}