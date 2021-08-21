# Event Driven Applications
> ***is a logical pattern that we can choose to confine our programming within to avoid issues of complexity and collision. In this article we’re going to go over how Event-Driven Programming works and how we can make the best use of it in our Node.js projects.***


![fsfsfs](https://hazelcast.com/wp-content/uploads/2020/02/20_EventDrivenArchitecture.png)


1. Why is access control important?
> ***Access controls limit access to information and information processing systems. When implemented effectively, they mitigate the risk of information being accessed without the appropriate authorisation, unlawfully and the risk of a data breach. They apply anywhere access is required to perform a business activity and should be adhered to when accessing information in any format, on any device.***

2. Describe an application that would need access control.
> ***Access control (or authorization) is the application of constraints on who (or what) can perform attempted actions or access resources that they have requested. In the context of web applications, access control is dependent on authentication and session management:***

#### Authentication identifies the user and confirms that they are who they say they are. Session management identifies which subsequent HTTP requests are being made by that same user. Access control determines whether the user is allowed to carry out the action that they are attempting to perform.



3. What is a role used for?
> ***Role-based access control (RBAC) restricts network access based on a person’s role within an organization and has become one of the main methods for advanced access control. The roles in RBAC refer to the levels of access that employees have to the network.***

1. Why is role based access control more scalable than discretionary or mandatory access control?
> ***DAC is the way to go to let people manage the content they own. It might sound obvious, but for instance DAC is very good to let users of an online social network choose who accesses their data. It allows people to revoke or forward privileges easily and immediately. Reactive access control, Seeing further and Laissez-faire file sharing provide nice examples of research on DAC with users.***

###### RBAC is a form of access control which as you said is suitable to separate responsibilities in a system where multiple roles are fulfilled. This is obviously true in corporations (often along with compartmentalization e.g. Brewer and Nash or MCS) but can also be used on a single user operating system to implement the principle of least privilege. RBAC is designed for separation of duties by letting users select the roles they need for a specific task. The key question is whether you use roles to represent tasks performed on your system and assign roles in a central authority (in which case RBAC is a form of MAC); or if you use roles to let users control permissions on their own objects (leading to multiple roles per object and absolutely no semantics in roles, even though it’s theoretically possible).

###### Document the following Vocabulary Terms

- Authorization is the process of giving the user permission to access a specific resource or function. This term is often used interchangeably with access control or client privilege.

- Giving someone permission to download a particular file on a server or providing individual users with administrative access to an application are good examples of authorization.

- Role Based Access Control is a method of restricting network access based on the roles of individual users within an enterprise.

###### Capabilities is a fundamentally better approach to Identity and access management today’s ACL framework for creating secure Identity and Access Management system. By tying access to key, rather than a centralized control system, Capability-based models push security to edge, decentralizing large attack vectors known as honeypots.

###### Preview
> Which 3 things had you heard about previously and now have better clarity on?
1. Bearer Authorization
2. Capabilities
3. Access control
> Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
1. Network Packet
2. Database relations
3. Hashing data
> What are you most excited about trying to implement or see how it works?
1. Hashing data