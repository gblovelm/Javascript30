# Array Cardio Day 1

Practice with array methods map, reduce, sort and filter on objects, arrays and accessing data from a web page.
Uses ES6 syntax.

querySelectorAll returns a NodeList. This only has a forEach method available for looping over an array.
May need to convert this to an array so the above array methods can be used to pick out the required data 
- can be done using Array.from( (....) ) or using the ES6 spread operator [... (....) ]

use console.table() to output results in console window in a more readable format.
Can use template strings to more simply format data:

`${inventor.first} ${inventor.last}` produces the same result as:
inventor.first + ' ' + inventor.last


array.map:     outputs an array the SAME LENGTH as the input 

array.filter:  outputs a SMALLER array than the input 

array.reduce:  can calculate a running total as iterate over an array 

array.sort:    takes two arguments, output +1, -1. Bubbles items up and down an array.
