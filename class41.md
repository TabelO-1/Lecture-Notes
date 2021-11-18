# ✍️ Notes

1. What is the definition of the filter method?
* the `array.filter` method creates a new array with all the elements that pass the test implemented by the provided function.


2. What data type can you call a filter on?
* `ARRAY[]`

3. What does the syntax / pseudocode look like for the filter method?
* `array.filter(function(currentValue, index, arr), thisValue);`

4. What other methods do we know of that have the same syntax?
* `array.forEach()` & `array.map()`

5. Which parameters are required for the filter method?
* Function(), CurrentValue

6. What is the output of the filter method?
* A new `ARRAY[]`. If non pass the test then you get an empty array.


7. How does filter decide which array elements to return?
* Whether they pass the provided condition.


8. Is the original array mutated in the filter process?
* No.

9. Does the filter method give us back a new array?
* Yes.

10. What does filter return if no array elements pass the test?
* An Empty `ARRAY[]`.


# Resources
- [MDN on Array.Filter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)
- [w3Schools on Array.Filter](https://www.w3schools.com/jsref/jsref_filter.asp)b