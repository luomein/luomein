---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Home
nav_exclude: true
---
## Recently Updated

| Title      | Date     |
| :---       |     ---: |{% assign sorted = site.pages | sort: 'updated_at' | reverse %}{% for post in sorted limit:20 %}{% if post.title and post.nav_exclude != true %}
| [{{ post.title }}]( {{ post.url | relative_url }} ) `{{ post.grand_parent }}` `{{ post.parent }}` | {{ post.updated_at  | date: '%Y-%m-%d' }} |{% endif %}{% endfor %}

## To Do List

### Prototyping

#### Tableau

  - [ ] Unicode Infograph

#### File Maker

  - [ ] Kitchen Ghantt Chart

#### Hepta

  - [ ] Site Map

### Review

#### Brain

  - [ ] The Extended Mind

### Zakka

#### Rainy Day

  - [ ] 防水布料
  - [ ] 雨衣，KiU、MORR

#### Clothes

  - [ ] Dove Tail

#### Ukraine

  - [ ] Secret Project Studio
  - [ ] MomCooksJam
  - [ ] Wander Chocolate Boutique
  - [ ] Etnodim
  - [ ] NESAMOVYTO

### 小鎮研究室

#### 視野

  - [ ] AIS
  - [ ] 手機顯微鏡
  - [ ] Rotating Sky Explorer

#### 輕食

  - [ ] Soft Mater, Rheology
  - [ ] 芽菜
  - [ ] 乾貨
