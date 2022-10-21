## Class 5 Reading Notes

**React Docs - Thinking in React**

1. **What is the single responsibility principle and how does it apply to components?**
*One such technique is the single responsibility principle, that is, a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.*
<br>

2. **What does it mean to build a ‘static’ version of your application?**
*To build a static version of your app that renders your data model, you’ll want to build components that reuse other components and pass data using props. props are a way of passing data from parent to child. If you’re familiar with the concept of state, don’t use state at all to build this static version. State is reserved only for interactivity, that is, data that changes over time. Since this is a static version of the app, you don’t need it.*
<br>

3. **Once you have a static application, what do you need to add?**
*Identify The Minimal (but complete) Representation Of UI State*
<br>

4. **What are the three questions you can ask to determine if something is state?**
<br>
1. Is it passed in from a parent via props? If so, it probably isn’t state.
<br>
2. Does it remain unchanged over time? If so, it probably isn’t state.
<br>
3. Can you compute it based on any other state or props in your component? If so, it isn’t state.
<br>
<br>

5.**How can you identify where state needs to live?**
*For each piece of state in your application:

Identify every component that renders something based on that state.
Find a common owner component (a single component above all the components that need the state in the hierarchy).
Either the common owner or another component higher up in the hierarchy should own the state.
If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.*
<br>

//----source: https://reactjs.org/docs/thinking-in-react.html


**Higher-Order Functions**

1.**What is a “higher-order function”?**
*Functions that operate on other functions, either by taking them as arguments or by returning them, are called higher-order functions. Since we have already seen that functions are regular values, there is nothing particularly remarkable about the fact that such functions exist. The term comes from mathematics, where the distinction between functions and other values is taken more seriously.*
*Higher-order functions allow us to abstract over actions, not just values. They come in several forms. For example, we can have functions that create new functions.*
<br>

2.**Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?**
*Line 2 is returning the formula m is > n;*
<br>

3.**Explain how either map or reduce operates, with regards to higher-order functions.**
*Map gets the data from one array, and builds a brand new one with the slected or changed data.*
<br>


//----source: https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK
