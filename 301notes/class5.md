# Putting it all Together

## What is the single responsibility principle and how does it apply to components?

single responsibility principle is a software development principle that states that a component or module should have one and only one reason to change. In the context of components, this means that a component should have a clear and well-defined purpose, and should only handle one specific set of tasks or functionalities. It helps to ensure that they are easy to understand, maintain, and reuse.

## What does it mean to build a ‘static’ version of your application?

creating the UI or user interface of your application without any interactivity or functionality

## Once you have a static application, what do you need to add?

need to add interactivity by implementing the necessary event handlers and state changes

## What are the three questions you can ask to determine if something is state?

Does it change over time?
Can it be computed from props or other state?
Does it need to be passed down from a parent component?

## How can you identify where state needs to live?

Identify every component that renders something based on that state.
Find a common owner component (a single component above all the components that need the state in the hierarchy).
Either the common owner or another component higher up in the hierarchy should own the state.
If you can't find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

## What is a “higher-order function”?

A higher-order function is a function that takes one or more functions as arguments or returns a function as its result. 

## Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

line 2 is defining and returning another function that takes a single argument, y.

## Explain how either map or reduce operates, with regards to higher-order functions.

map() is used to create a new array with the results of calling a function for every element in the original array and reduce() is used to reduce the elements in an array to a single value.