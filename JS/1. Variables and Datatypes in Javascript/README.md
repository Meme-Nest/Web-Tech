<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Contents**

- [Variables and Datatypes in Javascript](#variables-and-datatypes-in-javascript)
  - [Statically typed language and Dynamically typed languages](#statically-typed-language-and-dynamically-typed-languages)
  - [Variables in Javascript](#variables-in-javascript)
    - [Example](#example)
    - [Output :](#output-)
- [Redefining the variable inside the scope](#redefining-the-variable-inside-the-scope)
  - [var](#var)
  - [let](#let)
  - [const](#const)
- [Reinitializing the variable inside the scope](#reinitializing-the-variable-inside-the-scope)
  - [var](#var-1)
  - [let](#let-1)
  - [const](#const-1)
  - [Defrences](#defrences)
  - [Note:](#note)
- [Datatype](#datatype)
  - [Number](#number)
  - [String](#string)
  - [Boolean](#boolean)
  - [Null](#null)
  - [Undefined](#undefined)
  - [Array](#array)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Variables and Datatypes in Javascript

## Statically typed language and Dynamically typed languages

- **Statically typed languages** are such languages where the datatype of the variable must be specified by the programmer.

  eg: Java, C , C++.

- **Dynamically Typed language** are such languages where the datatype of the variable is specified by the language interpreter during runtime.

  eg: Javascript, Python, Ruby.

## Variables in Javascript

To declare variable in javascript, datatype is not provided by the programmer but the variable names in javascript must be declared using three keywords:

i.e : `var`, `let` and `const`

### Example

```js
var n = 100;
document.write(n + " ");

let x = 200;
document.write(x + " ");

const y = 500;
document.write(y + " ");
```

### Output :

![](img/variables.png)

# Redefining the variable inside the scope

## var

```js
{
  var n = 200;
  console.log(n);
  var n = 300;
  console.log(n);
}
```

> ### Output
>
> ![](img/var%20redefine.PNG)

## let

```js
{
  let n = 200;
  console.log(n);
  let n = 300;
  console.log(n);
}
```

> ### Output
>
> ![](img/let%20redefine.PNG)

## const

```js
{
  const n = 200; // SyntaxError: Identifier 'y' has already been declared
  console.log(n);
  const n = 300;
  console.log(n);
}
```

> ### Output
>
> ![](img/const%20redefine.PNG)

# Reinitializing the variable inside the scope

## var

```js
{
  var n = 200;
  console.log(n);
  n = 300;
  console.log(n);
}
```

> ### Output
>
> ![](img/var%20reinitialization.PNG)

## let

```js
{
  let n = 200;
  console.log(n);
  n = 300;
  console.log(n);
}
```

> ### Output
>
> ![](img/let%20reinitialization.PNG)

## const

```js
{
  const n = 200;
  console.log(n);
  n = 300;
  console.log(n);
}
```

> ### Output
>
> ![](img/const%20reinitialization.PNG)

## Defrences

| var                                                                     | let                                                                        | const                                                                        |
| ----------------------------------------------------------------------- | -------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| Variable declared using `var` keyword can be accessed outside the scope | Variable declared using `let` keyword cannot be accessed outside the scope | Variable declared using `const` keyword cannot be accessed outside the scope |
| Variable can be redeclare once created.                                 | Variable cannot be redeclare are once created                              | Variable cannot be redeclared once created.                                  |
| Variable can be reinitialized once declared.                            | Variable can be reinitialized once declared. created                       | Variable cannot be reinitialized once declared.                              |

## Note:

Every Languages will be having different flavours i.e

1. **Scripting Language**: In scripting style of programming, code doesn't include class object or functions. Scripting language use interpretation.

2. **Procedural Language**: In procedural style of programming, only functions will be there.

   - Eg: C

3. **Object-Oriented Language**: In Object-oriented style of programming, class objects methods will be there and programming languages will be compiled and interpreted languages.
   - Eg: Java, C++

# Datatype

1. Number
1. String
1. Boolean
1. null
1. undefined
1. Array
1. object

## Number

<dd>In Javascript any size of numbers, whole number ald real number is stored using the "number" datatype.</dd>

```js
var n = 100;
console.log(n);
console.log(typeof n);

n = 2848324887449;
console.log(n);
console.log(typeof n);

n = 458.27391;
console.log(n);
console.log(typeof n);
```

![](img/Number.PNG)

## String

```js
let s = "k";
console.log(s);
console.log(typeof s);

let s1 = "k";
console.log(s1);
console.log(typeof s1);

let s2 = "Kodnest";
console.log(s2);
console.log(typeof s2);

let s3 = "Kodnest";
console.log(s3);
console.log(typeof s3);
```

![](img/String.PNG)

## Boolean

```js
let b = true;
console.log(b);
console.log(typeof b);
```

![](img/Boolean.PNG)

## Null

```js
var s;
console.log(s);
console.log(typeof s);
```

![](img/Null.PNG)

## Undefined

```js
var s;
console.log(s);
console.log(typeof s);
```

![](img/undifined.PNG)

## Array

```js
var a = [1, 2, 3, 4, 5];
console.log(a);
console.log(typeof a);
```

![](img/Array.PNG)
