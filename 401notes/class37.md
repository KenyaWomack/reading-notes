# Redux - Combined Reducers

## Why create multiple reducers?

allows you to manage different parts of your application's state separately. 

## How would you combine multiple reducers?

using the combineReducers() function provided by the Redux library. This function allows you to create a single root reducer that combines the functionality of multiple individual reducers. 

## How will you manage state as an immutable object? why?

Managing state as an immutable object means that once the state is set, it cannot be directly modified. Instead, any changes to the state result in the creation of a new state object. It helps in understanding and debugging the application's behavior. Immutable data structures can be more efficient in terms of memory usage and performance. Instead of making deep copies of the entire state object, immutable updates can create new objects by reusing the unchanged parts of the previous state.

## combineReducers is a utility function to simplify the most common use case when writing ___ _____ 

Redux reducers

## Explain how combineReducers assembles the new state tree.

The combineReducers function takes an object as its argument, where the keys represent different slices of the state, and the values are the corresponding reducer functions for those slices.

During the initialization of the Redux store, the combineReducers function is called to create a root reducer. This root reducer will be responsible for handling all actions and updating the state tree.

When an action is dispatched, the root reducer is invoked. It then delegates the action to each individual reducer specified in the combineReducers argument.

Each individual reducer receives the corresponding slice of the state and the action. The reducer examines the action type and decides how to update its specific slice of the state.

Each reducer returns the updated slice of the state. The combineReducers function collects all the updated slices and combines them into a new state tree.

The new state tree, consisting of all the updated slices, is returned by the root reducer and becomes the new overall state of the Redux store.

## How would you define initial state in an app using combineReducers?

In an app using combineReducers, the initial state for each slice of the state can be defined within the individual reducers. The combineReducers function itself does not directly handle the initial state. When defining a reducer, you can specify an initial state as the default value of the state parameter in the reducer function.

## Why will you want to split your reducing functions as your app becomes more complex?

As an app becomes more complex, splitting reducing functions becomes necessary to maintain a scalable and organized codebase.

## The _____ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to ____

combineReducers, the Redux createStore function

## What is a popular convention when naming reducers?

A popular convention when naming reducers in Redux is to use the domain or feature name followed by the word "Reducer". This convention helps to make the purpose and responsibility of the reducer clear and follows a consistent naming pattern across the application.

## What are your learning goals after reading and reviewing the class README?

to become more proficient using  reducers
