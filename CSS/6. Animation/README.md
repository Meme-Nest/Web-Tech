<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Contents**

- [Animation](#animation)
    - [Output](#output)
  - [Example 2](#example-2)
    - [Output](#output-1)
  - [Notes](#notes)
  - [Syntax for creating animation in css](#syntax-for-creating-animation-in-css)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Animation

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Document</title>
    <style>
      .ani {
        height: 100px;
        width: 100px;
        border: 10px groove red;
        background-color: lime;
        /* animation-name: august_ani ;
            animation-duration: 3s;
            animation—iteration—count: infinite; */
        animation: august_ani 3s infinite;
      }
      /* animation */
      @keyframes august_ani {
        from {
          background—color: lime;
          border: 30px ridge red;
        }
        to {
          background-color: blue;
          border: 60px groove yellow;
        }
      }
    </style>
  </head>
  <body>
    <p class="ani"></p>
  </body>
</html>
```

### Output

![](gif/Animation1.gif)

## Example 2

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Document</title>
    <style>
      .ani2 {
        height: 100px;
        width: 100px;
        border: 10px solid red;
        background-color: lime;
        border-radius: 200px;
        position: relative;
        /* animation-name: august_ani ;
            animation-duration: 3s;
            animation—iteration—count: infinite; */
        animation: animation1 10s infinite;
      }
      /* animation */
      @keyframes animation1 {
        0% {
          left: 0px;
          top: 0px;
        }
        25% {
          left: 350px;
          top: 0px;
        }
        50% {
          left: 350px;
          top: 350px;
        }
        75% {
          left: 0px;
          top: 350px;
        }
        100% {
          left: 0px;
          top: 0px;
        }
      }
    </style>
  </head>
  <body>
    <div style="height:500px">
      <p class="ani2"></p>
    </div>
  </body>
</html>
```

### Output

![](gif/Animation2.gif)

## Notes

- animation-name property specifies the animation name to an element.
- if an element specified with the animation-name property then that element will be applied with the specified animation

  ## animation-duration

  - animation-duration property specifies the duration of the animation on the element.

  ## animation-iteration-count

  - animation-iteration-count property specifies the total iteration of the repetition of the animation to be infinite.

  ## animation property

  - animation property specifies all the above animation properties at once.

## Syntax for creating animation in css

---

```css
@keyframes animation_name{
/* animation */
)
```

Here, @keyframes is an annotation used in css for creating animation.
