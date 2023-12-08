
#  AWS 
- AWS stands for Amazon Web Services.
- The AWS service is provided by the Amazon that uses distributed IT infrastructure to provide different IT
  resources available on demand. It provides different services such as infrastructure as a service (IaaS), platform as a service (PaaS) and packaged software as a service (SaaS)
  
![image](https://github.com/Ayus0721/AWS/assets/147092631/28c6b8e6-edd4-493e-8c47-d9eb7c84bb5d)
- Amazon launched AWS, a cloud computing platform to allow the different organizations to take advantage of reliable IT infrastructure


# What is Cloud Computing?
- It is the use of remote servers on the internet to store, manage and process data rather than a local 
   server or personal computer
# There are basically 3 categories in cloud computing

![image](https://github.com/Ayus0721/AWS/assets/147092631/98bd5b6d-0cd3-4a33-be7a-3bbd085a1960)
![image](https://github.com/Ayus0721/AWS/assets/147092631/d8252688-a6d3-4ca2-b070-14b9e9f27067)
![service models](https://github.com/Ayus0721/AWS/assets/147092631/b97fefbb-46f7-47db-ae8c-e53ce0429445)


## Advantages 
- faster time to market
- scalability and flexibility
- cost savings
- better collaboration
- advanced security
- data loss prevention
## Disadvantages
- risk of vendor lock-in
- less control over underlying cloud insfra
- concerns about security risks like data privacy and online threats
- integration complexity with exisiting systems
- unforseen costs and unexpected expenses

![image](https://github.com/Ayus0721/AWS/assets/147092631/6c25f6b4-b142-4f86-be8e-b4273c918093)

![image](https://github.com/Ayus0721/AWS/assets/147092631/6cfe07cb-eb1c-4107-acb4-43677dacce49)

- Example of private implementation softwares : openstack , opennebula
 
## Different domains in which AWS offer services:
- Compute:
 It is used to process data on the cloud by making use of powerful processors which serve multiple instances
at a time
- Storage and Content Delivery:
The storage as the name suggests, is used to store data in the cloud, this data can be stored anywhere but
content delivery on the other hand is used to cache data nearer to the user so as to provide low latency.
- Database:
  The database domain is used to provide reliable relational and non-relational database instances managed by AWS
- Networking:
  It includes services which provide a variety of networking features such as security, faster access etc
- Management Tools:
  It includes services which can be used to manage and monitor your AWS instances.
-  Security and Identity:
  It includes services for user authentication or limiting access to a certain set of audience on your AWS resources.

- Application Services: It includes simple services like notifications, emailing and queuing.

  # Compute Services
  
- Amazon EC2
- Amazon EC2 Auto Scaling
- Amazon Elastic Container Registry
- Amazon Elastic Container Service
- Amazon Elastic Kubernetes Service
- Amazon Lightsail
- AWS Batch
- AWS Elastic Beanstalk
- AWS Fargate
- AWS Lambda
- AWS Serverless Application Repository
- AWS Outposts
- VMware Cloud on AWS

# AWS EC2
![image](https://github.com/Ayus0721/AWS/assets/147092631/f02921d5-7c1a-4d55-8502-5728edef7b60)

- EC2 stands for Amazon Elastic Compute Cloud.
- It is a web service which provides re-sizable compute capacity in the cloud.
- It is designed to make the web scale computing easier for developers.

![image](https://github.com/Ayus0721/AWS/assets/147092631/12607679-caf8-4fd4-9a50-eeee766a1144)


# AWS EC 2 offers 5 different types of instances

![image](https://github.com/Ayus0721/AWS/assets/147092631/013a1cf1-538b-48ff-904c-bfa858dd1b02)

- ## 1. General Instances:

- For applications that require a balance of performance and cost.
- E.g email responding systems, where you need a prompt response as well as the it should be cost effective, since it doesn’t require much processing
  
-  ## 2. Compute Instances

- For applications that require a lot of processing from the CPU.
- E.g analysis of data from a stream of data, like Twitter stream

  
- ## 3. Memory Instances
  
- For applications that are heavy in nature, therefore, require a lot of RAM
- E.g when your system needs a lot of applications running in the background i.e
multitasking.

- ## 4. Storage Instances

- For applications that are huge in size or have a data set that occupies a lot of space.
- E.g When your application is of huge size

- ## 5. GPU Instances

- For applications that require some heavy graphics rendering
- E.g 3D modelling etc

# AWS Elastic Beanstalk

Elastic Beanstalk quickly deploy and manage applications in AWS without worrying about the underlying
infrastructure.

![image](https://github.com/Ayus0721/AWS/assets/147092631/7190b3d2-9b48-4711-a723-333484004420)


- Elastic Beanstalk is a service provided by AWS which is used for deploying infrastructure which consists of many AWS services
- These services include AWS S3, EC2, auto-scaling, cloud watch, Elastic load balancer, and simple notification service
- It is easy to start with Elastic Bean Stalk as you can see AWS Management Console, the command line interface or the API
- All you have to do is choose your platforms such as Node.js or Ruby and Amazon EC2 instance type.
- After the code is uploaded the AWS Elastic Beanstalk will handle the rest of the activities such as provisioning, load balancing, auto-scaling, and other activities.
- AWS does not implement any extra charges for Elastic Beanstalk as you have pay only for the AWS
  resources needed to run your applications without any hidden or upfront cost
  
![image](https://github.com/Ayus0721/AWS/assets/147092631/04ef1c1f-dca4-46f7-81d2-be2bf26fb26f)
![image](https://github.com/Ayus0721/AWS/assets/147092631/9b544d6f-eb1f-4983-a3be-e427cf7f8e3a)

# AWS Elastic Load Balancing

![image](https://github.com/Ayus0721/AWS/assets/147092631/f176605c-1cae-41dd-b5b9-1a8db6b51b28)

- ELB automatically manages the workload on your instances and distributes them to other instances in case of an
  instance failure.

- # What is Load Balancer?
- Load Balancer is a virtual machine or appliance that balances your web application load that could be Http or
  Https traffic that you are getting in. It balances a load of multiple web servers so that no web server gets
  overwhelmed.
# Types of Load Balancer
  ![image](https://github.com/Ayus0721/AWS/assets/147092631/39081e8d-7ed8-4448-9cbc-f3025409c802)

- # Application Load Balancer
- An Amazon Web Services (AWS) launched a new load balancer known as an Application load balancer
  (ALB) on August 11, 2016.
- It is used to direct user traffic to the public AWS cloud.
- It identifies the incoming traffic and forwards it to the right resources. For example, if a URL has
  /API extensions, then it is routed to the appropriate application resources.
- It is operated at Layer 7 of the OSI Model.
- It is best suited for load balancing of HTTP and HTTPs traffic.
- Application load balancers are intelligent, sending specific requests to specific web servers
- If we take an example of TESLA. We have three models of TESLA, i.e., TESLA Model X, TESLA Model S, and TESLA Model 3 and TESLAs have onboard computing facility. You will have a group of web
  servers that serve the Model X, a group of web servers that serve the Model S, and similarly for Model 3.
  We have one Load balance that checks whether the incoming traffic comes from either Model X, Model S or Model 3, and then sends it to the intended froup of servers.

- # Network Load Balancer
- It is operated at the Layer 4 of the OSI model.
- It makes routing decisions at the transport layer (TCP/SSL), and it can handle millions of requests per
  second.
- When a load balancer receives a connection, it then selects a target from the target group by using a flow hash routing algorithm.
  It opens the TCP connection to the selected target of the port and forwards the request without modifying the headers.
- It is best suited for load balancing the TCP traffic when high performance is required.
- # Classic Load Balancer
- It is operated at Layer 4 of the OSI model.
- It routes the traffic between clients and backend servers based on IP address.
- For example, an Elastic Load balancer receives a request from a client on TCP port 80, it will then routes
  the request to a specified port of backend servers. The port on which the Load Balancer routes to the target
  server will be having port number 80. The backend server will then send the requested data back to the
  ELB, which will then forward the Backend server reply to the client. According to the client's perspective,
  the request has been fulfilled by the ELB, not by the backend server.
- Classic Load balancers are legacy Elastic load balancers.

- It can also be used for load balancing the HTTP or HTTPs traffic and use layer 7-specific features, such as
  X-forwarded and sticky sessions.
- You can also use the Layer 4 load balancing for applications that rely purely on the TCP protocol.

# AWS Lambda

- AWS Lambda is used to execute backend code without worrying about the underlying architecture, you just upload the code and it runs, it’s that simple!

- # What is AWS Lambda?

- Amazon explains, AWS Lambda (λ) as a ‘serverless’ compute service, meaning the developers, don’t have
  to worry about which AWS resources to launch, or how will they manage them, they just put the code on
  lambda and it runs, it’s that simple! It helps you to focus on core-competency i.e. App Building or the code.
- Lambda is used to encapsulate Data centres, Hardware, Assembly code/Protocols, high-level languages,
  operating systems, AWS APIs.
- Lambda is a compute service where you can upload your code and create the Lambda function.
- Lambda takes care of provisioning and managing the servers used to run the code.
- While using Lambda, you don't have to worry about scaling, patching, operating systems, etc.

- # Then why not EC2 ?

![image](https://github.com/Ayus0721/AWS/assets/147092631/57cb2b9d-4e38-4b02-96e8-0d4036a37528)



- But, if your code will be running for hours, and you expect a continuous stream of requests, you should
  probably go with EC2, because the architecture of Lambda is for a sporadic kind of workload, wherein there
  will be some quiet hours and some spikes in the no. of requests as well.
- For example, logging the email activity for say a small company, would see more activity during the day
  than in the night, also there could be days when there are less emails to be processed, and sometimes the
  whole world could start emailing you! In both the cases, Lambda is at your service
- Considering this use case for a big social networking company, where the emails are never ending because
  it has a huge user base, Lambda may not be the apt choice.

- # AWS Autoscaling
- The Autoscaling feature is used to scale up and down automatically as and when required.
- The application available at AWS requires space and load and the Auto Scaling helps us by providing
  surety that there is a sufficient number of Amazon EC2 instances available to handle that load.
- You can set a limit on EC2 instances such that the number doesn’t go below this.
- The maximum numbers of EC2 instances can be set to be on a safer side.
- AWS Autoscaling ensures that your group has a sufficient amount of servers.
- Auto-scaling automatically modifies the EC2 instance as per your demand changes.
- One can access Auto Scaling by signing into the AWS Management Console.
- AWS Auto-scaling helps you if you are using language-specific APIs rather than submitting requests over
  HTTP or HTTPS Auto Scaling provides a benefit of libraries, Sample code, tutorial, and other resources
  for the development of the software. 
- It also helps us with some functions such as retrying requests, and handling error responses, making it is
  easier for the applicant to get started.


# AWS Autoscaling
- The Autoscaling feature is used to scale up and down automatically as and when required.
- The Auto Scaling helps us by providing surety that there is a sufficient number of Amazon EC2 instances available to handle that load.
- You can set a limit on EC2 instances such that the number doesn’t go below this
- The maximum numbers of EC2 instances can be set to be on a safer side.
- AWS Autoscaling ensures that your group has a sufficient amount of servers.
- Auto-scaling automatically modifies the EC2 instance as per your demand changes
- One can access Auto Scaling by signing into the AWS Management Console.
- AWS Auto-scaling helps you if you are using language-specific APIs rather than submitting requests over
  HTTP or HTTPS Auto Scaling provides a benefit of libraries, Sample code, tutorial, and other resources
  for the development of the software. 

- It also helps us with some functions such as retrying requests, and handling error responses, making it is
  easier for the applicant to get started.
# Amazon Elastic Container Service
- # AMAZON EC2 CONTAINER SERVICE (ECS)
- Amazon EC2 Container Service (Amazon ECS) is a highly scalable, fast, container management service
  that makes it easy to run, stop, and manage Docker containers on a cluster of Amazon EC2 instances.
- Amazon ECS uses Docker images in task definitions to launch containers on EC2 instances in our clusters.
- Docker is a technology that allows us to build, run, test, and deploy distributed applications that are based
  on Linux containers
  
- ECS is basically a set of APIs that turn EC2 instances into compute cluster for container management:

- 1. EC2 instances must call RegisterContainerInstance API to signal that they are ready to run containers.
- 2. Need to call RegisterTaskDefinition API to define the tasks (setting an image, command and memory for docker
  run etc.)
- 3. We use RunTask API to start a new task.
- 4. Lastly, we make a CreateService API call to run a long-running container

- # Storage and Content Delivery
- Storage

-  Amazon S3
-  Amazon Elastic Block Store
-  Amazon Elastic File System
-  Amazon FSx for Lustre
-  Amazon FSx for Windows File Server
-  Amazon S3 Glacier
-  AWS Storage Gateway

![image](https://github.com/Ayus0721/AWS/assets/147092631/54c76a2a-99b3-4291-a401-0daa4d2457a1)
![image](https://github.com/Ayus0721/AWS/assets/147092631/6dc3bb3b-26bf-43a9-a4cf-6be8980d8847)
- #  S3 AWS
- S3 stands for simple storage service, it is used for storing data in the form of objects in the AWS Cloud.
-  Amazon Simple Storage Service (S3) is a storage for the internet.
- It is designed for large-capacity, low-cost storage provision across multiple geographical regions.
- Amazon S3 provides developers and IT teams with Secure, Durable and Highly Scalable object storage.
- S3 is a safe place to store the files.
- It is Object-based storage, i.e., you can store the images, word files, pdf files, etc.
- The files which are stored in S3 can be from 0 Bytes to 5 TB.
- It has unlimited storage means that you can store the data as much you want.
- Files are stored in Bucket. A bucket is like a folder available in S3 that stores the files.
- S3 is a universal namespace, i.e., the names must be unique globally. Bucket contains a DNS address.
  Therefore, the bucket must contain a unique name to generate a unique DNS address.


- # Amazon Glacier

-  Glacier is an archiving service offered by Amazon, which offers low cost data archiving.
- Amazon Glacier is extremely low cost, secure, and durable storage service for data archiving and
  backup.
- It is designed to keep the cost low and optimized for the cold data where the retrieval time is 3 to 4 hours.
  Within Glacier, the user can reliably store the small and large amount of data.
- In AWS Glacier, there is no limit for the data user stores. Moreover, the data is secure and can access
  easily.
- Amazon Glacier helps to protect the data by redundantly storing it on multiple devices using multiple
  facilities.
- AWS Glacier has a Data Integrity Check which regularly monitors the data in the Glacier.
- It also provides security and fine-grained access to the data of the user with AWS Access Management
  policies.


![image](https://github.com/Ayus0721/AWS/assets/147092631/ab96042c-00e1-43c0-87c1-8bd455190b7f)

- # Amazon EBS
-  Amazon Elastic Block Store (EBS) is a block storage system used to store persistent data.
-  Amazon EBS is suitable for EC2 instances by providing highly available block level storage volumes.
-  It has three types of volume
1. General Purpose (SSD)
2. Provisioned IOPS (SSD)
3. Magnetic.
- # Amazon EBS Benefits
- Reliable and secure storage − Each of the EBS volume will automatically respond to its Availability
  Zone to protect from component failure.
- Secure − Amazon’s flexible access control policies allows to specify who can access which EBS volumes.
  Access control plus encryption offers a strong defense-in-depth security strategy for data.
- Higher performance − Amazon EBS uses SSD technology to deliver data results with consistent I/O
  performance of application.
- Easy data backup − Data backup can be saved by taking point-in-time snapshots of Amazon EBS
  volumes.

![image](https://github.com/Ayus0721/AWS/assets/147092631/a9c93738-3168-47bb-ba38-bc4abfafba0b)

- # What is AWS Storage Gateway?
- Amazon Storage Gateway is a modified storage service which enables the applications to use the
  AWS Cloud for storage purpose.
- Amazon SG can help for backup and archiving, cloud processing, disaster recovery, and migration.
- Standard storage protocol such as NFS, SMB, and Amazon EBS connects the applications to a gateway
  appliance using standard storage protocol.
- The gateways get connected to the storage services such as Amazon S3, Amazon Glacier, and Amazon
  EBS.
- This service benefits the user in many ways such as It includes highly-optimized data transfer mechanism.
- Low-latency data along with the on-premise local cache provides access to the data.

- # CloudFront CDN
![image](https://github.com/Ayus0721/AWS/assets/147092631/a7fde5cb-5ca2-43f1-802e-edc095143524)
- CloudFront CDN (Computer Delivery Network) is a system of distributed servers that deliver web pages
  and other web content to a user based on the geographic locations of the user, the origin of the webpage
  and a content delivery server.
- Suppose I am running the website outside the UK and I am serving the website all around the world.
- When the user wants to access my website, then they request to the web server, and users from different
  countries will have different latency.
- For example, People who live in Australia will have more latency than those who stay in India.
- South Africa has a terrible latency, but they would run internet backbone that makes quicker to connect to
  the UK.
- This is how it works with CloudFront CDN in which people spread all around the world, and they can turn
  on access to the web page, audio files, etc. in the UK.
  Snowball
- The Snowball is a way of transferring your data physically. In this Amazon sends an equipment to your
  premises, on which you can load the data. It has a kindle attached to it which has your shipping address
  when it is shipped from Amazon. When data transfer is complete on the Snowball,

  # Database
- # AWS database service includes the following services:
- Amazon Relational Database Service: It supports six (Amazon aurora ,MySQL ,PostgreSQL’s Server,Oracle, MariaDB)commonly used database engines.
- Amazon Aurora: It is a MySQL-Compatible relational database with five times performance.
- Amazon DynamoDB: It is a fast and flexible NoSQL database service.
- Amazon Redshift: It is a petabyte-scale data warehouse service.
- Amazon Elasticache: It is an in-memory cache service with support for Memcached and Redis.
- AWS Database Migration Service: It is a service that provides easy and inexpensive to migrate yourdatabases to AWS cloud.

- The Amazon Relational Database Service (RDS AWS) is a web service that makes it easier to set up, operate,
  and scale a relational database in the cloud. It provides cost-efficient, re-sizable capacity in an industry-standard
  relational database and manages common database administration tasks.
  So people often develop a misconception, when they confuse RDS with a database.
  RDS is not a database, it’s a service that manages databases, having said that, let’s discuss the databases that
- # RDS can manage as of now:
- Amazon aurora
- Mysql
- PostgreSQL
- SQL Server
- Oracle
- MariaDB
- # VPC AWS
- Amazon VPC lets you launch AWS resources in a virtual network that you define. It closely resembles a
  traditional network that you’d operate in your data centre.
- Amazon Virtual Private Cloud (VPC) helps a firm or a user by providing virtual cloud space for integrating
  the business.
- With AWS VPC one can completely monitor virtual networking environment, including the selection of
  your own IP address range, the creation of subnets, and configuration of route tables and network gateways
  these features helps a lot to integrate businesses.
- Amazon VPC allows you to logically analyse the section of Amazon Cloud where one can launch AWS
  Resources in the virtual network.
- To provide secure and easy access fourth and sixth revision to the Internet Protocol can be used.
- VPC in AWS as a logical container that separates resources you create from other customers within the
  Amazon Cloud. It is you defining a network of your own within Amazon.

![image](https://github.com/Ayus0721/AWS/assets/147092631/ac75d27b-38f0-4614-aabf-919a28a251e8)

  
-  # Subnet and Its Utility
   Subnets are like breaking a large network into sub-networks. Maintaining a smaller network is easy as
- # What Is Route Table?
- Route table can be understood as a table that contains rules for routing traffic within and outside a subnet.
  The route table is also used to add Internet Gateway to the subnet. There can be multiple route tables in a VPC.
- # What Is Internet Gateway?
- Internet Gateway allows instance to connect to the internet. It allows the user to make the subnet pubic by
  providing a route to the internet. With the help of Internet Gateway, an instance can access the internet and the
  resources outside instance can access the instance.

- # What is NAT?
- NAT - Network Address Translation.
- NAT is designed for IP address conservation. It enables private IP networks that use unregistered IP addresses to
  connect to the Internet.
- # How does NAT work?
- NAT allows a single device, such as a router, to act as an agent between the Internet and a local network, which
  means a single unique IP address is required to represent an entire group of computers to public network i.e
  Outside of their Network.
- # What is NAT Instance?
- NAT instance enable instances in the private subnet to initiate outbound traffic to the Internet but prevent the
  instances from receiving inbound traffic initiated by someone on the Internet.
-  Note: NAT Instance is a legacy, you can use NAT Gateway
- # What is NAT Gateway?
- NAT Gateway is a managed NAT service that provides better availability, higher bandwidth, and requires
less administrative effort.

- # Amazon Route 53
![image](https://github.com/Ayus0721/AWS/assets/147092631/6bb3f61f-6091-44e4-a5be-ae4321df7d21)

- Route 53 is a highly scalable and highly available Domain Name System by Amazon AWS. The name is in
  reference to the TCP and UDP’s port 53 where DNS requests are addressed.
- AWS Route 53 is a domain name system. Domain name system translates human-readable domain name
  such as www.amazon.com to machine-readable IP address such as 192.0.2.44. Amazon Route 53
  connects the request of users to the system running in AWS. This system includes Amazon
  EC2 instances, Elastic Load Balancing load balancers, or Amazon S3 buckets. Moreover, it can connect
  the user infrastructure outside of AWS. Amazon Route 53 is totally compatible with IPv6. It is designed to
  boost business in a reliable and cost-effective way. AWS Route 53 answers all the queries with the help of
  the global network of DNS servers.
  Queries of the domain are sent to the nearest DNS Server and thus it answers with the best possible
  performance. With the help of AWS management console or easy-to-use API, one can create and manage
  the public DNS. AWS Route 53 also helps us to register an available domain name. It helps in a way such that the person has to pay only for the management of domains, and the registered domains in AWS.











  
