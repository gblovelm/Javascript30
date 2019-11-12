Flex Panel Image Gallery. Set of 5 panels of images in columns using CSS flexbox.

Uses Javascript to detect a click event on any panel and add a class to the associated HTML element 
to transition to a wider panel and larger centered text size. 
Javascript then detects a 'transitionend' event to add a further class 'open-active' to the HTML element to bring in additional text 
to the top and bottom of the panel.

Uses CSS transformY to bring text in from top and bottom.

In CSS
'>' DIRECT children of element (not grandchildren)
'+' ADJACENT sibling (one IMMEDIATELY preceded by former selector)
'~' ALL siblings (more generic version of '+'

Useful to go to Devtools 'Elements' and manually type in an extra class to an element thats defined in the CSS 
to see the effect of it before running 'live'.

flex: 5 makes panel 5 times as wide as panels with flex: 1

can see what is being transitioned using console.log(e.propertyName) in function toggleActive
