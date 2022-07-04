---
title: Index
---

# Jon's Recipe Collection

### Dinners
* [[Baked Minty Rice with Feta and Pomegranate Relish]]
* [[Baked Rice with Confit Tomatoes and Garlic]]
* [[baked_lamb_oregano_meatballs|Baked Lamb And Oregano Meatballs]]
* [[celeriac_red_wine_stew_cheddar_dumplings|Celeriac and Red Wine Stew With Cheddar Dumplings]]

#### New section below
```
{% for dinner in site.dinner %}
  <h3>
    <a href="{{ dinner.url }}">
      {{ dinner.title }} by {{ dinner.chef }}
    </a>
  </h3>
{% endfor %}
```
