# Chart.js & Canvas :

- Charts are way better method for displaying data visually rather than tables and traditional methods, and one
easy method to implement charts to your page is using chart.js plugin which is a well documented plugin helps drawing charts using the canvas 
HTML5 element .

- It helps building alot of different kinds of charts like pie,line and bar charts and so many more .

- Firstly we have to download chart.js then copy chart.min.js to our working directory and import the script .

- Drawing a line chart :
    - First we have to create a canvas element so chart.js can draw on it .
    - then we add a script to retrieve the contec=xt of that canvas .
    - we add extra data for our chart .

**We can draw another charts using the same concepts but with different objects for each chart type .**


### Chart files : 

- We can get the latest version from npm, which is a github release .

### Canvas Element in HTML5 :

- Canvas element is an image like element with only width and height attributes by default 300 px x 150 px.
- It's a good practice to specify an id so it can be recognized using scripts .
- It can be styled using CSS like any other element .
- Doesn't need fallback content so older browser can render it will just ignore the canvas element if not supported .
- Requires a closing tag .
- Canvas is used as a drawing suface for 2d or 3d context contents .
- we can check for it's support in browsers either using the fallback content or programitically using canvas.getcontext('2d') .


### Drawing shapes with the canvas : 

- The grid : 
    - The grid is used to determine the starting of the drawing or working on canvas and it is usually in the top left corner
    and everything will be in relative to it .

- Drawing rectangles : 
    - There is three methods used to draw rectangulars :
        - fillRect : creates a filled rectangle .
        - strokeRect : outline rectangle .
        - clearRect : creates a transperent rectangle leaving an empty rectangle space .

- Drawing paths : 
    - Create the path .
    - Use the methods for drawing on this path .
    - Method used for drawing paths : 
        - beginPath() : creates a path and the drawing starts from it .
        - path methods : set different paths for objects . 
        - closePath() , stroke() and fillPath() are used to handle the attitude of paths .
        - The moveTo() function is used to move the pen .

- Lines : 
    - Use lineTo() to draw a line .


- arcs : 
    - we use arc or arcTo methods to draw an arc with the radius argument included .

### Applying styles and colors : 

- Color : 
    - fillStyle fills the content with color , other wise strokeStyle outlines the content with the color value .
    - Color is a string CSS value or gardient , color object .

- Transperancy : globalAlpha is used to adjust the transperancy using the CSS transperancy values .

- Line Styling : 
    
    - We use line width to control the width of the line and also we use lineCap to set the look of the line ending .
    - lineJoin is used to se the appearance of the corners when two lines meet .
    - getLineDash returns the dash array . 
    - setLineDash sets the line dash pattern .
    - lineDashOffSet sets where to start the dash set .


- Gardient 
    - Like any element styles can be filled with : 
        - Linear gradient : using linearGradient method .
        - radial gradient : used to create radial gradient .
        - conic gradient : starts an angle to create a gradient .


### Drawing text :

- We use fillText to create filled text, and as all other etyling we use strokeText to create outline text .
- Text can be styled using the normal CSS text properties .
- measureText() is used to obtain more information about the text in details .

