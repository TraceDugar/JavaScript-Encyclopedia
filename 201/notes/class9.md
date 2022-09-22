## Class 9 notes

**Html Forms**

1. Web forms are a very powerful tool for interacting with users — most commonly they are used for collecting data from users, or allowing them to control a user interface.
//-source: https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form

2. Try to understand how users want to fill in forms. This is where doing some usability testing and user research on your forms becomes handy. User mental models is a UX concept that can help you with that. Nielsen Norman Group describes it as “what the user believes about the system at hand”. Ask your tester to think aloud and tell you how they would fill the form.
Which steps do they expect? What come first? What comes next? This will give you a better idea of how to structure your form in a more user-friendly way.
//-source: https://www.smashingmagazine.com/2018/08/ux-html5-mobile-form-part-1/
 
4. Form, ormally defines a form and attributes that determine the form's behavior. 
 Fieldset, is a convenient way to create groups of widgets that share the same purpose, for styling and semantic purposes.
 Legend, ormally describes the purpose of the fieldset it is included inside.
 Label,  is the formal way to define a label for an HTML form widget. 
 Headers, used for titing sections.
 //-source: https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form

**JS**
1. Events are signals that something will happen/ is happening.

2. Inside the addEventListener() function, we specify two parameters: 
the name of the event we want to register this handler for, and the code that comprises the handler function we want to run in response to it.

3. Sometimes, inside an event handler function, you'll see a parameter specified with a name such as event, evt, or e. 
This is called the event object, and it is automatically passed to event handlers to provide extra features and information.
It is important for delegating events.

4. Event bubbling and capture are terms that describe phases in how the browser handles events targeted at nested elements.
In the capturing phase:

The browser checks to see if the element's outer-most ancestor (<html>) has a click event handler registered on it for the capturing phase, and runs it if so.
Then it moves on to the next element inside <html> and does the same thing, then the next one, and so on until it reaches the direct parent of the element that was actually clicked.
  
  In the bubbling phase, the exact opposite of the capturing phase occurs:

The browser checks to see if the direct parent of the clicked element has a click event handler registered on it for the bubbling phase, and runs it if so.
Then it moves on to the next immediate ancestor element and does the same thing, then the next one, and so on until it reaches the <html> element.
  
//-source:https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events#a_series_of_fortunate_events
