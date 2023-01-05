# Class 29 reading notes

(https://reactjs.org/docs/hooks-reference.html#usereducer)

1. Name an alternative to the useState Hook.
An alternative to useState. Accepts a reducer of type (state, action) => newState, and returns the current state paired with a dispatch method. (If you’re familiar with Redux, you already know how this works.)
<br>

2. Why might the useReducer Hook be preferable to the useState Hook?
useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks.
<br>

3. What are two ways to set the initial state?
lazy initiation, and bailing out of a dispatch.
<br>

(https://blog.logrocket.com/guide-to-react-usereducer-hook/)

1. In terms of state, what does useReducer expect to receive as a parameter?
Hook. It accepts a reducer function as its first parameter and the initial state as the second.
<br>

2. What does useReducer return?
useReducer returns an array that holds the current state value and a dispatch function to which you can pass an action and later invoke it
<br>

3. Explain dispatch to a non-technical recruiter.
Dispatch is a function that takes in it tells the reducer what action to perform. and also updates the state of the function.
