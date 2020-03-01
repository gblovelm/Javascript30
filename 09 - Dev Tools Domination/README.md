Includes 14 must-know dev tools tricks.

To find out what JS code is changing your page, go to Elements panel in Chrome Devtools 
- select area affected - right click on 'Break on Attribute Modifications' and the line of code causing the problem is shown.

console.log tricks - Various:
- some examples here with more in the index-FINISHED.html file

Use console.log for interpolated comments:
```
console.log(`Hello I am ${var}`)
```
Can use CSS styling on console.log output. Use ; to separate multiple CSS definitions
```
console.log('%c Hello', 'font-size:50px');
```
Use console.warn and console.error for stack tracing
console.info('some text') gives an info. symbol in the console window you can easily pick out.

Testing
```
console.assert(test for something, 'that didnt work'); 
```
second part provides an error message if the test fails. 
There is no output if the test passes.

```
console.dir(p);
```
- useful as shows all the properties and methods on 'p'. console.log(p) would just show p

console.group(), console.groupEnd(), console.groupCollapsed() all useful for collating quantities of data.
e.g. when wanting to run a loop on manageable chunks in the console window.

console.count('Martin') tells you how many times 'Martin' occurred in the output

Use console.time() to measure time taken to do something.

console.table() displays an array of objects in a nice formatted table.




