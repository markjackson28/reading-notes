# Redux - Asynchronous Actions

[Home](https://markjackson28.github.io/reading-notes/)

## Summary/Notes of readings

*How granular should your reducers be?*

- As much as you want. It depends on what you want it to do.

*Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched.*

- Con because you want single responsibility for actions.

*Name a strategy for preventing the above*

- Have better names actions.

*Terms*

Store: holds the whole state tree of your application. The only way to change the state inside it is to dispatch an action on it. [Ref].(https://redux.js.org/api/store)

Combined Reducers: a helper function that combines multiple reducers for use into the store. [Ref.](https://redux.js.org/api/combinereducers)

*Which 3 things had you heard about previously and now have better clarity on?*

- Redux.

*Which 3 things are you hoping to learn more about in the upcoming lecture/demo?*

- Redux, React, MaterialUI.

*What are you most excited about trying to implement or see how it works?*

- Redux.

*Preparation Materials*

- [async actions](https://redux.js.org/advanced/asyncactions)
- [thunk middleware](https://github.com/reduxjs/redux-thunk)
- [redux thunk](https://alligator.io/redux/redux-thunk/)
