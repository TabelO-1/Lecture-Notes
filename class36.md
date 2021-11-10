# ✍️ Notes


1. What is the definition of Array.map?
    * the `map()` method creates a new array populated with the results of calling a provided function AKA a callback function on every element in the calling array.

2. What data type can you call map on?
    * array.

3. What does the pseudocode for map look like?
    * `array.map(callback(currentValue, index, arr), thisArg);`.

4. What are the 2 input arguments for map?
    * `callback` and `thisArg`.

5. What are the arguments the callback function takes in?
    * `currentValue`, `index`, and `arr`.

6. What is currentValue referring to?
    * the current item in the array that is being used.

7. What is the output of map?
    * A new array back with each element being the result of the callback function

8. Does map mutate the original array?
    * no

9. What does it mean when an argument is optional?
    * It does not have to be used for your `array.map` for it to work

10. What is the only difference between Array.forEach and Array.map?
    * `array.forEach` returns undefined. `array.map` returns a new array.

# Resources
    - [MDN on map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)
    - [w3Schools on map](https://www.w3schools.com/jsref/jsref_map.asp)
    - [Why and when to use forEach, map, filter, reduce, and find in JavaScript](https://medium.com/@JeffLombardJr/understanding-foreach-map-filter-and-find-in-javascript-f91da93b9f2c)
- [YouTube: Shred Talk on Map](https://www.youtube.com/watch?v=erLq0zb01y4&list=PLVngfM2hsbi-L6G8qlWd8RyRbuTamHt3k&index=7)