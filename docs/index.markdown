---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Home
nav_exclude: true
---
## Recently Updated

| Title      | Date     |
| :---        |     ---: |

{% assign sorted = site.pages | sort: 'last_modified_at' %}
{% for post in sorted limit:5 %}
{%- if post.title -%}
| {{ post.title }} | {{ post.updated_at  | date: '%Y-%m-%d' }} |
{%- endif -%}


{% endfor %}


## To Do List

### Review

#### Brain

 - The Extended Mind

### Zakka

#### Ukraine

 - Secret Project Studio
 - MomCooksJam
 - Wander Chocolate Boutique
 - Etnodim
 - NESAMOVYTO

### 小鎮研究室

#### 輕食

 - 乳化作用
 - 芽菜
