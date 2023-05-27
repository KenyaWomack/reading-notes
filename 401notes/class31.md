# Context API

## Summarize the five principles for structuring state

Single Source of Truth: Maintain a single, centralized source of truth for the application's state. This means storing the state in a single location (such as a top-level component or a state management library) and passing it down to child components as needed.

State is Read-Only: State should not be modified directly. Instead, it should be updated through well-defined actions or events. This ensures that state changes are predictable and can be tracked.

Changes are Made with Pure Functions: State changes should be made using pure functions called reducers. Reducers take the current state and an action as input and return a new state. This helps in keeping the state changes predictable and testable.

State Updates are Predictable: State updates should follow a predictable pattern. Given the same input, the state should always produce the same output. This helps in debugging and understanding how the state changes over time.

Derive State as Needed: Rather than duplicating or storing derived data, it is recommended to derive state as needed from the existing state. This reduces redundancy and ensures that the derived data stays in sync with the source of truth.

## What problem do Contexts aim to solve?

prop drilling in React applications. Prop drilling refers to the process of passing props through multiple intermediate components to reach a deeply nested component that needs access to those props. This can become cumbersome and lead to code that is harder to maintain and understand.

## What is one technique to try before useContext?

use prop drilling with component composition. Prop drilling involves passing down props from a parent component to its child components, and further down to their child components if needed.

## What hook complements useContext for complex applications?

 useReducer. 
