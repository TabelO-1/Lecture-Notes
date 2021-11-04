# ✍️ Notes

1. What is the definition of forEach?
    *  `Array.forEach()` allows you to iterate through an array and executes a provided function once for each array element.
2. What data type can you call forEach on?
    *  An Array.
3. What does the pseudocode for forEach look like?
    *  `array.forEach(callback(currentValue, index, arr), thisValue);
4. What are the 2 input arguments for forEach?
    *  Must have a callback function, which is a function that runs on each item inside of the array.
    * thisValue, a value to be passed to the function to be used as it's `this` value
    * Index: optional, the array index of the currentValue
    * array: optional. The array object the current element belongs to. *this is rarely used*
5. What are the arguments the callback function takes in?
    *  `callback(currentValue, index, arr)`
6. What is currentValue referring to?
    *  This is the value of the current element that the `forEach()` is looking at. It is not an index, it is the value OF that index.
7. What is the output of forEach?
    *  undefined
8. Does forEach mutate the original array?
    * By default, `forEach()` does not mutate the array.
9. What does it mean when an argument is optional?
    * It means you do not have to use this arguement


# Resources
- [MDN on forEach](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach)
- [w3Schools on forEach](https://www.w3schools.com/jsref/jsref_foreach.asp)
- [JavaScript — The difference between ForEach, and For…In](https://codeburst.io/javascript-the-difference-between-foreach-and-for-in-992db038e4c2)
