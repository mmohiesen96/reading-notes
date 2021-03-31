# HTML Images :
- Images are important things to develop a high quality websites and can express alot about the web page you are visiting.

- How to implement images in your site ?
    - Use the `<img/>` self closing tag and it's an inline element that means it doesn't start on a new line and attibutes can be invoked like : .
        - src : The source or the link of the image .
        - alt : Shows an alternative text of the image if broken .
        - title : gives more information about the photo when hovering over the photo .
        - height and width : specify the dimensions of the photo.
    
    - Rules for creating images :
        - Save images in the right format .
        - Save images at the right format .
        - Use the correct resolution .
    
    - There are many tools to edit photos and ensure or improve their qualities for example : PhotoShop.

    - Image extensios and their properties :
        - JPEG : Used for pictures with many colors and high quality.
        - GIF/PNG : Usually used for same color for large areas or to little numbers.

    - Images used in the web should be saved at 72ppi so that the website can load faster due higher quality images won't increase the quality .

    - Vector images :are created by placing points on a grid and then drawing lines between those points , with the benefit of not changing quality when changing the dimesnions of the photo

    - Animated GIF's : used to display animated gif's and gif's can be designed using special software or using online tools.

    - Figure tag : HTML 5 introduced `<figure>` along with the `figcaption` to place the image with it's caption inside it .


    _______________________________________________________________________________________

    # CSS Colors :

    **Color can be applied on the page either background color or goreground color :**
    - Foreground color which is applied for text tags .
    - Back ground color is applied to every element since HTML treats every element as it is in a box.

    - Types of color formulas :
        - RGB : Expressed with the amountof red green and blue mixture .
        - RGBA : the same as RGB with the extra alpha value which expresses the transperancy .
        - HEX : HEXADECIMAL code to express the value of the color . 
        - HSL : Color expressed by hue , saturation and lighting .
        - HSLA : HSL with the alpha transperancy value .

    - Contrast is the percent between the colors for the background and foreground colors.

    - **Opacity is deisplaying the behind element through increasing tranperancy for the forwarding element.**


    _______________________________________________________________________________________

    # HTML Text :

    - The properties that affects and controls the text can be split into :

        - Font and style that controls the appearence of the text .
        - Properties that affects the text no matter what the font or style of it .

    - The major fonts are : 
        - serif : this font have extra details at the end of letters.
        - mono-serif : have a straight forward endings of letters .
        - mono-space : gives each letter a fixed m width size .

    - to determine a font to use we use font-family property which is given more values to replace the font family if the browser of the user does'nt support that specific family .

    - we can also setermine the font size by using font-size property which can be gives pixels , percentages or em's which are the size of letter em .

    - a method to use a font even if a browser does'nt support it is using the @font-face property that will download the font package to ths user's machine and takes the src attribute which specifies the url for that font .

    - More text modifications can be made like : 
        - font-weight : given a numeric value or a describing word like bold , bolder so on.. 

        - text-style : given values like italic or oblique values .

        - text-decoration : gives a specifi text decoration like underline , overline , line through and blink and so on . 

        - Line-height : increases the space between the top and bottom lines .

        - word-spacing and letter spacing : are used to increase the space between words or letters in a word . 

        - text-align : used to align specific text to a specific position .

        - text-indent : gives the text indent using pixels .

        - text-shadow : gives a dark version of the word and takes three lengths with a color value .

        - styling first letter or first line using the pseudo class :first-line , :first-letter .

        - styling links : using pseudo visited and link pseuo classes . 

        - Interacting with users using pseudo classes like hover , focus , active . 

        - Selectors with examples :

            - p[name of class] : matches p elments with that name of class . 
            - p[class = "dog"] : targets p's with the class dog . 
            - p[class ~= "dog"] : elements that attribute seperated with spaces and on of them is dog . 
            - p[class ^= "d"] : elements that start with a specific prefix . 
            - p[class *= "do"] : matches an element with a specific substring whic is do in this case . 
            - p[class $="$f"] matchs a specific suffix .


            