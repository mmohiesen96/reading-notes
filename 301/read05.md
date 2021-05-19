# Thinking REACT 

- I'll go into various steps to show the logic of react :
    - assume we have a moch and api that have the final result .
        - The first step to build a react app is to make the mock or the data you have a component hierarchy .
        - then you have to sketch rectangles around every component .
        - use the single responsibility principle to decide which is a component or not .

        - The second step is to build a static version of your application .
        - build a static version because static UI with no interactivity needs less thinking .
        - Complete the interface without using states because states are used for interactivities .

        - The third step is to complete your UI .
        - Keep your code dry .
        - arrange the data that you have in json files .
        - use the props to handle these stuff to keep it static .

        - Identify your state lifecycle and where to be implemented .
        - In addition to their job or what they should render .
        - For each piece of state in your application:

        - Identify every component that renders something based on that state.
        - Find a common owner component (a single component above all the components that need the state in the hierarchy).
        - Either the common owner or another component higher up in the hierarchy should own the state.
        - If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.


        ### Use the previous stratigies to make react applications and It will go smoothly .