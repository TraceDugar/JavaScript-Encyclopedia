##Class 09 Reading Notes

**Understanding the JavaScript Call Stack**

1. **What is a ‘call’?**
*The call stack is primarily used for function invocation (call). Since the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous.*
<br>

2. **How many ‘calls’ can happen at once?**
*In Asynchronous JavaScript, we have a callback function, an event loop, and a task queue. The callback function is acted upon by the call stack during execution after the call back function has been pushed to the stack by the event loop.*
<br>

3. **What does LIFO mean?**
*LIFO: When we say that the call stack, operates by the data structure principle of Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.*
<br>

4. **Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.**
*Their drawing //----source: https://cdn-media-1.freecodecamp.org/images/QgR2uIk7tW0YNz0Xm8g0jAPeRFI0e4sCejsv*
<br>

5. **What causes a Stack Overflow?**
*A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.*
<br>


//----source: https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4

**JavaScript error messages**

1. **What is a ‘reference error’?**
*This is as simple as when you try to use a variable that is not yet declared you get this type os errors.*
<br>

2. **What is a ‘syntax error’?**
*I know it’s in the name of the errors, but like it says itself, this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.*
<br>

3. **What is a ‘range error’?**
*Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.*
<br>

4. **What is a ‘type error’?**
*Like the name indicates, this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.*
<br>

5. **What is a breakpoint?**
*You can also add conditional breakpoints by right-clicking a previous set breakpoint, which will make your program stop at that point only if a condition is met, this is awesome for when you want to debug huge cycles for specific values. You can also add conditional breakpoints by right-clicking a previous set breakpoint, which will make your program stop at that point only if a condition is met, this is awesome for when you want to debug huge cycles for specific values. You can also add conditional breakpoints by right-clicking a previous set breakpoint, which will make your program stop at that point only if a condition is met, this is awesome for when you want to debug huge cycles for specific values. You can also add conditional breakpoints by right-clicking a previous set breakpoint, which will make your program stop at that point only if a condition is met, this is awesome for when you want to debug huge cycles for specific values. You can also add conditional breakpoints by right-clicking a previous set breakpoint, which will make your program stop at that point only if a condition is met, this is awesome for when you want to debug huge cycles for specific values.*
<br>

6. **What does the word ‘debugger’ do in your code?**
*The breakpoint can also be achieved by putting a debugger statement in your code in the line you want to break.*
<br>

//----source: https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c
