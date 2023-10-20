# Lab Report 2
## By Jason Boenjamin
### Part 1
<br>
This lab report is about Servers and SSH Keys.
<br>

![Image](CSE15_Lab2_SC1.png)
- This screenshot displays what the user will see when they enter the website.
- [Website Link At The Time](http://ieng-202.ucsd.edu:7034)

![Image](CSE15_Lab2_SC2.png)
- For this first screenshot, we are specifically using `/add-messages?s=Hello`.
 - The methods that are called in my code are  `handleRequest(URI url)`. The outcome of the server depends on what url is placed in. In this case, "Hello" is the query that needs to be added to the website.
 - The server updates and the website now prints `1. Hello`, since "Hello" is the first string entered.

![Image](CSE15_Lab2_SC3.png)
- For this second screenshot, we are specifically using `/add-messages?s=How are you?`.
- Similarly, the methods that are called in my code are `handleRequest(URI url)`. The outcome of the server is, again, changed because the query has changed to add "How are you?", instead of "Hello".
- The server updates and the website now prints `1. Hello\n2. How are you?`, since "How are you?" is added after the previous `/add-message`


<br>
- The relevant arguments for both screenshots, method `handleRequest(URI url)` is "URL".
<br>
- The values of url change the request because you can either `/add-messages` or display the starting screen.
