# Class 26

Name 5 Javascript UI Frameworks (other than React):

* React
* Vue
* Angular
* Ember
* Backbone.js
* Mithril


**What’s the difference between a framework and a library?**

When you use a library, you are in charge of the flow of the application. You are choosing when and where to call the library. When you use a framework, the framework is in charge of the flow. It provides some places for you to plug in your code, but it calls the code you plugged in as needed.


## React
![](https://reactjs.org/logo-og.png)

**React** is an open-source, front end, JavaScript library for building user interfaces or UI components. It is maintained by Facebook and a community of individual developers and companies.

**The smallest React example looks like this:**
```
`ReactDOM.render(

Hello, world!
, document.getElementById('root') );`
```

**JSX**
it is a syntax extension to JavaScript.
```
 const element = <h1>Hello, world!</h1>;
 ```

**Why JSX?**

React embraces the fact that rendering logic is inherently coupled with other UI logic:

* how events are handled
* how the state changes over time,
* how the data is prepared for display.

**Rendering Elements**

* Elements are the smallest building blocks of React apps.
* Unlike browser DOM elements, React elements are plain objects, and are cheap to create. React DOM takes care of updating the DOM to match the React elements.
* React elements are immutable.
* React Only Updates What’s Necessary

**SASS**

Syntactically awesome style sheets (Sass) is an extension of CSS that enables you to use things like variables, nested rules, inline imports and more.

Sass is the most mature, stable, and powerful professional grade CSS extension language in the world.
Sass is completely compatible with all versions of CSS.