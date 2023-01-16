# Class 36 Reading Notes

(https://egghead.io/courses/getting-started-with-redux)

What is the first principle of Redux?
Whether or not your app is simple or complex.
<br>

what is a store and what do we use our reducers for within that store?
The store binds together the three principles of redux, it holds the current application state object its lets you dispatch actions, specify the reducer that tells how state is updated with actions.
<br>

Name three Redux store methods given to us by createStore and describe their use.
getState() , dispatch(), and subscribe().
<br>

Explain to a non-technical recruiter what combineReducers() does and why it is useful.
It helps us not write repititive code and combines the actions of the reducers within our app.
