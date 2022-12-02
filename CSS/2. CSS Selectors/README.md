<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Contents**

- [CSS Selectors](#css-selectors)
  - [1. Universal Selector](#1-universal-selector)
    - [HTML](#html)
  - [2. Id Selector](#2-id-selector)
  - [3. Class Selector](#3-class-selector)
  - [Element Selector](#element-selector)
  - [Group Selector](#group-selector)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# CSS Selectors

<dd>CSS Selectors is used to select a perticular html element and based on the selection style is applied</dd>

1. Universal Selector
1. Id Selector
1. Class Selector
1. Group Selector

## 1. Universal Selector

- Universal selector is used to select all the elements in the webpage
- Universal selector is represented using `*`

### HTML

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Document</title>
    <style>
      * {
        color: firebrick;
        background-color: aquamarine;
        font—family: cursive;
      }
    </style>
  </head>
  <body>
    <p><u>Universal selector</u> is used to select alt the elements in the</p>
    <p>Universal selector is represented using *</p>
  </body>
</html>
```

## 2. Id Selector

- Id selector is used to select the html element based on the id.
- Id selector provides unique id to the html elements by using id attribute.
- Id selector is represented using #.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Document</title>
    <style>
      #KOD123 {
        color: darkorange;
        background-color: antiquewhite;
      }
      #one {
        color: darkcyan;
        background-color: aquamarine;
      }
    </style>
  </head>
  <body>
    <h3 id="KOD123">ld Selector</h3>
    <p id="KOD234">
      ld is used to select the html element based on the id. Id selector
      provides unique id to the html elements by using id attribute.
    </p>
    <p>Id selector is represented using #</p>
  </body>
</html>
```

## 3. Class Selector

- Class Selector is used to classify more than one html elements and based on the class, style is applied.
- Class attribute is used to classify the elements.
- Class selector is represented using `.`

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Document</title>
    <style>
      .augesta3 {
        color: red;
        background-color: cornsilk;
      }
      .augusta2 {
        color: yellow;
        background-color: red;
      }
    </style>
  </head>
  <body>
    <h3 class="augesta3">Class Selector</h3>
    <p class="augesta2">
      <u>class selector</u> is used to classify more than one html elements and
      based on the class, style is applied.
    </p>
    <p class="augesta2">class attribute is used to classify the elements.</p>
    <p class="augesta3">class selector is represented using .(dot)</p>
  </body>
</html>
```

## Element Selector

Element selector is used to select the html elements based on the element name.

## Group Selector

Group Selector is used to group one or more html elements and based
on the group style is applied.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Document</title>
    <style>
      p /* element selector */ {
        color: red;
        background—color: cornsilk;
      }
      /* group selector */
      h3,
      pre {
        color: red;
        background—color: lawngreen;
      }
    </style>
  </head>
  <body>
    <h3 class="augesta3">Element Selector</h3>
    <p class="augesta2">
      <u> Element selector </u> is used to select the html elements based on the
      element name.
    </p>
    <h3>Group Selector</h3>
    <pre><u>Group Selector</u> is used to group one or more html elements and based on the group style is apt tied.</pre>
  </body>
</html>
```
