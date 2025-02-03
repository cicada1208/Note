---
html:
  embed_local_images: false
  embed_svg: false
  offline: true
  toc: true

print_background: true

export_on_save:
  html: true
---

# Collect your documents with a book

View the book with "<i class="fa fa-book fa-fw"></i> Book Mode".

## Examples

- [Book example](/s/book-example)
- [Slide example](/s/slide-example)
- [YAML metadata](/s/yaml-metadata)
- [Features](/s/features)

## Themes

- [Dark theme](/theme-dark?both)
- [Vertical alignment](/theme-vertical-writing?both)

## Test

123
~~**456**~~

==highlight==

我覺得你應該在這裡使用 `行內代碼` 才對。

> We're living the future so
> the present is our past.

```javascript
function add(x, y) {
  return x + y;
}
```

- Item 1
- Item 2

  - Item 2a
  - Item 2b

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] this is a complete item
- [ ] this is an incomplete item

| First Header                | Second Header       |
| --------------------------- | ------------------- |
| Content from cell 1         | Content from cell 2 |
| Content in the first column |                     |

上標 30^th^
下標 H~2~O

$ 1 + 2 $

腳注 [^1]
[^1]: This is a footnote

腳注 2 [^2]
[^2]: Test

```mermaid
graph LR
A-->B;
```

---

![cat](pic/cat.jpg){width="50%"}

@import "pic/cat.jpg" {width="50%" title="圖片標題" alt="我的 alt"}

###### tags: `Templates` `Book`

@import "test2.md"
