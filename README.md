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
2. Draw the polygon.  

**Hints:**   
The interior angle of a regular polygon is ((sides− 2)×180)/sides.  
Remember to subtract that angle from 180.  
You will need to play around with the forward distance to get the turtle to stay inside the graphics canvas.  
Also, remember that the *input* statement always returns a string.  
(As a side note, this code is actually python 2 not python 3. It shouldn't matter EXCEPT that python 2 does not have an 'eval' function.  Is there another way to convert a string to an integer?)


Optional Exercise: 
Once you have the basic program down, feel free to add some color to your polygon..


When you are finished, commit and push your code and create a pull request, as per usual.