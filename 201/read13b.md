# CSS Transforms : 
- a new layout and positioning technique that can be applied in two dimensional form and three dimensional form .

- The syntax :
    - Starts with prefixes to ensure browser support like :
        - webkit, moz and o prefixes followed with no prefixes to override them .
    - then the transform property followed by the type of the transform.
    - the value between parenthesses .

## 2D Transform :

- 2D transforms works on the y and x axis to rotate the element using rotate value whic will rotate the lement clockwise if it is positive and the opposite if negative value provided .

- Scale property is used to make the element appear larger or smaller using a scale form 0.01 to 1 which is the original any value bigger than 1 is bigger than the element .

- We can give the scale property two values for the x and y axis .

- Translate property is like the relative position property that moves the element without affecting the document flow using x and y axis .

- The skew property is used to distort elements on x and y axis and the syntax is similar to the sclae value .

- Transform-origin value is used to locate the element in it's box using the x and y axis if one value provided it is for both axis and if one it will be used for both axes .

- Prespective value is the vanishing point can be set to none or a value and that value will increase the vanishing area by the viewer .

- Prespective-origin is the same as transform-origin property with the same values .

## 3D Transform :

- 3D transform : in addition to the x and y axis there is a z axis to work with in 3D transforms .

    - The 3D transform uses the same properties like the 2D scales .
    - But the major difference is that we can work on the z axis which is the depth .
    - So in each value we can use the z scale or the z rotate and so on .
    - backface value is used to show or hide the back of the element when rotating .

# CSS Transitions : 

- Transition is used to control the behavior of an element when a state changes from one to another state.

- Transition have 4 popular properties which is :
    - transition-property : gives the state of the element
    - transition-duration :  the duration that will be transmitted from one state to another , if two properties provided the values in order will be applied according to the properties given .
    - transition-timing-function : the style of the change in behavior .
    - transition-delay : is used to delay the transition time .

- There is ashort hand for transitions which we can provide all of the values in one property in the same order they are provide .

- we use the keyframes to identify the stages of the animation :
    - We use the same with transition values with the animation property with the same short hand .
    
