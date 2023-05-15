# Class 10

## Understanding the JavaScript Call Stack

- What is a ‘call’?

The invocation of a function.

- How many ‘calls’ can happen at once?

One.

- What does LIFO mean?

Last in first out.

- Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

A call stack would look like a a bunch of boxes stacked on top of eachother. The parameters would be pushed in first and then the function followed by any callbacks it may hold.

- What causes a Stack Overflow?

A function that calls instelf over and over again until the stack decides it doesn't want to play anymore.

## JavaScript error messages

- What is a ‘reference error’?

When you try to use a variable that is not yet declared.

- What is a ‘syntax error’?

This occurs when you have something that cannot be parsed in terms of syntax.

- What is a ‘range error’?

Incorrect manipulation of a ranged variable like an array or object.

- What is a ‘type error’?

This types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

- What is a breakpoint?

A point here your code will run up to in order to so you can verify if everything is working correctly up to that point.

- What does the word ‘debugger’ do in your code?

