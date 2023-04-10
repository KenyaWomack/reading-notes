# Passing Functions as Props

## What does .map() return?

The map() method in JavaScript creates a new array by calling a provided function on each element in the original array.

## If I want to loop through an array and display each value in JSX, how do I do that in React?

to loop through an array and display each value in JSX, you can use the map() method in conjunction with JSX. 

## Each list item needs a unique ____

key prop

## What is the purpose of a key?

key prop helps React identify each element in the virtual DOM, and improve performance when updating and rendering the component.

## What is the spread operator?

represented by three consecutive dots (...) and is used to spread or expand the elements of an iterable object (like an array or an object) into a new array or object.

## List 4 things that the spread operator can do.

Create a new array with elements from an existing array, Copy an existing array into a new array, Merge multiple objects into a new object, and then Pass an array or object as arguments to a function

## Give an example of using the spread operator to combine two arrays.

const array1 = [1, 2, 3];
const array2 = [4, 5, 6];
const combinedArray = [...array1, ...array2];
console.log(combinedArray); // [1, 2, 3, 4, 5, 6]

## Give an example of using the spread operator to add a new item to an array.

const originalArray = [1, 2, 3];
const newItem = 4;
const newArray = [...originalArray, newItem];
console.log(newArray); // [1, 2, 3, 4]

## Give an example of using the spread operator to combine two objects into one

const object1 = { foo: 'bar', baz: 42 };
const object2 = { qux: true, quux: 'hello' };
const combinedObject = { ...object1, ...object2 };
console.log(combinedObject); // { foo: 'bar', baz: 42, qux: true, quux: 'hello' }

## In the video, what is the first step that the developer does to pass functions between components?

create the function wherever the state is that we are going to change

## In your own words, what does the increment function do?

takes the current value of a "count" state variable, increments it by 1, and then sets the new value as the new state of the component.

## How can you pass a method from a parent component into a child component?

defining the method in the parent component and passing it to the child component as a prop.

## How does the child component invoke a method that was passed to it from a parent component?

the child component can call the method as a function.
