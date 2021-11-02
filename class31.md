# ✍️ Notes

1. What are loops used for in programming?
    * Loops offer a quick and easy way to do something quickly
    * Handy if you want to run the same code over and over but with different data each time
2. What are the 5 different types of loops we work with in JavaScript?
    * For Loops: Loops through a block of code a number of times
    * While Loop: Loops through a block of code while a specified condition is true
    * Do While: also loops through a block of code while a specified condition is truw
    * For In: Loops through the properties of an object
    * For Of: Loops throught the values of an iterable object
3. What is the definition of a for loop?
    * The for statement creates a loop that consists of three option expressions, enclosed in () and seperated by ;, followed by a statement (usually a block statement) to be executed in the loop
4. What is the syntax and pseudocode of a for loop?
    * ``` for (initialExperssion; conditional expression; interatorExpression) {code block to run at every iteration;} ```
5. What does the initial expression do?
    * The initialExpression is ran once at the begging of the for loop and it initializes the variable used in the loop
6. Why is it important to use `let` when declaring the `i` variable in a loop?
    * the variable i will only be in the scope of the for loop
7. What does the conditional expression do?
    * Defines the condition for the loop to run. If the condition returns true, the loop will start over again, if it returns false, the loop will end.
8. What does the iterator expression do?
    * it adds/minus one iteration for each time the loop is run.
    `i++, i--`
9. When a for loop executes, the following occurs:
    * STEP 1: The initializing expression is executed once and initializes a loop counter
    * STEP 2: The conditional expression is evaluated, If it evaluated to true, the loop statements execute. IF it avaluateds to false, the loop ends.
    * STEP 3: The statements inside the code block execute.
    * STEP 4: Then the iterator expression is executed and either increments or decrements the loop to the next iteration.
    * STEP 5: Lastly, we circle back up to step 2 and the for loop continues to run until the condition returns false
10. What is a callback function?
    * 
11. When do we use a callback function?
    * 


# Resources
- [MDN on Loops and Iteration](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)
- [MDN on the for statement](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for)
- [w3Schools on For Loop](https://www.w3schools.com/js/js_loop_for.asp)
- [w3Schools on Callback Functions](https://www.w3schools.com/js/js_callback.asp)
- [MDN on Callback Functions](https://developer.mozilla.org/en-US/docs/Glossary/Callback_function)