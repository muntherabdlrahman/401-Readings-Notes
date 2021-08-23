# Message Queues
![csd](https://miro.medium.com/max/976/1*cCyPNzf95ygMFUgsrleHtw.png)

## What does it mean that web sockets are bidirectional? Why is this useful?
> ***Whereas HTTP relies on a client request to receive a response from the server for every exchange, WebSockets allow for full-duplex bidirectional communication. This enables the server to send real-time updates asynchronously, without requiring the client to submit a request each time.***

## Does socket-io use HTTP? Why?
> ***The socket API supports different protocols from the transport layer and down. That means that if you would like to use TCP you use sockets. But you can also use sockets to communicate using HTTP, but then you have to decode/encode messages according to the HTTP specification***

## What happens when a client emits an event?
> ***To emit an event from your client, use the emit function on the socket object. To handle these events, use the on function on the socket object on your server. Sent an event from the client!***

## What happens when a server emits an event?
> ***the client side will receive the handel of changes and got the results***

## What happens if a client “misses” an event?
> ***he will receive the response after he be connected***

## How can we mitigate this?
> ***make an queue***


Term|Def
----|---
Socket | Java Socket programming is used for communication between the applications running on different JRE. … Socket and ServerSocket classes are used for connection-oriented socket programming
Web Socket | WebSocket is the communication Protocol that provides bidirectional communication between the Client and the Server over a TCP connection
Socket.io | Socket.IO enables real-time, bidirectional and event-based communication. It works on every platform, browser or device, focusing equally on reliability and speed.
Client | The definition of a client means a customer or a person who uses services. An example of a client is a student being tutored at a college writing center. …
Server | A server is a computer program or device that provides a service to another computer program and its user, also known as the client. In a data center, the physical computer that a server program runs on is also frequently referred to as a server.
OSI Model | he OSI Model (Open Systems Interconnection Model) is a conceptual framework used to describe the functions of a networking system. The OSI model characterizes computing functions into a universal set of rules and requirements in order to support interoperability between different products and software.
TCP Model | It stands for Transmission Control Protocol/Internet Protocol. The TCP/IP model is a concise version of the OSI model. It contains four layers, unlike seven layers in the OSI mode
TCP | TCP stands for Transmission Control Protocol a communications standard that enables application programs and computing devices to exchange messages over a network. It is designed to send packets across the internet and ensure the successful delivery of data and messages over networks
UDP |  The User Datagram Protocol, or UDP, is a communication protocol used across the Internet for especially time-sensitive transmissions such as video playback
Packets | Packets are the basic units of communication over a TCP/IP network. Devices on a TCP/IP network divide data into small pieces, allowing the network to accommodate various bandwidths, to allow for multiple routes to a destination, and to retransmit the pieces of data which are interrupted or lost.


## Rooms

> ***A room is an arbitrary channel that sockets can join and leave. It can be used to broadcast events to a subset of clients:***
Emit cheatsheet
Reserved events

### On each side, the following events are reserved and should not be used as event names by your application:

1. connect
2. connect_error
3. disconnect
4. disconnecting
5. newListener
6. removeListener