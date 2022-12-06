# 3. Loop Control Construct
1. ## For loop
    - Iterates over iterable objects
    - Example
    ```js
    var a=[10,20,30,40,50]
    for(var i = 0;i<a.length;i++){
        console.log(a[i])
    }
    ```

1. ## For-of loop
    - Iterates over iterable objects
    - Example
    ```js
    var a=[10,20,30,40,50]
    for(var i : a){
        console.log(i)
    }
    ```
1. ## For-in loop
    - Iterates over non-iterable objects
    ```js
    var dog={
    name: "Rocky",
    age:10,
    bread:"Pog"
    }
    for(var k in dog)
    {
        console.log(dog[k])
    }
    ```
## Notes
- for loop and for-of loop is used to iterate on the iterable object.
- Iterable objects are such objects which have the index positions. Eg: array.
- for-in loop is used to iterate on non-iterable objects. Non-iterable
- Object are such objects which doesn't have the index positions.
eg: Object 
1