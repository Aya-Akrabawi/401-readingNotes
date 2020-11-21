# class 31

## React Hooks:

![](https://i.morioh.com/2934a8d84c.png)

**What Are Hooks, Exactly?**

Hooks are a new addition in React 16.8. They let you use state and other React features without writing a class. 
let's take a step back and think about code reuse to understand hooks.
Today, there are a lot of ways to reuse logic in React apps. We can write simple functions and call them to calculate something. We can also write components (which themselves could be functions or classes). Components are more powerful, but they have to render some UI. This makes them inconvenient for sharing non-visual logic. This is how we end up with complex patterns like render props and higher-order components.
Functions seem to be a perfect mechanism for code reuse. Moving logic between functions takes the least amount of effort. However, functions can’t have local React state inside them. You can’t extract behavior like “watch window size and update the state” or “animate a value over time” from a class component without restructuring your code or introducing an abstraction like Observables. Both approaches hurt the simplicity that we like about React.
Hooks solve exactly that problem. Hooks let you use React features (like state) from a function — by doing a single function call. React provides a few built-in Hooks exposing the “building blocks” of React: state, lifecycle, and context.

this example is written with react hooks:

![](https://user-images.githubusercontent.com/1768483/59966958-6724b980-94f1-11e9-878f-92ab951f9ff3.gif)

**When would I use a Hook?**
If you write a function component and realize you need to add some state to it, previously you had to convert it to a class. Now you can use a Hook inside the existing function component. We’re going to do that right now!

**How does this work?**
by convention, we use set + state-variable to name this function useState() takes a single param, which is the initial value to assign to the state variable

**Basic Hooks**
useState
useEffect
useContext