AJAX Type Ahead project.

User enters letters into a form and the matching city and state names are highlighted and displayed 
along with a population size in a colummn list.
Population size is formatted with a general purpose function that adds commas every third digit.

The list is sourced from github with 1000 cities-worth of data in JSON format.

Use 'fetch' in JS to get the data, filter down to a subset where city name or state will match.
fetch returns a promise. Call .then on the promise but only returns a blob of data as fetch 
doesnt know what format the data is in. But we know its in JSON format and there is a JSON method 
available with fetch - so call that - which returns another promise with the required array of data.

Aim to use const for variables, arrays. Can push data into a const array using the ES6 spread operator:
cities.push(...array) - each input is like an array index (avoids getting an array of arrays doing it this way).

Can put a variable into a regex:
  ```
  const regex = new RegExp(wordToMatch, 'gi');
  return place.city.match(regex) || place.state.match(regex);
```

Display function used to listen for a change or keyup event.
This runs the function to find the matches and then displays them.
Need to click OUTSIDE the HTML form input for a change event to be recognised.

