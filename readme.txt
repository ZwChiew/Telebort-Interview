Concepts Used (DOM): 

To decrement time each 1 second: 
Used setInterval(function, 1000) 
take note of the id
call clearInterval(id) when time is 0 (times up)

To highlight work taiped: 
Add in span tag to each char of the randomized word. 
To select, used querySelectorAll("span"), 
then select the correct span (containing current char) using indexing. 
+2 when indexing since we have 2 span tag earlier in the HTNL. 
Add in class of ("highlight") to the span tag to highlight character 

To disable button: 
After user press start button, add in new styles to the button ("disable") and change opacity
Use condition checking to make sure clicking button have no effect after users has clicked for first time (game started)

To determine which Char to taip:
Use event object (e.key) to capture char that user taip 
Use indexing to know which character we are currently on
Increment index whenever user has taip the same char until the last char.
At the last char, play success audio and generate new word

