## Website Performance Optimization portfolio project



### Part 1: Optimize PageSpeed Insights score for index.html

##### Modifications made to the index.html assignment page:

* Optimized image pizzeria.jpg from W: 2048px, H:1536 px to a new size of W: 100px, H: 75px for index.html page.

* On index.html, moved the google webfont link at the end of the page.

* Minified and inlined style.css file.

* Made pizzeria-lg.jpg for pizza.html for index.html so it only has the smaller size image.

* Async was added to google analytics script.


###Part 2: Optimize Frames per Second in pizza.html.

#### Mofidfications made to main.js

* Changed all querySelector to getElementById for performance improvement.

* On function changePizzaSizes, changed querySelectorAll with getElementsByclassName and moved the variables from for loop to outside of loop.

* On document.addEventListener, looped through 32 instead of 200 pizzas.

* Created a new function NewPizza() to generate random pizzas and appends all the pizzas only once

* Moved document.body.scrollTop outside of the for loop in updatePositions function;

### Instructions for running the application
 
 1. Download the /dist/ folder in your computer.
 1. To inspect the site on your phone, you can run a local server:
 
   ```bash
   $> cd /path/to/your-project-folder
   $> python -m SimpleHTTPServer 8080
   ```
 
 1. Open a browser and visit localhost:8080.
 1. Download and install [ngrok](https://ngrok.com/) to make your local server accessible remotely:
 
   ``` bash
   $> cd /path/to/your-project-folder
   $> ngrok 8080
   ```
 
 1. Copy and paste into your browsers address bar the public URL ngrok provides to you. Then run Google Chrome's Dev Tools to inspect.


