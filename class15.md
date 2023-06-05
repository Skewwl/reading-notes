# Class 15

## What is OAuth

- What is OAuth?

OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential.

- Give an example of what using OAuth would look like.

This makes me think of logging into zoom with my google login or logging into netlify with my github login.

- How does OAuth work? What are the steps that it takes to authenticate the user?

The first website, using OAuth, logs into another account of the user's to verify their id. The other account genereates a one-time token & secret for the first website. The first website presents these items to gain authorization. The user then approves (or the software approves on its own) a particular action and then the first website is given an access token which it gives to recource it is trying to access. The second website allows the client on behalf of the user.

- What is OpenID?

OpenId authenticates users to software, OAuth lets software authenticate users via other software in order to gain that user authorization to a resource.

## Authorization and Authentication flows

- What is the difference between authorization and authentication?

Authorization is the granting of acces to something. Authentication is proof that something is what it is being claimed to be.

- What is Authorization Code Flow?

It is the string of actions that happen after you click on the the second website which you are expecting to grant you autorization. Like getting request and access tokens to verify your identity.

- What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

A percentage of applications cannot securely store a Client Secret without OAuth 2.0's Proof Key for Code Exchange.

- What is Implicit Flow with Form Post?

Using OpenID Connect the web app requests and obtains tokens through the front channel, without the need for secrets or extra backend calls. With this method, you don’t need to obtain, maintain, use, and protect a secret in your application.
