## Pizza optimization project

This project involved getting a web page to run at 60 fps.



### Getting started

To view this project, go  [here](http://matthewmagee05.github.io/views/pizza.html).  
Or launch the pizza.html file in your browser of choice located in views/pizza.html.


### Changes made

Below is some of the optimization changes made to make the project run smoother. 

* At line 449, I moved the variables outside of the for loop, and used the getElementsByClassName loop instead of the querySelectorAll method call.
* At line 503 I replace querySelectorAll with getElementsByClassName.
* With help from forum posts at Udacity.com, found the calculations to rebuild the phases variable.
* Added a boolean variable at line 518 that determines if the window is animating.
* Added the animationCheck function to check if the screen is animating.  Included that function in the listener.
* Reduced the amount of pizzas from the high of 200 down to 48.



