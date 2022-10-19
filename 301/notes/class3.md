## Class 3 Reading Notes

**React Docs - lists and keys**

1.**What does .map() return?**
*a new array.*

2.**If I want to loop through an array and display each value in JSX, how do I do that in React?**
*You can build collections of elements and include them in JSX using curly braces {}.*
*We loop through the numbers array using the JavaScript map() function. We return a li element for each item.* 
*Finally, we assign the resulting array of elements to listItems.*

3. **Each list item needs a unique ____.**
*key*

4.**What is the purpose of a key?**
*A “key” is a special string attribute you need to include when creating lists of elements.*

//----source: https://reactjs.org/docs/lists-and-keys.html


**The Spread Operator**

1.**What is the spread operator?**
*The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.*

2.**List 4 things that the spread operator can do.**
  
  <ol>
  <li>Copying an array
  <li>Using Math functions
  <li>Using an array as arguments
  <li>Combining objects
  </ol>

3.**Give an example of using the spread operator to combine two arrays.**
*const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩*

4.**Give an example of using the spread operator to add a new item to an array.**
*const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]*

5**Give an example of using the spread operator to combine two objects into one.**
*const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂*


//----source:https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab

**How to Pass Functions Between Components**
1.**In the video, what is the first step that the developer does to pass functions between components?**
*Creates increment function, passing in person object*

2.**In your own words, what does the increment function do?**
*Increment, adds 1 to a total it its being incremented to, and decremenet is subtracting one.*

3.**How can you pass a method from a parent component into a child component?**
*Using props*

4.**How does the child component invoke a method that was passed to it from a parent component?**
*this.props.methodName*

//----source: https://www.youtube.com/watch?v=c05OL7XbwXU
