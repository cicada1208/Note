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
- <del>Strikethrough</del>
- ==high light==
- 上標 30^th^
- 下標 H~2~O
- 數學式 $ 1 + 2 $

---

## List

1. Item 1
2. Item 2
    - Item 2a
    - Item 2b

---

`description lists key`

:   description 1.

    description 2.

---

- [x] Item 1
    - [ ] Item 1a
- [ ] Item 2
- [x] Item 3

---

## Table

|  Method  | Description                          |
| :------: | ------------------------------------ |
|  `PUT`   | :material-check-all: Update resource |
|  `GET`   | :material-check:     Fetch resource  |
| `DELETE` | :material-close:     Delete resource |

{{ read_excel('basics/table1.xlsx', engine='openpyxl', colalign=("center","right")) }}

---

## Block

使用 `行內代碼` 展示。

---

> We're living the future so
> the present is our past.

---

???+ note inline end "Customed Title"

    Lorem ipsum dolor sit amet, consectetur adipiscing elit.

!!! tip "Customed Title"

    Lorem ipsum dolor sit amet, consectetur adipiscing elit.

---

```javascript
function add(x, y) {
  return x + y;
}
```

---

## Footnotes

腳注 [^1]
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

```mermaid
graph LR
A-->B;
```

---

## Picture

![cat](basics/cat.jpg){data-title="title" data-description="description" width="40%" align=right loading=lazy}
![cat](basics/cat.jpg){data-description="description" width="30%" loading=lazy}

Lorem ipsum dolor sit amet, consectetur adipiscing elit.Nulla et euismod nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor massa, nec semper lorem quam in massa.
