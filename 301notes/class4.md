# React and Forms

## What is a ‘Controlled Component’?

derives its value from the state in the parent component and notifies the parent component of user actions through callbacks

## Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why

store the user's responses in the component state as soon as they enter them, rather than waiting for them to submit the form to get real time feedback and a better user experience

## How do we target what the user is entering if we have an event handler on an input field?

by accessing the value of the input element through the event object

## Why would we use a ternary operator?

a shorthand way of writing conditional statements in JavaScript.

## ewrite the following statement using a ternary statement:

if(x===y){
  console.log(true);
} else {
  console.log(false);
}

(x === y) ? console.log(true) : console.log(false);
