# Class 08

## API Design Best Practices

- What does REST stand for?

Representational state transfer.

- REST APIs are designed around a ____.

Resource (and the main factors that the resource, maybe a business, focus on)

- What is an identifier of a resource? Give an example.

The part of a url that identifies a resource. In https://adventure-works.com/orders/1 /orders/1 would be the identifier.

- What are the most common HTTP verbs?

The most common operations are GET, POST, PUT, PATCH, and DELETE.

- What should the URIs be based on?

URIs should be based on the entities they are representing, nouns not verbs.

- Give an example of a good URI.

/customers/5

- What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

A chatty web API is one that may require a client to make multiple requests to get all of the information they desire, this is a bad thing because they added requests increases the load on the web server.

- What status code does a successful GET request return?

200

- What status code does an unsuccessful GET request return?

404

- What status code does a successful POST request return?

201

- What status code does a successful DELETE request return?

204
