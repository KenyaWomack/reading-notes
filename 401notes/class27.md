# Hook

## Summarize the five steps of thinking in react.

Break the UI into a component hierarchy: Start by breaking down the user interface (UI) into smaller, reusable components. Identify the different parts of the UI and determine which components can be created to represent those parts.

Build a static version of the UI: Create a static version of the UI without any interactivity. This involves rendering the components with hard-coded data and focusing on the structure and layout of the UI.

Identify the minimal, but complete, representation of UI state: Determine the minimal set of mutable state that the UI needs to handle. Identify the data that should be stored and updated within the components to reflect the user interactions and changes in the UI.

Determine where the state should live: Decide which component(s) should own and manage the state. This involves finding a common parent component for the components that need access to the shared state. The state should be lifted up to the nearest common ancestor component that needs to modify or pass down the data.

Add inverse data flow: Establish the data flow and interactions between components by adding the necessary event handlers and callbacks. Enable the components to update the state and propagate the changes to the relevant components. This allows for interactivity and dynamic updates in the UI.

## What is one reason a local variable isn’t sufficient for managing a React component?

local variables are scoped within a specific function or block and are not persistent across renders. React components are designed to be reusable and maintain their state across renders. They need to preserve their data and state even when the component is unmounted and re-rendered.

## What is the argument to the useState hook, and what are the two parts of its return array?

 the initial value of the state. It defines the initial state of the component. The first element of the array is the current state value. The second element of the array is a function that allows you to update the state.

## How can Component A access state from Component B?

  lift the state up to a common parent component and pass it down as props to the child components

## What are your learning goals after reading and reviewing the class README?

Describe the lifecycle of a React component
