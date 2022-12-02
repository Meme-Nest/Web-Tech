<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Contents**

  - [
  Welcome to HTML and CSS
](#welcome-to-html-and-css)
- [CSS (Cascading Style Sheet)](#css-cascading-style-sheet)
  - [Syntax](#syntax)
- [Basic CSS Styling Properties](#basic-css-styling-properties)
  - [Color](#color)
  - [Font Family](#font-family)
  - [Text Align](#text-align)
  - [Font Size](#font-size)
  - [Background Color](#background-color)
  - [Border](#border)
    - [Example](#example)
- [Types of CSS](#types-of-css)
  - [Inline CSS](#inline-css)
    - [Example](#example-1)
  - [Internal CSS](#internal-css)
  - [External CSS](#external-css)
    - [Example](#example-2)
    - [Notes](#notes)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# CSS (Cascading Style Sheet)

## Syntax

![](img/syntax.PNG)

# Basic CSS Styling Properties

1. [Color](#color)
1. [font-family](#font-family)
1. [font-size](#font-size)
1. [text-align](#text-align)
1. [background-color](#background-color)
1. [border](#border)

## Color

```html
<h1 style="color:red">Hello World</h1>
```

> Output
>
> <h1 Style="color:red">Hello World</h1>

---

## Font Family

```html
<h1 style="font-family:cursive">Hello World</h1>
```

> Output
>
> <h1 Style="font-family:cursive">Hello World</h1>

---

## Text Align

```html
<h1 style="text-align:center">Hello World</h1>
```

> Output
>
> <h1 Style="text-align:center">Hello World</h1>

---

## Font Size

```html
<h1 style="font-size:20px">Hello World</h1>
```

> Output
>
> <h1 Style="font-size:20px">Hello World</h1>

---

## Background Color

```html
<h1 style="background-color:blue">Hello World</h1>
```

> Output
>
> <h1 Style="background-color:blue">Hello World</h1>

---

## Border

```html
<h1 style="border:solid">Hello World</h1>
```

> Output
>
> <h1 Style="border:solid red">Hello World</h1>

---

### Example

```html
<h2
  style="color:green;
font-fami ly : cursive;
text-align: center;
font-size:25px;
background-color: yellow;
border: solid"
>
  Welcome to HTML and CSS
</h2>
```

<h2
  style="color:green;
font-fami ly : cursive;
text-align: center;
font-size:25px;
background-color: yellow;
border: solid"
>
  Welcome to HTML and CSS
</h2>

# Types of CSS

- There are three types of css
  1. [Inline CSS](#inline-css) - Styled is used as attribute
  1. [Internal CSS](#internal-css) - Style is used as tag
  1. [External CSS](#external-css) - Style is used as stylesheet

## Inline CSS

<dd>Inline CSS is used to apply unique style to single element in the web page.
    <br>Style is used as attribute
</dd>
    
### Example
```html

<h1 style="color:red">Hello World</h1>
<h1 style="color:green">Hello World</h1>
```

## Internal CSS

#### Example

```html
<html>
  <head>
    <title>My WebPage</title>

    <style>
      hl,
      h2 {
        color: darkbtue;
        background—color: tightpink;
        text-align: center;
      }
      p {
        color: green;
        background-color: aqua;
        font-size: 20px;
      }
    </style>
  </head>
  <body>
    <h1>Heading1</h1>
    <p>Paragraph</p>
    <h1>Heading2</h1>
    <p>Paragraph</p>
    <h1>Heading2</h1>
  </body>
</html>
```

> ### Output
>
> ![](img/internal.PNG)

## External CSS

![](img/external%20css.PNG)

### Example

![](img/homepage.PNG)

### Notes

- External CSS is used to add common styling for different web elements in different webpages.

In external css separate style sheet is created and linked for multiple webpages(html files) in the web application.

- \<link> tag is used to link the stylesheet to the html file.
- \<link> tag must be used inside the head tag

In the \<link> tag, rel="stylesheet" attribute specifies the relationship of the html file and css file.

- href attribute specifies which stylesheet must be added to the html file.

- type="text/css" attribute specifies the type of file.
