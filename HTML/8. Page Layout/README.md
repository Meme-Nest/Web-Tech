<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Contents**

- [Page Layout](#page-layout)
- [Semantic tags](#semantic-tags)
    - [Example :](#example-)
  - [Header](#header)
  - [Nav](#nav)
  - [Section](#section)
  - [Article](#article)
  - [Aside](#aside)
  - [Footer](#footer)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Page Layout

![](img/Page%20Layout.png)

# Semantic tags

To create page layouts HTML provides semantic tags.

- [Header](#header)
- [Nav](#nav)
- [Section](#section)
- [Article](#article)
- [Aside](#aside)
- [Footer](#footer)

---

### Example :

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Document</title>
    <style>
      header,
      nav,
      footer {
        height: 50px;
        width: 99%;
        border: 5px solid;
      }
      section {
        width: 70%;
        height: 300px;
        border: 5px solid;
      }
      article {
        width: 70%;
        height: 100px;
        border: 5px solid;
      }
      aside {
        margin-left: 71%;
        margin-top: -64%;
        width: 28%;
        height: 415px;
        border: 5px solid;
      }
    </style>
  </head>
  <body>
    <header>header</header>
    <nav>nav</nav>
    <section>section</section>
    <article>article</article>
    <aside>aside</aside>
    <footer>footer</footer>
  </body>
</html>
```

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Document</title>
    <style>
     header,nav,footer{
        height:50px;
        width:99%;
        border: 5px solid;
     }
     section{
        width:70%;
        height:300px;
        border:5px solid;
     }
     article{
       width:70%;
        height:100px;
        border:5px solid; 
     }
     aside{
        margin-left:71%;
        margin-top:-64%;
        width:28%;
        height:415px;
        border:5px solid;
     }
    </style>
  </head>
  <body>
   <header>header</header>
   <nav>nav</nav>
   <section>section</section>
   <article>article</article>
   <aside>aside</aside>
   <footer>footer</footer>
  </body>
</html>

---

## Header

<dd>In this header tag the header contents like introductory contents, logo, authorship information etc will
be designed.</dd>

## Nav

<dd>This tag defines set of navigation links in the webpage.</dd>

## Section

<dd>This tag defines all the main contents of the webpage.</dd>

## Article

<dd>This tag defines all the section related information.</dd>

## Aside

<dd>This tag defines the content which is indirectly related to te surrounding content.<br>
Eg: Tips, adds etc.
</dd>

## Footer

<dd>
his tag defines the footer documents which is related to the webpage.<br>
Eg: sitemap, about us, terms and conditions, follow us, related documents, etc
</dd>
