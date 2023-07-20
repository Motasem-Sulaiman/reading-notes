# AWS: Events

## What is the difference betweeen SQS and SNS?
-   SQS is a fully managed message queuing service that enables decoupling of components in a distributed system. It allows you to send, store, and receive messages between different components of an application without the components needing to directly interact with each other.
- SNS is a fully managed notification service that allows you to send messages or notifications to a large number of subscribers (endpoints) through multiple delivery protocols, such as HTTP, email, SMS, and more.

## What are some use cases for both SNS and SQS?
SQS:
- Eventual Consistency
- Decoupled Components
- Distributed Systems

SNS:
- Broadcast Notifications
- Email and SMS Notifications
- Application Logs and Monitoring


## Describe how to use SQS and SNS in a “fanout” pattern.
- Create an SNS Topic:
- Subscribe SQS Queues to the SNS Topic:
- Publish Messages to the SNS Topic:
- Consuming Messages from SQS Queues:


## Explain how “push notifications” work, using SNS.
- Setting up SNS Topic:
- Subscribing Endpoints:
- Sending Push Notifications:
- Message Delivery:
- Handling Notifications on Endpoints:


## How might a large scale, distributed application make use of a Queue system like SQS?
- Asynchronous Communication
- Load Leveling and Backpressure
- Microservices Communication
- Scalability and Auto-scaling