# 401 class_26

## React Quick Start

- What are the building blocks of a React app?

Components.

- What is the difference between an HTML element and a React component?

An html element is a piece of a webpage but it can only ever be the size of itself, the solitary element. In React a component can be made up of multiple elements if the developer decides.

- What is JSX and why do we use it?

JSX is essentially HTML inside of a js file. Which can live inside of the components return statement.

- Describe the process of embedding JavaScript expressions in JSX.

To add js logic into the JSX portion of your component you need to wrap the JSX in curly braces.

- Does React or JSX have any special features for iteration or conditional logic?

No.

- How does React know to respond to a user’s inputs?

By adding event handler functions inside of the opening JSX tag, like so:

return (
    <button onClick={handleClick}>
      Click me
    </button>
  );

- What word indicates that a React component manages data with a Hook?

Use. 

- How can two react components share data?

By passing a variable down via component attributes.

## Render and Commit

- What are the three steps of refreshing a React UI?

Trigger the app, render the JSX, and commit to the DOM.

- How do you trigger updates to a component after the initial render?

Updating state.

- Does React recreate DOM nodes on every rerender?

No.

- After React has updated the DOM, what still needs to happen before the user sees the change?

Rerendering of new nodes.
