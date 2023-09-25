# 401 class_27

## Thinking in React

Summarize the five steps of thinking in react.

- Break the UI into a component hierarchy
- Build a static version in React
- Find the minimal but complete representation of UI state
- Identify where your state should live
- Add inverse data flow

## State: A Component’s Memory

What is one reason a local variable isn’t sufficient for managing a React component?

- Changes to local variables won’t trigger renders.

What is the argument to the useState hook, and what are the two parts of its return array?

- The arguenment is the starting value for the state variable. The first value is the set variable and the second value is the method to re-set the variable.

How can Component A access state from Component B?

- It cannot it's state is independent.
