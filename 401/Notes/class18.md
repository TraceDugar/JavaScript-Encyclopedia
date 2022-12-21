# Class 18

(https://www.serverless.com/amazon-api-gateway)

What is Amazon API Gateway?
Amazon API Gateway is a managed service that allows developers to define the HTTP endpoints of a REST API or a WebSocket API and connect those endpoints with the corresponding backend business logic. It also handles authentication, access control, monitoring, and tracing of API requests.
<br>

Why is Amazon API Gateway an important part of the Serverless ecosystem?
Within the Serverless ecosystem, API Gateway is the piece that ties together Serverless functions and API definitions. Being able to trigger the execution of a Serverless function directly in response to an HTTP request is the key reason why API Gateway is so valuable in Serverless setups: it enables a truly serverless architecture for web applications. When using API Gateway together with other AWS services, it’s possible to build a fully functional customer-facing web application without maintaining a single server yourself. This brings the advantages of the serverless model—scalability, low maintenance, and low cost due to low overhead—to mainstream web applications.
<br>

How does API Gateway integrate with other AWS services?
Many AWS services support integration with Amazon API Gateway, including:

AWS Lambda: run Lambda functions to generate HTTP API responses.
AWS SNS: publish SNS notifications when an HTTP API endpoint is accessed.
Amazon Cognito: provide authentication and authorization for your HTTP APIs.
API Gateway supports direct integrations that can be configured in the API Gateway user interface (or via the API Gateway’s own API) for the following actions:

Invoking an AWS Lambda function.
Invoking another HTTP endpoint, with or without VPC Link.
Making an HTTP call against the API of any AWS service that provides an HTTP API.
Returning a mock response generated within API Gateway without calling out to other services
<br>

(https://aws.amazon.com/api-gateway/)

What are the some benefits of using Amazon API Gateway?
API Gateway handles all the tasks involved in accepting and processing up to hundreds of thousands of concurrent API calls, including traffic management, CORS support, authorization and access control, throttling, monitoring, and API version management. API Gateway has no minimum fees or startup costs. You pay for the API calls you receive and the amount of data transferred out and, with the API Gateway tiered pricing model, you can reduce your cost as your API usage scales.
<br>

What two API types might you choose from?
RESTful API's as well as Websocket APIs
<br>

(https://www.dynamodbguide.com/what-is-dynamo-db/)

What is DynamoDB?
DynamoDB is a hosted NoSQL database offered by Amazon Web Services (AWS). It offers:

reliable performance even as it scales;
a managed experience, so you won't be SSH-ing into servers to upgrade the crypto libraries;
a small, simple API allowing for simple key-value access as well as more advanced query patterns.
<br>

Under what circumstances would you recommend DynamoDB over MongoDB?
Applications with large amounts of data and strict latency requirements. As your amount of data scales, JOINs and advanced SQL operations can slow down your queries. With DynamoDB, your queries have predictable latency up to any size, including over 100 TBs!

Serverless applications using AWS Lambda. AWS Lambda provides auto-scaling, stateless, ephemeral compute in response to event triggers. DynamoDB is accessible via an HTTP API and performs authentication & authorization via IAM roles, making it a perfect fit for building Serverless applications.

Data sets with simple, known access patterns. If you're generating recommendations and serving them to users, DynamoDB's simple key-value access patterns make it a fast, reliable choice.
<br>

(https://dynamoosejs.com/getting_started/Introduction)

Explain to a non-technical friend how DynamoDB works.
DynamoDB allows developers to store vast amounts of data with very little upkeep or security concerns.
<br>

(https://dynamoosejs.com/getting_started/Introduction)

What is Dynamoose?
Dynamoose is a modeling tool for Amazon's DynamoDB. Dynamoose is heavily inspired by Mongoose, which means if you are coming from Mongoose the syntax will be very familiar.
<br>

What are some key features of Dynamoose?
Type safety,
High level API,
Easy to use syntax,
DynamoDB Single Table Design Support,
Ability to transform data before saving or retrieving items,
Strict data modeling (validation, required attributes, and more),
Support for DynamoDB Transactions,
Powerful Conditional/Filtering Support,
Callback & Promise support,
AWS Multi-region support.
<br>

