
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
  
