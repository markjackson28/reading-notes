
# Class 05

[Home](https://markjackson28.github.io/reading-notes/)

## Summary/Notes of readings 

[React Docs - thinking in React](https://reactjs.org/docs/thinking-in-react.html)

*How would you break a mock into a component heirarchy?*

- “Draw boxes around every component (and subcomponent) in the mock and give them all names.”

*What is the ```single responsibility principle``` and how does it apply to components?*

- That a component should do one thing. It applies to components because you have to decide  if a component should do one thing or multiple.

*What does it mean to build a ‘static’ version of your application?*

- Build the app that renders but with no interactivity.

*Once you have a static application, what do you need to add?*

- Add state.

*What are the three questions you can ask to determine if something is state?*

- “Is it passed in from a parent via props? If so, it probably isn’t state.”
- “Does it remain unchanged over time? If so, it probably isn’t state.”
- “Can you compute it based on any other state or props in your component? If so, it isn’t state."

*How can you identify where state needs to live?*

- “Identify every component that renders something based on that state.”
- “Find a common owner component (a single component above all the components that need the state in the hierarchy).”
- “Either the common owner or another component higher up in the hierarchy should own the state.”
- “If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.”

## Things I want to know more about
