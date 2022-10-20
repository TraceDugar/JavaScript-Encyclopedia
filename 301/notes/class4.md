## Class 4 Reading ntoes

**React Docs - Forms**

1. **What is a ‘Controlled Component’?**

*In HTML, form elements such as input, textarea, and select typically maintain their own state and update it based on user input.* 
*In React, mutable state is typically kept in the state property of components, and only updated with setState().*
*We can combine the two by making the React state be the “single source of truth”. Then the React component that renders a form also controls what happens in that form on subsequent user input.*
*An input form element whose value is controlled by React in this way is called a “controlled component”.*
  
 <br>
  
2. **Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.**

*Since the value attribute is set on our form element, the displayed value will always be this.state.value, making the React state the source of truth. Since handleChange runs on every keystroke to update the React state, the displayed value will update as the user types.*
*With a controlled component, the input’s value is always driven by the React state. While this means you have to type a bit more code, you can now pass the value to other UI elements too, or reset it from other event handlers.*
<br>

3. **How do we target what the user is entering if we have an event handler on an input field?**

*In React, a textarea uses a value attribute instead. This way, a form using a textarea can be written very similarly to a form that uses a single-line input.*
<br>


//----source:https://reactjs.org/docs/forms.html

**The Conditional (Ternary) Operator Explained**

1. **Why would we use a ternary operator?**

*Shorten your if statements into one line of code with the conditional operator*
<br>

2.**Rewrite the following statement using a ternary statement:**

*x ==== y (true ? 'ture' : 'false"*
<br>

//----source:https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff
