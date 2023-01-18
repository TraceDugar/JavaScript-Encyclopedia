# Class 38

(https://redux.js.org/advanced/asyncactions)

Why use Redux middleware?
Redux middleware can do anything when it sees a dispatched action: log something, modify the action, delay the action, make an async call, and more. Also, since middleware form a pipeline around the real store.dispatch function, this also means that we could actually pass something that isn't a plain action object to dispatch, as long as a middleware intercepts that value and doesn't let it reach the reducers.

Middleware also have access to dispatch and getState. That means you could write some async logic in a middleware, and still have the ability to interact with the Redux store by dispatching actions.
<br>

Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.
The state is updated by the ui which does the deposit command, the action /thunk goes to middleware where it inturn goes to the api as a req.  Once we get the response it dispatched the response and state is updated.
<br>

How are we accommodating async in our Redux app?
at the moment using redux, create store.
<br>

(https://github.com/reduxjs/redux-thunk)

Why would you need redux-thunk middleware?
Thunk middleware for Redux. It allows writing functions with logic inside that can interact with a Redux store's dispatch and getState methods.
<br>

Redux Thunk middleware allows you to write action creators that return a **function** instead of an action.

<br>

Describe how any return value from the inner thunk function will be made available.
Redux Thunk middleware allows you to write action creators that return a function instead of an action. The thunk can be used to delay the dispatch of an action, or to dispatch only if a certain condition is met. The inner function receives the store methods dispatch and getState as parameters.
