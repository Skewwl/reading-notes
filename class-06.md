# class-06.md

### JavaScript Object Basics

- How would you describe an object to a non-technical friend you grew up with?

An object is like a variable that can hold multiple multiple multiple values of different types. For example you can store a boolean and a number and a function all inside of one object.

- What are some advantages to creating object literals?

You might use an object literal when you want to transfer a series of structured, related data items in some manner, or when you want to address data by name.

- How do objects differ from arrays?

With objects you get to use the name associated with the data and with arrays you use an index number that stores the data.

- Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

If an object property name is held in a variable, then you can't use dot notation to access the value, so you would use bracket notation.

Evaluate the code below. What does the term this refer to and what is the advantage to using this?
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}

Console: Spot is 14 in human years
The 'this' keyword refers to the current object the code is being written inside. 'This' enables you to use the same method definition for every object you create.


###Introduction To The DOM

- What is the DOM?

The DOM is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content.

- Briefly describe the relationship between the DOM and JavaScript.

The DOM is not part of the JavaScript language, but is instead a Web API used to build websites. JavaScript can also be used in other contexts.

