# HTML Links : 

- Def. : Anchor tag or  link tag is the tag that allows us to teleprot between our web site pages or other pages .

- Implemented through : `<a href = "the link to teleport to">text to be displayed</a>`.

- types of links : 
    - Absolute URL : URL's that take you to a page on the public web.
    - Relative URL : a relative url that is from your site or from the website folder.

- Relative URL Structure : applies a hierarchial structure that is every file or folder that is inside another one is considered a child - parent relationship
for example : child > parent > grand parent .

- To access realtive links from the href attribute that can be done by the following examples : 
    - in the same folder : just the file name.
    - in a a child folder : name of folder/file name.
    - in a grand child folder : grandchild/parent/file.
    - in a parent : ../file name.
    - in a grand parent : ../../file.

- Other link attributes and their functions : 
    - mailto attribute : opens the default email app and fills the to section.
    - target(_blank) : opens the link in a new window.
    - use the # to refer to a place in the same page using a class or id.

    _______________________________________________________________________________________
    # CSS Layout :

    - Building blocks : css treats all html elements as blocks of two types :
        - Inline block : flows with the adjacent content .
        - block elements : that takes the full screen width and starts on a new line .
        Containers are block elements inside another block element and can be nested more than that .

    
    - Positioning : CSS has the following positioning schema : 

        - Normal flow : this value will treat the lement the way it is structured by default. 
        - Relative : moves the element according to it is normal flow with providing coordinates the element moves without affecting other elements.
        - Absolute : position the element with ignoring the space it supposed to be into .
        - Fixed : positions the element according to the window of the browser so it can move while scrolling .
        - floating : floats the element according to it's container to the far right or the far left .


    ## Screen sizes :
    - Resolution : is the number of dots a screen can show in an inch and it can be adjusted .

    - Fixed width layouts : allows the designer to control the pixel perfectly , control the element more accuratly and the contents will stay with the same size in the other hand it is not flexible with screens and does'nt allow the fonts to change and can run or on certain devices . (concentrated on accurate pixels with low dependancy on rem's and percentages .)

    Liquid layout : a lyout that streches and fits as much as your screen .
    (Uses percentages and rems rather than pixels).

    _______________________________________________________________________________________

    # Functions , Objects : 
    - Functions are a series of instructions that are grouped together and can be recalled anytime.
    - objects : are series of information about a specific element which acts as a real object with attributes and behaviors.
    
    **Functions for example can be declared :**
    function funcName(parameter list){
        code instructions;
    }

    - invoking functions can be done using their names with paranthesses and the parameters if existed.

    - return keyword is used to make the function returns a specific value to the cariable or whatever is using or invoking it.

    - immediatly invoked functions are functions equaled to a variable and held with ().

    -  variable scope : is two types global and local the global variable can work any where through the program , local scope is the variable  that can be used only in the scope it is declared.