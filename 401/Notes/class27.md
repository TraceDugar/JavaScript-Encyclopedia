# Class 27 Notes

(https://reactjs.org/docs/hooks-intro.html#motivation)

1. What was the motivation for introducing Hooks?
Hooks solve a wide variety of seemingly unconnected problems in React that we’ve encountered over five years of writing and maintaining tens of thousands of components. Whether you’re learning React, use it daily, or even prefer a different library with a similar component model, you might recognize some of these problems.
<br>

2. What changes are important regarding implementing Hooks versus Component Classes?
With Hooks, you can extract stateful logic from a component so it can be tested independently and reused. Hooks allow you to reuse stateful logic without changing your component hierarchy. This makes it easy to share Hooks among many components or with the community.
<br>

3. Hooks allow you to reuse stateful logic without changing ___ _______.
compnonent heircarchy
<br>

(https://reactjs.org/docs/hooks-overview.html)

1. Name two rules imposed by React Hook usage.
  1. Only call Hooks at the top level. Don’t call Hooks inside loops, conditions, or nested functions.
  2. Only call Hooks from React function components. Don’t call Hooks from regular JavaScript functions. (There is just one other valid place to call Hooks — your own custom Hooks. We’ll learn about them in a moment.)
<br>

2. How would you identify a custom Hook and why might you create one?
Sometimes, we want to reuse some stateful logic between components. Traditionally, there were two popular solutions to this problem: higher-order components and render props. Custom Hooks let you do this, but without adding more components to your tree.
<br>

(https://reactjs.org/docs/hooks-state.html)

1. What is a Hook?
A Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components. We’ll learn other Hooks later.
<br>

2. When would I use the useState Hook?
If you write a function component and realize you need to add some state to it, previously you had to convert it to a class. Now you can use a Hook inside the existing function component. We’re going to do that right now!
<br>

If you were to add React state to a function component by declaring a state variable:
<br>
  1. What does calling useState do?
  It declares a “state variable”. Our variable is called count but we could call it anything else, like banana. This is a way to “preserve” some values between the function calls — useState is a new way to use the exact same capabilities that this.state provides in a class. Normally, variables “disappear” when the function exits but state variables are preserved by React.
  <br>
  
  2. What do we pass to useState as an argument?
  The only argument to the useState() Hook is the initial state. Unlike with classes, the state doesn’t have to be an object. We can keep a number or a string if that’s all we need. In our example, we just want a number for how many times the user clicked, so pass 0 as initial state for our variable. (If we wanted to store two different values in state, we would call useState() twice.)
  <br>
  
  3. What does useState return?
     It returns a pair of values: the current state and a function that updates it. This is why we write const [count, setCount] = useState(). This is similar to this.state.count and this.setState in a class, except you get them in a pair. If you’re not familiar with the syntax we used, we’ll come back to it at the bottom of this page.
     
