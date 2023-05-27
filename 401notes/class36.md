# Application State with Redux

## What is the first principle of Redux?

The first principle of Redux is the "Single Source of Truth." It refers to the idea that the entire state of your application is stored in a single JavaScript object called the "store." In other words, the state of your application is centralized and kept in one place.

## what is a store and what do we use our reducers for within that store?

a store is an object that holds the entire state of your application. It is responsible for managing the state and providing methods to access and update it. The store is created using the createStore function from the Redux library.

The store in Redux acts as a container for the state, and it is the single source of truth for your application's data. It holds the current state of your application and provides methods to dispatch actions and handle state updates.

## Name three Redux store methods given to us by createStore and describe their use.

getState(): This method is used to retrieve the current state of the Redux store. It returns the current state object that represents the entire state tree of your application. You can use this method to access and read the state from any part of your application. For example, you can call store.getState() to retrieve the current state and display it in a component.

dispatch(action): This method is used to dispatch an action to the Redux store. It accepts an action object as an argument and triggers the state update process. When you call store.dispatch(action), the store invokes the corresponding reducer function, passing the current state and the action. The reducer then returns a new state based on the action, and the store updates its state accordingly. This method is used to initiate state changes in your application.

subscribe(listener): This method allows you to register a listener function that will be called whenever the state in the Redux store changes. The listener is invoked every time an action is dispatched and the state is updated. You can use this method to subscribe to store updates and respond to state changes in your application.

## Explain to a non-technical recruiter what combineReducers() does and why it is useful.

combineReducers() is a utility function provided by Redux that allows you to combine multiple reducer functions into a single reducer. In Redux, reducers are responsible for specifying how the state should be updated in response to actions. They take the current state and an action as input and return a new state.

## Looking ahead at this module’s course schedule, What do you look forward to learning?

getting better with react components

## What are your learning goals after reading and reviewing the class README?

The roles of Actions and Reducers
