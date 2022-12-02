<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Contents**

- [Basic Tags in HTML](#basic-tags-in-html)
  - [Heading Tags](#heading-tags)
- [h1](#h1)
  - [h2](#h2)
    - [h3](#h3)
    - [output](#output)
  - [Paragraph Tag](#paragraph-tag)
  - [Pre-Formatted Tag](#pre-formatted-tag)
    - [Difference between \<p> and \<pre>](#difference-between-%5Cp-and-%5Cpre)
  - [Anchor Tag](#anchor-tag)
    - [Notes :](#notes-)
  - [Inline and block Tags](#inline-and-block-tags)
  - [Break Tag](#break-tag)
  - [Horizontal Rule Tag](#horizontal-rule-tag)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->



# Basic Tags in HTML

## Heading Tags

- In HTML, to display different levels of headings Heading Tags are used.
- There are 6 levels of heading tags i.e `<hl>`, `<h2>`,`<h3>`,`<h4>`,`<h5>` and `<h6>`.
- All of these tags are used to display different levels of headings.
- `<hl>` tag is used to display the most important headings and `<h6>` tag is used to display the least important headings in the webpage.

```html
<h1>h1</h1>
<h2>h2</h2>
<h3>h3</h3>
<h4>h4</h4>
<h5>h5</h5>
<h6>h6</h6>
```

### output

  <h1>h1</h1>
  <h2>h2</h2>
  <h3>h3</h3>
  <h4>h4</h4>
  <h5>h5</h5>
  <h6>h6</h6>

---

## Paragraph Tag

```HTML
<p></p>
```

## Pre-Formatted Tag

```HTML
<pre></pre>
```

### Difference between \<p> and \<pre>

1. \<p> tag and \<pre> tag both are used to display the paragraph in the webpage.
2. \<p> displays the content in different font size and font style when compared to \<pre> tag.
3. \<p> will not preserve the space where as \<pre> tag will preserve the space as it is in the paragraph.
4. When there is multiple line in the paragraph tag will adjust the size and display the content in proper paragraph format whereas \<pre> tag will display the content in a single line by exceeding the limit screen width.

## Anchor Tag

```HTML
<a href="https://www.google.co.in/"> Google </a>
```

#### output

<a href="https://www.google.co.in/"> Google </a>

---

### Notes :

- **Anchor tag** is used to create hyper text or hyper links in the webpage.
- **Attributes** : Attributes are the mechanism to add extra behavior or functionalities to the tags.
- **Attributes** are used in the open tags of any tags.
- href attribute in anchor tag is used to link the Webpage for the given hyper text.

## Inline and block Tags

- **Block level tag** are such tags which will start the contents in the new line. Block level tags will
  automatically give the line break.
  - eg: all the heading tags, \<pre>,
- **Inline tags** are such tags which will display the content in the same line. It will not give the line break.

  - eg: \<a>

> Example : \<p> is block tag and \<a> is inline tag
> ![](img/inline%20and%20block%20tags.PNG)

---

## Break Tag

---

```HTML
<br>
```

- Break tag is used to break the line
  > ![break tag](img/break%20tag.PNG)

---

## Horizontal Rule Tag

---

```HTML
<hr>
```

- \<hr> tag or horizontal rule tag is used to display one horizontal line in the webpage. This tag mainly used to separate the contents in the webpage

> ![](img/hr%20tag.PNG)
