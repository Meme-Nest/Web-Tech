<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Contents**

- [Transformation in CSS](#transformation-in-css)
    - [Notes](#notes)
  - [Rotate](#rotate)
  - [Scale](#scale)
  - [Skew](#skew)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Transformation in CSS

1. [Rotate](#rotate)
1. [Scale](#scale)
1. [Skew](#skew)

### Notes

- transformation properties in css is used to change the coordinates of an object or element.
- For transformation, css provides "transform" property. To the transform property we can add more effects like rotate skew, scale, translate, matrix etc.

## Rotate

<dd><b>rotate(angle)</b> : This function specifies the angle of rotation on the element.</dd>

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Rotate</title>
    <style>
      .div1 {
        height: 300px;
        width: 300px;
        border: 10px solid white;
        text-align: center;
      }
      .p1 {
        position: relative;
        top: 70px;
        height: 100px;
        width: 100px;
        border: 10px solid white;
        transform: rotate(30deg);
      }
    </style>
  </head>
  <body>
    <div class="div1">
      <center>
        <p class="p1">Hello!</p>
      </center>
    </div>
  </body>
</html>
```

<!DOCTYPE html>
<html lang="en">
 <head>
    <title>Rotate</title>
    <style>
        .div1{
            height:300px;
            width:300px;
            border: 10px solid white;
            text-align:center;
        }
        .p1{
            position:relative;
            top:70px;
            height:100px;
            width: 100px;
            border: 10px solid white;
            transform: rotate(30deg);
        }
    </style>
 </head>
   <body>
    <div class="div1">
        <center>
            <p class="p1">Hello!</p>
        </center>
    </div>
  </body>
</html>

## Scale

<dd><b>scale(x-axes,y-axes)</b>: This function specifies the scale transformation along with x and y axes based on the scale angle.</dd>

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Rotate</title>
    <style>
      .div2 {
        height: 300px;
        width: 300px;
        border: 10px solid white;
        text-align: center;
      }
      .p2 {
        position: relative;
        top: 70px;
        height: 100px;
        width: 100px;
        border: 10px solid white;
        /* transform: scale(1,2); */
        transform: scale(2, 1);
      }
    </style>
  </head>
  <body>
    <div class="div2">
      <center>
        <p class="p2">Hello!</p>
      </center>
    </div>
  </body>
</html>
```

<!DOCTYPE html>
<html lang="en">
 <head>
    <title>Rotate</title>
    <style>
        .div2{
            height:300px;
            width:300px;
            border: 10px solid white;
            text-align:center;
        }
        .p2{
            position:relative;
            top:70px;
            height:100px;
            width: 100px;
            border: 10px solid white;
            /* transform: scale(1,2); */
            transform: scale(2,1);
        }
    </style>
 </head>
   <body>
    <div class="div2">
        <center>
            <p class="p2">Hello!</p>
        </center>
    </div>
  </body>
</html>

## Skew

<dd>
<b>skew(x-axes,y-axes)</b> : This function specifies the skew transformation along with x and y axes based on the skew angle
</dd>

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Rotate</title>
    <style>
      .div3 {
        height: 300px;
        width: 300px;
        border: 10px solid white;
        text-align: center;
      }
      .p3 {
        position: relative;
        top: 70px;
        height: 100px;
        width: 100px;
        border: 10px solid white;
        /* transform: scale(1,2);  */
        transform: skew(25deg);
      }
    </style>
  </head>
  <body>
    <div class="div3">
      <center>
        <p class="p3">Hello!</p>
      </center>
    </div>
  </body>
</html>
```

<!DOCTYPE html>
<html lang="en">
 <head>
    <title>Rotate</title>
    <style>
        .div3{
            height:300px;
            width:300px;
            border: 10px solid white;
            text-align:center;
        }
        .p3{
            position:relative;
            top:70px;
            height:100px;
            width: 100px;
            border: 10px solid white;
             /* transform: scale(1,2);  */
            transform: skew(25deg);
        }
    </style>

 </head>
   <body>
    <div class="div3">
        <center>
            <p class="p3">Hello!</p>
        </center>
    </div>
  </body>
</html>
