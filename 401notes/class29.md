# Advanced State with Reducers

## What is the motivation for adding a reducer?

The motivation for adding a reducer to a React component is to handle complex state management and logic in a more organized and scalable way. While simple state management can often be handled by the useState hook, as an application grows in complexity, managing state with just useState can become cumbersome and harder to maintain.

## What are actions in the context of a reducer? How are they different than setting state directly?

 actions are objects that describe a type of state change or an event that occurred in the application. setting state directly in a component bypasses the structured approach provided by actions and reducers.

## What common list operation is useReduce named for, and why?

The useReduce hook in React is named after the common list operation called "reduce" or "fold." The reduce operation is used to iterate over a list or array and accumulate its values into a single value. It takes a callback function and an initial value, and then applies the callback function to each element of the list, combining them into a single result.

## When should you switch from useState to useReducer?

Complex state transitions, Shared state and actions, Large state objects, Middleware or side effects

## What are your learning goals after reading and reviewing the class README?

learning more about reducers
