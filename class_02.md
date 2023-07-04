# 401 class_02

### An introduction to NodeJS and Express

Explain middleware, answer as though I were a non-technical recruiter.

- Middleware is an additional process we can tack on to an inbound server request.

Express is the most popular server side framework.

Express is “unopinionated.” What does that mean?

- Unopinionated means that the developer can approach the development and layout of their server from almost any angle and use many different related packages to reach their end goal.

What is a module and why is modularity useful to us as developers?

- A module is a certain functionality that is tucked away in another file and brought into the the server file via a variable. This is useful because it allows us a humans to keep our server free of clutter and easier to read.

### What is NPM?

What version of npm are you running on your machine?

- 9.7.1

What command would you type to install a library/package called ‘jshint’ into your node project?

- npm i jshint

### What is TDD?

Explain why tests are important. Please explain as though I were your non technical elder.

- Tests ensure that key aspects of the logic are performing.

What are three expected benefits of testing

- Many teams report significant reductions in defect rates, at the cost of a moderate increase in initial development effort.
- The same teams tend to report that these overheads are more than offset by a reduction in effort in projects’ final phases.
- TDD leads to improved design qualities in the code, and more generally a higher degree of “internal” or technical quality.

Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.

- Individual: 1. Writing too many tests at once. 2. Writing tests that are too large or coarse-grained. 3. Writing overly trivial tests.
- Team: 1. Partial adoption – only a few developers on the team use TDD. 2. Poor maintenance of the test suite.

### CI/CD

What are three benefits of Continuous Integration?

- Built into GitHub (source management app). Every integration to the code is validated by a test. The tests are automated.

What is the difference between Continuos Delivery and Continuous Deployment?

- Continuous delivery validates the code up to the point of being production ready. Continuous deployment is the creation of a testing framework which upon passing will automatically push your code out in production.

Explain how GitHub fits into this process assuming the listener comes from a non-technical background.

- GitHub is the place where Dev's store all of their code for collaboration. GitHub also has a testing functionality built into it that runs automatically when you try to merge new code to a certain place. 
