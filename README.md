API GateWay in Microservice
========================

## Main features in the API Gateway pattern

> Reverse proxy or gateway routing

> Requests aggregation

> Cross-cutting concerns or gateway offloading

## Direct client-to-microservice communication

![no-gateway](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/architect-microservice-container-applications/media/image12.png)

## Single custom API Gateway service

![single-gateway](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/architect-microservice-container-applications/media/image12.png)

## Multiple custom API Gateways

![multiple-gateway](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/architect-microservice-container-applications/media/image12.png)


# Software Architecture #

> Single process. 

> Client / Server (2 processes collaborating). 

> 3 Tier systems (3 processes collaborating in chains).

> N Tier systems (N processes collaborating in chains).

> Service oriented architecture (lots of processes interacting with each other).

> Peer-to-peer architecture (lots of processes interacting without a central server).

> Hybrid architectures - combinations of the above architectures.


![Common Software Architectures](http://tutorials.jenkov.com/images/software-architecture/software-architecture-introduction-2.png)

## Enterprise architect vs Solution architect vs Technical architect #

![Picture Architect](https://i.stack.imgur.com/ALg2V.jpg)

![Enterprise Architect](https://image.slidesharecdn.com/benorstella2007soapresentation-140307044612-phpapp01/95/enterprise-architecture-og-soa-trender-13-638.jpg?cb=1394167659)

### Monolithic Architecture ###

![Monolithic Architecture](https://i.pinimg.com/originals/90/65/aa/9065aa51ee351656f71ede4dce1887de.png)


> Pros and Cons of the Monolithic Architecture

![Pros and Cons](https://d32myzxfxyl12w.cloudfront.net/assets/images/article_images/4e1889d1e9ac4ae36f1ce491b225575656f177d7.png?1495613101)

### Service Oriented Architecture (SOA) ###
``
	Descriptions
``

![SOA](https://qph.fs.quoracdn.net/main-qimg-b9c03799cb16addaab9ca1eb88d8dbcc)

### Microservice Architecture ###

![Microservice](https://www.seekpng.com/png/full/380-3804084_microservice-architecture-of-uber-microservices-architecture-diagram.png)

> Data Flow in the Microservices Architecture

![Data Flow](https://d32myzxfxyl12w.cloudfront.net/assets/images/article_images/c1de72bfea7d3fbb91a5d077973e8064639e36e3.gif)

> Pros and Cons of the Microservices Architecture

![Pros and Cons](https://d32myzxfxyl12w.cloudfront.net/assets/images/article_images/4e27f6ecd221c17a466257cbf5a9a71836946fff.png)

# Scaling #
``
	Imagine that you are buying a brand new car which can accommodate 4 people in it. Now, say 10 of your friends need to go for a vacation. What would you do?
``

> Would you buy a bigger car? - Vertical Scaling

> Would you buy one more Nissan car ? - Horizontal Scaling


### Vertical scaling ###
``
	Descriptions
``

![Vertical](https://docs.bmc.com/docs/TSLogAnalytics/110/files/721194061/794585309/1/1491485444762/Horizontal+versus+vertical+scaling.png)


### Horizontal Architecture ###

``
	Descriptions
``
# SaaS PaaS IaaS #

``
	SaaS, PaaS, and IaaS are simply three ways to describe how you can use the cloud for your business.
``

![SaaS-PaaS-IaaS](https://www.bigcommerce.com/blog/wp-content/uploads/2018/10/saas-vs-paas-vs-iaas-breakdown.jpg)

### Software as a Service ###
``
	SaaS platforms make software available to users over the internet, usually for a monthly subscription fee.
``

``
	SaaS: BigCommerce, Google Apps, Salesforce, Dropbox, MailChimp, ZenDesk, DocuSign, Slack, Hubspot.
``
### Platform as a Service ###
``
	PaaS: AWS Elastic Beanstalk, Heroku, Windows Azure (mostly used as PaaS), Force.com, OpenShift, Apache Stratos, Magento Commerce Cloud.
``
### Infrastructure as a Service ###
``
	IaaS examples: AWS EC2, Rackspace, Google Compute Engine (GCE), Digital Ocean, Magento 1 Enterprise Edition*.
``
# Other #
### Synchronous ###


![Synchronous-Asynchronous](http://tutorials.jenkov.com/images/software-architecture/software-architecture-introduction-3.png)

### Asynchronous ###

![advantages](https://2.bp.blogspot.com/-hso1gQedFFI/WB9MW4o7X3I/AAAAAAAAPq8/TbpnJuAwBGs6cT6VI4FtFC9CR8UQstqoACLcB/s400/difference-between-synchronous-and-asynchronous-messages.gif)

### Blocking ###

![blocking](https://strongloop.com/blog-assets/2014/01/threading_java.png)

### Non-Blocking ###

![non-blocking](https://cdn-images-1.medium.com/max/1600/1*WVP8haZ_BXxVPEzsPDZWsQ.png)

### Multi-tenant Architecture For SaaS ###

![Multi-tenant](https://miro.medium.com/max/1294/1*8leW0qv4y05TWEohdrtPuw.jpeg)

> Single tenant: single software, serving single customer only, (single)independent database

> Multi-tenant: serving multiple customers, sharing the software app along with sharing a single database

### Git Branching Workflow ###
![git-realease](https://jeffkreeftmeijer.com/git-flow/git-flow.png)