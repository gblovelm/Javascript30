# Array Cardio Day 2

Uses a couple of arrays in the html to test out some additional array methods.

Array.prototype.some() - returns TRUE if at least one item in the array is a match

Array.prototype.every() - returns TRUE if all the array items are a match

Array.prototype.find() - like array.filter() expecpt it just returns the first one that matches

Array.prototype.findIndex() - returns the index (starting at 0) of the item

Can find the content at location 'index' with e.g.  
```
comments.slice(0, index);
```

Can rebuild the array minus the item at location 'index with:
```
const newComments = [
        ...comments.slice(0, index), 
        ...comments.slice(index + 1)
    ];
```

