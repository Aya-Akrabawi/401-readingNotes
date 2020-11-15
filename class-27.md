# Class 26

**Components**

split the UI into independent, reusable pieces, and think about each piece in isolation. This page provides an introduction to the idea of components.

**Stateful and Stateless Components**

Stateful and stateless components have many different names.

They are also known as:

* Container vs Presentational components

* Smart vs Dumb components

The literal difference is that one has state, and the other doesn’t. That means the stateful components are keeping track of changing data, while stateless components print out what is given to them via props, or they always render the same thing.

**React life cycles**

**Mounting**

* componentWillMount
* render
* componentDidMount
**Updating**

* componentWillReceiveProps
* shouldComponentUpdate
* componentWillUpdate
* render
* componentDidUpdate
**Unmounting**

* componentWillUnmount

## Review:

* Does a deployed React application require a server?
No

* Why do we prefer to test a React application at the behavior rather than the unit level?

because it allows us to easily refactor code going forward.

* What does ```npm run build do```?

does nothing unless you specify what "build" does in your package.json file. It lets you perform any necessary building/prep tasks for your project, prior to it being used in another project.

