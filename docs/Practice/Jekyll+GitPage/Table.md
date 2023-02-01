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
    - 以迴圈產生 Table 內容時，需注意 Whitespace Control。

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
