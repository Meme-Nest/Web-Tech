# Object in JS
## 3 ways to create objects
1. Scripting
1. Procedural
1. Object Oriented

## Scripting Way of creating object

- Javascript stores the object in the form `Key: Value` pair.
- This form of creating the object in javascript is called as JSON format.
- JSON stands for Javascript Object Notation.


```js
var dog={
    name: "Rocky",
    age:10,
    bread:"Pog"
}
console.log(dog) //-> {name: 'Rocky', age: 10, bread: 'Pog'}
console.log(typeof(dog)) //-> object
```

## Accessing the elements
```js
var dog={
    name: "Rocky",
    age:10,
    bread:"Pog"
}
console.log(dog.name) // -> Rocky
// using [""]
console.log(dog["bread"]) // -> pog
```

## Adding properties to object
```js
var dog={
    name: "Rocky",
    age:10,
    bread:"Pog"
}

dog['color']='brown'
console.log(dog) //-> {name: 'Rocky', age: 10, bread: 'Pog', color: 'brown'}
```