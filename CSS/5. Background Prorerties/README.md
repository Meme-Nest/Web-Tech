<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Contents**

- [Background Properties](#background-properties)
  - [Notes](#notes)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Background Properties

1. background-color
1. background-image
1. background-position
1. background-repeat

```html
<html lang="en">
<head>
    <title>Document</title>
    <style>
        .p{
            height:350px;
            width: 550px;
            border: 10px cyan;
            border-style: ridge;
            background-color: darkcyan;
            background—image: url("img2.jfif") ;
            background—repeat : no-repeat ;
            background-position: center;
        }
        .p:hover{
            background-color: aqua;
            background—image: url ("img/img2.jpg") ;
        }
    </style>
</head>
<body>
    <p class="p">Welcome to web technologies: HTML CSS and Javascript</p>
</body>
</html>
```



## Notes

- background-color property is used to apply background color to the element or the complete web page

- background-image: url("image_name") property is used to apply background image to the webpage or the element.

- background-position property is used to set the background image in the particular position i.e. center,right,left,top,
  bottom.

- When the background image is not fitting to the webpage then the tiling of the image will happen. Tiling is a
  process of image is repeating to fit the background. To avoid tiling we can use "background-repeat" property.
