# class 9:

**Express Router Parameters**
1- parameters can be read in the rote.
2- middleware can run on any route.
3- middleware can be run on every request.
4- express allow to run middleware only when certain parameters are expected or deleted or eliminating the choice.
**Sub Documents in Mongoose**
Mongoose is a schema driven ORM, which gives us the opportunity to provide structure to our Mongo documents. By default, Mongo (all NoSQL Databases, really) are not structured by default With the addition of “Sub Documents”, Mongoose gives you the ability to take that a step further and use a schema to describe a deeper part of a data model. This can be useful when a document contains potentially a list of other documents

**Virtual joining**
The Virtual Join function allows a single form to display information from many files. You cannot modify virtually joined information but it can link with other files using Find and Fill.

### Vocabulary Terms:

**Routing** is the process of selecting a path for traffic in a network or between or across multiple networks.

**The prefix method** is used to prefix each route in the group with a given URI. For example, you may want to prefix all route URIs within the group with admin:

```
Route::prefix('admin')->group(function () {
    Route::get('users', function () {
        // Matches The "/admin/users" URL
    });
});
```

**request body** is data sent by the client to your API. A response body is the data your API sends to the client. Your API almost always has to send a response body. But clients don't necessarily need to send request bodies all the time.

**Request “Query”** If the parameter is of a singular type (like int, float, str, bool, etc) it will be interpreted as a query parameter.

**Request “Params”** When you declare other function parameters that are not part of the path parameters, they are automatically interpreted as "query" parameters.
