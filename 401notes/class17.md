#  AWS: S3 and Lambda

## What is Amazon S3?

Amazon S3 (Simple Storage Service) is a scalable object storage service offered by Amazon Web Services (AWS). It provides developers and businesses with secure and durable storage for storing and retrieving any amount of data over the internet.

## Name some use cases for Amazon S3.

Backup and Restore: S3 is commonly used for backing up critical data and ensuring its durability. Data Archiving: S3 offers long-term storage and archival capabilities. Content Storage and Distribution: S3 is well-suited for storing static website content, media files (images, videos, audio), documents, and other digital assets.

## Name some benefits of using Amazon S3.

Scalability: S3 provides virtually unlimited storage capacity, allowing you to scale your storage needs seamlessly as your data grows. Durability and High Availability: S3 is designed for durability, offering 99.999999999% (11 nines) of data durability. Security: S3 offers robust security features to protect your data. It provides encryption options for data at rest and in transit, allowing you to choose between server-side encryption or client-side encryption with your own keys. 

## What is AWS Lambda?


AWS Lambda is a serverless computing service provided by Amazon Web Services (AWS). It allows you to run your code without provisioning or managing servers. With AWS Lambda, you can upload your code and the service takes care of automatically scaling and managing the infrastructure required to run your code in response to events

## Name some use cases for AWS Lambdas.

Serverless Web Applications: Lambda functions can serve as the backend for web applications, handling requests from clients, processing data, and interacting with databases. Real-time File Processing: Lambda functions can process files as soon as they are uploaded to services like Amazon S3. This can include tasks such as image resizing, data validation, file format conversion, and more. Data Processing and ETL: Lambda functions can be used for data transformation, extraction, and loading (ETL) tasks. They can process streaming data from sources like Amazon Kinesis or handle batch processing of data stored in Amazon S3 or Amazon DynamoDB. 

## Describe “serverless” to a non-technical friend.

Imagine you want to build a website or an application that requires a server to handle all the requests and process the data. Traditionally, you would need to set up and manage your own server, which can be complex and time-consuming.

But with serverless computing, you don't have to worry about managing servers anymore. It's like renting a fully equipped kitchen instead of building and maintaining your own. In a serverless environment, you write your code and deploy it to a cloud platform like AWS, and the platform takes care of all the server management for you.

In this serverless model, you only pay for the actual usage of your code, not for running and maintaining servers 24/7. It's like paying for the time you spend in the kitchen, rather than paying for the kitchen itself.

Serverless allows you to focus on writing and improving your code without getting caught up in the complexities of infrastructure management. It scales automatically to handle as much traffic as you need, so you don't have to worry about your website or application crashing during peak usage.

## What is a CDN?

A CDN, or Content Delivery Network, is a geographically distributed network of servers that work together to deliver content to users quickly and efficiently. It is designed to improve the performance, reliability, and availability of websites, applications, and other digital content.

## How does a CDN work with relation to the website visitor?

Request Routing, Content Caching, Cache Miss

## What are the benefits of employing a CDN?

mproved Website Performance,Faster Content Delivery, Enhanced User Experience

## What are your learning goals after reading and reviewing the class README?

to learn as much as possible about serverless functions
