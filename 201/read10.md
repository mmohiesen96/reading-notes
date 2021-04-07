# JS Debugging : 
- Error handling is used to detect errors, or handle potential errors .

- JavaScript runs using the order execution , so that it runs line by line , and some
codes depends on other code .
- execution context : that varies so that contexts splits into :
    - global context : the code that don't belong to any block .
    - function context : the code that is wrapped in a function block .

- JavaScript uses the stacking method so that when a function needs to call another function the current
function stacks and runs that function then continue .

- Scopes are the living spaces for a variable , object or function and can be local or global .

- Erorrs : When JavaScript occurs an error it stops running and searches for the handling code to handle that error .

- Error objects are used to handle errors when faced , for example urlerror , syntax error and more 
and each of objects contain the following properties :
    - name.
    - message.
    - filenumber.
    - linenumber.

- How to deal with errors : 
    - Debug the script : that means tracking donw , using the console to find the error .
    - Handling errors : using try , catch , throw and finally .

- Developer tools using browsers : we can use the browser to debugg code of JS so that we can find errors
so that we can inspect the page to inspect these errors and what are their types and where to find the error 
we also can use the console to type scripts .

- in the browser console we can use the console scripts to debugg code  , using break points to put a break 
to stop the code from running at this point or conditional break points and also we can step into the code .

- we can use debugger keywored to make a break point .

## Error Handling : 

- We can handle errors through our code using :

    - try : specifies where the expected error is and try this code .
    - catch : if the code fails this will run .
    - finally : this code will run in both ways .

- Throwing errors : We can throw errors to handle the error before the compiler interepts it ,
otherwise we can make our own errors , like using the thrwo new ('Error message').