---
layout: default
title: GFM Markdown
nav_order: 1
parent: Jekyll+GitPage
grand_parent: Practice
updated_at:   2023-01-30 22:30:00 +0800
---
# GFM (GitHub Flavored Markdown)

遇到以下幾個問題。

## [Disallowed Raw HTML](https://github.github.com/gfm/#disallowed-raw-html-extension-)

不支援iframe，這會使得嵌入的Youtube影片無法顯示。

解決方式，在_config.yml裡面將以下此行註解掉即可。

```yml
#markdown: GFM
```

## [Task list items](https://github.github.com/gfm/#task-list-items-extension-)

雖然文件上寫說有支援，但實際並未正確顯示。解決方式同前，在_config.yml裡面將以下此行註解掉即可。

```yml
#markdown: GFM
```
