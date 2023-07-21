# 401 class_07

## Intro to JWT

- What is a JSON Web Token (JWT)?

A large encoded string with three parts all seperated by a period. 

- When should we use JSON Web Tokens?

To authenticate a user.

- Claims are expected in which structural component of a JWT?

The payload.

## Are JWTs Secure?

- If I get a JWT and I can decode the payload, how can we call that secure?

Because there will be a secret attached which will prevent this.

- If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.

The Secret.

- Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.

You just have to add the secret and you're good.

## JWTs Explained

- Why use JWT?

For authentication.

- JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.

This is useful because it makes the logic easier and sending the token faster. Compact means the file is smaller and easier to send and self-contained means that the file has all of the information inside of itself so we don't need to make more queries to a db.

- What are the three components (the structure) of a JWT signature?

A header, payload, and signature.
