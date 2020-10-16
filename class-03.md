
# Read: Class 03
**no sql database**
NoSQL can be defined as an approach to database designing, which holds a vast diversity of data such as key-value, multimedia, document, columnar, graph formats, external files, etc. NoSQL is purposefully developed for handling specific data models having flexible schemas to build modern applications.

![](https://shishirkumarblog.files.wordpress.com/2019/05/sql-vs-nosql.png?w=584)

**pure function** : Its return value is the same for the same arguments (no variation with local static variables, non-local variables, mutable reference arguments or input streams from I/O devices).

**higher-order function:** function that takes a function as an argument, or returns a function.

**immutable state:** (unchangeable object) is an object whose state cannot be modified after it is created. object: one of JavaScript’s data types. It is used to store various keyed collections and more complex entities.

**object-oriented programming (OOP)**: is about creating objects that contain both data and functions.

**class** :is an extensible program-code-template for creating objects, providing initial values for state (member variables) and implementations of behavior (member functions or methods).

**prototype** : The prototype is an object that is associated with every functions and objects by default in JavaScript, where function’s prototype property is accessible and modifiable.

**super** : keyword is used to access and call functions on an object’s parent.

**inheritance** : the mechanism of basing an object or class upon another object (prototype-based inheritance) or class (class-based inheritance), retaining similar implementation.

**constructor** : function that creates an instance of a class which is typically called an “object”.

**instance** : is an object containing data and behavior described by the class.

**context** : It refers to the object within the function being executed.

**this**: this keyword refers to an object, that object which is executing the current bit of javascript code. Test Driven Development (TDD) : is a process for writing software that provably satisfies the software requirements.

**Jest** : JavaScript testing framework maintained by Facebook, Inc. with a focus on simplicity.

**Continuous Integration (CI)** :development practice that requires developers to integrate code into a shared repository several times a day.

**unit test** : level of software testing where individual units components of a software are tested.


**Why would a developer choose to make data models?**
becuase A data model not only improves the conceptual quality of an application, it also lets you leverage database features that improve data quality.
**What purpose do CRUD operations serve?**
user-interface conventions that allow viewing, searching and modifying information through computer-based forms and reports.
**What kind of database is Postgres? What kind of database is MongoDB?**
Postgres: relational database management system.
MongoDB: Not SQL related.
**What is Mongoose and why do we need it?**
Object Data Modeling (ODM) library for MongoDB and Node. js. It manages relationships between data, provides schema validation, and is used to translate between objects in code and the representation of those objects in MongoDB.

 
 
 ### previouse class:
 
  **Name 3 advantages to Test Driven Development**


1. Better program design and higher code quality
2. Detailed project documentation
3. Code flexibility and easier maintenance

  **In what case would you need to use beforeEach() or afterEach() in a test suite?**

before/after every ``it`` block in the current context and all nested contexts.

  **What is one downside of Test Driven Development**


It necessitates a lot of time and effort up front, which can make development feel slow to begin with.


  **What’s the primary difference between ES6 Classes and Constructor/Prototype Classes?**


that a class defines a type which can be instantiated at runtime, whereas a prototype is itself an object instance.


  **Name a use case for a static method**

Static methods are used for the functionality that belongs to the class “as a whole”. It doesn't relate to a concrete class instance. 

  **Write an example of a Higher Order function and describe the use case it solves**


```const arr1 = [1, 2, 3];
const arr2 = arr1.map(function(item) {
  return item * 2;
});
console.log(arr2);
```

to return the multiplication of each number inside the array by 2.



