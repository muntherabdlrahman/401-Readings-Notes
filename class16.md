# AWS: Cloud Servers
![ssss](https://www.cloudways.com/wp-content/uploads/2018/05/cw-amazon.png)

## Describe the Web-Request-Response-Cycle
> ***The request/response cycle traces how a user’s request flows through the app.***

1. A user opens his browser, types in a URL, and presses Enter.
2. When a user presses Enter, the browser makes a request for that URL.
3. The request hits the Rails router (config/routes.rb). The router maps the URL to the correct controller and action to handle the request.
4. The action receives the request and passes it on to the view.
5. The view renders the page as HTML.
6. The controller sends the HTML back to the browser. The page loads and the user sees it.

![sfsfsfs](https://d1.awsstatic.com/Products/product-name/diagrams/product-page-diagram_CloudFormation.ad3a4c93b4fdd3366da3da0de4fb084d89a5d761.png)


## Explain what a “server” is, as it relates to the WRRC

> ***All resources are hosted on a server. The server’s location on the web can be identified by its IP address, however, IP addresses aren’t particularly user friendly, and instead we use URLS (such as http://www.google.co.uk) to search for a resource. Once the client’s request has reached the server, the server will search for and return the information the client is requesting. Often times, this means querying a database, loading the information into an html page, and returning the HTML text to the user in the body of the HTTP response.***

## What does it mean to “deploy” an application?

> ***Application Deployment (also referred to as Software Deployment) is the process of installing, configuring, and enabling a specific application or set of applications, usually through an application manager (app manager) or software management system, to a specific URL on a server.***
![sfas](https://d1.awsstatic.com/product-marketing/CloudTrail/Product-Page-Diagram-AWSX-CloudTrail_How-it-Works.d2f51f6e3ec3ea3b33d0c48d472f0e0b59b46e59.png)

Terms|def
-----|---
Server| is a piece of computer hardware or software (computer program) that provides functionality for other programs or devices, called “clients”, This architecture is called the client–server model.
Pub/Sub| Pub/Sub allows services to communicate asynchronously, with latencies on the order of 100 milliseconds.
Pub/Sub| used for streaming analytics and data integration pipelines to ingest and distribute data. It is equally effective as messaging-oriented middleware for service integration or as a queue to parallelize tasks.
WRRC|The request/response cycle traces how a user’s request flows through the app. Understanding the request/response cycle is helpful to figure out which files to edit when developing an app (and where to look when things aren’t working).