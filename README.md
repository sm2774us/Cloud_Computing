# Cloud_Computing

# [](#AWS)AWS

## [](#basic-types-and-products-built-around-them)3 basic types of cloud services and the AWS products that are built based on them

[![](https://github.com/sm2774us/Cloud_Computing/blob/master/AWS-3-BASIC-SERVICES.PNG)](https://github.com/sm2774us/Cloud_Computing/blob/master/AWS-3-BASIC-SERVICES.PNG)

### [](#compute) Compute

Compute domain helps us in the following aspects:
* To run any application
* Control and manage server functions such as scaling and deployment
* Run event-initiated statless applications

1. **Amazon EC2**: 
 - Amazon Elastic Compute Cloud (Amazon EC2) provides scalable computing capacity in the Amazon Web Services (AWS) cloud. 
 - Using Amazon EC2 eliminates your need to invest in hardware up front, so you can develop and deploy applications faster. 
 - You can use Amazon EC2 to launch as many or as few virtual servers as you need, configure security and networking, and manage storage.  
 - Amazon EC2 enables you to scale up or down to handle changes in requirements or spikes in popularity, reducing your need to forecast traffic.

2. **AWS Elastic Beanstalk (PaaS - Platform as a Service)**:
 - AWS Elastic Beanstalk is an easy-to-use service for deploying and scaling web applications and services developed with Java, .NET, PHP, Node.js, Python, Ruby, Go, and Docker on familiar servers such as Apache, Nginx, Passenger, and IIS. 
 - You can simply upload your code and Elastic Beanstalk automatically handles the deployment, from capacity provisioning, load balancing, auto-scaling to application health monitoring. 
 - At the same time, you retain full control over the AWS resources powering your application and can access the underlying resources at any time. 
 - There is no additional charge for Elastic Beanstalk - you pay only for the AWS resources needed to store and run your applications.

3. **AWS Lambda (FaaS - Function as a Service)**:
 - AWS Lambda lets you run code without provisioning or managing servers. You pay only for the compute time you consume.
 - With Lambda, you can run code for virtually any type of application or backend service - all with zero administration.
 - Just upload your code and Lambda takes care of everything required to run and scale your code with high availability. 
 - You can set up your code to automatically trigger from other AWS services or call it directly from any web or mobile app.

4. **AWS Auto Scaling**:
 - AWS Auto Scaling monitors your applications and automatically adjusts capacity to maintain steady, predictable performance at the lowest possible cost. 
 - Using AWS Auto Scaling, it’s easy to setup application scaling for multiple resources across multiple services in minutes.

5. **Amazon Lightsail**:
 - Lightsail is an easy-to-use cloud platform that offers you everything needed to build an application or website, plus a cost-effective, monthly plan.

[![](https://github.com/sm2774us/Cloud_Computing/blob/master/AWS-1-COMPUTE-SERVICE.PNG)]
(https://github.com/sm2774us/Cloud_Computing/blob/master/AWS-1-COMPUTE-SERVICE.PNG)

### [](#storage) Storage

Storage domain helps us in the following aspects:
* It holds all the information which the applications use
* They additionally support archival compliance requirements
* Object, file and block storage are the popular storage services

1. **Amazon S3 (Object Storage)**
 - Amazon Simple Storage Service (Amazon S3) is an object storage service that offers industry-leading scalability, data availability, security, and performance. 
 - This means customers of all sizes and industries can use it to store and protect any amount of data for a range of use cases, such as websites, mobile applications, backup and restore, archive, enterprise applications, IoT devices, and big data analytics. 
 - Amazon S3 provides easy-to-use management features so you can organize your data and configure finely-tuned access controls to meet your specific business, organizational, and compliance requirements. 
 - Amazon S3 is designed for 99.999999999% (11 9's) of durability, and stores data for millions of applications for companies all around the world. 

2. **Amazon S3 Glacier (For Archiving)**
 - Amazon S3 Glacier and S3 Glacier Deep Archive are a secure, durable, and extremely low-cost Amazon S3 cloud storage classes for data archiving and long-term backup. 
 - They are designed to deliver 99.999999999% durability, and provide comprehensive security and compliance capabilities that can help meet even the most stringent regulatory requirements. 
 - Customers can store data for as little as $1 per terabyte per month, a significant savings compared to on-premises solutions. 
 - To keep costs low yet suitable for varying retrieval needs, Amazon S3 Glacier provides three options for access to archives, from a few minutes to several hours, and S3 Glacier Deep Archive provides two access options ranging from 12 to 48 hours.

3. **Amazon Elastic Block Store (EBS) (Drive Attachment for EC2 instances)**
 - Amazon Elastic Block Store (EBS) is an easy to use, high performance block storage service designed for use with Amazon Elastic Compute Cloud (EC2) for both throughput and transaction intensive workloads at any scale. 
 - A broad range of workloads, such as relational and non-relational databases, enterprise applications, containerized applications, big data analytics engines, file systems, and media workflows are widely deployed on Amazon EBS.
 
4. **Amazon Elastic File System (EFS) (File Share for EC2 instances)**
 - Amazon Elastic File System (Amazon EFS) provides a simple, scalable, fully managed elastic NFS file system for use with AWS Cloud services and on-premises resources. 
 - It is built to scale on demand to petabytes without disrupting applications, growing and shrinking automatically as you add and remove files, eliminating the need to provision and manage capacity to accommodate growth.

### [](#networking) Networking

