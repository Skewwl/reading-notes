# class_37

## Multiple Reducers Example

Why create multiple reducers?

- For modularity and organization: Multiple reducers allow for a more organized codebase. Each reducer can handle a specific slice of the application's state. This modular approach makes it easier to manage the code and reduces complexity.
- For parallel development: When working in a team, different developers can work on different reducers without interfering with each other's code. This separation allows for parallel development and easier code integration.

How would you combine multiple reducers?

- Import combineReducers and then call combineReducer with and arguement that is an object where each key has a value that is a unique reducer. Resulting in each property of the object being a reducer we can call.

How will you manage state as an immutable object? why?

- Use pure functions: Reducers in Redux should be pure functions that return new state objects instead of mutating the existing state.

## Redux Docs: Using Combined Reducers

combineReducers is a utility function to simplify the most common use case when writing ___ _____ .

- Redux reducers

Explain how combineReducers assembles the new state tree.

- When an action is dispatched, the root reducer calls each individual reducer with the current state and the action. Each reducer independently processes the slice of the state it's responsible for and returns an updated state. combineReducers then merges these individual state updates into a single new state tree, where each slice corresponds to the specific state updated by its respective reducer.

How would you define initial state in an app using combineReducers?

- When using combineReducers, each individual reducer can define its own initial state. The state defined in each reducer represents the initial state for the corresponding slice of the overall state tree.

## Redux Docs: Combined Reducer Syntax

Why will you want to split your reducing functions as your app becomes more complex?

- As an application grows in complexity, the state management logic can become intricate and challenging to maintain within a single reducing function.

The _____ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to ____.

- combineReducers

What is a popular convention when naming reducers?

- Adding 'Reducer' to the end of the reducer function, like cartReducer.
