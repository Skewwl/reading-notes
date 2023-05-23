# Class 12

## Status Codes Based On REST Methods

* In your own words, describe what each group of status code represents:

100’s = Informantional, "You're request was recieved but..." or "You're request was recieved and..."
200’s = Success!
300’s = Redirection.
400’s = Client error.
500’s = Server Error.
What is a status code 202? It means that the request met all validation requirements at the time of sending
What is a status code 308? Permenant Redirect- this tells the client to use another URL to access the resource and not use the current URL anymore.
What code would you use if an update didn’t return data to a client? Status 204 for successful update, nothing to return.
What code would you use if a resource used to exist but no longer does? 410, its gone!
What is the ‘Forbidden’ status code? 403, you don't have the authorization.

## Build A REST API With Node.js, Express, & MongoDB - Quick - First 20 minutes

* Why do we need to pull our MongoDB database string out of our server and put it into our .env?

Because we don't want anyone who looks at our github files to have access to the info in our DB, we want them to be authorized personel who inquire through our api.

* What is middleware?

When a server gets a request, middleware is the code that runs before the request hits its route.

* What does app.use(express.json()) do?

It assigns the express.json() middleware, which allows our server to accept json as a body instead of a post, get, etc. element.

* What does the /:id mean in a route?

The colon makes the following string a parameter that we can access by typing request.params. Specifically the id can be readed at request.params.id.

* What is the difference between PUT and PATCH?

Put will update the entire object where patch will update specific properties of the object.

* How do you make a default value in a schema?

Create a default key set to a value, like: recievedDate: {type: Date, required: true, default: Date.now}

* What does a 500 error status code mean?

The server encountered an unexpected condition that prevented it from fulfilling the request.

* What is the difference between a status 200 and a status 201?

200 is success, typical of a get request. While 201 is a creation success, typical of a post request. 
