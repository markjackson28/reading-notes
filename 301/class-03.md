
# Class 03

[Home](https://markjackson28.github.io/reading-notes/)

## Summary/Notes of readings 

[React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)

*What does .map() return?*

- .map() returns a new array the same length as the array that is passed in.

*If I want to loop through an array and display each value in JSX, how do I do that in React?*

- You put the array variable into curly braces in the function.

*Each list item needs a unique ____.*

- ID.

*What is the purpose of a key?*

- ‘Keys help React identify which items have changed, are added, or are removed.’

[The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

*What is the spread operator?*

- The spread operator ‘expands an iterable object arr into the list of arguments’

*List 4 things that the spread operator can do.*

- Copy an array, concatenating or combining arrays, use math functions, and using an array as arguments.

*Give an example of using the spread operator to combine two arrays.*

```
const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩
```

*Give an example of using the spread operator to add a new item to an array.*

```
const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]
```

*Give an example of using the spread operator to combine two objects into one.*

```
const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂
```

[How to Pass Functions Between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)

*In the video, what is the first step that the developer does to pass functions between components?*

- The developer creates an ‘increment’ function.

*In your own words, what does the ```increment``` function do?*

- The increment function updates the states count whenever a name is clicked.

*How can you pass a method from a parent component into a child component?*

- Wherever you want to pass the method, you add ```this.props.nameofmethod()```.

*How does the child component invoke a method that was passed to it from a parent component?*

- You pass in whatever prop you want to invoke into the parentheses. ```this.props.nameofmethod(this.props.nameofkey)```
