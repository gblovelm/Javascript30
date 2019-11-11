# Design Notes

Drum machine that displays a set of labelled keys with a background image filling the screen.
When a key is pressed a keydown event is recognised and an associated audio element is found and played. 
The key is animated as the sound is played.
The appropriate sample is reset back to the start position every time a keydown event occurs.
This allows for samples to be replayed in a 'machine gun' like way before the end of each sample is reached.
Multiple keys can be pressed at the same time.

Uses 'classList' to add and remove a CSS class from an HTML element.
Javascript is used to add a 'playing' class to the div element associated with the pressed key 
and remove it once a transform end event occurs.

