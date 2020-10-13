
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



