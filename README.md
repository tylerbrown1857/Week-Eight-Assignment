# Week-Eight-Assignment
Week Eight Labs



Lab One

Part One:    
:turtle:  
To do this lab, you will be modifying the code in **index.html**  Don't panic. You are not touching any of the HTML code, only the Python part of it.  Here is what to do:  

Look inside the index.html file. Inside it, at about line 50, you will see some sample python turtle code that starts with:  

	import turtle   
	t = turtle.Turtle()  
      

You can run this code by "running" the html file in cloud9.  This will start a server and give you a URL that will allow you to connect to the page in the browser.  That page will then let you run the python code.  Go ahead a click the **run** button to run the sample turtle program.

[**NOTE:** Do not click on the url in Cloud9, that will open the page as a webpage in the cloud9 IDE, however, the turtle graphics will not work.]

You can make changes directly on the page in your browser to test them, but they will not be saved in the HTML file.  Open up the index.html file in the IDE and delete the *for* block. Now you should write your own code.  Your python code should do the following:  

1. Prompt the user for the desired number of sides for a polygon. 
2. Sanitize the input.  The value the user enters should be greater than 2 and less than 25.
2. Draw a polygon with the requested number of sides.  

**Hints:**   
The interior angle of a regular polygon is ((sides− 2)×180)/sides.  
Remember to subtract that angle from 180.  
You will need to play around with the forward distance to get the turtle to stay inside the graphics canvas.  
As for sanitizing the input, you can't really draw a 2 (or less) sided polygon. You can create one with more sides,
but after a certain point, it is just circle. 
You can either put the input inside a loop or simply end the program if the number of sides is out of bounds.  
(As a side note, this code is actually python 2 not python 3. It shouldn't matter EXCEPT that in python 2,
the *input* function assumes you are entering a numeric value. In python 2 you use **raw_input** to enter a string.)


Optional Exercise: 
Once you have the basic program down, feel free to add some color to your polygon..


When you are finished, commit and push your code and create a pull request, as per usual.