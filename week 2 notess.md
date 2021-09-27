# CIT week 2 
## important things i learned 

## 2.1 A Brief History
_The idea of computing in a "cloud" traces back to the origins of utility computing, a concept that computer scientist John McCarthy publicly proposed in 1961_

## 2.2 buisness drivers 
_The origins and inspirations of many of the characteristics, models, and mechanisms covered throughout subsequent chapters can be traced back to the upcoming business drivers. It is important to note that these influences shaped clouds and the overall cloud computing market from both ends._

###### Capacity Planning

_Capacity planning is the process of determining and fulfilling future demands of an organization's IT resources, products, and services. Within this context, capacity represents the maximum amount of work that an IT resource is capable of delivering in a given period of time. A discrepancy between the capacity of an IT resource and its demand can result in a system becoming either inefficient (over-provisioning) or unable to fulfill user needs (under-provisioning). Capacity planning is focused on minimizing this discrepancy to achieve predictable efficiency and performance._
* Lead Strategy - adding capacity to an IT resource in anticipation of demand
* Lag Strategy - adding capacity when the IT resource reaches its full capacity
* Match Strategy - adding IT resource capacity in small increments, as demand increases

###### Cost Reduction

_A direct alignment between IT costs and business performance can be difficult to maintain. The growth of IT environments often corresponds to the assessment of their maximum usage requirements._
* technical personnel required to keep the environment operational
* upgrades and patches that introduce additional testing and deployment cycles
* utility bills and capital expense investments for power and cooling
* security and access control measures that need to be maintained and enforced to protect infrastructure resources
* administrative and accounts staff that may be required to keep track of licenses and support arrangements

## Organizational Agility

_Businesses need the ability to adapt and evolve to successfully face change caused by both internal and external factors. Organizational agility is the measure of an organization's responsiveness to change._

## 2.3 Concepts and Terminology 

###### Cloud

_A cloud refers to a distinct IT environment that is designed for the purpose of remotely provisioning scalable and measured IT resources. The term originated as a metaphor for the Internet which is, in essence, a network of networks providing remote access to a set of decentralized IT resources._

###### IT Resource

_An IT resource is a physical or virtual IT-related artifact that can be either software based, such as a virtual server or a custom software program, or hardware-based, such as a physical server or a network device._

###### On-Premise

_As a distinct and remotely accessible environment, a cloud represents an option for the deployment of IT resources. An IT resource that is hosted in a conventional IT enterprise within an organizational boundary (that does not specifically represent a cloud) is considered to be located on the premises of the IT enterprise, or on-premise for short. In other words, the term "on-premise" is another way of stating "on the premises of a controlled IT environment that is not cloud-based." This term is used to qualify an IT resource as an alternative to "cloud-based." An IT resource that is on-premise cannot be cloud-based, and vice-versa._
* An on-premise IT resource can access and interact with a cloud-based IT resource.
* An on-premise IT resource can be moved to a cloud, thereby changing it to a cloud-based IT resource.
* Redundant deployments of an IT resource can exist in both on-premise and cloud based environments.

###### Scaling
_Scaling, from an IT resource perspective, represents the ability of the IT resource to handle increased or decreased usage demands._
* Horizontal Scaling - scaling out and scaling in
* Vertical Scaling - scaling up and scaling down

###### Horizontal Scaling
_The allocating or releasing of IT resources that are of the same type is referred to as horizontal scaling (Figure 4). The horizontal allocation of resources is referred to as scaling out and the horizontal releasing of resources is referred to as scaling in. Horizontal scaling is a common form of scaling within cloud environments._

###### Vertical Scaling
_When an existing IT resource is replaced by another with higher or lower capacity, vertical scaling is considered to have occurred._

###### Cloud Service
_Although a cloud is a remotely accessible environment, not all IT resources residing within a cloud can be made available for remote access._

## 2.4 Goals and Benefits

###### Reduced Investments and Proportional Costs
_Similar to a product wholesaler that purchases goods in bulk for lower price points, public cloud providers base their business model on the mass-acquisition of IT resources that are then made available to cloud consumers via attractively priced leasing packages._

###### Increased Scalability
_By providing pools of IT resources, along with tools and technologies designed to leverage them collectively, clouds can instantly and dynamically allocate IT resources to cloud consumers, on-demand or via the cloud consumer's direct conﬁguration._

###### Increased Availability and Reliability
_The availability and reliability of IT resources are directly associated with tangible business benefits._

## 2.5 Risks and Challenges

###### Increased Security Vulnerabilities
_The moving of business data to the cloud means that the responsibility over data security becomes shared with the cloud provider. The remote usage of IT resources requires an expansion of trust boundaries by the cloud consumer to include the external cloud. It can be difﬁcult to establish a security architecture that spans such a trust boundary without introducing vulnerabilities, unless cloud consumers and cloud providers happen to support the same or compatible security frameworks - which is unlikely with public clouds._

###### Reduced Operational Governance Control
_Cloud consumers are usually allotted a level of governance control that is lower than that over on-premise IT resources. This reduced level of governance control can introduce risks associated with how the cloud provider operates its cloud, as well as the external connections that are required to communicate between the cloud and the cloud consumer._

## 2.6 From Google's Perspective
_As our understanding of cloud computing evolves, I thought it might help to examine how Google, an early pioneer of cloud computing, perceives this topic._

1. Cloud computing is user-centric

_Once you as a user are connected to the cloud, whatever is stored there - document, messages, images, applications, whatever - becomes yours. In addition, not only is the data yours, but you can also share it with others. And you should expect that many different devices will be able to access this data._

2. Cloud computing is task-centric

_Instead of focusing on the application and what it can do, when working with the cloud, your focus moves to what you need done and how that application can do it for you. Traditional applications - word processing, spreadsheets, email and so on - are becoming less important than the documents that they can create._

3. Cloud computing is powerful

_Connecting hundreds or thousands of computers together in a cloud creates a wealth of computing power impossible with a single desktop PC._

4. Cloud computing is accessible

_Because data gets stored in the cloud, users can instantly retrieve more information from multiple places. You are not limited to a single source of data, as you are within a desktop PC environment._

5. Cloud computing is intelligent

_With all the data stored on the computers in the cloud, data mining and analysis are necessary to access this information in an intelligent manner._

6. Cloud computing is programmable

_Many of the tasks that are necessary with cloud computing will wind up being automated. For example, to protect the integrity of the data, information stored on a single computer in the cloud will need to be replicated on other computers in the cloud. If one of these computers goes offline, the cloud's programming automatically redistributes load to one of these replicated backups._

## 2.7 From Amazon's Perspective
###### Six Advantages of Cloud Computing
_As our understanding of cloud computing evolves, I thought it might help to examine how Amazon, an early pioneer of cloud computing, perceives this topic. From Amazon's perspective, there are six benefits of cloud computing:_

1. Trade capital expense for variable expense
_Instead of having to invest heavily in data centers and servers before you know how you’re going to use them, you can only pay when you consume computing resources, and only pay for how much you consume._

2. Benefit from massive economies of scale
_By using cloud computing, you can achieve a lower variable cost than you can get on your own. Because usage from hundreds of thousands of customers are aggregated in the cloud, providers such as Amazon Web Services can achieve higher economies of scale which translates into lower pay as you go prices._

3. Stop guessing capacity
_Eliminate guessing on your infrastructure capacity needs. When you make a capacity decision prior to deploying an application, you often either end up sitting on expensive idle resources or dealing with limited capacity. With Cloud Computing, these problems go away. You can access as much or as little as you need, and scale up and down as required with only a few minutes notice._

4. Increase speed and agility
_In a cloud computing environment, new IT resources are only ever a click away, which means you reduce the time it takes to make those resources available to your developers from weeks to just minutes. This results in a dramatic increase in agility for the organization, since the cost and time it takes to experiment and develop is significantly lower._

5. Stop spending money on running and maintaining data centers
_Focus on projects that differentiate your business, not the infrastructure. Cloud computing lets you focus on your own customers, rather than on the heavy lifting of racking, stacking and powering servers._

6. Go global in minutes
_Easily deploy your application in multiple regions around the world with just a few clicks. This means you can provide a lower latency and better experience for your customers simply and at minimal cost._

## 2.8 From Dilbert's Perspective
* Pointy Hair Boss: Alan has been out of the workforce for a long time. I need you to ease him back in.
* Alan: Do you have a binder of the company policies?
* Dilbert: It's in the Clouds.
* Alan looks up at the sky.

1. Summarize a few key points made in the readings or videos.
the power of the cloud is unmatch is very much giving. 
2. Identify two quotes that were made, that you found interesting.
dilberts persective is how i see the cloud sometimes. it is so funny laugh out loud. i found the other persectives very interesting because i can see why they see cloud computing in those ways. 
3. What new facts did you learn from this section?
cloud computing existed in the 60s. that does not exist to me. but i guess it did but go off 70s 
4. What questions remain in your mind after reading this section?
why was this reading so long? i want to cry. 
