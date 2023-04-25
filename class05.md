# Class 05

## React Docs - Thinking in React

- What is the single responsibility principle and how does it apply to components?

A component should only do one thing. If it ends up growing it should be subdivided.

- What does it mean to build a ‘static’ version of your application?

Build a version of the app that doesn't have any interactivity. 

- Once you have a static application, what do you need to add?

Identify where state should live and add it so that the app can be dynamic.

- What are the three questions you can ask to determine if something is state?

1. Does it remain unchanged over time? If so, it isn’t state.
2. Is it passed in from a parent via props? If so, it isn’t state.
3. Can you compute it based on existing state or props in your component? If so, it definitely isn’t state!

- How can you identify where state needs to live?

Often, you can put the state directly into their common parent.

## Higher-Order Functions

- What is a “higher-order function”?

Functions that operate on other functions, either by taking them as arguments or by returning them.

- Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

Line 2 is returning a boolean value. It creates an arrow function that takes a parameter and compares it to the parameter from the higher order function.

- Explain how either map or reduce operates, with regards to higher-order functions.

The map method transforms an object by applying a function to all of its elements and building a new array from the returned values. 
