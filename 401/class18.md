# Readings: AWS: API, Dynamo and Lambda


## Reading

[AWS API Gateway Overview](https://www.serverless.com/amazon-api-gateway)

- What is Amazon API Gateway?
  - API Gateway is the piece that ties together Serverless functions and API definitions.
- Why is Amazon API Gateway an important part of the Serverless ecosystem?
  - The advantages of the serverless model—scalability, low maintenance, and low cost due to low overhead—to mainstream web applications.
- How does API Gateway integrate with other AWS services?
  - Invoking an AWS Lambda function.
  - Invoking another HTTP endpoint, with or without VPC Link.
  - Making an HTTP call against the API of any AWS service that provides an HTTP API.
  - Returning a mock response generated within API Gateway without calling out to other services.

[AWS API Gateway](https://aws.amazon.com/api-gateway/)

- What are the some benefits of using Amazon API Gateway?
  - Efficent API development
  - Performance at any scale
  - Cost saving at scale
- What two API types might you choose from?
  - RESTful and Web Socket APIs

[AWS DynamoDB Guide](https://www.dynamodbguide.com/what-is-dynamo-db/)

- What is DynamoDB?
  - DynamoDB is a fully managed, serverless NoSQL database service provided by AWS.
- Under what circumstances would you recommend DynamoDB over MongoDB?
  - Choose DynamoDB for seamless scalability, tight AWS integration, and a fully managed service.

[AWS DynamoDB](https://aws.amazon.com/dynamodb/)

- Explain to a non-technical friend how DynamoDB works.
  - DynamoDB is like a digital filing cabinet that stores and organizes data for easy access.

[Dynamoose](https://dynamoosejs.com/getting_started/Introduction)

- What is Dynamoose?
  - Dynamoose is a modeling tool to model db for DynamoDB.
- What are some key features of Dynamoose?
  - 