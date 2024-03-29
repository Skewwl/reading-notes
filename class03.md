# Class 03

## React Docs - lists and keys

- What does .map() return?

A new array with each element being the result of the callback function.

- If I want to loop through an array and display each value in JSX, how do I do that in React?

Use the .map() operator to return a new array but with each element in the array encompassed by <li> nodes. Then return the variable assigned to the new array in curly braces inside of a <ul> node.

- Each list item needs a unique ____.

Key.

- What is the purpose of a key?

JSX elements directly inside a map() call always need keys. A key helps React infer what exactly has happened, and make the correct updates to the DOM tree.

## The Spread Operator

- What is the spread operator?

It is three periods that copies the data from an iterable object.

- List 4 things that the spread operator can do.

  1. Include existing data as a part of the new object you’re creating.
  2. Combine multiple arrays.
  3. Add a new item to an array.
  4. Combine objects.


- Give an example of using the spread operator to combine two arrays.

const arr3 = [...arr1, ...arr2]

- Give an example of using the spread operator to add a new item to an array.

arr1 = [...arr1, item1]

- Give an example of using the spread operator to combine two objects into one.

const obj3 = {...obj1, ...obj2}
  
## How to Pass Functions Between Components

- In the video, what is the first step that the developer does to pass functions between components?

The first thing that the developer does is creates a JSX attribute with a name and assigns it to {this.functionName} to reference the method that exists on the component.

- In your own words, what does the increment function do?

It takes in a person, loops through the state’s ‘people’ array using the map function, finds matching name on an object, increments the count in the matching object, creates a new array with the updated count, then uses setState to the new array with the updated count.

- How can you pass a method from a parent component into a child component?

You can pass a method down from a parent component into a child component by creating a JSX element attribute and assigning it to the object prototype method

- How does the child component invoke a method that was passed to it from a parent component?

By calling the method through props inside of its own prototype method. This will pass the change back up, then back down.
