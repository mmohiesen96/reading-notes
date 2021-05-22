# NodeJS 

- What is NodeJS .. Alot of definitions that defines what node is but here is what I think is convinience 
    - Node.js is an event-based, non-blocking, asynchronous I/O runtime that uses Google's V8 JavaScript engine and libuv library.

- The V8 Engine is the javascript open source engine that runs on google chrome .
- It also runs on other chromium based browsers .
- It was enhanced by : 
    - file system API .
    - HTTP library .
    - number of operating system related utilities .

- How to install NODEJS :
    - It is recommended to install Node using version manager like nvm which allows you to control which version to use each project .

- Use the command node followed by the name of the file to run the code .
- NodeJS hasexcellent support for ECMAScript 6 .


## NPM 

- A package manager that comes with nodeJS .
- The world's largest software registry .

- We can install a package using the command npm install the name of the package .
- We can also use npm to install packages locally :
    - npm init -y to initialize a package.json locally .
    - followed by npm install the package name .
    - The package will be installed and saved as a dependancy in the package.json file .

- the node modules file is where npm creates and installs packages and dependencies .
- It can be recreated anytime using npm install command .
- For example use npm install jshint locally as an dependency .




# Why NODEJS 

- When working with any modern JS library you are expected to be familiar with node .
- Because most of modern libraries depends on node and npm .
- Node allows us to start JS projects on a server .
- Node is particularly suited to building applications that require some form of real-time interaction or collaboration — for example, chat sites, or apps and also it is suitable for building API's .

### Running Node version 12.21.0
### Running npm version 6.14.11



# Pair programming

- So many techniques like code reviews , iterative loops are proved to improve developers produce .
- Pair programming works as the following : 
    - Programmers takes two roles the Driver and the Navigator .
    - The Driver is the actual one who is typing the code and executes .
    - The navigator is the one that gives suggestions and ideas .
    - Both will be involved in improving the quality of the code .

- Greater efficiency
    - It's a lot faster to catch mistakes when two people are thinking on the same code .

- Engaged collaboration
    - When two are working on the same code the focus will be more than if they cwere working alone .

- Learning from fellow students
    - Pair programming allows collagues to learn new approaches from each other .

- Social skills
    - Improves the social skills of the partners .

- Job interview readiness
    - It's common to work pair programming in interviews .

- Work environment readiness
    - In real time jobs this a normal approach to work by pairs .

# GeoCoding 

- Reverse geo Turns coordinates into human readable addresses .
- Forward geo Turns human readable addreses into coordinates .
- auto complete :Provides options for user input by understanding it on-the-fly, returning matches as a dropdown.
    - Can match on full words as well as substrings
    - Plugins for easy implementation
- Nearby Returns specified Points of Interests .
- Timezone Helps understand current time at any given point on earth .

# Axios 

- API installed using this command npm install axios .
- Axios is : a Javascript library used to make HTTP requests from node.js or XMLHttpRequests from the browser that also supports the ES6 Promise API .

- What does it improve : 
    - Axios improves the error handling process .
    - Controls and manages Requests made on the server side .


# async & await 

- We use the async keyword in a front of a function to make it an async function .
- async functions returns an object of type Promise .
- We can also make funtion expressions and arrow functions an async functions .
- Use the then method to invoke a value for example : then(x => console.log(x)) .
- The async functions only comes with advantage when combined with the await keyword .
- await keyword can only be used in async functions .
- await can be used in front of any async based function component .
- it is used for waiting when the promise fulfills .

