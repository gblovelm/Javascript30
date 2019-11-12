# Fun with HTML Canvas

Draw multi-coloured lines with the cursor on the screen.

Canvas is like MS Paint where you get a block of pixels on the screen to draw in.

You draw on the 'context', not directly on the pixels. Context can be 2D or 3D.
2D is used here.

Set the canvas width and height - in this example its set to fill the whole window.
Set up event listeners for mousedown, mousemove, mouseup and mouseout.
Use detection of a mousedown event to update X,Y location variables.

The canvas rendering object 'globalCompositeOperation' is used for display effects.
Lots of different modes available in the mozilla documentation for this.


