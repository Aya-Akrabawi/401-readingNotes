# Class 37

### combineReducers(reducers)

**The combineReducers**
The combineReducers helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore. It is pulling in more than one reducer from source and creating a keyed object from them.
The resulting reducer calls every child reducer and gathers their results into a single state object. The state produced by combineReducers() namespaces the states of each reducer under their keys as passed to combineReducers()
```
export default theDefaultReducer = (state = 0, action) => state;

export const firstNamedReducer = (state = 1, action) => state;

export const secondNamedReducer = (state = 2, action) => state;

// Use ES6 object literal shorthand syntax to define the object shape
const rootReducer = combineReducers({
  theDefaultReducer,
  firstNamedReducer,
  secondNamedReducer
});

const store = createStore(rootReducer);
```
**actions**
Each reducer technically has it’s own actions and creators. and If an action is dispatched with both reducers recieving it, both would respond to it.

**Concept**
The most common state shape for a Redux app is a plain Javascript object containing “slices” of domain-specific data at each top-level key,