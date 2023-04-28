# Readings: AWS: Events

### Reading

[AWS SQS vs SNS](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)

- What is the difference betweeen SQS and SNS?
  - SNS is a distributed publish-subscribe service. SQS is distributed queuing service.
- What are some use cases for both SNS and SQS?
  - SNS you can use if you need to send to multiple subscribers, sqs you only need one subscriber.

[AWS SNS and SQS](https://www.youtube.com/watch?v=mXk0MNjlO7A)

- Describe how to use SQS and SNS in a “fanout” pattern.
  - In a fanout pattern, create an SNS topic and multiple SQS queues. Subscribe each SQS queue to the SNS topic, and messages published to the topic are delivered to all subscribed queues.

- Explain how “push notifications” work, using SNS.
  - SNS push notifications are messages sent from a server to client devices without a client request. With SNS, create a topic, configure platform-specific credentials, and register client devices to send notifications.

[SQS and SNS Basics](https://www.youtube.com/watch?v=UesxWuZMZqI)

- How might a large scale, distributed application make use of a Queue system like SQS?
  - Amazon SQS can be an essential part of a large-scale distributed application, allowing for efficient communication between microservices, horizontal scaling, batch processing, retry logic, and delayed processing.

### Bookmark and Review

[SNS Javascript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SNS.html)

[SQS Javascript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SQS.html)