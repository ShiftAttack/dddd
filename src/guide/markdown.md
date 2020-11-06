---
icon: markdown
title: Markdown Enhance
category: Guide
tag:
  - markdown
---


`vuepress-theme-hope` enables more syntax in Markdown via the built-in [md-enhance](https://vuepress-md-enhance.mrhope.site) plugin.

## Enable all

You can set `themeconfig.mdEnhance.enableAll` to enable all features of the [md-enhance](https://vuepress-md-enhance.mrhope.site) plugin.

```js {3-5}
module.exports = {
  themeConfig: {
    mdEnhance: {
      enableAll: true,
    },
  },
};
```

## New Feature

### Superscript and Subscript

19^th^ H~2~O

- [View Detail](https://vuepress-theme.mrhope.site/guide/feature/markdown/sup-sub/)

### Align

::: center
I am center
:::

::: right
I am right align
:::

- [View Detail](https://vuepress-theme.mrhope.site/guide/feature/markdown/align/)

### Footnote

This text has footnote[^first].

[^first]: This is footnote content

- [View Detail](https://vuepress-theme.mrhope.site/guide/feature/markdown/footnote/)

### Mark

You can mark ==important words== .

- [View Detail](https://vuepress-theme.mrhope.site/guide/feature/markdown/mark/)

### Flowchart

@flowstart
cond=>condition: Process?
process=>operation: Process
e=>end: End

cond(yes)->process->e
cond(no)->e
@flowend

- [View Detail](https://vuepress-theme.mrhope.site/guide/feature/markdown/flowchart/)

### Tex

$$
\frac {\partial^r} {\partial \omega^r} \left(\frac {y^{\omega}} {\omega}\right)
= \left(\frac {y^{\omega}} {\omega}\right) \left\{(\log y)^r + \sum_{i=1}^r \frac {(-1)^i r \cdots (r-i+1) (\log y)^{r-i}} {\omega^i} \right\}
$$

- [View Detail](https://vuepress-theme.mrhope.site/guide/feature/markdown/tex/)

### Presentation

@slidestart

## Slide 1

A paragraph with some text and a [link](https://mrhope.site)

---

## Slide 2

- Item 1
- Item 2

---

## Slide 3.1

```js
const a = 1;
```

--

## Slide 3.2

$$
J(\theta_0,\theta_1) = \sum_{i=0}
$$

@slideend

- [View Detail]((https://vuepress-theme.mrhope.site/guide/feature/markdown/presentation/))
