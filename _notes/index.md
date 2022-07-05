---
title: Index
---

### Meals
* [[baked_minty_rice_feta_pomegranate_relish|Baked Minty Rice with Feta and Pomegranate Relish]]
* [[baked_rice_confit_tomatoes_garlic|Baked Rice with Confit Tomatoes and Garlic]]
* [[baked_lamb_oregano_meatballs|Baked Lamb And Oregano Meatballs]]
* [[celeriac_red_wine_stew_cheddar_dumplings|Celeriac and Red Wine Stew With Cheddar Dumplings]]
* [[corn_cauliflower_chowder|Corn & Cauliflower Chowder]]
* [[lamb_backstrap_black_garlic_sauce_-_network_t|Lamb Backstrap with Black Garlic Sauce]]
* [[lamb_cauliflower_aioli|Lamb chops & cauliflower with garlic & lemon yoghurt]]
* [[lamb_feta_meatball_flatbreads|Lamb And Feta Meatball Flatbreads]]
* [[loaded_cauliflower|Loaded Cauliflower]]
* [[quiche_lorraine|Quiche Lorraine]]
* [[tarte_de_tomates_lardons_et_le_ménez_hom_(or_som|Tarte de Tomates]]

### Breakfasts
* [[breakfast_crumble_w_cherries_&_yoghurt|Breakfast crumble with cherries and yoghurt]]
* [[dutch_baby_bananas_&_berries|Dutch baby with bananas & berries]]
* [[eggs_in_purgatory|Shakshuka]]

### Baking
* [[bee_stings|Bee Stings]]
* [[updated_no_knead_bread|No Knead Bread]]
* [[shortcrust_pastry|Shortcrust Pastry]]
* [[griddle_scones|Griddle Scones]]

### Sweet Snacks
* [[almond_raspberry_slice|Almond Raspberry Slice]]
* [[forgotten_cookies|Forgotten Cookies]]
* 

### Components
* [[cabbage_kimchi_(baechu_kimchi)|Cabbage kimchi]]
* [[basic_japanese_dashi|Dashi]]


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
