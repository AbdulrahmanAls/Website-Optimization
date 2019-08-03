## Website Performance Optimization portfolio project
This project [Website Performance Optimization portfolio project](https://github.com/udacity/frontend-nanodegree-mobile-portfolio) made by **Cameron Pittman** 

He asks me to optimize this website 
* index.html achieves a PageSpeed score of at least 90 for Mobile and Desktop.
* Optimizations made to views/js/main.js make views/pizza.html render with a consistent frame-rate at 60fps when scrolling.
* Time to resize pizzas is less than 5 ms using the pizza size slider on the views/pizza.html page. Resize time is shown in the browser developer tools.

### Getting started
* Download project zip file 
* Unzip the file 
* Open the index.html 

#### Part 1: Optimize PageSpeed Insights score for index.html

1. Check out the repository
1. To inspect the site on your phone, you can run a local server

  ```bash
  $> cd /path/to/your-project-folder
  $> python -m SimpleHTTPServer 8080
  ```

1. Open a browser and visit localhost:8080
1. Download and install [ngrok](https://ngrok.com/) to the top-level of your project directory to make your local server accessible remotely.

  ``` bash
  $> cd /path/to/your-project-folder
  $> ./ngrok http 8080
  ```

1. Copy the public URL ngrok gives you and try running it through PageSpeed Insights! Optional: [More on integrating ngrok, Grunt and PageSpeed.](http://www.jamescryer.com/2014/06/12/grunt-pagespeed-and-ngrok-locally-testing/)

#### Part 2: Optimize Frames per Second in pizza.html and resize pizzas is less than 5 ms

1. Open views/pizza.html 
2. You might find the FPS Counter/HUD Display useful in Chrome developer tools described here: [Chrome Dev Tools tips-and-tricks](https://developer.chrome.com/devtools/docs/tips-and-tricks).

