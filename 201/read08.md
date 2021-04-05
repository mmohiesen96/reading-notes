  # CSS Layout :

    - Building blocks : css treats all html elements as blocks of two types :
        - Inline block : flows with the adjacent content .
        - block elements : that takes the full screen width and starts on a new line .
        Containers are block elements inside another block element and can be nested more than that .

    
    - Positioning : CSS has the following positioning schema : 

        - Normal flow : "static value" this value will treat the lement the way it is structured by default. 
        - Relative : moves the element according to it is normal flow with providing coordinates the element moves without affecting other elements.
        - Absolute : position the element with ignoring the space it supposed to be into .
        - Fixed : positions the element according to the window of the browser so it can move while scrolling .
        - floating : floats the element according to it's container to the far right or the far left .

    - Floating items : the float property is used to control the flow of an element and takes it from it is original flow to the far right or left .
    - Clearing the float :The clear property means that no element , containing an element should touch the left or righthand sides of the container .

**Clear take left , right , both , none values**
## Screen sizes :

    - Resolution : is the number of dots a screen can show in an inch and it can be adjusted .

    - Fixed width layouts : allows the designer to control the pixel perfectly , control the element more accuratly and the contents will stay with the same size in the other hand it is not flexible with screens and does'nt allow the fonts to change and can run or on certain devices . (concentrated on accurate pixels with low dependancy on rem's and percentages .)

    Liquid layout : a lyout that streches and fits as much as your screen .
    (Uses percentages and rems rather than pixels).

**Multiple style sheets can be applied to the same page**