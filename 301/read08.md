# API Design best practices

- A well designed API should aim to support :
    - Platform independence : Any client should be able to use the API .
    - Service evolution : API should be evolved and updated .

## What is REST 

- Representational State Transfer (REST) as an architectural approach to designing web services .
- It's based on hypermedia .
- REST APIs are designed around resources .
- A resource has an identifier, which is a URI that uniquely identifies that resource .
- Clients interact with a service by exchanging representations of resources .
- REST APIs use a uniform interface . 
- Operations which are popular are : GET, POST, PUT, PATCH, and DELETE .
- REST APIs use a stateless request model .

## Organize the API design around resources

- Focus on the entities that the API exposes .
- POST requests should be based on nouns .
- Avoid exposing the internal DataBase design .
- Use GET request to retrieve items .
- Adopt a consistent naming convention in URIs .
- Avoid requiring resource URIs more complex than collection/item/collection .
- Avoid chatty web APIs which will cause latency and may increase the cost and bandwith .

## API Operations : 
- GET retrieves a representation of the resource at the specified URI. The body of the response message contains the details of the requested resource.
- POST creates a new resource at the specified URI. The body of the request message provides the details of the new resource. Note that POST can also be used to trigger operations that don't actually create resources.
- PUT either creates or replaces the resource at the specified URI. The body of the request message specifies the resource to be created or updated.
- PATCH performs a partial update of a resource. The request body specifies the set of changes to apply to the resource.
- DELETE removes the resource at the specified URL.

## Filter and paginate data
-  the API can allow passing a filter in the query string of the URI Which will increase the efficency .
- Also consider imposing an upper limit on the number of items returned .
- Give all optional parameters in query strings meaningful defaults.


# RegEx 

## Anchor 
- ^ starts with .
- $ at the end ends with .
- ^ $ exact string match .

## Quantifiers 
- ab* a followed by b's at least zero.
- ab+ a followed by b's at least one .
- ab{2} a followed by 2 b's .
- ab{2,} a followed by 2 or more b's .
- ab{2,5} a followed by 2 up to 5 b's .
- a(bc)* a followed by zero or more bc's .
- a(bc) {2,5} a followed by 2 to 5 bc's .


## OR operator |
- a(c|d) a followed by c or d .


## Character classes
- \d matches a digit .
- \w matches a word .
- \s matches a whitespace .
- . matches any character .

**negations for the character classes are the same letters but capital(upper case)**


## Bracket expression 
- [abc] matches a string that have a ,b or c .
- [a-c] the same .
- [0-9]% charcter from 0 to 9 followed by % .

## Look ahead and look behind 

- d(?=r)       matches a d only if is followed by r, but r will not be part of the overall regex match . 
- (?<=r)d      matches a d only if is preceded by an r.