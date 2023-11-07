# class 39

## Redux Toolkit (RTK)

### What concerns are addressed by Redux Toolkit?

- Immutable Updates: It simplifies state updates by providing utility functions that produce new state objects when changes are made, avoiding direct mutation.
- Store Setup: It streamlines the store setup process by providing a function like configureStore to configure a store with default settings.
- Handling Immutable State: It simplifies the creation of reducers and actions that deal with immutable state updates.

### What does configureStore() do?

- configureStore() is a function provided by Redux Toolkit used to create a Redux store with sensible defaults and built-in middleware. It simplifies the process of setting up a store by providing sane default configurations and automatically adding commonly used middleware, such as Redux DevTools and Redux Thunk, among others.

### How would I use createSlice()?

createSlice() is a function provided by Redux Toolkit for defining a slice of the Redux state, including actions and reducers, all in a single place. It simplifies the creation of reducers and action creators by generating them based on the provided initial state and a set of reducer functions.

## MobX

### What is Mobx?

- MobX is a state management library that focuses on making state management simple and scalable by using reactive programming concepts. It is often used in frontend development, to manage state and keep the UI in sync with the state changes.

### How does MobX make it “impossible” to produce an inconsistent state?

- 1) Observables: These are state variables that MobX is aware of and automatically tracks changes to. When any observable variable changes, MobX automatically detects the change and propagates it to any code that depends on it. 2) Reactions: In MobX, reactions are the pieces of code that automatically run when the observed state changes. This could be updating the user interface, making network requests, or performing other actions. 3) Actions: Changes to the observed state should always happen within actions. An action in MobX is a piece of code that is allowed to modify the observable state. By making changes within actions, MobX ensures that observers and reactions are kept in sync, making it harder to produce inconsistent states.

By ensuring that changes to the state happen only through actions, MobX guarantees that the state changes are consistent and the observers react predictably to these changes.

### How would we build a reactive user interface?

- Define Observables.
- Create Reactions.
- Actions for State Changes: Ensure that any changes to the observed state happen within actions. This keeps the state changes consistent and ensures that the UI updates in response to those changes.
- Integrate with Components: Use useObserver hook (for React) to wrap your components. This will make your components reactively update when the observed state changes.
