# Class 04

## React Docs - Forms

- What is a ‘Controlled Component’?

An input form element whose value is controlled by React.

- Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

As soon as the user enters the data into the form. Because a JavaScript event handler function that updates the submission of the form data to state will update as the user types in the input area.

- How do we target what the user is entering if we have an event handler on an input field?

event.target.value

## The Conditional (Ternary) Operator Explained

- Why would we use a ternary operator?

In place of simple if statements or inside of JSX where if statements cannot live.

- Rewrite the following statement using a ternary statement:

if(x===y){
  console.log(true);
} else {
  console.log(false);
}

x === y ? console.log(true) : console.log(false)
