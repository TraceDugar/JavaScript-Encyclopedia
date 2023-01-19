# class 39 notes

(https://redux-toolkit.js.org/introduction/getting-started)

What concerns are addressed by Redux Toolkit?

<ul>
<li>"Configuring a Redux store is too complicated"</li>
<li>"I have to add a lot of packages to get Redux to do anything useful"</li>
<li>"Redux requires too much boilerplate code"</li>
</ul>

<br>

What does configureStore() do?
configureStore(): wraps createStore to provide simplified configuration options and good defaults. It can automatically combine your slice reducers, adds whatever Redux middleware you supply, includes redux-thunk by default, and enables use of the Redux DevTools Extension.
<br>

How would I use createSlice()?
createSlice(): accepts an object of reducer functions, a slice name, and an initial state value, and automatically generates a slice reducer with corresponding action creators and action types.
<br>

(https://mobx.js.org/getting-started.html)

What is Mobx?
MobX is a simple, scalable and battle tested state management solution. This tutorial will teach you all the important concepts of MobX in ten minutes. MobX is a standalone library, but most people are using it with React and this tutorial focuses on that combination.
<br>

How does MobX make it “impossible” to produce an inconsistent state?
MobX makes state management simple again by addressing the root issue: it makes it impossible to produce an inconsistent state. The strategy to achieve that is simple: Make sure that everything that can be derived from the application state, will be derived. Automatically.
<br>

How would we build a reactive user interface?
Ok, so far we made a silly report reactive. Time to build a reactive user interface around this very same store. React components are (despite their name) not reactive out of the box. The observer HoC wrapper from the mobx-react-lite package fixes that by basically wrapping the React component in autorun. This keeps the component in sync with the state. This is conceptually not different from what we did with the report before.
<br>

(https://redux-toolkit.js.org/tutorials/intermediate-tutorial)

What take-away(s) did this tutorial provide?
It provided a guide on how to use react-toolkit as well as advice on how to use it.
