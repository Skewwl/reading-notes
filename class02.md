# Class 02

## React lifecycle

- Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

Render!

- What is the very first thing to happen in the lifecycle of React?

The use of a constructor.

- Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

Constructor, render, componentDidMount, React Updates, componentWillUnmount.

- What does componentDidMount do?

 Invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. Also, setState() can be called here, but it should be used sparingly, because it will cause a rerender, which can lead to perfomance issues.


## React State Vs Props

- What types of things can you pass in the props?

You can pass any JavaScript value through them, including objects, arrays, and functions.

- What is the big difference between props and state?

While both hold information that influences the output of render, they are different in one important way: props get passed to the component (similar to function parameters) whereas state is managed within the component.

- When do we re-render our application?

React components automatically re-render whenever there is a change in their state or props. A simple update of the state, from anywhere in the code, causes all the user interface elements to be re-rendered automatically.

- What are some examples of things that we could store in state?

JavaScript values / objects.
