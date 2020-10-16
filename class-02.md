# Classes, Inheritance, Functional Programming

**What’s the primary difference between ES6 Classes and Constructor/Prototype Classes?**

that a class defines a type which can be instantiated at runtime, whereas a prototype is itself an object instance.
Name a use case for a static method
when you want to provide class level access a method where the method should be callable without an instance of the class.
Write an example of a Higher Order function and describe the use case it solves
sort, reduce, filter, forEach, map are examples of Higher Order functions
they are used to make code more general or flexible by parameterising behaviour.

**Inheriting "methods"**
JavaScript does not have "methods" in the form that class-based languages define them. In JavaScript, any function can be added to an object in the form of a property. An inherited function acts just as any other property, including property shadowing as shown above (in this case, a form of method overriding).

When an inherited function is executed, the value of this points to the inheriting object, not to the prototype object where the function is an own property.

## Vocabulary Terms:
**ecosystem:** a collection of software projects, which are developed and co-evolve in the same environment' 
**Node.js:** is a JavaScript runtime built on Chrome's V8 JavaScript engine.
**V8 Engine**: V8 is Google's open source high-performance JavaScript and WebAssembly engine, written in C++. 
**module**:a module is a part of a program. Programs are composed of one or more independently developed modules that are not combined until the program is linked. A single module can contain one or several routines. 
**package:** is a collection of programs that perform similar functions or have similar features. 
**node package manager (npm):** npm is the world's largest Software Registry. The registry contains over 800,000 code packages. Open-source developers use npm to share software. Many organizations also use npm to manage private development.
**server:** is a type of software that is designed to be used, operated and managed on a computing server. It provides and facilitates the harnessing of underlying server computing power for use with an array of high-end computing services and functions. 
**environment:** The state of a computer, usually determined by which programs are running and basic hardware and software characteristics. 
**interpreter:** A JavaScript engine is a program or an interpreter which executes JavaScript code. A JavaScript engine can be implemented as a standard interpreter, or just-in-time compiler that compiles JavaScript to bytecode in some form. 
**compiler:** The source code is passed through a program called a compiler, which translates it into bytecode that the machine understands and can execute.


**Why would you want to run JavaScript code outside of a browser?**
Running JavaScript without/outside a browser means you are using node.js technology to execute your JavaScript code. This type of usage of javascript typically refers to backend programming where your javascript code will interact with your database and can be used to create RESTful APIs.
**What is the difference between a module and a package?**
A module is a single file (or files) that are imported under one import and used. e.g. A package is a collection of modules in directories that give a package hierarchy.

**What does the node package manager do?**
 1- for publishing of open-source Node. js projects.
 2- for interacting with said repository that aids in package installation, version management, and dependency management.

