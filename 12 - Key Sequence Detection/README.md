Detect a sequence of keys and do something.

Listen for a 'key up' event
Store each key press into an array using
```
pressed.push(e.key);
```
Then we want the end 6 letters of the array checked against a reference 'wesbos'
The leftmost side of the array is the FIRST key pressed
The right side of the array is the last key pressed
The array only needs to hold a maximum of 6 characters.

www.cornify.com/js/cornify.js  is used to add random stuff to the screen.

Can turn an array into a string with this
```
pressed.join('');
```
