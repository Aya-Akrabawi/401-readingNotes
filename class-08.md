# Class 08:

**What is Express API?**
The way to construct a web API is to follow the RESTful approach . REST APIs are resource-based interfaces. On the web this means that data resources are represented by URIs (paths) accessed via HTTP.

**What is routing in Express?**
Routes can be managed in separate modules from the main server, Routing refers to how an application’s endpoints (URIs) respond to client requests.

```
var express = require('express')
var app = express()

// respond with "hello world" when a GET request is made to the homepage
app.get('/', function (req, res) {
  res.send('hello world')
})
```

You define routing using methods of the Express app object that correspond to HTTP methods; for example, app.get() to handle GET requests and app.post to handle POST requests.

Express 4.0 comes with the new Router. Router is like a mini express application. It doesn't bring in views or settings, but provides us with the routing APIs like .use, .get, .param, and route.

**What is Express Middleware**
Express Middleware A series of functions that the request “goes through”Each function receives request, response and next as parameters

Route Middleware router.use() Route middleware in Express is a way to do something before a request is processed. This could be things like checking if a user is authenticated, logging data for analytics, or anything else we'd like to do before we actually spit out information to our user.

**Name 3 real world use cases where you’d want to change the request with custom middleware**
method override
check auth
logger
cors

**True or false: The route handler is middleware?**
True

**In what ways can a middleware function end the process and send data to the browser?**
res.download() Prompt a file to be downloaded.
res.end() End the response process.
res.json() Send a JSON response.
res.jsonp() Send a JSON response with JSONP support.
res.redirect() Redirect a request.
res.render() Render a view template.
res.send() Send a response of various types.
res.sendFile() Send a file as an octet stream.
res.sendStatus() Set the response status code and send its string representation as the response body.

**At what point in the request lifecycle can you “inject” middleware?**
any where in the request cycle before send the response res.method();

**What can cause express to error with “Request headers sent twice, cannot start a second response”**
when you send another response for the same request. can't set header

### Vocabulary Terms

**Middleware** : functions that have access to the request object (req), the response object (res), and the next middleware function in the - application’s request-response cycle.

**Request Object** : the values that the client passed to the server during an HTTP request and other info related to the client.

**Response Object** : its a carrier during the request-response lifecycle, will be sent lastly to the client after finished the lifecycle.

**Application Middleware **: software that provides services beyond those provided by the operating system to enable the various components of a distributed system to communicate and manage data.

**Routing Middleware **: determining how an application responds to a client request to a particular endpoint.
