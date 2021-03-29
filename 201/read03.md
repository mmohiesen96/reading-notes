# HTML Lists :
- HTML provide us with three different types of lists :
    - Ordered list : lists where each list item is numbered or given a specific order type.
    - Unordered list : lists where list items are ordered and organized withdots or bullets.
    - Definition list : made up of list of terms with a definition of each term.


### Ordered List : Can be defined using the ol tag and li tags which are wrapped inside the ol tag.
- For example :  
<ol>
    <li>ordered list item 1</li>
    <li>ordered list item 2</li>
</ol>

### UnOrdered List : Defined using ul tag with li tags inside of it .
- For example : 
<ul>
    <li>Unordered list item 1</li>
    <li>Unordered list item 2</li>
</ul>

### Definition List : Uses dl tag to define it and wrapped in between the tags pairs of dt and dd tags which are terms and their definitions.
- For example : 
<dl>
    <dt>term 1</dt>
    <dd>The first definition</dd>
    <dt>term 2 </dt>
    <dd>The second definition</dd>
</dl>


___________________________________________________________________________________________


# CSS Boxes :
- **CSS Treats every HTML elements like it's in a box with height and width by default these boxes have their content width and height**

- ***Box properties :***
    - Dimensions : using height and width properties allows us to control the box dimensions and we can give it pixels , percentages or em's **percentages are used to identify the percent of that specific dimesnsion according to it's parent element**.

        - Limiting height and width : using the min and max properties with the height or width and mainly used to apply the responsive term and to give max width that an element can be displayed , also the minimum size that an element can shrink.

    - Overflow : property to tell the browser what to do if the content of the box is larger than the box itself nad can have these two values : 
        - Hidden : used to hide the extended content .
        - scroll : to achieve a narrow scroll bar to scroll into the content .

    - Border , Margin and padding : These three properties are well related and the dimension of each one is added to the box's height and width and can be explained as the following : 
        - Border : each element has a default 0px border which can be modified given a specific type, width and color.
        - Margin : Is basically the space between the box border and it's adjacent boxes or edges.
        - Padding : is the actual space between the content and the border of the box.

    - Centering elements : you can center elements either using text-align property for full-width boxes or setting the left and right margin to auto for fixed width boxes.

    - Display property : is to adjust how the browser should show a specific element and can be given inline / block / inline-block and none values .

    - Hiding boxes : can be achieved through the visibility property and can be given hidden , visible values.

    - Box shadow is added with four values that represents horizontal offset , vertical offset , blur distance and spread of shadow.

    - Border radius can be added to wrap the corners to give the box a more rounded shape
    and if given more than 2 different dimensions that will cause elliptical shapes.
    _______________________________________________________________________________________

    # Basic JS instructions :

    ### Arrays :

     - Items in array are ordered by index starting from 0 items can be accesed through that index with the [] to acquire the length a built in length property can be invoked which returns the length.

     - Expression are used to compare or state mathmatical expressions , operators types are arithmetic , string and boolean operators .



    _______________________________________________________________________________________

    # Desicions and loops :

    - Switch statement : is a conditional statement that have a casing structure and written with the keyword case followed by several cases and ended by the default case .

    **Type corcion is where java script does behind the scenes operations to convert a data type so it doesnt cause an error**

    - Truthy and falsy values : falsy values are values treated as false boolean in the other hand truthy values are values which is treated as true values.


    - Loops : are statements in JavaScript used to do a block of code more than once or loop through it types of loops : 
        - for loop : 
        - while loop : 
        - do while loop :

    - loop counters are the decision makers in the loops they tells the loop how many times the loop should iterate  