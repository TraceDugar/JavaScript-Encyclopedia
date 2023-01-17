# Class 37 Notes

(https://www.youtube.com/watch?v=gBER4Or86hE)

Why create multiple reducers?
To handle all of the data within an application.
<br>

How would you combine multiple reducers?
Create a combinereducer function, then pass in the data that will be modified in the object, and also the correlating reducer.
<br>

How will you manage state as an immutable object? why?
Always return a new state object.
<br>

(https://redux.js.org/recipes/structuring-reducers/using-combinereducers/)

combineReducers is a utility function to simplify the most common use case when writing Redux Reducers .

<br>

Explain how combineReducers assembles the new state tree.
combineReducers will call each slice reducer with its current slice of state and the current action, giving the slice reducer a chance to respond and update its slice of state if needed. So, in that sense, using combineReducers does "call all reducers", or at least all of the slice reducers it is wrapping.
<br>

How would you define initial state in an app using combineReducers?
combineReducers takes an object full of slice reducer functions, and creates a function that outputs a corresponding state object with the same keys. This means that if no preloaded state is provided to createStore, the naming of the keys in the input slice reducer object will define the naming of the keys in the output state object. The correlation between these names is not always apparent, especially when using ES6 features such as default module exports and object literal shorthands.
<br>

(https://redux.js.org/api/combinereducers/)

Why will you want to split your reducing functions as your app becomes more complex?
You'll want to split your reducing function into separate functions, each managing independent parts of the state.
<br>

The combineReducers helper function turns an object whose values are different reducing functions into a single reducing function you can pass to ____.

<br>

What is a popular convention when naming reducers?
A popular convention is to name reducers after the state slices they manage, so you can use ES6 property shorthand notation: combineReducers({ counter, todos }). This is equivalent to writing combineReducers({ counter: counter, todos: todos }).
