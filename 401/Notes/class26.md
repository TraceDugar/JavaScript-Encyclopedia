## Class 26 Reading Notes

(https://facebook.github.io/react/docs/hello-world.html)

1. What are the building blocks of a React app?
Elements and compnonents.
<br>

2. What is the difference between an element and a React component?
A React element is an object representation of a DOM node. A component encapsulates a DOM tree.
<br>

3. What are some advantages of React’s component based architecture?
It's modular nature.
<br>

(https://facebook.github.io/react/docs/introducing-jsx.html)

1. What is JSX and why do we use it?
It is called JSX, and it is a syntax extension to JavaScript. We recommend using it with React to describe what the UI should look like. JSX may remind you of a template language, but it comes with the full power of JavaScript.
<br>

2. Describe the process of embedding JavaScript expressions in JSX.
You can put any valid JavaScript expression inside the curly braces in JSX. For example, 2 + 2, user.firstName, or formatName(user) are all valid JavaScript expressions.
<br>

3. Is it safe to embed user input in JSX? Explain.
By default, React DOM escapes any values embedded in JSX before rendering them. Thus it ensures that you can never inject anything that’s not explicitly written in your application. Everything is converted to a string before being rendered. This helps prevent XSS (cross-site-scripting) attacks.

<br>

(https://facebook.github.io/react/docs/rendering-elements.html)

1. Explain what a React Component is to a non-technical friend.
A react component is a modular piece of code that can be moved from one react app to another
<br>

2. Describe mutability and React Components, specifically, how is the UI updated?
This can change in a UI to give the user the most correct / accurate datat as intended, and it does this by updating the DOM.
<br>

3. If changes are made to the UI, what does React update?
The Dom, and only whats necessary.
<br>

[Sass](https://devhints.io/sass)
[React I](https://devhints.io/react)
[React II](https://reactcheatsheet.com/)
