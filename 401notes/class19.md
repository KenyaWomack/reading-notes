# Events

## What is the difference between SQS and SNS?

SQS (Simple Queue Service) is a distributed message queue service that decouples the components of a system by allowing them to communicate asynchronously. It enables reliable and scalable message-based communication between different parts of an application or between different applications. SNS (Simple Notification Service) is a publish-subscribe messaging service that allows applications to send notifications and deliver messages to multiple subscribers. It provides a highly flexible and efficient way to broadcast messages to multiple recipients.

## What are some use cases for both SNS and SQS?

SNS: Event Notifications, Mobile Push Notifications, Email and SMS Messaging

SQS: Decoupled Application Components, Workload Balancing, Message Processing and Background Tasks

## Describe how to use SQS and SNS in a “fanout” pattern

Create an SNS topic: Start by creating an SNS topic in your AWS account. The topic acts as a central point for publishing messages.

Create SQS queues: Create multiple SQS queues, each representing a subscriber or a separate system that needs to receive the messages. These queues will act as endpoints for the messages.

Subscribe SQS queues to the SNS topic: Subscribe each SQS queue to the SNS topic. This allows the queues to receive messages published to the SNS topic. Each queue will have a subscription ARN associated with it.

Publish messages to the SNS topic: Whenever you want to send a message to all the subscribers, you publish it to the SNS topic. SNS then takes care of delivering the message to all the subscribed SQS queues.

Receive messages from SQS queues: Each subscriber or system can independently retrieve messages from its respective SQS queue using the queue's API or SDK. This ensures that each subscriber processes the messages at its own pace.

## Explain how “push notifications” work, using SNS

Set up the mobile device platform: Configure the mobile device platform you want to send push notifications to, such as iOS, Android, or other platforms. This involves registering your application with the platform-specific push notification service (e.g., Apple Push Notification Service - APNS for iOS).

Create an SNS platform application: In the AWS Management Console, create an SNS platform application corresponding to the mobile device platform you want to target. Provide necessary details and credentials to establish a connection between SNS and the platform-specific push notification service.

Register devices: On the client-side (e.g., mobile app), the device registers with the platform-specific push notification service and obtains a unique device token. This token is then sent to your backend server.

Store device tokens: In your backend server, store the device tokens obtained from the mobile devices. Associate the tokens with specific users or endpoints to ensure targeted delivery.

Create an SNS topic: Create an SNS topic that represents the specific push notification message you want to send. The topic acts as a logical channel for publishing messages.

Subscribe devices to the SNS topic: Subscribe the device tokens to the SNS topic. This allows SNS to deliver push notifications to the registered devices.

Publish push notifications: Whenever you want to send a push notification, you publish a message to the SNS topic. SNS then uses the registered device tokens to deliver the notifications to the respective devices via the platform-specific push notification service.

Delivery to mobile devices: The platform-specific push notification service receives the push notification message from SNS and delivers it to the intended mobile devices. The devices display the notification to the user based on the platform's notification handling mechanism.

## How might a large scale, distributed application make use of a Queue system like SQS?

Decoupling components, Smooth traffic spikes, Load balancing and scalability, Fault tolerance and reliability

## What are your learning goals after reading and reviewing the class README?

differences between SNS and SQS
