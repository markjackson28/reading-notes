# Component Lifecycle / `useEffect()` Hook

[Home](https://markjackson28.github.io/reading-notes/)

## Summary/Notes of readings

*Why do we not need more .html pages in a multi-page React app?*

- Because React is a single page app.

*If we wanted a component to show up on every page, where would we put it and why?*

- Inside the `<BrowserRouter />`, outside a `<Route />` because you want `<BrowserRouter />` to have access to that component but not in a specific route.

*What does routing do with the components that were rendered when a new route is requested?*

- It will render the component that is associated with that route.

*What does props.children contain?*

- Properties of the children component.

*How do `useState()` and `this.setState()` differ?*

- `this.setState()` is a class component whereas `useState()` is a functional component.

*Terms*

- State Hook: ‘A Hook is a special function that lets you “hook into” React features. For example, `useState` is a Hook that lets you add React state to function components. We’ll learn other Hooks later.’ [Ref.](https://reactjs.org/docs/hooks-state.html)

- Mounting and Un-Mounting: React lifecycle methods that determines what to render.

*Which 3 things had you heard about previously and now have better clarity on?*

- useState.

*Which 3 things are you hoping to learn more about in the upcoming lecture/demo?*

- React, State, functional components.

*What are you most excited about trying to implement or see how it works?*

- `useState`.

*Preparation Materials*

[Effects Hook](https://reactjs.org/docs/hooks-effect.html)
