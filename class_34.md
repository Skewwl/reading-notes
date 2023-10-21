# class_34

## Review API Server Build

Explain the difference between a query string parameter and a path parameter.

- The path is the resouces address on the internet. The query string is the part of the url that comes after the question mark. It usually specifies and gives more direction as to what resource to are hoping to aquire.

What would our API URL with a path id parameter be given the following information:
Domain: http://our-site.com
v3
model name: stuff
id: things

- http://our-site.com/v3/stuff/things

We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.

- The interface works by making calls to our api. These calls can be diferent depending on what you what to do with our resources. For example if you wanted to simply recieve our data then you can make a get request and use our data in your application. You can specify what data you want by following our docs. Get calls with different params and querys will return different information to you.

## Review Auth Server Build

Describe how you would use middleware to implement basic and bearer auth.

- I would place an app.use() middleware that houses an auth function at the beginning of my routes to make sure that everyone is sent through a verification process before being able to access resources.

Describe the handshake necessary to implement OAuth.

- First the user requests access to something, that user's computer needs to register with OAuth and get an id and a secret to authorize itself to the server which is currently wanting authorization. If access is granted or denied will determine where the user will be sent next. If granted then the user's computer is granted an access token wich is given to the server. Yay!

Describe how Role Based Access Control works to a non-technical friend.

- Role Based Access control allows an individual's account access to whatever their role is predetermined to have access to. If they have a position change at work and their roles changes then they may lose or gain clearance based on the new role that their new position at work is attached to.
