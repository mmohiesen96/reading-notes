# Objects :
- Objects : are set of variables and functions used to recognize and represent a model with unique properties and behaviors .

- In objects variables are known as properties of the object and also the funtions will be recognized as methods that belongs to that object behavior .

- Object properties are organized as key/value pairs along with the methods .

- Example on how to create and access the objects properties and methods :

    - let Obj = {
        prop1 : 'val1',  
        prop2 : 'val2',  
        prop3 : 'val3',  
        firstMethod :function() {  
            //code;  
            return statement;   
        }  
    };  

    - To acces this object we use the dot annotaition for example to access a property :   

    **let val = Obj.prop1;**

    - also to access the methods in that object :   
    **let methodReturn = Obj.firstMethod();**


    _______________________________________________________________________________________

    # Document object model :
    - DOM : is a way to specify how the browser should save a model of the HTML page and how JavaScript can access and modify this model and elements of it .

    - How this process works ?! 

        - when a browser loads a page The DOM specifies how to make a model of that page using the DOM tree which consists of objects to each part of that page .

        - Then it identifies methods to access and modify these objects using JavaScript , people call the DOM model an API because it makes the program communicate with it is parts .

    - The DOM Tree majorly consists of four main types of nodes :

        - The document node : it represents the entire page and corresponds on the top of the tree .
        - Element node : identifies the elements of the page which are the tags used to structure the page .
        - Attribute nodes : are the attributes in the opening tag of the element, and they are not a child of that element but a part of it .
        - Text node : after accessing the element then you reach the text to modify/update you want to achieve .

    - How to use the DOM tree : 

        - Locate the element node you want to work with :
            - Select individual element  :
                - getElementById() : returns the element with that id .
                - querySelector() : Use CSS selector and returns the first match .

            - Select multiple elements : 
                - getElementsByClassName : returns all elements with a specific class .
                - getElementsByTagName : returns all elements with that tag name .
                - querySelectorAll() : CSS selector with all matches .

            - Traversing between nodes : 
                - parentNode : selects the parent of this node (one element).
                - previousSibling/nextSibling : select the previous or next sibling of the tree element .  
                - firstChild/lastChild : select the first or last child of that element .
        - use the text , child and attributes of that class : 
            - use the nodeValue property to access or update the text node value .
            - we Use innerHTML to access child elements nad text content and we use textContent to access the content of the node , we can use multiple methods to add or remove nodes 

                - createElement()
                - createTextNode()
                - appendChild(),removeChild()

            - Methods used to access and modify the class/id attributes : 
                - hasAttribute()
                - getAttribute()
                - setAttribute()
                - removeAttribute()


        - Caching DOM queries :

        - Methods that are used to access elements are called queries and you can access one or a nodelist so one or more elements :
            - methods to access one elements : 
                - getElementById() : the fastest and more efficent way to acces an element .
                - querySelector() : a recent edition to search for the first element with a specific CSS selector . 

            - methods to acces a list of elements (nodeList) : 
                - getElementsByTagName()
                - getElementByClassName()
                - querySelectorAll()

                **length property is used to return the length of the node list , item() method will return a specific node**

            **You can use loops to do a specific action to all node list items , or traversing the nodelist**

        - Traversing the DOM tree can be done using the following properties : 

            - parentNode : selects the parent of this node (one element).
            - previousSibling/nextSibling : select the previous or next sibling of the tree element .  
            - firstChild/lastChild : select the first or last child of that element .

            **Libraries like jQuery used to avoid the white space problem since all of the browsers except IE deals with white spaces as text nodes**

        - Updating and accessing the text contents can be done by :
            - innerText : should be avoided because lack of performance .
            - nodeValue : used to access the elements and update the value using replace().
            - textContent : used just to access the text content .

        - Adding/removing HTML content :

            - Using innerHTML : used to access and update elements and can be given a string value of the markup and the content to be added or an empty string to remove an element .

            - DOM manipualtion : createElement() => creatTextChild => appendChild() , we can use remove child to remove an element .


    ## Cross-Site Scripting Attacks :

    - If you add HTML to a page using methods,
         you need to be aware of XSS , otherwise,
            an attacker could access your confirmation.

### Inspecting the chrome page then goinf to properties followed by objects will let you examine the DOM of the page .