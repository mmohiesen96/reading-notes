## Packages and Import

- Package = directory. Java classes can be grouped together in packages .
- The directory name must be the same as the package name .
- The first line must be the package declaration .
- Package declaration order : 
    - Package declaration . 
    - imports .
    - class or interface .

- Three options for import : 
    - Either import the the single class using import class.class .
    - Import the whole class with all it's sub classes class.* .
    - Access the Class directly .

- Common imports :
    
import java.awt.*;	Common GUI elements.
import java.awt.event.*;	The most common GUI event listeners.
import javax.swing.*;	More common GUI elements. Note "javax".
import java.util.*;	Data structures (Collections), time, Scanner, etc classes.
import java.io.*;	Input-output classes.
import java.text.*;	Some formatting classes.
import java.util.regex.*;	Regular expression classes.

- Static imports allows to access class members and methods without having to make an instance of that class .


## Loops

- Lopps : is executing a block of code until a specified condition evaluates to false .

- Types of loops in java : 
    - For : A for loop is a control structure that allows us to repeat certain operations by incrementing and evaluating a loop counter.
    - Enhanced for-loop : an enhanced version of for loop that is shorthanded with just a variable and a result .

    - While : The while loop is Java's most fundamental loop statement. It repeats a statement or a block of statements while its controlling Boolean-expression is true.

    - Do-While : The do-while loop works just like the while loop except for the fact that the first condition evaluation happens after the first iteration of the loop.