# Functional programming 

- Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data .

### Pure functions 

- When learning functional programming the first thing you need to know is oure functions and it's restricts :

    - It returns the same result if given the same arguments (it is also referred as deterministic) .
    - It does not cause any observable side effects .
    - For example when calculating datat that is external and changeable , or reading from files which will be changed 
    this will be impure function .
    - Random number generator also can't be pure .
    - mutability is discouraged in functional programming .
    - A function that edits data or causes changes on global variable is impure to fix that don't change the variable just return the value .

- Pure function benefits : 

    - it gets easier to understand our programs .
    - every function is isolated and unable to impact other parts of our program . 
    - Pure functions are stable, consistent, and predictable .
    - The code’s easier to test .


### Immutability

- The second thing functional programming is about is Immutability .
- When data is Immutable the state of data will not change, instead we will create a new object of it containing the new data .
- To handle the iteration muatbility we use recursion which will call a function and the function will call it self several times .
- also to handle strings mutability we use function composition or function chaining .

**pure functions + immutable data = referential transparency**



### Functions as first-class entities

- The idea of functions as first-class entities is that functions are also treated as values and used as data .
- Functions as first-class entities can : 
    - refer to it from constants and variables .
    - pass it as a parameter to other functions .
    - return it as result from other functions .

### Higher-order functions

- Are functions that either :
    - takes one or more functions as arguments .
    - returns a function as its  . 


### Filter 

- Given a collection, we want to filter by an attribute. The filter function expects a true or false value to determine if the element should or should not be included in the result collection . 


### Map 

- The map method transforms a collection by applying a function to all of its elements and building a new collection from the returned values.


### reduce 

- The idea of reduce is to receive a function and a collection, and return a value created by combining the items.





# Modules & require() 

- Modules are pieces of code in a file that does a specific Job .
- To use the module outside of the current file we use the require keyword .
- In order to use the module we have to module.exports = what we need from the module .
- After those steps we can use the imported module in our code .