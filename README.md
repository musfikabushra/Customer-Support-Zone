1. What is JSX, and why is it used?

JSX (JavaScript XML) is a syntax extension for JavaScript used with React. It allows developers to write HTML-like code inside JavaScript, making UI structure easier to describe and read.

2. What is the difference between State and Props?

Props: Data passed from a parent to a child component, immutable.

State: Component’s internal, mutable data that updates the UI when changed.

3. What is the useState hook, and how does it work?

useState is a React hook for managing local state in functional components.

Returns: [state, setState] → current state and updater function.

Calling setState updates the state and triggers a re-render of the component.

4. How can you share state between components in React?

Ways to share state:

Props: Share between parent and child.

Lift state up: Share between sibling components via their common parent.

Context API: Share state deeply without prop drilling.

State libraries: Redux, Zustand, Recoil, etc., for complex/global state.

5. How is event handling done in React?

Key points for React event handling:

Use CamelCase event names, e.g., onClick, not onclick.

Pass a function, not a string, e.g., {handleClick} not "handleClick()".

React uses synthetic events, which are wrappers around native events for cross-browser consistency.
