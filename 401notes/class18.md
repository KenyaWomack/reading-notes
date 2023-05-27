# AWS: API, Dynamo and Lambda

## What is Amazon API Gateway?

Amazon API Gateway is a fully managed service provided by Amazon Web Services (AWS) that enables developers to create, publish, monitor, and secure APIs (Application Programming Interfaces) for their applications. It acts as a gateway that sits between the client applications and the backend services, allowing developers to expose their functionalities through APIs.

## Why is Amazon API Gateway an important part of the Serverless ecosystem?

Serverless API Management, API Gateway for Serverless Functions, Request Transformation and Validation

## How does API Gateway integrate with other AWS services?

AWS Lambda, AWS Identity and Access Management, AWS Cognito

## What are the some benefits of using Amazon API Gateway?

API Management, Scalability, Serverless Integration

## What two API types might you choose from?

RESTful APIs (Representational State Transfer): RESTful APIs are based on the principles of the REST architectural style. WebSocket APIs: WebSocket APIs enable real-time, bidirectional communication between clients and servers over a single, long-lived connection. 

## What is DynamoDB?

DynamoDB is a fully managed NoSQL database service provided by Amazon Web Services (AWS). It is designed to provide fast and predictable performance with seamless scalability. DynamoDB is known for its low-latency data access and ability to handle high-scale applications.

## Under what circumstances would you recommend DynamoDB over MongoDB?

If you prefer a fully managed database service where AWS takes care of the operational aspects, such as provisioning, scaling, and maintenance, DynamoDB is a good choice. MongoDB, on the other hand, requires more management and maintenance efforts as it is typically deployed on self-managed infrastructure. DynamoDB excels in providing seamless scalability and low-latency performance. It can handle high request volumes and large datasets without manual sharding or configuration changes. 

## Explain to a non-technical friend how DynamoDB works.

In DynamoDB, you organize your data into tables. Think of a table as a spreadsheet with rows and columns. Each table has a primary key, which is a unique identifier for each item (row) in the table. Items are the individual pieces of data you store in a DynamoDB table. Each item consists of one or more attributes (columns) with their corresponding values. For example, if you have a table to store user data, each item could represent a user, and the attributes could be their name, age, email, etc. Items are the individual pieces of data you store in a DynamoDB table. Each item consists of one or more attributes (columns) with their corresponding values. For example, if you have a table to store user data, each item could represent a user, and the attributes could be their name, age, email, etc.

## What is Dynamoose?

a popular npm package for working with Amazon DynamoDB in Node.js applications. It acts as an Object Data Modeling (ODM) library, similar to how Mongoose is used with MongoDB.

## What are some key features of Dynamoose?

Object Data Modeling, Schema Definition, Model Creation, Querying and Filtering

## What are your learning goals after reading and reviewing the class README?

how to become me efficient in lambda
