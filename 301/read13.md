# HTTP Status codes 

- 100 - 199Permalink
These are informational status codes that means request will fail before they start sending the body.

- 200 - 299Permalink
These are the success codes. They tell the client that its request was accepted.

- 300 - 399Permalink
These are redirection codes. They tell the client that the resource they are requesting isn’t available at the expected location anymore.

- 400 - 499Permalink
These are the client error codes. They are all about invalid requests a client sent to a server. There are several causes to this, timeouts, wrong URI, missing authentication, etc. 


- 500 - 599Permalink
These are the server error codes. Often they indicate problems with overwhelmed servers or unreachable servers behind proxies .


## CRUD 

- CRUD Stands for : Create , Read , Update , Delete .

    - CREATE: 
        The create action is usually implemented via HTTPs POST method .

    - READ:
        The read action gets implemented via HTTPs GET method and used to fetch resource representations .
    
    - UPDATE:
        An update can be implemented with an HTTP PUT or PATCH method.

    - DELETE:
        The delete action can be implemented with the HTTP DELETE method.


- Example code : 

    - 202 Accepted - Often used for asynchronous processing. This code tells the client that the request was valid .

    - 308 Permanent Redirect - This tells the client to use another URL to access the resource and not use the current URL anymore.

    - 403 Forbidden - The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.



## REST API 

- app.use(express.json) is used to accept json as the body of our database . 

- We need our dotenv file to store sensitive information .

- Middleware is software which lies between an operating system and the applications running on it .

- the :/d is the url piece that we will have access to it's data which the user enters .

- PUT updates all the information not only the updates that user passes like PATCH .

- You can give the schema element a default value normally like in JS  .

- Status code 500 means that there is an error with the server .

- 200 status code is everything is successful in general in the other hand 201 means that something was created .

- 400 status that means something is wrong with the user input .
