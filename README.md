# Lab2-JQuery
First take the <a href="https://www.khanacademy.org/computing/computer-programming/html-css-js/html-css-js-intro/e/quiz--javascript-recap">Khan quiz</a> to make sure you know basic javascript. In this assignment you will implement a jquery ajax call to get the current weather. 

The weather section should do the following:

1) Allow the user to type characters into a form. With each keystroke, query a <a href="https://students.cs.byu.edu/~clement/CS360/ajax/getcity.cgi?q=P">REST service</a> that will return a list of cities in utah that have those characters as a prefix. This will provide a hint to the user as to what legal values can be. Put these options into a list. These <a href="http://bioresearch.byu.edu/cs260/jquery/Lab1.html">hints</a> may be helpful.

2) When the user selects the submit button, take the entry from the form and put it into the CITY box on the page. These <a href="http://bioresearch.byu.edu/cs260/jquery/Lab2.html">hints</a> may be helpful.

3) The submit button will also query the <a href="http://www.wunderground.com/weather/api/d/docs">weatherunderground REST service</a> to get the current weather for that city. These <a href="http://students.cs.byu.edu/~clement/CS360/jquery/Lab3.html">hints</a> may be helpful.

4) There is another button that will query the ____ REST service.

Or in other words:

- [ ] You have the basic layout of the weather form (the input box, output, etc.)
- [ ] As you type characters in the city input, the application suggests legal values.
- [ ] When the submit button is pressed, you correctly fill in the City box.
- [ ] You make the request to the weatherunderground site and fill in the weather div;

**Submit to learningsuite the URL to your live webpage, along with any comments you have that will make your assignment easier to grade. You should have utilized the github classroom link to get started with the assignment.**

#### Grading:


- You will be graded as follows (there's some room for partial credit, don't worry):


Passoff Level | Behavior | Points
--- | --- | ---
Minimal Passoff | You've got the basic layout of the weather app Your basic javascript functionality works (suggestions, filling in the city box, etc.) | 45%
Passoff | Your page is lacking one or two parts of the functionality (ex. the full cities list isn't working, or the API call isn't right, etc.) |	70%
Basic Passoff | You have all the required functionality | 85%
Good Passoff | You utilize the other required REST service | 95%
Perfect Passoff | Your page looks really good. This is subjective, so wow us. | 100%

