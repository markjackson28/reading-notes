# Redux - Combined Reducers

[Home](https://markjackson28.github.io/reading-notes/)

## Summary/Notes of readings

*Why choose Redux instead of the Context API for global state?*

- Redux is better and more robust for state management.

*What is the purpose of a reducer?*

- Take in a previous value and current value; then ‘reduce’ the the two into a new value.

*What does an action contain?*

- Type and payload.

*Why do we need to copy the state in a reducer?*

- Because state in immutable.

*Terms*
- Immutable State: State that is not able to mutate.
- Time Travel in Redux: ‘the ability to move back and forth among the previous states of an application and view the results in real time’ [Ref.](https://blog.scottlogic.com/2017/03/09/relogic-2.html#:~:text=Time%20travel%20is%20the%20ability,is%20always%20exactly%20the%20same.)
- Action Creator: Creates an action function with a type and payload.
- Reducer: a function that takes in a previous value, current value and returns a new value.
- Dispatch: a function that calls/‘dispatches’ an action.

*Which 3 things had you heard about previously and now have better clarity on?*

- Redux.

*Which 3 things are you hoping to learn more about in the upcoming lecture/demo?*

- Redux, React, MaterialUI.

*What are you most excited about trying to implement or see how it works?*

- Redux.

*Bookmark*

- [Multiple Reducers Example](https://www.youtube.com/watch?v=gBER4Or86hE)
- [Redux Docs: Using Combined Reducers](https://redux.js.org/recipes/structuring-reducers/using-combinereducers/)
- [Redux Docs: Combined Reducer Syntax](https://redux.js.org/api/combinereducers/)
