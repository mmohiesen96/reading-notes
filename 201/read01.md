# Introduction :
* ## How People access the web ?
    - Browsers : You can access a website using a special softwar called web browsers 
    popular examples are :
        - Firefox , Chrome , Opera and safari

    - Web servers : special requests are sent to a special computer called web server in order for that server to respond and give useful information.
    - Devices : Accesing web pages can be done through out a wide varity of devices like desktops , laptops and mobile phones etc. .
    - Screen readers : special software that can read the content to the user and specially used by people who have visual impairments.


* ## How websites are created ?
    - What you see is actually your web browser rendering the actual HTML and CSS content that it recieves from the website host .
    -  Small websites often are created using HTML and CSS But in large websites that needs databases and multiple access to server here high level programming languages like C# , PHP and Java  are envolved .
    - The most recent versions of HTML is 5 and for CSS  is 3 . 
**Websites are mainly built by HTML ,CSS But in the new era new technologies formed up.**

* ## How the Web works ?
    - First you connect to a ISP which Internet Service Provider and you type the domain name so your browser can establish a connection.

    - Then you connect to a DNS which is Domain Name System and it's roll to give your browser information like ip and connection type to that very specific website and also sends a special code to authorize the access .

    - The unique number returns to your Computer and at this moment you have been authorized to access that website .

___________________________________________________________________________________________

 # Structure of a web page :

 - Web pages are a digitalized version of the usual documents that we are facing every day 
 How is that ?
    - They act like a news paper in structure with a heading and a subheading and maybe an image below of it and that to achieve a hierarchy information displaying .

## Web page structuring using HTML :

- To structure a web page like a document structure a special HTML code is implemented 
and that code is implemented using HTML tags which are **Special words wrappen inside <>**

and each tag is a special order to the browser .

- The anatomy of the tag is like the following :
    - #### An opening tag which is :
        - the opening angular bracket <.
        - The element name for example p or h1.
        - The closing angular bracket >.
    - #### A closing tag which is :
        - The angular bracket with a slash </.
        - The element name **again** .
        - The closing angular bracket >. 

    - #### Atrributes : Are special features that can be added to the opening tag to give special ability to the specified tag and that goes as the following ==> <p class=""></p>

    - #### The main anatomy of a web page is the mainly 3 tags Which are the html , head and body tags and mainly the only tag that gets rendered to the page is the body tag .



___________________________________________________________________________________________

# An extra Markup ..

- DOCTYPE is used to give the browser information about what version of HTML to use in order to render the website .

- Comment tags are mainlt an important tag so the code can be more readable and to put extra notes or guide lines and can be implemented through "!-- --" in the angular brackets .

- Class and ID attributes are the most common identifiers of a HTML element and in more details :
    - Class : Can be used in more than one element "Not Unique" and the most common identifier.    
    - ID : Can't be used for more than one element "Unique".

## Block elements VS. Inline elements :

- Block Elements : Elements that take the conent height and the whole screen width.
    - for example : p , ul , li , h1 .. h6.
- Inline Elements : Elements that take the height and width of there content .
    - for example : img , b , em , a.

___________________________________________________________________________________________

### The div container : it's mainly used to group elements in a block level element so a varity of properties can be applied to that box .



### span element is like the equivalent of the div for inline text to be contained in the span container .


### Iframes : a small window that is shown in your site that displays info outside your site and have some major attributes which are useful like :
-
    - src : the linke where to get the information from . 
    - scrolling : to allow
    - height and width : to specify the dimensions for the iframe.
    - seamless : is similar to the scrollbar
    - border : to specify a border to that frame .


### The meta element : is an element to give special communication and information to the web browser and it's name and content properties can take these special values :

-   - author.
    - content.
    - pragma.
    - keywords.

___________________________________________________________________________________________

# HTML5 Layout elements :
- Layout elements : tags to organize the structure instead of the div and too much css and they are:

    - Header and footer : Are used for the main header and footer . 
    - nav :Is used to identify the navigation bar and usually it's elements are defined as a list . 
    - Article : Will help you with paragraphs and articles . 
    - aside : an aside block element that acts like a navigation bar but
    When it's in the article it means that it express info. about the article but not som neccesary info.
    When it's outside the article it gives info. about all the site.
    - Section : seperates the structure to several sections and each section can have the main components and IS independant from other sections.

    - hgroup : used to group a set of headers together.

    - figures : used with images , videos , diagrams .

    - div :used to sepearte the site to squares that are seperate .

- You can link contents using the anchor tag .

display : block ; css attribute to help old browsers to understand the new HTML 5 elements.



___________________________________________________________________________________________

# Proccess and desig for a website :
Steps for building a website :
- Target the audience ...
	- what are the ages of visitors ?
	- what kind of devices they use ?
	- visitor's average income ?
and so many information would be better to know , you should also create virtual customers or visitors for your website.
- The service or the purpose of your website ...
	- content and design .
	-examine the specific goals of the user or visitors.
- identify what users are trying to achieve : that can be done by virtual customers or feedback .
- Provide the type of information users need.
-  Doing the previous steps will increase how often users will vidit your website ,
and that's also another requirement or a tip for building a good website.


Sitemaps :
site maps are basic diagrams that describes your website structure , tips for building it :
- Start with the homepage as the root .
- the navigation bar after that .
- don't make it too complex .

Wireframes : 
Are basic sketchs used to take the first look or the basic look of your interfaces.
- It's done using squares and crossed squares to express the contents .

* The visualizing techniques main reason is the following :
- Content Organizing due to the big amount information .
- Priorization to give a distinct look to the website .
- Organizing grouping contents in chunks or blocks and that will make them easy to maintain.

* VISUAL HIERARCHY : Is a method or a concept to give an attractive look to the webpage depending on :
- Size.
- Color.
- Style.

* Ways to organize visual elements :
- Proximity.
- Closure.
- Continuance.
- Whitespaces.
- Color.
- Borders.

___________________________________________________________________________________________

# JavaScript introduction :

### What is a script ?

- Is a set of instructions which is followed by a computer to achieve a goal that's like alot of real life example :
    - Recipes.
    - Handbooks.
    - Manuals.

- To write a good script :
    - list the tasks to be achieved.
    - divide the task into smaller tasks and that is the way that human brain thinks.
        - Define the goal .
        - Design the script.
        - Code each step .

## Design the script :
- Once you define the goals you want your script to achieve the designing process takes in place that can be done through representing your problem using a flowchart and a series of steps that is called pseudo code.


Example of designing a script :
1. The script is triggered when the button is clicked.
2. It collects the name entered into the form field.
3. It checks that the user has entered a value.
4. If the user has not entered anything, a message
will appear telling them to enter a name.
5. If a name has been entered, calculate the cost of
the sign by multiplying the number of letters by
the cost per letter.
6. Show how much the plaque costs. 

- The main idea to start programming is to think like a computer and learn the language vocabulary and syntax What is that ?    
    - Vocabulary : Is the words that the compiler of the language understands.
    - Syntax : Is the method that we combine these vocabularies and words .
### How computers fit in the real world ?
- Computers deal with world objects like their own created models .

#### How the Computer treats these models / objects ?
- Objects are the models that the computer creates and it consists of the following :
    - events : describes the behavior of the object.
    - properties : describe characteristics of object.
    - methods : are the actions that the current object does.

### How to write a Script :
- JavaScript is the behavioral layer at the site .
- You can write your script using any editor you might like .
- You should link the script to your html file through the script tag.
- the script will run where ever it was found .