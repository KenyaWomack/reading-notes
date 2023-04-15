# In memory storage

## What is a ‘call’?

he act of invoking or executing a function or method

## How many ‘calls’ can happen at once?

multiple function calls can happen concurrently, either through the use of multiple threads, asynchronous programming techniques, or event-driven architectures.

## What does LIFO mean?

Last-In, First-Out

## Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

function main() {
  console.log("Starting main...");
  doSomething();
  console.log("Finished main.");
}

function doSomething() {
  console.log("Starting doSomething...");
  doAnotherThing();
  console.log("Finished doSomething.");
}

function doAnotherThing() {
  console.log("Starting doAnotherThing...");
  console.log("Finished doAnotherThing.");
}

main();

## What causes a Stack Overflow?

when the call stack of a program or process exceeds its allocated size

## What is a ‘reference error’?

occurs in JavaScript when a program tries to access a variable or function that does not exist or has not been defined.

## What is a ‘syntax error’?

when the syntax of a statement or expression is incorrect or invalid

## What is a ‘range error’?

type of error that occurs in programming when a program tries to manipulate a value that is outside the range of acceptable values for a particular operation or data type.

## What is a ‘type error’?

occurs in programming when a program tries to perform an operation on a value of an incorrect data type.

## What is a breakpoint?

 tool used in software development to pause the execution of a program at a specific point in the code, allowing developers to inspect the state of the program and debug any issues

 ## What does the word ‘debugger’ do in your code?

 a tool that developers use to test and debug code.
 