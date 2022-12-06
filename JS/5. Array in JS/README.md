# Array in JS

```js
var arr=[10,20,30,40,50]
console.log(arr)
console.log(typeof(arr))
var arr=[10,true,"Memenest",10.5]
console.log(arr)
console.log(typeof(arr))
```

![](Array%20in%20js.PNG)

## Adding element in Array
```js
var arr=[10,true,"Memenest",10.5]
arr[2]=100
console.log(arr) // => [10,100,"Memenest",10.5]
```

## Push()
<dd>Appends new elements to the end of an array, and returns the new length of the array.</dd>

```js
var arr=[10,true,"Memenest",10.5]
arr.push(100)
console.log(arr) // => [10,true,"Memenest",10.5,100]
```
## unshift()

<dd>Inserts new elements at the start of an array, and returns the new length of the array.</dd>

```js
var arr=[10,true,"Memenest",10.5]
arr.unshift("Start")
console.log(arr) // => ["start",10,true,"Memenest",10.5]
```

## Pop()
<dd>Removes the last element from an array and returns it.</dd>

```js
var arr=[10,true,"Memenest",10.5]
arr.pop()
console.log(arr) // => [10,true,"Memenest"]
```


## Push()

```js
var arr=[10,true,"Memenest",10.5]
arr.push()
console.log(arr) // => [true,"Memenest",10.5]
```
## Shift()

<dd>Removes the first element from an array
and returns it.</dd>

```js
var arr=[10,true,"Memenest",10.5]
arr.shift()
console.log(arr) // => [true,"Memenest",10.5]
```
## Fetching element in Array

```js
var arr=[10,true,"Memenest",10.5]
console.log(arr[2]) // => "Memenest"
```

## Splice()
- Sysntax  :
    -  `splice(index,deleteCount)`
    - `splice(index,deleteCount,ItemToBeDeleted)`

### Example
```js
arr=[10,20,30,40,50]
arr.splice(2,2) // => [10,20,50]
```

```js
arr=[10,20,30,40,50]
arr.splice(1,2) // => [10,50]
```
```js
arr=[10,20,30,40,50]
arr.splice(1,0) // => [10,20,30,40,50]
```

```js
arr=[10,20,30,40,50]
arr.splice(1,2,100,true,50,40,50) // => [10,100,true,50,40,50]
```
```js
arr=[10,20,30,40,50]
arr.splice(2,1,100,20) // => [10,20,100,20,40,50]
```
```js
arr=[10,20,30,40,50]
arr.splice(0,0,20,50,30,100) // => [20,50,30,100,10,20,30,40,50]
```

## Slice()
<dd>Returns a copy of a section of an array. For both start-index and end-index. End-index is exclusive.</dd>

```js
var ar = [10,20,30,40,50]
console,log(ar) // -> [10,20,30,40,50]
var new_ar=ar.slice(1,3)
console,log(ar) // -> [10,20,30,40,50]
console,log(new_ar) // -> [20,30]

var new_ar1 = ar.slice(0,4)
console.log(new_ar1)// -> [10,20,30,40,50]
```