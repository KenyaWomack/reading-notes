# Redux - Additional Topics

## What concerns are addressed by Redux Toolkit?

 Redux Toolkit simplifies the process of setting up a Redux store by providing a set of utility functions and a standardized way of writing Redux code. Redux Toolkit uses the Immer library under the hood, which allows you to write "mutating" code that produces immutable updates to the state. Redux Toolkit provides a configureStore() function that simplifies the configuration of a Redux store. It automatically sets up sensible defaults, such as enabling Redux DevTools Extension, applying middleware (including Redux Thunk), and enabling additional Redux Toolkit features.

## What does configureStore() do?

  It creates an instance of the Redux store using the provided reducer or a combination of reducers.It automatically applies middleware to the store. By default, it includes Redux Thunk middleware, which allows for asynchronous actions. It enables integration with Redux DevTools Extension, which provides advanced debugging and time-traveling capabilities for Redux state.

## How would I use createSlice()?

  automatically generates the action types based on the slice name and action names, and also handles the immutability of state updates using the immer library, which makes it easier and more concise to define reducers in Redux Toolkit

## What is Mobx?

   a state management library for JavaScript and TypeScript applications. It provides a simple and reactive way to manage the state of your application and keep it in sync with your user interface. Mobx is often used in frontend frameworks like React, Angular, and Vue.js.

## How does MobX make it “impossible” to produce an inconsistent state?

   enforcing strict rules and patterns in how the state is managed and updated

## How would we build a reactive user interface?

   Identify the parts of your application state that need to be reactive. Establish a connection between the observables and the user interface elements that depend on them. Define the reactions or side effects that should occur when the observable state changes.Capture user interactions, such as button clicks, form submissions, or mouse movements, and update the observable state accordingly.

## What take-away(s) did this tutorial provide?

great quick start references, shows how to use redux the correct way, in-depth description of the building process for Redux

## What are your learning goals after reading and reviewing the class README?

learn more about Mobx
