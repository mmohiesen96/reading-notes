# Compnent based Architecture 

- Components are used to divide the proplem into sub problems to make it easier to handle the content of the application .
- The primary objective of components is reusability .

- What is a component?
    - A component modular, portable, replaceable, and reusable functionallity that is high level interface .


- What are the charactistics of a component?
    - Reusability − Components are usually designed to be reused in different situations for a specific task.

    - Replaceable − Components may be replaced with other components.

    - Not context specific − Components are designed to operate in different environments.

    - Extensible − A component can be extended from existing components to provide new behavior.

    - Encapsulated − A component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state.

    - Independent − Components are designed to have minimal dependencies on other components


- What are the advantages of using component based architecture?

    - Ease of deployment .
    - Reduced cost .
    - Ease of development .
    - Reusable .
    - Reliability
    - Modification of technical complexity .
    - Independent .


# Props

- Props stands for Properties and is a keyword in react which is used to pass data between components .

- Data in props flows in one direction from parent to child one way (uni-Directional flow) .

- Props data are read-only data That mean they can't be changed after reaching the child .

- props are passed to components like function arguments .

# Intro to react 

- React is a declarative, efficient, and flexible JavaScript library for building UI's .

- we Compose UI's using a special small pieces of code called components .

- render method is used to display a description of what we want to see in screen .

- We pass data from one component to another through props, I explained that in the previous subject .

- We make an interactive component by giving it functions to do (Event listeners) or give them a class to control CSS or handle their behavior .

- We use states in the component constructor to handle data that can be changed through their usage in the component .

- We can view and debug components from the developer tools provided by modern browsers .

- Keys are unique in adjacent components and must be used in iterators to identify each element .


# JSX 

- JSX is an extension to JS Syntax and it's recommended to use it with react .

- Why JSX ?
    - React doesn't require using JSX but it is a visual aid to get more control over the elements that I'll use which are the components .

- to use a declared varibale or constant in JSX we embed them in curly braces .

- we can use the curly braces to use JSX expression into a statement .

- If a tag is empty you can close it directly with / .

- It can help preventing injection attack , by ensuring that you can't use anything injected outside from your code .

# Rendering elements

- An element decribes what you will show in screen .

- React elements are not DOM elements ad considered objects and cheap to make .

- To render reactDOM elements we use render method which takes the lelment and the root to be displayed at as parameters .

- React only updates what is neccessary and have to be updated based on your functions . 


# More about components : 
- Components are the architecture that is used in react .

- Components extends or inherits from react.component class .

- Components are pieces of code that does a functionality or shows something .

- Components are cheaper in building than DOM elements since they are objects . 


