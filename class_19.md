# class_19

## AWS SQS vs SNS

- What is the difference betweeen SQS and SNS?

Simple Notification Service  is a distributed publish-subscribe service that can push out event notifications to a large number of recipients. Simple Queue Service is a distributed queuing service where recievers have to poll their queue to recieve the messages.

- What are some use cases for both SNS and SQS?

SNS: triggering different AWS mechanisms like a function and sending confirmation emails to customers.
SQS: Queing online orders to be packaged and another queue for when they should ship.

## AWS SNS and SQS

- Describe how to use SQS and SNS in a “fanout” pattern.

SNS can send out the occurance of an event to trigger a lambda function and while also sending the event to another reciepient's SQS.

- Explain how “push notifications” work, using SNS.

When an event occurs the SNS fires off its array of actions.

## SQS and SNS Basics

How might a large scale, distributed application make use of a Queue system like SQS?

SQS allows for more scalable and segmented software applications. It promotes loose coupling between components,  and enables asynchronous processing.
