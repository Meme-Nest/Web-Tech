<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Contents**

- [Border Properties](#border-properties)
    - [Example](#example)
    - [ 
     Solid  
     Dotted  
     Ridge  
     Groove  
     Dashed  
     Mixed  
  ](#solid--%0A-----dotted--%0A-----ridge--%0A-----groove--%0A-----dashed--%0A-----mixed)
    - [](#)
    - [](#-1)
    - [](#-2)
    - [](#-3)
    - [](#-4)
    - [](#-5)
    - [](#-6)
    - [](#-7)
    - [](#-8)
    - [](#-9)
    - [](#-10)
    - [Output :](#output-)
  - [Border Radius](#border-radius)
    - [Example](#example-1)
    - [ Border Radius  
     Border Radius  
  ](#border-radius--%0A-----border-radius)
    - [](#-11)
    - [](#-12)
    - [](#-13)
    - [Output :](#output--1)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Border Properties

    border: <thickness> <border type> <color>;
    border-top: <thickness> <border type> <color>;
    border-right: <thickness> <border type> <color>;
    border-bottom: <thickness> <border type> <color>;
    border-left: <thickness> <border type> <color>;

### Example

```html
<html lang="en">
  <head>
    <title>Document</title>
    <style>
        .sol{
            border: 2px solid black;
        }
        .dot{
            border: 15px dotted red;
        }
        .rid{
            border: 15px ridge green;
        }
        .groove{
            border: 15px groove red;
        }
        .dashed{
            border: 5px dashed red;
        }.mixed{
            border-top: 15px red;
            border-top-style:solid;
            border—bottom: 10px black;
            border-bottom-style : dashed ;
            border—right:20px double green;
            border—left: 10px dotted blue;
        }
    </style>

  </head>
  <body>
    <h3 class="sol"> Solid  <h3>
    <h3 class="dot"> Dotted  <h3>
    <h3 class="rid"> Ridge  <h3>
    <h3 class="groove"> Groove  <h3>
    <h3 class="dashed"> Dashed  <h3>
    <h3 class="mixed"> Mixed  <h3>
  </body>
</html>
```

### Output :

<html lang="en">
  <head>
    <title>Document</title>
    <style>
        .sol{
            border: 2px solid black;
        }
        .dot{
            border: 15px dotted red;
        }
        .rid{
            border: 15px ridge green;
        }
        .groove{
            border: 15px groove red;
        }
        .dashed{
            border: 5px dashed red;
        }.mixed{
            border-top: 15px red;
            border-top-style:solid;
            border—bottom: 10px black;
            border-bottom-style : dashed ;
            border—right:20px double green;
            border—left: 10px dotted blue;
        }
    </style>

  </head>
  <body>
    <h3 class="sol"> Solid  <h3>
    <h3 class="dot"> Dotted  <h3>
    <h3 class="rid"> Ridge  <h3>
    <h3 class="groove"> Groove  <h3>
    <h3 class="dashed"> Dashed  <h3>
    <h3 class="mixed"> Mixed  <h3>
  </body>
</html>

---

## Border Radius

![](img/border%20Radius.PNG)

### Example

```html
<html lang="en">
  <head>
    <title>Document</title>
    <style>
        .head{
            border: 10px solid hotpink;
            border-radius: 50px;
        }
        .bottom{
            border: 10px solid hotpink;
            border-bottom-left-radius: 50px;
            border-top-left-radius: 50px;
            border-bottom-right-radius: 10px;
            border-top-right-radius: 10px;
            text-align:center;
        }
    </style>

  </head>
  <body>
    <h3 class="head"> Border Radius  <h3>
    <h3 class="bottom"> Border Radius  <h3>
  </body>
</html>
```

### Output :

<html lang="en">
  <head>
    <title>Document</title>
    <style>
        .head{
            border: 10px solid hotpink;
            border-radius: 50px;
        }
        .bottom{
            border: 10px solid hotpink;
            border-bottom-left-radius: 50px;
            border-top-left-radius: 50px;
            border-bottom-right-radius: 10px;
            border-top-right-radius: 10px;
            text-align:center;
        }
    </style>

  </head>
  <body>
    <h3 class="head"> Border Radius  <h3>
    <h3 class="bottom"> Border Radius  <h3>
  </body>
</html>
