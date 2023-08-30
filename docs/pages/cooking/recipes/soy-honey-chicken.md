---
layout: default
parent: Recipes
grand_parent: Cooking
title: Soy Honey Chicken
categories:
    - Dinner
    - Easy
featured_image: ./images/soy-honey-chicken.png
recipe:
  servings: 2
  prep: 20 min
  cook: 40 min
  ingredients_markdown: |-
    - 2 chicken thighs
    - Good amount of broccoli
    - 2-3 clove garlic
    - 1/4 cup soy sauce
    - 1/5-1/4 cup honey
    - Olive or sesame oil
  directions_markdown: |-
    1. Cook chicken in a nonstick pan, err on the side of slightly under
    2. Blanch the broccoli (best done in parallel with 1)
    3. Roast the broccoli in the chicken pan (maybe add olive/sesame oil), remove after
    4. Brown garlic in olive or sesame oil in chicken pan
    5. Add the soy sauce and honey to that pan
    6. Add the chicken back to the pan, flip as sauce reduces
    7. Once happy with sauce, plate chicken and broccoli, pour excess sauce over veg
---

<h1>{{ page.title }}</h1>
<img src="{{ page.featured_image }}" style="border-radius: 10px">

### Categories:
{% for tag in page.categories %}
{%- if forloop.last -%}
{{ tag }} 
{%- else -%} 
{{ tag }}, 
{%- endif -%}
{% endfor %}

### Servings:
{{ page.recipe.servings }}

### Time:
Prep: {{ page.recipe.prep }} \
Cook: {{ page.recipe.cook }}

### Ingredients:
{{ page.recipe.ingredients_markdown }}

### Directions:
{{ page.recipe.directions_markdown }}
