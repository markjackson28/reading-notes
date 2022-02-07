# Redux - Additional Topics

[Home](https://markjackson28.github.io/reading-notes/)

## Summary/Notes of readings

*What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?*

- Create a function that will fetch the data you want to pre-load and dispatch that at the highest level of the app. 

*When using a thunk/async action that dispatches the actual action, which do you export from your reducer?*

- The thunk/async function that makes the call.

*Which 3 things had you heard about previously and now have better clarity on?*

- Redux.

*Which 3 things are you hoping to learn more about in the upcoming lecture/demo?*

- Redux, React, MaterialUI.

*What are you most excited about trying to implement or see how it works?*

- Thunk.

*Terms*

Middleware: Function that intercepts a request and does whatever the dev wants such as verification and much more.

Thunk: ‘a piece of code that does some delayed work.’ [Ref.](https://redux.js.org/usage/writing-logic-thunks)

*Preparation Materials*

- [Redux Toolkit (RTK)](https://redux-toolkit.js.org/)
  - [Tutorial](https://redux-toolkit.js.org/tutorials/overview)

*Alternative State Managers*

- [MobX](https://mobx.js.org/getting-started.html)
- [HookState](https://hookstate.js.org/)
