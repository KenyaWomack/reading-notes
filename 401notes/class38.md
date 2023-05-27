# Redux - Asynchronous Actions

## Why use Redux middleware?

Handling asynchronous operations, Logging and debugging, Authentication and authorization

## Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.

the flow starts with a component dispatching an action, which is a plain JavaScript object describing the type of action and optional payload. The action is then passed to the Redux store.Next, the action flows through any applied middleware. Middleware functions can intercept the action, perform additional logic, and modify it if needed. After the middleware, the action reaches the reducers.Once the state is updated by the reducer, the changes are propagated to the connected components.

## How are we accommodating async in our Redux app

Redux provides a few popular middleware libraries like Redux Thunk, Redux Saga, and Redux Observable that help manage async operations.With Redux Thunk, action creators can return functions instead of plain action objects. These functions can then perform async operations, such as API requests, and dispatch further actions based on the async results.

## Why would you need redux-thunk middleware?

when you need to handle asynchronous operations, such as API requests, in your Redux app.  Redux Thunk allows you to dispatch functions as actions instead of plain objects.

## Redux Thunk middleware allows you to write action creators that return a ____ instead of an action.

function

## Describe how any return value from the inner thunk function will be made available.

When a thunk function is dispatched, Redux Thunk middleware intercepts it and invokes the function. The inner thunk function can have asynchronous logic, such as making API calls or performing other asynchronous operations. Once the asynchronous operations are complete, the inner thunk function can dispatch regular actions to update the Redux store.

## What are your learning goals after reading and reviewing the class README?

learning more about thunk
