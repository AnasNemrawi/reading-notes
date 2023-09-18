# Redux - Asynchronous Actions

## async actions

[async actions](https://redux.js.org/tutorials/fundamentals/part-6-async-logic)

1. Why use Redux middleware?

> Redux reducers are meant to be pure functions that do not contain side effects, so middleware provides a way to handle such logic separately.

2. Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.

- Event/action triggers.

- Dispatch action.

- Middleware handles asynchronous logic.

- Middleware dispatches actions to update the store.

- Reducers process actions and update the state.

- Updated state is provided to React components.

3. How are we accommodating async in our Redux app?

> using Thunk functions allow to perform async tasks like API calls and dispatch actions when they complete. This helps manage async operations in Redux.

## thunk middleware

[thunk middleware](https://github.com/reduxjs/redux-thunk)

1. Why would you need redux-thunk middleware?

> to handle asynchronous actions and side effects in Redux application

2. Redux Thunk middleware allows you to write action creators that return a ____ instead of an action.

> return a function instead of an action. This function can perform asynchronous operations

3. Describe how any return value from the inner thunk function will be made available.

> Any return value from the inner function will be available as the return value of dispatch itself




