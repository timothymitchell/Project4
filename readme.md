## Website Performance Optimization portfolio project



### Part 1: Optimize PageSpeed Insights score for index.html

##### Modifications made to the index.html assignment page:

:one: Optimized image pizzeria.jpg from W: 2048px, H:1536 px to a new size of W: 100px, H: 75px for index.html page.

:two: On index.html, moved the google webfont link at the end of the page.

:three: Minified and inlined style.css file.

:four: Made pizzeria-lg.jpg for pizza.html for index.html so it only has the smaller size image.

:five: Async was added to google analytics script.


###Part 2: Optimize Frames per Second in pizza.html.

#### Mofidfications made to main.js

:one: Changed all querySelector to getElementById for performance improvement.

:two: On function changePizzaSizes, changed querySelectorAll with getElementsByclassName and moved the variables from for loop to outside of loop.

:three: On document.addEventListener, looped through 32 instead of 200 pizzas.

:four: Created a new function NewPizza() to generate random pizzas and appends all the pizzas only once

:five: Moved document.body.scrollTop outside of the for loop in updatePositions function;


