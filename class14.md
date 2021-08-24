# Event Driven Architecture
![dsfsf](https://www.daitan.com/wp-content/uploads/2017/11/Event-Driven-Architectures.png)

## What’s the difference between a FIFO and a standard queue?
> ***Standard queues guarantee that a message is delivered at least once and duplicates can be introduced into the queue. FIFO queues ensure a message is delivered exactly once and remains available until a consumer processes and deletes it; duplicates are not introduced into the queue***

## How can the server be assured a message was properly received?
> ****by giving back to message queue that he received the message***

## What classic design pattern is best represented by event driven programming?
> ***One of the most popular design patterns used by software developers is a factory method. It is a creational pattern that helps create an object without the user getting exposed to creational logic. The only problem with a factory method is it relies on the concrete component***

## How do you test an event driven system?
> ***by adding test file and testing it with jest library***


![dsfs](https://cdn.tiempodev.com/wp-content/uploads/2020/06/03161101/Event-Driven-Architecture-01.jpg)

Term|Def
----|---
FIFO Queue | A FIFO queue is a queue that operates on a first-in, first-out (FIFO) principle. This means that the request (like a customer in a store or a print job sent to a printer) is processed in the order in which it arrives.
Pub/Sub | Publish/subscribe messaging, or pub/sub messaging, is a form of asynchronous service-to-service communication used in serverless and microservices architectures. In a pub/sub model, any message published to a topic is immediately received by all of the subscribers to the topic



