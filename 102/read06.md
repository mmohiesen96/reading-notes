# CSS :
 Is the rules that control how the content of your page should appear.

* CSS for cascading style sheets .
* Block line elements are elements that takes a certain block on the page and starts on a new line .
- ex. \<p>\<div>\<h1-6>

* Inline elements are elements that stays on the same line and operates at it .
- ex. \<b>\<em>\<img>.

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


## Color :

- Foreground color : color property can help you to specify the color of the text .
<br> You can specify colors in three ways : 
    - RGB : Red , Green , Blue values .
    - HEX CODE : Using hexadecimal codes for red green and blue by using 2 fields for each color as following "rrggbb".
    - Color name : you can specify just the color name.<br>

Background color : Same three ways can specify the background color by default it's transperent.

#### Color Concepts :
- Hue : it's generally the degree of the color .
- Saturation : the amount of grey in the color . 
- Brightness : how much black in the color .
- Contrast : is how the color would appear and be more readable .
- Opacity : Generally it's for transpearncy of the color or an element .

#### HSL Colors : 
Hue , saturation , lightness , alpha : alpha is for opacity or transperancy.




