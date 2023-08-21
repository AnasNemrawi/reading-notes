# 'useState()' Hook

## Thinking in React

1. Summarize the five steps of thinking in react.

> 1.Component Hierarchy: Break down the UI into components and subcomponents, considering design and data model.

> 2.Static Version: Build a non-interactive version of the app using reusable components and props.

> 3.Minimal State: Identify the essential changing data (state) needed for interactivity.

> 4.State Placement: Determine which component should hold and manage the identified state.

> 5.Data Flow: Enable data flow between components for user interaction, updating state through event handlers.


## State: A Component’s Memory

1.What is one reason a local variable isn’t sufficient for managing a React component?
- Local variables don't persist or trigger re-renders in React.

2.What is the argument to the useState hook, and what are the two parts of its return array?
- the initial state value. and a function.

3.How can Component A access state from Component B?

- Components can't directly access each other's state but state could be shared using props



