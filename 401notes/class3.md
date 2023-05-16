Express REST API

## Classes are a template for creating 

 objects in object-oriented programming

## Can a class declaration be hoisted?

 class declarations are not hoisted

## How would you describe a constructor and contextual “this” to a non-technical friend?

 A constructor is a special method that is used to create and initialize objects based on a blueprint called a class. In JavaScript, "this" is a special keyword that refers to the current object being accessed or used within a function or method. It allows us to refer to the object's own properties and methods.

## Within Express, what does routing refer to?

 the process of determining how an incoming HTTP request should be handled based on the requested URL path and HTTP method. It involves defining the endpoints or routes of an application and specifying the corresponding actions or middleware functions to be executed when a specific route is matched.

## What is the difference between a route path and a route method?

  The route path defines the URL pattern that a specific route should match.  The route method, also known as the HTTP method or verb, represents the type of operation that the client wants to perform on a resource.

## When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?

   It is typically used when you want to execute multiple middleware functions sequentially or when you want to pass control to the next route handler.it is essential to call next() at the appropriate time to pass control to the next middleware or route handler. Failing to call next() will result in the request-response cycle being stuck, and subsequent middleware or route handlers will not be executed.

## What is an Express Router?

a feature provided by the Express.js framework that allows you to create modular, mountable sets of routes. It provides a way to organize and separate different parts of your application's routes into reusable components.

## By what mean do we initialize express.Router() in an express server?

create an instance of the router using the express.Router() method

## What do we use route middleware for?

 used to perform operations on the request and response objects in the middle of the request-response cycle for a specific route. It allows you to add additional functionality or logic to your routes, such as authentication, data validation, logging, error handling, and more.

 ## What are your learning goals after reading and reviewing the class README?

I want to understand routing more.
