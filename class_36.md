# class_36

## Dan Abramov Redux Tutorials

- What is the first principle of Redux?

All state is contained in a single object, the state tree.

- what is a store and what do we use our reducers for within that store?

A store is an object that we can pull our of our Redux package. We create our store based on a reducer like function we have already created. From here we can call store.dispatch to mutate our state.

- Name three Redux store methods given to us by createStore and describe their use.

1. getState which returns our current state.
2. dispatch which allows is to change our state.
3. subscribe which lets us create a callback that will run every time our dispatch function runs so that we can keep our ui to our current state.

- Explain to a non-technical recruiter what combineReducers() does and why it is useful.

combineReducers is a helper function in Redux that simplifies the process of managing these reducers. Its primary purpose is to take multiple reducers and combine them into a single, coherent state object. It's useful because it organizes all reducers to one place and still promotes modular development.
