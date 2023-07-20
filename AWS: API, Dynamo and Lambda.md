# AWS: API, Dynamo and Lambda

## What is Amazon API Gateway?
Amazon API Gateway is a managed service that allows developers to define the HTTP endpoints of a REST API or a WebSocket API and connect those endpoints with the corresponding backend business logic. It also handles authentication, access control, monitoring, and tracing of API requests.
## Why is Amazon API Gateway an important part of the Serverless ecosystem?
 it enables a truly serverless architecture for web applications. When using API Gateway together with other AWS services, it’s possible to build a fully functional customer-facing web application without maintaining a single server yourself.
## How does API Gateway integrate with other AWS services?

- AWS Lambda: run Lambda functions to generate HTTP API responses.
- AWS SNS: publish SNS notifications when an HTTP API endpoint is accessed.
- Amazon Cognito: provide authentication and authorization for your HTTP APIs.

## What are the some benefits of using Amazon API Gateway?
- Easy monitoring
- Flexible security controls
- RESTful API options
- Efficient API development



## What two API types might you choose from?

 - RESTful APIs
 - WEBSOCKET APIs


## What is DynamoDB?
is a hosted NoSQL database offered by Amazon Web Services (AWS)


## Under what circumstances would you recommend DynamoDB over MongoDB?
- When you prefer a fully managed service with minimal operational overhead 
- When scalability is a critical requirement, and you need a database that can handle rapidly changing or unpredictable workloads.
- For applications that require fast and predictable response times


## Explain to a non-technical friend how DynamoDB works.
DynamoDB is like a magical table that can store and organize your data in items with attributes. It's incredibly fast, can handle a lot of information and requests, and ensures your data is secure and always available.

## What is Dynamoose?
Dynamoose is a modeling tool for Amazon's DynamoDB.

## What are some key features of Dynamoose?
Type safety
High level API
Easy to use syntax
DynamoDB Single Table Design Support
Callback & Promise support
AWS Multi-region support