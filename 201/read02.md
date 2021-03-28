# HTML Text :
## html text and text decorations varies to alot of elements and we'll get to them in details :
- Headers : are kind of text that specifies a header for the document and varies in size and importance from 1 to 6 descending.
- Paragraphs : The type of text that you can create paragraph into .
- Bold : text decoration that gives a font the bold layout .
- Italic : text decoration that gives a font the italic layout .
- subScript : considers a word or a character as a subscript for the previous word and majorly used in chemical operations .
- superScript : considers a word or a character as a superscript for the previous word and majorly used in Mathmatical concepts .

#### White spacing : is often used to make the code more readable and anyway the browser wouldn't identify the spaces as commands and that is Called ***White space collapsing***.


- Line breaks and horizontal breaks : Line breaks are escaping the text to a new line using br element and horizontal rule is a seperating element that creates a seperating horizontal line .

#### Semantic elements : are not elements that are intended to modify the structure of your webpage but to add extra information to your pag , and visual modification .

- Strong and emphasize elements : Strong adds extra importance to the text wrapped into it and emphasize element means that the text changed into another image .

- block quote element : is used to indent the quotation block in addition to the q element that wraps the text into "".

- Abbreviation element ("abbr") : gives a small note about an acronym that exists in the text .

- Cite elements : is used to refer to an author of something.

- dfn element : used for definition and wraps the content into the italic layout.

- Address element : to psecify email and address.
- editing elements : ins , del , s specifies edited elements .



# Introduction to CSS :

- The major issue with css is to imagine every html element like in a box 
**There is 3 types of elements considering the block view**:
    - Block elements : takes the width of the screen.
    - inline elements : takes the width and height of its content.
    - inline-block elements : acts like block elements with fixed height and width .

* CSS associates style rules with HTML elements using selectors .
* CSS rules consists of selectors that may be :
    - Element name selector.
    - Id selector.
    - Class selector.<br>
after the selector in curly brackets there is :
    - A CSS property like font-family , color .
    - A value of that property .<br>
.

- Using external CSS :
 You can achieve that using the html tag which is <link> with those attributes :
    - href : specifies the path of the style sheet .
    - rel : specifies the relationship between the HTML file and this one which is style sheet .
    - type : the type of the file which is style/css.<br>

- Internal CSS : Use the \<style> tag to include internal styling .


## Selectors :
**allows you to direct rules to a specific element in a HTML document .**

Types of selectors : 
- Universal ("*") : Applies to all elements in a document .
- Type ("h1,p,pre") : Applies to the selected tag name .
- Class (".class") : to a specific class .
- Id ("#Id") : TO AN ID .
- Child ("li>a") : to a direct child of an element.
- Descendant ("p a") : Matches a descendant of the element not just a child.
- Adjacent sibling ("h1+b") : Matches the next sibling.
- General sibling ("h1~p") : Matches a general sibling.


### Rule precedence :
- The last rule will apply.
- You can add !important after a rule that specify that it takes higher precedence .

### Inheritance :
* Child elements can inherit some properties "Not all" .



# JavaScript basic instructions : 
 - JS consists of statements that declares or does some function that ends with semi colon and it can be organized into blocks of code or in {}.
 - Comments are use to give notes about the code and to summarzie some of the functions and ther is multi line comments and single line comments .

 - Variables are a method to change frequently changing data we use key words let and var to initialize a variable and then we initialize them using the equal sign followed by a semi colon. 
 - JS is case sensitive to naming variables and keywords variables must start with a dollar sign or  an underscore or a letter only and cant start with a number and must contain just one of the three contents i mentioned earlier and the best practice to use a meaningful name with upper camel case applied.

 - Data type are string which are wraped in single or double quotes , numbers like integers and floats and boolean that maybe false or true .
 - Arrays : are data structures that have fixed sizes to store a list of items of different types can be declared as an ordinary varibale but initialized using[] with items wrapped inside seperated by a comma .

 - Items in array are ordered by index starting from 0 items can be accesed through that index with the [] to acquire the length a built in length property can be invoked which returns the length.

 - Expression are used to compare or state mathmatical expressions , operators types are arithmetic , string and boolean operators .



 # Decisions in JS :

 ### Comparison operators :
- == : used to compare two values if equal .
- != : used to compare two values if not equal .
- === (strict equal) : used to compare two values and types ("preferable to use more than ==").
- !== (strict not equal): used to compare two values if not equal in values and types .
- \> : used to identify if the first is greater than the second .
- <  : used to identify if the first is less than the second .
- <= : used to identify if the first is less than or equal the second .
- \>=:used to identify if the first is greater than or equal the second .


* Comparison operators return true or false .

* Logical operators are used to combine the result of two or more comparison statements .

Logical operators : 
- && (and) : Tests more than one condition .
- || (or)  : Tests at least one condition .
- ! (not) : Takes at least on boolean result and inverts it .

- If statement is decision statement used to apply a block of code if the condition which is boolean expression is true and otherwise another block of code is intemedated.