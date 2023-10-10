# class_31

## Choosing the State Structure

Summarize the five principles for structuring state.

- Group related state. If you always update two or more state variables at the same time, consider merging them into a single state variable.
- Avoid contradictions in state. When the state is structured in a way that several pieces of state may contradict and “disagree” with each other, you leave room for mistakes. Try to avoid this.
- Avoid redundant state. If you can calculate some information from the component’s props or its existing state variables during rendering, you should not put that information into that component’s state.
- Avoid duplication in state. When the same data is duplicated between multiple state variables, or within nested objects, it is difficult to keep them in sync. Reduce duplication when you can.
- Avoid deeply nested state. Deeply hierarchical state is not very convenient to update. When possible, prefer to structure state in a flat way.

## Passing State Deeply with Context

What problem do Contexts aim to solve?

- Contexts aim to solve the repetative passing of state to many components.

What is one technique to try before useContext?

You could try passing down sate through props until it becomes to verbose of an action.

What hook complements useContext for complex applications?

useReducer! You can combine reducers and context together to manage state of a complex screen.
