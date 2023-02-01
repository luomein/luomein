---
layout: default
title: Table範例
nav_order: 2
parent: Jekyll+GitPage
grand_parent: Practice
updated_at:   2023-02-01 10:30:00 +0800
nav_exclude: true
---
- 注意事項
    - 有些標籤在 Table Markdown 中無法正常顯示。
    - [以迴圈產生 Table 內容時，需注意 Whitespace Control。](https://stackoverflow.com/questions/35642820/jekyll-how-to-use-for-loop-to-generate-table-row-within-the-same-table-inside-m)

## [Table Markdown](https://github.github.com/gfm/#tables-extension-)

```
| head1        | head two          | three |
|:------------:|:------------------|------:|
| #1           | swedish fish      | 123   |
| #2           | egg               | 5     |
```

## [Formatting Text in Tables](https://www.markdownguide.org/extended-syntax/#formatting-text-in-tables)

### Inline Code Snippet

| head1        | head two          | three |
|:------------:|:------------------|------:|
| #1           | `swedish` fish      | 123   |
| #2           | egg               | 5     |

```
| head1        | head two          | three |
|:------------:|:------------------|------:|
| #1           | `swedish` fish      | 123   |
| #2           | egg               | 5     |
```

### 需要以 HTML Tag 才能顯示的格式

- [換行](https://www.markdownguide.org/hacks/#line-breaks-within-table-cells)

- [Lists Within Table Cells](https://www.markdownguide.org/hacks/#lists-within-table-cells)

### Button and Label

- ✅  搭配 Links 可正常顯示

| head1        | head two          | three |
|:----------:  |:------------------|------:|
| #1           | swedish fish [Link button](http://example.com/){: .btn  .fs-8 } [Link button](http://example.com/){: .btn .btn-blue }     | 123   |
| #2           | egg  [Link button](http://example.com/){: .label .fs-1 } [Link button](http://example.com/){: .label .label-green }             | 5     |

```
| head1        | head two          | three |
|:----------:  |:------------------|------:|
| #1           | swedish fish [Link button](http://example.com/){: .btn  .fs-8 } [Link button](http://example.com/){: .btn .btn-blue }     | 123   |
| #2           | egg  [Link button](http://example.com/){: .label .fs-1 } [Link button](http://example.com/){: .label .label-green }             | 5     |
```


- ❌  無法顯示的格式

| head1        | head two          | three |
|:----------:  |:------------------|------:|
| #1           | swedish fish {: .fs-8 }  | 123   |
| #2           | egg  {: .label }      | 5     |

```
| head1        | head two          | three |
|:----------:  |:------------------|------:|
| #1           | swedish fish {: .fs-8 }  | 123   |
| #2           | egg  {: .label }      | 5     |
```
