# Node Ecosystem, TDD, CI/CD
**Why would you want to run JavaScript code outside of a browser?**


js allows you to write programs in JavaScript which can be run outside the browser. JavaScript is no longer just a browser scripting language. It's used for things it's not intended for, thus you hear about new frameworks being released everyday.

**What is the difference between a module and a package?**


A module is a single JavaScript file that has some reasonable functionality. A package is a directory with one or more modules inside of it and a package. json file which has metadata about the package. Now it's very common for people to refer to a package as a module.

**What does the node package manager do?**


Node Package Manager (NPM) is a command line tool that installs, updates or uninstalls Node. js packages in your application. It is also an online repository for open-source Node. js packages.

**Provide code snippets showing 3 different ways to export a function from a node module**


modules.exports = functionName()
export function functionName(){return 'written code'}
modules.exports = {firstFunction() , secondFunction() }

**What is NPM?**


-npm is the world's largest Software Registry.

The registry contains over 800,000 code packages.

Open-source developers use npm to share software.

Many organizations also use npm to manage private development.
### Definitions:

1- **Array.map()**:The map() method creates a new array with the results of calling a function for every array element. The map() method calls the provided function once for each element in an array, in order.

2- **Array.reduce()**: The reduce() method reduces the array to a single value. The reduce() method executes a provided function for each value of the array (from left-to-right). The return value of the function is stored in an accumulator (result/total).

3- **SuperAgent**: is a light-weight, flexible and expressive Ajax library. ... The Github APIs support CORS and so you can make Ajax requests to them directly from here.
 
**superagent with then/catch**
```
superagent.post('/api/pet').then(console.log).catch(console.error);
 ```

 **promise with async/await**
```
(async () => {
  try {
    const res = await superagent.post('/api/pet');
    console.log(res);
  } catch (err) {
    console.error(err);
  }
})();
```
4- **Promises in JavaScript**
It allows you to associate handlers with an asynchronous action's eventual success value or failure reason. This lets asynchronous methods return values like synchronous methods: instead of immediately returning the final value, the asynchronous method returns a promise to supply the value at some point in the future.

5- **Are all callback functions considered to be Asynchronous? Why or Why Not?**
yes, because when we pass a callback to a function, we expect that function to call our callback function some other time. However, it isn't automatically asynchronous. 

**Which 3 things had you heard about previously and now have better clarity on?**


1- Array.reduce()
2- promise with async/await
3-  NodeJS

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**


1- full stack issues
2- learn more about npm 
3- learn more about promises
**What are you most excited about trying to implement or see how it works?**


try more npm packages 