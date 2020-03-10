JS Objects vs Arrays - Reference vs Copy

Convert function to arrow function
```
function (inverter) {..}
```
goes to 
```
inverter => {..}
```

filter - selectively returns an array with a smaller number of elements
map - takes in an array - changes it - then returns an array of the same length
sort - takes in two items - e.g.
```
const ordered = inventors.sort((a, b) => a.year > b.year ? 1 : -1);
console.table(ordered);
```

reduce - builds up a solution - e.g. running total
Can define an initial value of 0 so doesnt start with an undefined value
```
const totalYears = inventors.reduce((total, inventor) => {
  return total + (inventor.passed - inventor.year);
  }, 0);
```

Can call QuerySelector on just an existing element rather than the whole document.
QuerySelector returns a NodeList - this doesnt include map. Need to convert the Nodelist to an array e.g. by using Array.from(...)

Task: Sum up the number of instances of each element with the same name in array.

- start with a blank object
- iterate over each element
- check if the element exists yet. If no then add it to the object, 
if yes then increment the number of instances of the element recorded.
```
if (!obj[item]) {
  obj[item] = 0;  // add the item to the object
}
obj[item]++;      // increment the number of recorded instances
return obj;
}, {3};
```

  

