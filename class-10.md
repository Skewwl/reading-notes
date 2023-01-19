# class-10.md

## HTML Forms
### Your first Web Form. How To Structure A Web Form.

- Why are forms so important in web development?

Web forms are one of the main points of interaction between a user and a website or application. Forms allow users to enter data, which is generally sent to a web server for processing and storage. It allows developers to create a page that stores information for businesses.

- When designing a form, what are some key things to keep in mind when it comes to user experience?

The bigger your form, the more you risk frustrating people and losing users. Keep it simple and stay focused: ask only for the data you absolutely need.

- List 5 form elements and explain their importance.
  - <Form> The element that encompasses the entire operation, can be thought of like a header.
  - The <fieldset> element is a convenient way to create groups of widgets that share the same purpose, for styling and semantic purposes. 
  - You can label a fieldset by including a <legend> element just below the opening fieldset tag. The text content of the <legend> formally describes the purpose of the fieldset it is included inside.
  - The <label> element is important if you want to build accessible forms.
  - <input> is where the user puts their data which we store IMO it is the most important cause thats like the whole point.

## Learn JS
### Introduction To Events.

- How would you describe events to a non-technical friend?

An event is something that happens that we want to know about, it lets us know that an action has taken place or data has arrived.

- When using the addEventListener() method, what 2 arguments will you need to provide?

The name of the event and a function to handle the event.

- Describe the event object. Why is the target within the event object useful?

A parameter inside an event handler function, specified with a name such as event. It is automatically passed to event handlers to provide extra features and information. The target property of the event object is nice to have because it is a reference to the element the event occurred upon.

- What is the difference between event bubbling and event capturing?
  
Event bubbling describes how the browser handles events targeted at nested elements, starting with the most nested event. Event capturing works in reverse. The event fires first on the least nested element, and then on successively more nested elements, until the target is reached.

 


  
