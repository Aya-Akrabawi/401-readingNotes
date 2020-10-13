# Advanced Mongo/Mongoose

## The Repository Design Pattern:

In Software Engineering a **design pattern** is a reusable solution to a general problem occurring in a given context in software design. A design pattern is not a design which is directly transferred into code(source or machine).
In order for our application to use Repositories, first we need to set things up.
We are going to need:

* UserRepository
* EloquentUserRepository
* A way to bind UserRepository and EloquentUserRepository

## Testing Node.js + Mongoose with an in-memory database:

To create a mongoose schema and a service that executes some operations with that schema.
1. Setup & Install dependencies
2. Write code to test
  2.a Product schema
  2.b Product service
3. Configure jest
4. In-memory database handling
5. Write some tests
6. Try it out!


## Why would a developer choose to make data models?
- A data model not only improves the conceptual quality of an application, it also lets you leverage database features that improve data quality.

## What purpose do CRUD operations serve?
- these operations map well to the HTTP verbs most frequently used in REST: Create (SQL INSERT) POST Used to support the creation of a child resource, but can also modify the underlying state of a system.

## What kind of database is Postgres? What kind of database is MongoDB?
>- Postgres: relational database management system.
>>- MongoDB: Not SQL related.


## What is Mongoose and why do we need it?
-  Object Data Modeling (ODM) library for MongoDB and Node. js.

## Describe how NoSQL Databases scale horizontally
- each node contains only part of the data

# TERMS:
- Database: its a place to hold and organize data inside it.
- data model: the model which organized the element of data.
- CRUD: create, read, update, and delete are the four basic functions of persistent storage
- schema: is a collection of logical structures of data.
- Structured Query Language (SQL):language for storing,manipulating and retrieving data in databases.
- MongoDB: cross-platform document-oriented database program. Classified as a NoSQL database program
- Mongoose: Mongoose is a MongoDB object modeling tool designed to work in an asynchronous environment.
- Record: Is composed of fields and contains all the data about one particular item in a database.
- document: A document database is a type of nonrelational database that is designed to store and query data as JSON-like documents.
- Object Relation Mapping (ORM): is a programming technique for converting data between incompatible type systems using object-oriented programming languages.

**Which 3 things had you heard about previously and now have better clarity on?**

nothing

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**

1- NoSQL
2- memory databas testing
3- deep knowing about mongo

**What are you most excited about trying to implement or see how it works?**

everything :P