# CSS Variables

Updates CSS variables through changes to HTML <input>s using Javascript.

Inputs are:
  Spacing: slide bar
  Blur: slide bar
  Base Colour: colour palette
  
Define CSS variables for each input as :root level.
Select all the inputs using querySelectorAll. This returns a NodeList, which has a (limited) number of methods available to control it.
A forEach loop is used to listen for a change event on each input. If a change occurs then a 'handleUpdate' function is called.
A change event could be a 'change' or 'mousemove' - the latter necessary to make sure an update happens every time.

Uses custom data attributes (data-*) and the dataset property so the units for the variables (e.g.'px') can be specified when needed.

