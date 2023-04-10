# State and Props

## ased off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

render

## What is the very first thing to happen in the lifecycle of React?

is its "mounting" 

## Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

constructor, render, componentDidMount, React Updates,componentDidUnmount

## What does componentDidMount do?

used to set up any initializations that require the component to be present in the DOM before they can be executed

## What types of things can you pass in the props?

strings, numbers, booleans, functions

## What is the big difference between props and state?

props are read-only and passed down from parent components, while state is owned and managed by the component itself.

## When do we re-render our application?

whenever there is a change in its props or state.

## What are some examples of things that we could store in state?

user input, data fetching, navigation