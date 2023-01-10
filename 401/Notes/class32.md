# Class 32 Reading notes

(https://medium.com/swlh/snackbars-in-react-an-exercise-in-hooks-and-context-299b43fd2a2b)

With regard to the React Context API, what does a “provider” do?
Our context provider is now responsible for both displaying the local state of the snackbars (we call them alerts), and for exposing an API for globally managing them.
<br>

With regard to the React Context API, how would we implement a “consumer” role?
The other half of the puzzle is we now need a consumer for this provider. It turns out that our custom hook from before is nothing more than a small wrapper around the useContext internal React hook, which consumes our new context.
<br>

Specifically with Context, how are we “wrapping” components to achieve our goals?
You’ll notice that value is a new object being created every single time this provider is rendered. That’s not great, because anything consuming this value from the context will potentially also be getting re-rendered.
<br>


(https://github.com/diegohaz/awesome-react-context)

Consume content from (at least) two more of the Awesome React Context links. After some familiarity with React Context, once again share your takeaways from each:
<br>

Takeaway 1: The what's new API video provides alot of information about how things are changing over times and what things were new at the time of this videos release.

<br>

Takeaway 2: The article by Diego Haz, pop over containers are something i want to dig deeper on whenever i have the time to do so!
