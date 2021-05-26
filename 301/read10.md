# The JavaScript Call Stack

- The call stack is primarily used for function invocation (call).
- the call stack is synchronous.
- A call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).
- the last function that gets pushed into the stack is the first to be pop out .
- The call stack maintains a record of the position of each stack frame. 
- A  stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point.


# JavaScript error messages && debugging 

- Types of error messages :

    - Reference errors :
        - This happens when trying to reach variables that are not yet declared . 
        - or hoisting let and const that takes time to hoist .
        - to fix this error declare before initialization .

    - Syntax errors :
        - this occurs when you have something that cannot be parsed in terms of syntax .

        - Ex : parse an invalid object using JSON.parse.

        - This can be solved by just fixing the syntax . 

    - Range errors :
        - manipulate an object with some kind of length and give it an invalid length IS THE CAUSE .

        - The best approach and best practice is ti immute your variables and don't mess with the lengths .

    - Type errors
        - his types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible . 

        - To fix this make atesting variable or test if the variable or object exists .


    - Debugging : 
        - To debug your JS code, the easiest and maybe the most common way its to simply console.log() .

        - by using chrome developer tools . 

        - The breakpoint can also be achieved by putting a debugger statement in your code in the line you want to break.

    - Handling errors
        - We use try and catch to handle errors .
        - That will make errors not to break the whole code .
        - The errors will show in a different way .

    - Tools for preventing runtime Errors :
        - quokka to evaluate your code as you type
        - eslint to make sure your style guide is consistency and it will grab you an error or two along the way and
        - For those of you looking to make JS a more strong typed experience you can check out stuff like TypeScript (like I said in a previous article, when learning I rather avoid libraries that abstract the core language so I wouldn’t recommend this last one when starting)


    





## Error Examples in ECMAScript 

    Error: Permission denied to access property "x"
    InternalError: too much recursion
    RangeError: argument is not a valid code point
    RangeError: invalid array length
    RangeError: invalid date
    RangeError: precision is out of range
    RangeError: radix must be an integer
    RangeError: repeat count must be less than infinity
    RangeError: repeat count must be non-negative
    ReferenceError: "x" is not defined
    ReferenceError: assignment to undeclared variable "x"
    ReferenceError: can't access lexical declaration`X' before initialization
    ReferenceError: deprecated caller or arguments usage
    ReferenceError: invalid assignment left-hand side
    ReferenceError: reference to undefined property "x"
    SyntaxError: "0"-prefixed octal literals and octal escape seq. are deprecated
    SyntaxError: "use strict" not allowed in function with non-simple parameters
    SyntaxError: "x" is a reserved identifier
    SyntaxError: JSON.parse: bad parsing
    SyntaxError: Malformed formal parameter
    SyntaxError: Unexpected '#' used outside of class body
    SyntaxError: Unexpected token
    SyntaxError: Using //@ to indicate sourceURL pragmas is deprecated. Use //# instead
    SyntaxError: a declaration in the head of a for-of loop can't have an initializer
    SyntaxError: applying the 'delete' operator to an unqualified name is deprecated
    SyntaxError: for-in loop head declarations may not have initializers
    SyntaxError: function statement requires a name
    SyntaxError: identifier starts immediately after numeric literal
    SyntaxError: illegal character
    SyntaxError: invalid regular expression flag "x"
    SyntaxError: missing ) after argument list
    SyntaxError: missing ) after condition
    SyntaxError: missing : after property id
    SyntaxError: missing ; before statement
    SyntaxError: missing = in const declaration
    SyntaxError: missing ] after element list
    SyntaxError: missing formal parameter
    SyntaxError: missing name after . operator
    SyntaxError: missing variable name
    SyntaxError: missing } after function body
    SyntaxError: missing } after property list
    SyntaxError: redeclaration of formal parameter "x"
    SyntaxError: return not in function
    SyntaxError: test for equality (==) mistyped as assignment (=)?
    SyntaxError: unterminated string literal
    TypeError: "x" has no properties
    TypeError: "x" is (not) "y"
    TypeError: "x" is not a constructor
    TypeError: "x" is not a function
    TypeError: "x" is not a non-null object
    TypeError: "x" is read-only
    TypeError: 'x' is not iterable
    TypeError: More arguments needed
    TypeError: Reduce of empty array with no initial value
    TypeError: X.prototype.y called on incompatible type
    TypeError: can't access dead object
    TypeError: can't access property "x" of "y"
    TypeError: can't assign to property "x" on "y": not an object
    TypeError: can't define property "x": "obj" is not extensible
    TypeError: can't delete non-configurable array element
    TypeError: can't redefine non-configurable property "x"
    TypeError: cannot use 'in' operator to search for 'x' in 'y'
    TypeError: cyclic object value
    TypeError: invalid 'instanceof' operand 'x'
    TypeError: invalid Array.prototype.sort argument
    TypeError: invalid arguments
    TypeError: invalid assignment to const "x"
    TypeError: property "x" is non-configurable and can't be deleted
    TypeError: setting getter-only property "x"
    TypeError: variable "x" redeclares argument
    URIError: malformed URI sequence
    Warning: 08/09 is not a legal ECMA-262 octal constant
    Warning: -file- is being assigned a //# sourceMappingURL, but already has one
    Warning: Date.prototype.toLocaleFormat is deprecated
    Warning: JavaScript 1.6's for-each-in loops are deprecated
    Warning: String.x is deprecated; use String.prototype.x instead
    Warning: expression closures are deprecated
    Warning: unreachable code after return statement