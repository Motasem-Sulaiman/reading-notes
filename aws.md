## What is an EC2 Instance?
An EC2 (Elastic Compute Cloud) instance is a virtual server in the cloud provided by Amazon Web Services (AWS). It is a fundamental building block of cloud computing on the AWS platform. EC2 instances allow you to run applications and services in a flexible and scalable manner without the need to invest in physical hardware.


## Name 2 use cases for EC2.
 - Run cloud-native and enterprise applications
 - Develop for Apple platforms


## Provide 1 reason to use ECS instead of a service such as Heroku, Digital Ocean, or Render.com.
 the level of control and flexibility it offers, allowing you to customize your application stack and take full advantage of the AWS ecosystem for security, scalability, and integration with other services.

## Where can we find EC2 on the AWS Console?
compute-->EC2
## Explain the general difference between T2 Micro and XL.
T2 Micro instances have fewer computing resources with a single vCPU and 1 GB of memory, suitable for low-traffic and lightweight workloads. On the other hand, T2 XL instances offer more computational power with multiple vCPUs and higher memory capacity, making them better suited for applications that require more processing capabilities, memory, and network performance.


## Explain a “Compute Cycle” to a non-technical friend.
 compute cycle is like a single step or unit of work that a computer performs to process data, make calculations, and generate results. Computers perform these cycles rapidly to execute tasks and perform various operations.

## What is Elastic Beanstalk?

Elastic Beanstalk is a fully managed service offered by AWS that simplifies the deployment and management of web applications. It automates the provisioning of infrastructure resources and handles tasks like capacity provisioning, load balancing, and scaling

## Describe the relationship between EC2 and Elastic Beanstalk.
EC2 provides the virtual server instances that power Elastic Beanstalk, while Elastic Beanstalk provides a managed platform that simplifies application deployment and management, utilizing EC2 instances and other AWS resources as needed.

## Name some benefits of using Elastic Beanstalk.

 - Monitoring and Logging: Elastic Beanstalk integrates with Amazon CloudWatch, providing built-in monitoring capabilities for your application. You can easily monitor various metrics, set up alarms, and access logs to gain insights into the performance and health of your application.

 - Easy Updates and Rollbacks: Elastic Beanstalk simplifies the process of updating your application. You can deploy new versions of your code without downtime, and if any issues arise, you can easily roll back to a previous version with a few clicks.

 - Multiple Language and Platform Support: Elastic Beanstalk supports various programming languages and frameworks, including Java, .NET, Node.js, Python, Ruby, and more. This flexibility allows developers to use their preferred languages and frameworks while benefiting from the managed deployment and scaling capabilities of Elastic Beanstalk.

 - Integration with Other AWS Services: Elastic Beanstalk integrates with other AWS services, such as Amazon RDS for managing databases, Amazon S3 for storing static assets, and Amazon CloudFront for content delivery. This integration enables developers to leverage additional AWS services seamlessly within their Elastic Beanstalk environment.

 - Easy Deployment: Elastic Beanstalk simplifies the deployment process by abstracting away the underlying infrastructure details. You can easily deploy your application with just a few clicks or by uploading your code. Elastic Beanstalk takes care of the rest, including resource provisioning, load balancing, and scaling.