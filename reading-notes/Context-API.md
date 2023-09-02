# Context API

## Choosing the State Structure
### Summarize the five principles for structuring state.

1. Group Related State: When managing state, group related pieces of state together. If multiple state variables always change together, consider merging them into a single state variable. This helps in keeping the state organized and ensures that related data stays in sync.

2. Avoid Contradictions in State: Structure your state in a way that prevents contradictory or "impossible" states. Avoid scenarios where multiple pieces of state may contradict or disagree with each other. This simplifies the logic and reduces the chances of errors.

3. Avoid Redundant State: If you can compute certain information from existing state variables or props during rendering, do not duplicate that information in the component's state. Instead, calculate it on-demand to keep the state minimal and prevent redundancy.

4. Avoid Duplication in State: When the same data is duplicated between multiple state variables or within nested objects, it becomes challenging to maintain consistency. Minimize duplication by sharing data when possible to ensure that all copies remain synchronized.

5. Avoid Deeply Nested State: Deeply hierarchical state can be difficult to update and manage. Prefer to structure your state in a flat manner whenever possible to simplify updates and reduce complexity.


## Passing State Deeply with Context

1. What problem do Contexts aim to solve?

> the problem of "prop drilling" which happens when you need to pass data from a parent component to a deeply nested child component. Context allows you to provide data to components in the entire tree below a parent component without explicitly passing it through props, making it convenient to access data at different levels of nesting.

2. What is one technique to try before useContext?

> passing props explicitly to maintain clear data flow.

3. What hook complements useContext for complex applications?

> 'useReducer' complements 'useContext' for handling complex state management in combination with context in more intricate applications.
