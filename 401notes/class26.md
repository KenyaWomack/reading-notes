#  Component Based UI

## What are the building blocks of a React app?

Components, JSX is a syntax extension used in React to write HTML-like code within JavaScript. State represents the data that can change over time in a React component. Props are used to pass data from a parent component to its child components.

## What is the difference between an HTML element and a React component?

In traditional web development using HTML, an HTML element represents a specific tag or element in the HTML markup, such as <div>, <p>, <h1>, etc.
HTML elements are predefined and provided by the HTML language itself. They define the structure and content of a web page.
HTML elements are static and declarative. They are primarily used for describing the structure and presentation of the UI.
HTML elements are primarily concerned with how the content is displayed and interacted with in the browser.

In React, a component is a reusable, self-contained piece of UI that encapsulates its own logic, structure, and rendering. It can be created using either function syntax (functional components) or class syntax (class components).
React components are built using JavaScript and JSX (JavaScript XML), which allows you to write HTML-like code within JavaScript.
React components are dynamic and interactive. They can have their own state, handle user interactions, and respond to changes in data.
React components are reusable and composable. They can be combined to build complex UI structures and can be easily reused throughout the application.
React components are focused on the logic and behavior of the UI, allowing for more dynamic and interactive user experiences.

## What is JSX and why do we use it?

JSX (JavaScript XML) is an extension to the JavaScript language syntax used in React applications. It allows you to write HTML-like code within JavaScript, making it easier to define and render React components.

## Describe the process of embedding JavaScript expressions in JSX.

In JSX, you can embed JavaScript expressions by using curly braces {}. This allows you to dynamically generate content, perform calculations, access variables, and execute functions within the JSX code.

## Does React or JSX have any special features for iteration or conditional logic?

React allows you to conditionally render elements based on conditions using different techniques

## How does React know to respond to a user’s inputs?

React knows to respond to a user's inputs through a mechanism called event handling. In React, you can attach event handlers to specific elements or components, which listen for user interactions such as clicks, key presses, form submissions, and more. When an event is triggered, React captures it and invokes the corresponding event handler function.

## What word indicates that a React component manages data with a Hook? 

"useState"

## How can two react components share data?


Two React components can share data by lifting the state up to a common parent component. This means that the data is stored in the parent component's state, and it is passed down to the child components as props. The child components can then access and modify the data through the props received from the parent. When the data is updated in the parent component, the changes propagate down to the child components, allowing them to reflect the updated data.

## What are the three steps of refreshing a React UI?

State Update: Modify the state of a component using setState() or useState() hook to trigger a re-render of the component.
Virtual DOM Reconciliation: React reconciles the changes made to the component's state by comparing the new Virtual DOM representation with the previous one.
Rendering: React updates the actual DOM by applying the necessary changes determined during the reconciliation process.

## How do you trigger updates to a component after the initial render?

Using State and setState(): If the component has internal state, you can update the state using the setState() method provided by React. This triggers a re-render of the component, reflecting the updated state.

## Does React recreate DOM nodes on every rerender?

No, React does not recreate DOM nodes on every rerender. React uses a virtual DOM (VDOM) to efficiently update the actual DOM

## After React has updated the DOM, what still needs to happen before the user sees the change?

 the browser needs to perform the painting or rendering of the updated DOM.

 ## Note the naming conventions in the Airbnb React/JSX Style Guide. What pattern(s) do you see?

 File names: JavaScript and JSX files are typically named using PascalCase, starting with a capital letter, and using descriptive names. For example, MyComponent.js or Header.jsx.

Component names: React component names are also written in PascalCase. This helps to differentiate components from regular HTML elements. For example, class MyComponent extends React.Component.

Props: Props passed to components are typically written in camelCase. This includes both attribute names in JSX and the corresponding variables in the component code. For example, <MyComponent myProp={value} />.

Event handlers: Event handler props are named using the on prefix followed by the event name in camelCase. For example, onClick, onSubmit, onChange.

Internal variables and functions: Internal variables and functions within components are named using camelCase. They often start with a verb or describe their purpose. For example, handleSubmit, isLoading, renderContent.

## Looking ahead at this module’s course schedule, What do you look forward to learning?

state hooks

## What are your learning goals after reading and reviewing the class README?

getting better with react
