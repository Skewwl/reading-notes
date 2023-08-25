# class_18

## AWS API Gateway Overview

- What is Amazon API Gateway?

API Gateway sits between the backend services of your API and your API’s users, handling the HTTP requests to your API endpoints and routing them to the correct backends.

- Why is Amazon API Gateway an important part of the Serverless ecosystem?

API Gateway is the piece that ties together Serverless functions and API definitions. Being able to trigger the execution of a Serverless function directly in response to an HTTP request is the key reason why API Gateway is so valuable in Serverless setups: it enables a truly serverless architecture for web applications. When using API Gateway together with other AWS services, it’s possible to build a fully functional customer-facing web application without maintaining a single server yourself.

- How does API Gateway integrate with other AWS services?

Gateway can invoke an AWS Lambda function when an api endpoint is reached.

## AWS API Gateway

- What are the some benefits of using Amazon API Gateway?

No minimum fees, only fees for data transfer. Easy to monitor api performance. Low latency. Savings at scale.

- What two API types might you choose from?

Restful APIs and Websocket APIs.

## AWS DynamoDB Guide

- What is DynamoDB?

A hosted NoSQL database offered by Amazon Web Services.

- Under what circumstances would you recommend DynamoDB over MongoDB?

I would recommend Dynamo over Mongo if someone is making an application with alot of the AWS infrastructure.

## AWS DynamoDB

- Explain to a non-technical friend how DynamoDB works.

DynamoDB is Amazon's version of a non-relational database. The benefit of DynamoDB is that it is fully integratable into the rest of AWS's managed & 'serverless' services.

## Dynamoose

- What is Dynamoose?

Dynamoose is a modeling tool for Amazon's DynamoDB. It was inspired by MongoDB's Mongoose modeling tool.

- What are some key features of Dynamoose?

  - Type safety
  - High level API
  - Easy to use syntax
  - DynamoDB Single Table Design Support
  - Ability to transform data before saving or retrieving items
  - Strict data modeling (validation, required attributes, and more)
  - Support for DynamoDB Transactions
  - Powerful Conditional/Filtering Support
  - Callback & Promise support
  - AWS Multi-region support
