# Component Life Cycle

- Mounting, Updating and Unmounting are three phases of component Life Cycle.
    - Mounting : First stage .
    - Updating : When Updating a compnent .
    - Unmounting : The last stage after rendering .

- Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
    - Rendering happens before component did mount .
- What is the very first thing to happen in the lifecycle of React?
    - Mounting is the first phase .
What does componentDidMount do?
    - componentDidMount Is a good place for any subscription.
- Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
    - Constructor .
    - render .
    - componentDidMount .
    - componentDidUpdate .
    - componentWillUnmount .

# React-Bootstrap 
- React-bootstrap is rebuilt with as react components with the removing of unnecessary dependencies like jQuery .

- Bootstrap with it's react version is compataible with alot of bootstrap themes that we already use and love .

- Every component is built with accesibility in mind which make it accesed by default behavior .

**Netlify is a web application used to view useful project and to put your projects on .**

- There are two ways to Model Data in react Which are : 
    - Props .
    - State .

- What types of things can you pass in the props?
    - data that should be handled outside of the component and no need to re render .
- What is the big difference between props and state?
    - Props You pass into the component and handled out of it , but state is handled into the component .
- When do we re-render our application?
    - When we change a state of a component .
- What are some examples of things that we could store in state?
    - changing data that should be changed by the component itself (Updating data) .


    # State and lifecycle 
    - ReactDOM.render is used to render changing data which is state data .
    - States are private and fully controlled by the component .
    - States are dynamic .
    - to add a state into a react child class we use this.state .
    - Setting up a DOM element is called mount .
    - Destroying element is called Unmount .
    - It's a good practice to edit state using setState .
    - State Updates May Be Asynchronous That means they might batch together for performance issues . 
    - The data flows downwards .


    # Handling events in react
    - Handling events in react is very similar to it in HTML .
    - We use {} to wrap the function passed as an event listener .
    - we don't use return false to prevent default behavior, instead we call that method directly .
    - We have to bind this for handling events .
    
    # Intro to react
    - react is a JS library for building UI's .
    - Components are elements we want to see on the screen and render method will do the job .
    - props are passed to components as parameters to control what the user view .
    - we use arrow functions with react to avoid confusing behavior of this .
    - We use states to build dynamic passed and changed into the components parameters alike .