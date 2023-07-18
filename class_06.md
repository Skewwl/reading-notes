# 401 class_06

## Securing Passwords
- Explain to a non-technical friend how you would safely hash and store a password.

Hashing is a good way to protect passwords. The benefit of hashing is that if someone steals the database with hashed passwords, they only make off with the hashes and not the actual plaintext passwords.

- What is Bcrypt?

An algorithm that uses a technique called key stretching for greater password security.

- Why might you use something like Bcrypt?

Because it is a hashing algorithm that is resistant to cyber attacks, it is good enough for most web applications that store users' passwords and other sensitive data.

## Basic Auth
- What is Basic Authentication?

A method for an HTTP user agent (web browser) to provide a user name and password when making a request.

- What properties are necessary in the header of a Basic Auth request?

Authorization: Basic <credentials>

- How are username:password in Basic Auth encoded?

They are merely encoded with Base64 in transit and not encrypted or hashed in any way. Basic authentication is typically used in conjunction with HTTPS to provide confidentiality.

## OWASP auth cheatsheet
- Define the authentication process to a non-technical recruiter.

Verify that an individual, entity or website is whom it claims to be.

- How should your error messaging respond (both HTTP and HTML)? Why?

An application must respond with a generic error message regardless of whether:
  - The user ID or password was incorrect.
  - The account does not exist.
  - The account is locked or disabled.
The account registration feature should also be taken into consideration, and the same approach of generic error message can be applied regarding the case in which the user exists. The objective is to prevent the creation of a discrepancy factor, allowing an attacker to mount a user enumeration action against the application.
