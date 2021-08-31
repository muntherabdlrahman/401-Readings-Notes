# AWS: Events
![img](https://blogs.sap.com/wp-content/uploads/2020/02/eventbridge-content-filtering-1-1024x435-1.png)

**These events are designed to educate you about AWS products, services, and solutions and help you develop the skills to design, deploy, and operate infrastructure and applications. Event content is delivered by subject matter experts from AWS, our partners, and our customers, who share how they have successfully built solutions on AWS.**


>***Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server
They are both ways you can implement an API. Within an Express Server you define your routes and write the logic for them. With AWS API Gateway, you set up your routes and then implement the functionality using lamda functions.***

#### List the AWS Database offerings and talk about the pros and cons of each
> ***AWS database offerings include:***


![img](https://www.testpreptraining.com/tutorial/wp-content/uploads/2019/09/image-16.png)


1. Amazon Timestream
2. DynamoDB
3. RDS
4. ElastiCache
5. Amazon Keyspaces
6. Amazon QLDB
7. Amazon DocumentDB
8. Neptune

#### They are each comparable to different db services. RDS is similar to oracle SQL, DynamoDB is similar to MongoDB, Aurora is MySQL, postrgeSQL compatible, etc.

1. Pros: They are scalable, managed, secure, easy to work with, and scalable

2. Cons: The only major con I can see is the cost.

### What’s the difference between a FIFO and a standard queue?
> ***A FIFO queue is first in first out and a standard queue provides at least once delivery and isn’t neccessarily ordered.***

### How can the server be assured a message was properly received?
> ***Logging and using timestamps and checking whether it was delivered based on the response sent from the endpoint.***

Terms|Def
-----|---
Serverless API |An API that lives in the cloud and is created using cloud services.
Triggers| Essentially a connection between resources. When something happens to a resource, it triggers an action to be taken.
Dynamo vs Mongo|  Dynamo is like the AWS version of Mongo. Mongo is open source and uses JSON objects, whereas Dynamo uses tables. MongoDB is less restrictive of data types and size.
Dynamoose vs Mongoose| Dynamoose is a modeling tool used for dynamo and mongoose is used for mongo.