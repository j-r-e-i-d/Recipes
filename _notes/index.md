---
title: Index
---

### Meals
* [[grilled_lamb_shoulder|Alison Roman's Grilled lamb shoulder]]
* [[baked_minty_rice_feta_pomegranate_relish|Baked Minty Rice with Feta and Pomegranate Relish]]
* [[baked_rice_confit_tomatoes_garlic|Baked Rice with Confit Tomatoes and Garlic]]
* [[baked_lamb_oregano_meatballs|Baked Lamb And Oregano Meatballs]]
* [[barbecued_squid_&_macadamia_tarator|Barbecued squid and macadamia tarator]]
* [[beef_cheek_&_dark_beer_ragu|Beef cheek & dark beer ragu]]
* [[cabbage_parmesan_buckwheat|Cabbage cream with cabbage]]
* [[celeriac_red_wine_stew_cheddar_dumplings|Celeriac and Red Wine Stew With Cheddar Dumplings]]
* [[chicken_braised_w_mushroom_&_thyme|Chicken braised with mushroom & thyme]]
* [[chicken_breast_w_garlic_&_black_bean_dressing|Chicken breast with garlic & black bean dressing]]
* [[chicken_w_salt_pepper_lime_&_bird's_eye_chilli_recipe|Chicken with salt pepper lime and bird's eye chilli]]
* [[corn_cauliflower_chowder|Corn & Cauliflower Chowder]]
* [[lamb_backstrap_black_garlic_sauce_-_network_t|Lamb Backstrap with Black Garlic Sauce]]
* [[lamb_cauliflower_aioli|Lamb chops & cauliflower with garlic & lemon yoghurt]]
* [[lamb_feta_meatball_flatbreads|Lamb And Feta Meatball Flatbreads]]
* [[loaded_cauliflower|Loaded Cauliflower]]
* [[quiche_lorraine|Quiche Lorraine]]
* [[braised_lamb_shoulder|Slow-braised lamb shoulder with aioli]]
* [[tarte_de_tomates_lardons_et_le_ménez_hom_(or_som|Tarte de Tomates]]

### Breakfasts
* [[apple_racuchy|Apple racuchy]]
* 
* [[breakfast_crumble_w_cherries_&_yoghurt|Breakfast crumble with cherries and yoghurt]]
* [[dutch_baby_bananas_&_berries|Dutch baby with bananas & berries]]
* [[eggs_in_purgatory|Shakshuka]]

### Baking
* [[bee_stings|Bee Stings]]
* [[updated_no_knead_bread|No Knead Bread]]
* [[shortcrust_pastry|Shortcrust Pastry]]
* [[griddle_scones|Griddle Scones]]

### Cakes
* [[amalfi_lemon_bay_leaf_&_olive_oil_cake|Amalfi lemon & olive oil cake]]
* [[autumnal_birthday_cake|Autumnal birthday cake]]
* [[bitter_orange_tart|Bitter Orange tart]]

### Desserts
* [[baked_custard_w_roast_rhubarb|Baked custard with roast rhubarb]]
* [[blackberry_&_lemon_mess|Blackberry & Lemon Mess]]
* [[blackberry_galette|Blackberry Galette]]
* [[chilled_apricot_puddings|Chilled apricot puddings]]

### Sweet Snacks
* [[almond_raspberry_slice|Almond Raspberry Slice]]
* [[forgotten_cookies|Forgotten Cookies]]
* 

### Components
* [[aioli|Aioli]]
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
