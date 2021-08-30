# AWS: API, Dynamo and Lambda
![img](https://miro.medium.com/max/1400/1*5Q43ntrN1TmBYOm3DU-lNw.png)

## What are serverless functions?
> ***A serverless function is a programmatic function written by a software developer for a single purpose. It’s then hosted and maintained on infrastructure by cloud computing companies. These companies take care of code maintenance and execution so that developers can deploy new code faster and easier.***

## Describe how a CDN works
![img](https://7backlink.com/wp-content/uploads/2017/10/cmn_en_fig_services_network_cdn_01.png)

> ***To minimize the distance between the visitors and your website’s server, a CDN stores a cached version of its content in multiple geographical locations (a.k.a., points of presence, or PoPs). Each PoP contains a number of caching servers responsible for content delivery to visitors within its proximity.***

> ***In essence, CDN puts your content in many places at once, providing superior coverage to your users. For example, when someone in London accesses your US-hosted website, it is done through a local UK PoP. This is much quicker than having the visitor’s requests, and your responses, travel the full width of the Atlantic and back.*** 

Terms:
Cloud Storage | Cloud storage is a cloud computing model that stores data on the Internet through a cloud computing provider who manages and operates data storage as a service. It’s delivered on demand with just-in-time capacity and costs, and eliminates buying and managing your own data storage infrastructure. This gives you agility, global scale and durability, with “anytime, anywhere” data access.
CDN | A content delivery network (CDN) refers to a geographically distributed group of servers which work together to provide fast delivery of Internet content.

![img](https://scdn1.plesk.com/wp-content/uploads/2019/04/25141138/image11.jpg)

> ***A CDN allows for the quick transfer of assets needed for loading Internet content including HTML pages, javascript files, stylesheets, images, and videos. The popularity of CDN services continues to grow, and today the majority of web traffic is served through CDNs, including traffic from major sites like Facebook, Netflix, and Amazon.***

## Amazon API Gateway
![img](https://d1.awsstatic.com/Test%20Images/MasonTests/Lambda_WebApplications.2139ddbc8a84f5564ee5846995f28c88e9db5c2d.png)
![img](https://cdn-digicloud.pressidium.com/wp-content/uploads/2020/04/Amazon-API-Gateway-Features-1024x680.jpg)
> ***Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale. APIs act as the “front door” for applications to access data, business logic, or functionality from your backend services. Using API Gateway, you can create RESTful APIs and WebSocket APIs that enable real-time two-way communication applications. API Gateway supports containerized and serverless workloads, as well as web applications.***

> ***API Gateway handles all the tasks involved in accepting and processing up to hundreds of thousands of concurrent API calls, including traffic management, CORS support, authorization and access control, throttling, monitoring, and API version management. API Gateway has no minimum fees or startup costs. You pay for the API calls you receive and the amount of data transferred out and, with the API Gateway tiered pricing model, you can reduce your cost as your API usage scales.***

## Amazon DynamoDB
![img](https://eadn-wc03-4064062.nxedge.io/cdn/wp-content/uploads/2021/02/DynamoDB_Diagram-02.png)

> ***Amazon DynamoDB is a key-value and document database that delivers single-digit millisecond performance at any scale. It’s a fully managed, multi-region, multi-active, durable database with built-in security, backup and restore, and in-memory caching for internet-scale applications. DynamoDB can handle more than 10 trillion requests per day and can support peaks of more than 20 million requests per second.***

> Many of the world’s fastest growing businesses such as Lyft, Airbnb, and Redfin as well as enterprises such as Samsung, Toyota, and Capital One depend on the scale and performance of DynamoDB to support their mission-critical workloads.

## Dynamoose
> ***Dynamoose is a modeling tool for Amazon’s DynamoDB. Dynamoose is heavily inspired by Mongoose.***

## Key Features:

1. Support for DynamoDB Transactions
2. Callback & Promise support
3. High level API
4. Type safety
5. Powerful Conditional/Filtering Support
6. Easy to use syntax
7. Strict data modeling (validation, required attributes, and more)
8. Ability to transform data before saving or retrieving documents