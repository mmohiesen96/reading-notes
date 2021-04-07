# Forms :

- Are mainly used to get information from a user, for example :signing up form, shopping order , google text box .

- Types of forms controls :
    - Text :
        - Text input : one line of text .
        - Password input : Used for passwords .
        - Text area : Used for multi - line texts .
    - Choices :
        - Radio buttons : allows the user to choose one choice .
        - Check box : used wehn a user can choose one or more choices .
        - Drop down list : Allows the user to choose one of listed options .
    - Submitting forms : 
        - Submit button : submits the information provided by user .
        - Submit image : Same as the submit button but you can use an image .
        - Uploading files : lets the user upload to the website .


- How a form works : 
    - The user fills a form with data , then the provided information gets saved and rendered using high level programming languagues
    then the server saves all inputs provided , then responds by creating a pgae to respond for the user .

- Form structure : 
    - `<form> tag` : the main tag the form lives inside .
    - action : the form url takes it's action from .
    - method : get or post (default get), post is used for sensitive data and long forms otherwise , use the get .

    -`<input>` : they all take the type attribute to specify : 
        - text : takes the name , max length and size properties.
        - passowrd :takes the name , max length and size properties.
        - textarea : takes the name , maxcol and maxrow properties .
        - radio : takes the value, name and checked properties .
        - checkbox : takes the value, name and checked properties .
        - `select` : used for dropdown lists takes the name property and :
            - `option` : tag used to specify the options with checked and value properties
            multiple property is used for multiple checkboxes.
        - file : used to make a file uploader .
        - Submit button : type submit with name and value property the same with the image submit button but with submit type .
        - date : input that is used with dates .
        - search : used for search queries .
    - `label` : Is used to label the form contents .
    - `fieldset` and `legend` :are used to wrap the form contents in boxes , the legend is used to put a legend name for the form.

- Form validation : Is done using JavaScript, but HTML5 provided a way to validate forms using the required attribute,
and that will decrease the work on the server , also it will ensure the user inputs a valid form .


___________________________________________________________________________________________________________________________________________________

# CSS for lsits , tables and forms :
- Lists properties :
    - list-style-type : specifies the type of the list counter .
    - list-style-position : inside or outside .
    - list style-image : puts an image icon instead of the bullets .
    - list-style : specifies the overall style for the list .

- Tables properties :
    - width : sets the width of the table .
    - padding : sets cell padding .
    - text-transform : sets the th's as uppercase letters .
    - font-size , letter-spacing : additional styling .
    - border-top and bottom : borders on top and bottom .
    - text-align : aligns the text in cells .
    - background-color : sets a aback color for sells or the whole table .
    - empty-cells : show , hide and inherit to show a border around empty cells .
    - border-spacing , border-collapse : sets a gap between borders and collapse the border or seperates it .


- Styling forms : 
    - Text inputs : Can use the color , font size , background color in addition to background-image , :focus pseudo class
    that changes the attitude of the input while it is used .
    - Styling buttons : using color and border-radius and :hover pseudo class , text-shadow and border bottom to make it more 3D alook.
    - Styling fieldsets and legends using the previous properties .
    - Cursor styling : using the cursor property which takes : 
        - auto
        - crosshair
        - default
        - pointer 
        - move 
        - text
        - wait
        - help 
        - url

    

    _______________________________________________________________________________________________________________________________________________


    # Events :
    - Events are actions that are taken by the users or by the page itself and can be handled by the developer to respond for them , 
    and make the page more interactive .
    
    - Types of events : 
        - UI events : occur when the user inter acts with the browser like load , scroll , error ,resize events .

        - keyboard : When the user interacts with the keyboard like keydown , keyup and keypress .

        - mouse : when the user interacts with the mouse like mouse down or up mouse over , db click .

        - Focus : occurs when the item gains focus like focus and blur events . 

        - Form events : interacting with forms like input , change , copy and paste evnets .

        - Mutation events : When DOM script changes the content of the page DOMnodeInserted or removed or modifiedtree .


    - Steps to handle events : 
        - Specify the element . 
        - Choose the event to handle . 
        - Call code to handle this event .

    - Types of event handlers : 
        - Traditional HTML event handlers : Using the attributes on a HTML tag to call a code (bad practice).
        - DOM event handler : are recognized by all the modern browsers and is done by 
        targeting the element and applying a single function while providing the event to be handled . 
        - Modern DOM event listener : adding an event listener providing the function and the event and the element to be handled.

    - Event object : object that stores information about the event that occured .
        - properties can be invoked to know the target event or type and also if cancellable .

    - Methods are used to change default behavior : 
        - preventDefault : method used to prevent the default behavior of an event. 
        - stopPropagation : to stop the event from bubbling up to it's ancestors .
    - Types of events that we can respond to : 
        - The W3C DOM specification
        - The HTMLS specification
        - In Browser Object Models 
 

