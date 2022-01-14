# Context API - Behaviors

[Home](https://markjackson28.github.io/reading-notes/)

## Summary/Notes of readings

*When you have multiple contexts, what component type should you use (class/function) and why?*

- I would say it depends on person to person but I would use functional because it seems a bit easier to comprehend.

*What are some good use cases for using the Context API for global state?*

- Themes and authentication.

*How can you best test context?*

- Try to use it throughout multiple components.

*Terms*

- Context: ‘Context provides a way to pass data through the component tree without having to pass props down manually at every level.’[Ref.](https://reactjs.org/docs/context.html)

- `useContext()`: ‘Accepts a context object (the value returned from `React.createContext`) and returns the current context value for that context. The current context value is determined by the `value` prop of the nearest `<MyContext.Provider>` above the calling component in the tree.’ [Ref.](https://reactjs.org/docs/hooks-reference.html#usecontext)

- Static Context: allows React to get the values without initializing the component.
