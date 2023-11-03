# class 38

## Reading: Async Actions

### Why use Redux middleware?

- Redux middleware extends the functionality of Redux by allowing developers to intercept actions before they reach the reducer. It provides a way to handle asynchronous actions, and modify actions before they reach the reducers.

### Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.

- The flow of asynchronous actions in Redux involves initiating an async action (e.g., an API request) using an action creator. The action creator, typically made with middleware like Redux Thunk, dispatches an action, but rather than a plain action object, it dispatches a function (thunk). This function receives the dispatch and getState arguments, allowing it to perform asynchronous operations. Within this function, you can perform API requests or other async tasks, dispatching regular synchronous actions with the fetched data when the asynchronous task completes.

### How are we accommodating async in our Redux app?

- Asynchronous actions in a Redux app are accommodated by using middleware like Redux Thunk. Redux Thunk allows action creators to return functions instead of plain action objects. These functions can contain asynchronous logic, like API calls, and dispatch further actions based on the received data or error responses.

## Reading: Thunk Middleware

### Why would you need redux-thunk middleware?

- Redux Thunk middleware is necessary to handle asynchronous actions in Redux. It allows action creators to return functions (thunks), enabling the dispatch of multiple actions, including asynchronous logic, API calls, and managing the flow of action dispatching.
Redux Thunk middleware allows you to write action creators that return a ____ instead of an action.

 ### Redux Thunk middleware allows you to write action creators that return a ___ instead of an action.

- function

### Describe how any return value from the inner thunk function will be made available.

The inner thunk function within Redux Thunk middleware can return a promise, which can then be accessed in the code using .then() if needed. The return value of the inner thunk function can be anything - a promise, a value, or undefined. If it's a promise, the resolved value of the promise will be available in the .then() function when the promise resolves.
