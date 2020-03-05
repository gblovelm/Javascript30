This is an animation using JS to pull in images from the side as you scroll down the page.
All images are initial translated off screeen 30% with opacity 0 , scale 0.95
A class is applied with scale 1 and opacity 1

Function checkSLide() runs every time the window is scrolled.
(Note can use console.count to check how many times an event occurs)
Use a Debounce function off the internet (lots available) - pass it a function
This makes the debounce fucntion run every x ms which slows it down [debounce(checkSlide, 500)]
Note should ALWAYS debounce scroll functions
Use a forEach loop
check the number of pixels scrolled relative to the bottom of the page
```
const slideInAt = (window.scrollY + window.innerHeight)
```
Want animation to start when half or more of the image is visible when scrolling
```
sliderImage.height / 2
```
want the animation to reverse as scroll past it through the top
Best to put calculated pixel values into a variable (then can console.log that variable)
