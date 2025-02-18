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

## Font style

- **Bold**

- ~~Strikethrough~~

- ==high light==

- 上標 30^th^

- 下標 H~2~O

- 數學式 $ 1 + 2 $

## Link with tooltip {#link-tooltip}

[Hover me](https://example.com "I'm a tooltip!")

## Icon with tooltip

:material-information-outline:{ title="Important information" }

## List

- Item 1
- Item 2

  - Item 2a
  - Item 2b

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] this is a complete item
- [ ] this is an incomplete item

## Table

| First Header                |    Second Header    |
| --------------------------- | :-----------------: |
| Content from cell 1         | Content from cell 2 |
| Content in the first column |                     |

## Block

使用 `行內代碼` 展示。

> We're living the future so
> the present is our past.

???+ note inline end "Customed Title"

    Lorem ipsum dolor sit amet, consectetur adipiscing elit.

!!! tip "Customed Title"

    Lorem ipsum dolor sit amet, consectetur adipiscing elit.

```javascript
function add(x, y) {
  return x + y;
}
```

腳注 [^1]
[^1]: This is a footnote

## Diagram

```mermaid
graph LR
A-->B;
```

---

## Picture

<img src='../test/cat.jpg' width=30%/>

![cat](test/cat.jpg){width="50%"}

@import "test/cat.jpg" {width="50%" title="圖片標題" alt="我的 alt"}
