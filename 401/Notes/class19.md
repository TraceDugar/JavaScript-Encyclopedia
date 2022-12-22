# Class 19 notes

(https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)

What is the difference betweeen SQS and SNS?
SQS and SNS are important components for scalable, large scale, distributed, cloud-based applications:

SNS is a distributed publish-subscribe service.

SQS is distributed queuing service.
<br>

What are some use cases for both SNS and SQS?
Choose SNS if:

You would like to be able to publish and consume batches of messages.
You would like to allow same message to be processed in multiple ways.
Multiple subscribers are needed.
Choose SQS if:

You need a simple queue with no particular additional requirements.
Decoupling two applications and allowing parallel asynchronous processing.
Only one subscriber is needed.
<br>

(https://www.youtube.com/watch?v=mXk0MNjlO7A)

Describe how to use SQS and SNS in a “fanout” pattern.

SNS - Publish messages to a topic that can deliver to many subscribers (fanout) of different types (SQS, Lambda, Email)

SQS - A system must poll the Queue to discover new events
<br>

Explain how “push notifications” work, using SNS.
Events trigger a message that get sent to the subscriber, ie. using a card and getting a notification from your bank of the amount charged and to what company.
<br>

(https://www.youtube.com/watch?v=UesxWuZMZqI)

How might a large scale, distributed application make use of a Queue system like SQS?
Message groups are created so that way consumers of a certain group may recieve the appropriate messages and it is a scalable solution,
