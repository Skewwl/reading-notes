# 401 class_03

## Review: ES6 Classes

- Classes are a template for creating objects.

- Is a class declaration hoisted?
No.
  
- How would you describe a constructor and contextual “this” to a non-technical friend?
A constructor is a schema or outline for an object that will be created in the future. We declare specific attributes of the object with the constructor by using the keyword 'this'. It is refering to the the created object, and saying, this object's attribute will be...

## Using Express Routing

- Within Express, what does routing refer to?
Routing refers to how an application’s endpoints respond to client requests.
  
- What is the difference between a route path and a route method?
The path is the string after the domain that defines the resource's endpoint. The method defines what the client is trying to do with the resource.
  
- When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?
You want to add next if you are creating an error handler or, more commonly, if you want to run through multiple functions when a request is recieved by a route. If next has been passed to your middleware as a parameter you must call next to pass control to the next middleware function.

## Express Routing

- What is an Express Router?
Express Routers are a way to organize your Express application such that your primary app. js file does not become bloated and difficult to reason.
  
- By what mean do we initialize express.Router() in an express server?
const router = express.Router()
  
- What do we use route middleware for?
Route middleware in Express is used to perform operations or execute functions that are specific to a particular route or group of routes.

  
