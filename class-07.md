# class 07:

**Express:**
Express is a routing and middleware web framework that has minimal functionality of its own: An Express application is essentially a series of middleware function calls.
**Express Middleware:**
Middleware functions are functions that have access to the request object (req), the response object (res), and the next middleware function in the application’s request-response cycle. The next middleware function is commonly denoted by a variable named next.
![](https://i.morioh.com/200522/661f29bd.jpg)
**Express Routing:**
* refers to how an application’s endpoints (URIs) respond to client requests. For an introduction to routing, see Basic routing.
* These routing methods specify a callback function called when the application receives a request to the specified route (endpoint) and HTTP method.
**Test Pyramid:**
The testing pyramid is a concept that helps you to balance your tests better. also, it delivers a graphical representation of a best-case test scenario.




**What’s the difference between PUT and PATCH?**
the PUT method to update the whole resource but PATCH is partially modified.

**Provide links to 3 services or tools that allow you to “mock” an API for development like json-server**
post man-mock, mockserver, mockserver-node

**Compare and contrast Swagger and APIDoc.js Which HTTP status codes should be sent with each type of (un)successful API call?**
swagger is wide spread more than apiDocs.js and can integrate with multiple services.
4xx bad request, 5xx server error

**Compare and contrast SOAP and ReST**
*SOAP* is Simple Object Access Protocol,
*REST* is Representational State Transfer,
SOAP is a protocol whereas REST is an architectural style for providing standards between computer systems on the web

**Vocabulary Terms**
**SOAP** Simple Object Access Protocol.
**REST Verbs** GET, POST, PUT, PATCH, and DELETE.
**CRUD Verbs** Create, Read, Update, and Delete.
**Swagger** Swagger is OPEN API documentation standard, used together with a set of open-source software tools.