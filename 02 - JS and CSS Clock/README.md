# Javascript and CSS Clock

Clock displayed with hour, minute and second hands updated using Javascript.
In CSS all the hands are horizontal at '9pm' position on top of each other when initially load the HTML.

CSS styling is added with the following features:
 - set the rotation point for each hand to the centre of the clock face, 
 - rotate all hands to 12 o'clock position as a starting reference point
 - provide a cubic bezier timing function so the hands simulate some overshoot as the move to the next position. 
 The shape of the bezier curve can be designed in chrome devtools and then copied to the css file.
 
Uses date methods setInterval(), setDate(), getSeconds(), getMinutes(), getHours()
 
Additional feature added to stop jitter effect that occurs as each hand goes through 12 o'clock position.
Conditional statements are used in JS to turn off the transition function as each hand moves to the 12 o'clock position and then turn it back on for the rest of the time.
 
