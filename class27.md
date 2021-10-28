# ✍️ Notes
1. List some of JavaScript's data types:
- Array, String, Boolean, Object, Function, Symbol, Undefined, Null

2. In JavaScript, ______ __________ is an object.
- All Javascript values, except primtives, are objects.

3. What are "JavaScript Primitives"?
- A primitive is a value that has no properties or methods. A primtive data type is data that has a primtive value

4. How many primitive data types are there?
- There are 7 primtive data types: string, number, bigint, boolean, undefined, symbol, and null.

5. What are the three JavaScript Primative Wrapper types?
- JavaScript provides three primitive wrapper types: Boolean, Number, and String types.

6. What does a JavaScript Primative Wrapper do?
- The primtive wrappers make it easier to call JavaScript's built-in methods on the primitive value.

7. What is the Primative Wrapper doing under the hood when you call a method on a variable that holds a number, a string, or a boolean?
- JavaScript will create an object of a corresponding type. Then call the method on the instance. And lastly, Javascript deletes the instance immediately after it is finished and moves onto the next script.

8. What are functions that are binded to an object called?
- method

9. So if almost everything in JavaScript is an object, what does that mean for most data types?
- Most data types will have their very own special methods built into JS.

10. What do these special built-in methods do?
- A method can accomplish any number of popular tasks in programming. A few popular tasks are: adding values, remove values, moving values, modifying values or reading values.

11. How do we access a method on an object?
- dot notation

12. How do we use a built-in method on a JavaScript data type?
- use dot notation on the variable name to invoke the method
```
let foo = "bannana!"
let caps = foo.toUpperCase();
console.log(caps) //BANNANA!
```

13. What kind of built-in methods are we going to learn about in 301?
- string methods
- array methods
- object methods
- number methods
- math methods

14. Where can you go to learn about the different methods avaiable to each data type?
- Google It!
- MDN Web Docs
- W3Schools

15. How am I suppose to know what to search for in Google?
- An easy way to search for methods that would help solve your algorithm is to use this pattern:
    > "how to" + "to the thing" + "data type" + "JavaScript"
    >
    > ex: "how to slice string JavaScript"
# TODO
 - [x] Copy paste
 - [x] Complete Lecture Notes
 - [x] Complete on time
 - [ ] ~~Conquer the World~~
# Resources
- [MDN on Standard built-in objects](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects)
- [w3Schools on Objects](https://www.w3schools.com/js/js_object_definition.asp)
- [MDN on Primitives](https://developer.mozilla.org/en-US/docs/Glossary/Primitive)
- [JavaScript Primitive Wrapper Types](https://www.javascripttutorial.net/javascript-primitive-wrapper-types/)
