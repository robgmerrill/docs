---
Title: "sepia()"
Subjects:
  - "Web Development"
  - "Web Design"
Tags:
  - "Images"
  - "Functions"
  - "Colors"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-css"
  - "https://www.codecademy.com/learn/paths/front-end-engineer-career-path"
  - "https://www.codecademy.com/learn/paths/full-stack-engineer-career-path"
---

## Definition

Changes the color of an element to sepia.

## Syntax

```css
filter: sepia(<value>);
```

where a required `<value>` can be one of the following:

- Number value: `0`, `1`
- Percentage value: `10%`, `50%`

**Note:** Value defaults to `1` or `100%` turning the element to sepia. A value of `0` and `0%` will leave element unchanged. Negative values as well as values greater than `1` or `100%` are not allowed.

## Example 1
 
Set sepia to `100%`:

```css
.banner-image {
  filter: sepia(100%);
}
```

