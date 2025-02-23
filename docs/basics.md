---
# the front matters of Markdown Preview Enhanced
html:
  embed_local_images: false
  embed_svg: false
  offline: true
  toc: true

print_background: true

export_on_save:
  html: true

# the front matters of Material for MkDocs
tags:
  - Basic
  - Extension
---

# Markdown basics & extensions

## Font formatting

- **Bold**
- *Italic*
- ~~Strikethrough~~
- ^^Underline^^
- Text with suggested changes: ==High light==
- Text with suggested changes: {++added++}
- Text with suggested changes: {--deleted--}
- Text with suggested changes: combined into {~~one~>a single~~} operation
- Text with suggested changes: {>>comments<<}
- 上標: 30^th^
- 下標: H~2~O
- Keyboard keys: ++ctrl+alt+del++

---

## Math block syntax

Blocks must be enclosed in `$$...$$` or `\[...\]` on separate lines.

$$
\cos x=\sum_{k=0}^{\infty}\frac{(-1)^k}{(2k)!}x^{2k}
$$

---

## Math inline block syntax

數學式 $1+2*3$

---

## List

1. ordered list 1
2. ordered list 2
    - unordered list 2a
    - unordered list 2b

---

## Description list

`key`

:   description 1.

    description 2.

---

## Task list

- [x] task list 1
    - [ ] task list 1a
- [ ] task list 2
- [x] task list 3

---

## Table

|  Method  | Description                          |
| :------: | ------------------------------------ |
|  `PUT`   | :material-check-all: Update resource |
|  `GET`   | :material-check:     Fetch resource  |
| `DELETE` | :material-close:     Delete resource |

/// caption | <
Table Caption prepend: to place a caption directly before a block
///

/// table-caption
Table Caption: to place a caption directly after a block
///

---

## Table by import file

{{ read_excel('basics/table1.xlsx', engine='openpyxl', colalign=("center","right")) }}

/// table-caption
Table Caption: to place a caption directly after a block
///

---

## Inline code

使用 `行內代碼` 展示。

---

## Introduction

> We're living the future so
> the present is our past.

---

## Admonition

???+ note inline end "Admonition Title"

    Lorem ipsum dolor sit amet, consectetur adipiscing elit.

!!! tip "Admonition Title"

    Lorem ipsum dolor sit amet, consectetur adipiscing elit.

---

## Code block

``` javascript linenums="1"
function add(x, y) {
  return x + y;
}
```

---

## Footnote

注腳 [^1]
[^1]:
    This is a footnote.
    Lorem ipsum dolor sit amet, consectetur adipiscing elit.

---

## Link with tooltip {#link-tooltip}

[Hover me](https://example.com "I'm a tooltip!")

---

## Icon with tooltip

:material-information-outline:{ title="Important information" }

---

## Diagram

``` mermaid
graph LR
A-->B;
```

---

## Picture

![cat](basics/cat.jpg){data-title="title" data-description="description" width="40%" align=right loading=lazy}
![cat](basics/cat.jpg){data-description="description" width="30%" loading=lazy}

Lorem ipsum dolor sit amet, consectetur adipiscing elit.Nulla et euismod nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor massa, nec semper lorem quam in massa.
