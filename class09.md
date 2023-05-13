# Class 09

## Functional Programming Concepts

- What is functional programming?

Functional programming is a programming approach that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.

- What is a pure function and how do we know if something is a pure function?

A pure function returns the same result if given the same arguments. We will know if it doesn't use any global variables.

- What are the benefits of a pure function?

It won't return any side effects and it is easier to test.

- What is immutability?

When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.

- What is Referential transparency?

If a function consistently yields the same result for the same input, it is referentially transparent. Pure functions + immutable data = referential transparency.

## Node JS Tutorial for Beginners #6 - Modules and require()

- What is a module?

A file that holds logical code to keep other files clean.

- What does the word ‘require’ do?

It brings in other functionality that we stored in a module (or brought in from elsewhere) and allows us to store that functionality in a variable.

- How do we bring another module into the file the we are working in?

var bananas = require('./moduleFile')

- What do we have to do to make a module available?

module.exports = bananas

## what I want to know more about

When we call module.exports can we export multiple things? 
Like: module.exports = counter, bananas;
If so, when we assign it to a variable in app.js or wherever, would we deconstruct it? 
Like: var countBananas = require('./countBananas') 
Then: let {counter, bananas} = countBananas
We probably shouldn't do this anyways but, ya know, if we lived by that mantra we definitely wouldn't have any firebreathers.
