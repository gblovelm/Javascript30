Purpose is to be able to check (put a line through) multiple checkboxes in a list by clicking on a start row and end row checkbox.

Define a variable to include all the checkboxes.

1. query all of the checkboxes:
```
const checkboxes = document.querySelectorAll('.inbox input[type="checkbox"]');
```
2. Loop over all the boxes looking for a click event (also covers keyboard entry) and run function 'handleCheck'
Look for the first box checked
check subsequent boxes until find the next one checked.
Define an 'inBetween'variable that goes valid (true) until come across the next box checked when it goes false.
