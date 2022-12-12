# Class 11 Reading notes

//----source:(https://www.digitalocean.com/community/tutorials/nodejs-event-driven-programming)

1.What native Node.js module allows us to get started with Event Driven Programming?
Node.js natively provides us with a useful module called EventEmitter that allows us to get started incorporating Event-Driven Programming in our project right away. Of course, creating our own version of EventEmitter wouldn’t be much of a challange, and in fact there are several modules published on npm such as EventEmitter2 and EventEmitter3 which promise a faster performance than the native EventEmitter.
<br>

2.What is the value of Object Oriented Programming used in tandem with Event Driven Programming?
The Object Oriented approach promotes the idea that all behavior of an individual unit (or object) be handled from code within that unit. Using this approach, applications are built with many different units that all speak to and interact with each other.

Imagine we’re building a mail application. We might have an object whose sole purpose is to process the incoming and outgoing mail messages for our client. This object would contain all of its own behavioral functions. We might have a sendMail function that delivers our mail to a server. We might also have a receiveMail function that tells the server to deliver us any new mail it has for us. We’ll call the object responsible for these server interactions our Mailbox.
<br>

3.Consider your knowledge of Event Driven Programming in the Web Browser, now explain to a non-technical friend how Event Driven Programming might be useful on the backend using Node.js.
Event Driven programming allows us to make objects in our code, and the events are what we say that those objects do.
<br>

