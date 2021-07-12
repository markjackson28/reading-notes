
# Class 02

[Home](https://markjackson28.github.io/reading-notes/)

## Summary/Notes of readings

[React lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

*Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?*

- render.

*What is the very first thing to happen in the lifecycle of React?*

- Mounting.

*Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates.*

- constructor, render, componentDidMount, React Updates, componentWillUnmount.

*What does componentDidMount do?*

- ‘This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions. If you do that, don’t forget to unsubscribe in componentWillUnmount().’

[React State Vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)

*What types of things can you pass in the props?*

- Most things that don’t need constant updating such as titles, text, ect.

*What is the big difference between props and state?*

- Props are handled outside of the component. State is handled inside the component.

*When do we re-render our application?*

- Whenever something is updating or changing such as a timer or checkbox.

*What are some examples of things that we could store in state?*

- Anything you want to change based on what you want or what the user action is. Or whatever information you want to hold from the component.

## Things I want to know more about
