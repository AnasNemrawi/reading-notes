# Component Based UI (React)

## React Quick Start

[React Quick Start](https://react.dev/learn).

1. What are the building blocks of a React app?

- they are components, Components are self-contained, reusable pieces of UI that have their own logic and appearance.

2. What is the difference between an HTML element and a React component?

- HTML elements are native browser elements, while React components are reusable UI pieces built with JavaScript that encapsulate logic and UI elements.

3. What is JSX and why do we use it?

- JSX is a syntax extension for JavaScript that allows you to write HTML-like code within JavaScript. It's used in React to define the structure and appearance of components in a more intuitive way.

4. Describe the process of embedding JavaScript expressions in JSX.

- wrap them in curly braces, like {expression}. This allows you to inject dynamic values into your JSX markup.

5. Does React or JSX have any special features for iteration or conditional logic?

- React provides techniques for iteration and conditional logic. You can use JavaScript features like loops and map functions for iteration, and regular JavaScript if statements or the ternary operator for conditional rendering.

6. How does React know to respond to a user’s inputs?

- through event handlers. You can attach event handlers to JSX elements using attributes like onClick, onChange, etc.

7. What word indicates that a React component manages data with a Hook?

- "use"

8. How can two react components share data?

- by lifting state up. This involves moving the shared state and logic to a common ancestor component and passing the data down as props to the child components.


## Render and Commit

[Render and Commit](https://react.dev/learn/render-and-commit).

1. What are the three steps of refreshing a React UI?

- Trigger, Render, Commit.

2. How do you trigger updates to a component after the initial render?

- by changing a component's state using 'setState'

3. Does React recreate DOM nodes on every rerender?

- No, React minimizes changes by updating only what's necessary.

4. After React has updated the DOM, what still needs to happen before the user sees the change?

- After updating the DOM, the browser paints the changes for the user to see.











