---
title: "Master Resilient Architecture: Solutions Architect Track | Session 6"
seoTitle: "Resilient Architecture: Solutions Architect "
datePublished: Sat Jul 06 2024 12:00:10 GMT+0000 (Coordinated Universal Time)
cuid: clya2oj1d000g09mmbmqr4nmv
slug: master-resilient-architecture-solutions-architect-track-session-6
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1720258870456/1bdc1e3d-b74c-4655-8ca3-a3a083d807ea.jpeg
tags: aws, devops, aws-certified-solutions-architect-associate

---

### 1\. Introduction About Session

In the Solutions Architect Track, it's crucial to design with resilience in mind. All architectures, regardless of size or type, should be built to withstand challenges. This session teaches how to enhance resilience in designs through a roleplaying exercise that explores practical methods for different types of architectures.

* **Greetings to Audience**
    
* **Focus on Architecting for Resilience:** Learn about building resilient architectures, discuss services and strategies for resilience, and engage in a roleplay to apply these concepts.
    
* **Understanding High Availability and Disaster Recovery:** Explanation of high availability and its significance, differentiation between high availability and disaster recovery, and the impact of resilience on customer experience and business continuity.
    
* **Building Resilience at Every Layer:** The necessity of resilience in infrastructure, applications, and databases can be achieved through techniques like load balancing, auto-scaling, and replication, with examples of AWS services that support resilient architectures.
    

### 2\. Importance of Building Resilience

This session emphasizes the importance of building resilient cloud architectures. It guides through managing multiple regions, addressing database performance issues, and implementing disaster recovery strategies. AWS Aurora Global databases are showcased, highlighting features such as asynchronous replication and read replicas. Furthermore, this explores various disaster recovery approaches based on Recovery Point Objective (RPO) and Recovery Time Objective (RTO), emphasizing the importance of selecting the best strategy based on workload criticality and acceptable downtime. 

* **Database Bottlenecks and Replication:** Discusses handling multiple regions and database bottlenecks, introduces AWS Aurora Global databases with asynchronous replication, and explains read replicas and write forwarding features.
    
* **Disaster Recovery Strategies:** Outlines four disaster recovery strategies—backup and restore, pilot light, warm standby, and active-active—explains RPO and RTO concepts and their impact on strategy selection, and emphasizes the cost implications of different strategies.
    
* **Load Balancing and Scaling:** Covers AWS load balancers (application, network, and gateway), explaining their role in traffic distribution and high availability, and discusses integration with third-party firewall appliances for security.
    
* **Deployment Strategies and Best Practices:** Introduces blue-green and canary deployment strategies for updates without downtime, highlights the AWS Well-Architected Framework's reliability and operational excellence pillars, and recommends using the AWS Well-Architected Tool for architectural review and best practices.
    

### 3\. Autoscaling

It addresses questions about utilizing a mix of reserved, on-demand, and spot instances in auto-scaling groups, as well as capturing data before instance termination. 

* **Auto Scaling Groups:** Understanding automated scaling, using reserved instances and savings plans, and mixing different instance types and purchase options.
    
* **Launch Templates :** Setting up launch templates through the console or YAML/JSON involves specifying instance preferences and attributes and including these templates in cloud formation templates.
    
* **Capacity Rebalancing and Lifecycle Hooks:** Replacement instances before termination, automation during scale-in and scale-out events, and using Lambda functions for pre and post-tasks.
    
* **Measuring Resilience :** Key Performance Indicators (KPIs) for resilience include understanding MTBF, MTTR, redundancy, scalability, and the importance of security and availability in architecture.
    

### 4\. AWS Free Resources and Whizlabs

Here also highlighted about the AWS free account, sandbox environments, and resources for practicing AWS services. It explains the salient features and utilization of AWS console, use free services, and the benefits of sandbox environments provided by training providers like Whizlabs. It explains in detail about the practice using these resources, the importance of de-provisioning to avoid costs, and offers a discount on a starter kit for extended learning.

* **AWS Free Account and Sandbox Environments :** Explains AWS free services and sandbox access, details on signing in and using the AWS console, and emphasizes the need for a credit card for an AWS free account.
    
* **Accessing AWS Services :** Lists services available in the free tier and sandbox, guides on creating S3 buckets and static websites, and encourages hands-on practice with available services.
    
* **Sandbox Access and Usage:** Discusses how to access sandboxes, clarifies that sandbox access is for practice and not the full platform, and advises against storing personal data in shared environments.
    
* **Structured Learning and Hands-On Labs :** Introduces a 12-week workshop for structured learning, provides instructions for basic and advanced modules, and highlights the importance of de-provisioning resources after use.
    
* **Starter Kit and Learning Resources :** Offers a discount on the starter kit with extensive resources, including access to courses, labs, and other cloud training, and emphasizes the value of practice for knowledge retention.
    
* **Group Mentoring and Roadmaps :** Mentions group mentoring sessions and cloud learning plans, provides roadmaps from industry experts for guided learning, and encourages feedback to improve future learning sessions.
    

### 5\. Learn with QnA

Here are some questions to focus on the main themes discussed, such as resilience, disaster recovery, and career development in cloud computing.

**Q1. What are the key components to ensure resilience in a cloud architecture?**

**ANSWER:** The key components for ensuring resilience in cloud architecture, focusing on the Solutions Architect Track. It emphasizes the importance of designing workloads to withstand component failures, using redundant data centers, and implementing strategies like load balancing and auto-scaling. The discussion also touches on the significance of disaster recovery planning and the use of AWS services to achieve high availability and fault tolerance.

* **Architect for resilience:** The importance of building simple to complex resilient architectures lies in ensuring that both in-house and customer-facing applications are resilient.
    
* **Achieving resiliency:** Focusing on how to attain resiliency in any architecture by discussing services that aid in resilience.
    
* **Measuring resilience:** Using KPIs like MTBF, MTTR, and redundancy levels helps understand the impact of resilience on business and finances.
    
* **Implementing resilience:** Involving developers, DevOps, SREs, and database experts, taking a holistic approach to implement changes at all layers.
    

**Q2. How does AWS support disaster recovery and what are the best practices?**

**ANSWER**: Here emphasizes the importance of resilience in architecture, ensuring systems are robust against disruptions. The session includes a roleplay between a customer and an AWS consultant, exploring scenarios and strategies for maintaining operations during failures.

* **Architecting for resilience:** The importance of building resilient systems cannot be overstated, as disruptions can significantly impact business operations and customer trust, leading to financial implications due to downtime.
    
* **Disaster Recovery strategies:** High availability and redundancy in design, disaster recovery planning and implementation, and the use of backups, snapshots, and cross-region replication**.**
    
* **AWS services for resilience :** Elastic Load Balancers and Auto Scaling for infrastructure, Aurora Global Databases and DynamoDB Global Tables for data, and CloudFormation templates for quick environment setup.
    
* **Operational excellence and reliability:** Using the AWS Well-Architected Framework as a guide, design principles for building resilient workloads and tools for architectural review and risk assessment are essential.
    

**Q3. Can you explain the difference between high availability and disaster recovery in AWS?**

**ANSWER:** The session provides a detailed explanation of high availability and disaster recovery in AWS, particularly in the context of a Solutions Architect Track discussion.

* **High Availability (HA)** in AWS is about designing systems that are robust and can handle different types of failures without downtime. It involves redundancy, such as deploying resources across multiple Availability Zones (AZs) to ensure there’s no single point of failure. HA strategies include using load balancers to distribute traffic evenly across servers and implementing auto-scaling to adjust resources automatically based on demand.
    
* **Disaster Recovery (DR)**, on the other hand, is about having a plan to recover from major incidents that cause significant service disruptions, like a data center going down. DR strategies in AWS may involve setting up a secondary site in a different region (warm standby), where a minimal version of the environment is always running and can be scaled quickly if needed. It also includes taking regular backups and having replication in place to minimize data loss (Recovery Point Objective or RPO) and reduce the time it takes to restore service (Recovery Time Objective or RTO).
    
* Moreover, HA focuses on continuous operation through redundancy and failover mechanisms, while DR is about having a plan and infrastructure to recover from catastrophic events. Both are crucial for maintaining service reliability and availability in AWS.
    

**Q4. How does load balancing contribute to a resilient AWS architecture?**

**ANSWER:** Load balancing plays a crucial role in creating a resilient AWS architecture by distributing incoming application traffic across multiple targets, such as EC2 instances, containers, and IP addresses. It enhances the system’s ability to handle traffic surges and ensures that no single server bears too much load, which can prevent outages and reduce latency. 

**Key Contributions**:

* **Prevents Overloading**: By evenly distributing traffic, load balancers prevent any single resource from being overwhelmed, which is essential for maintaining application performance and availability.
    
* **Supports Auto Scaling**: Load balancers work in conjunction with Auto Scaling to adjust the number of instances according to the load, ensuring that the architecture can scale up or down as needed.
    
* **Facilitates Fault Tolerance**: In the event of a failure, the load balancer can redirect traffic to healthy instances, minimizing the impact on users and maintaining service continuity.
    

**Q5. What role does auto scaling play in maintaining application performance and availability?**

**ANSWER:** Auto scaling plays a crucial role in maintaining application performance and availability by automatically adjusting the number of compute resources, such as servers, in response to varying load conditions. It ensures that the application has enough capacity to handle the workload without over-provisioning and incurring unnecessary costs. Here’s how it contributes:

* **Dynamically manages capacity**: Auto scaling monitors your application’s load and automatically scales compute resources up or down based on predefined rules and metrics, such as CPU utilization or network traffic.
    
* **Improves performance**: By providing the right amount of resources needed to handle the application’s load, auto scaling helps maintain optimal performance levels, preventing slowdowns or crashes during peak times.
    
* **Enhances availability**: It reduces the risk of application downtime by ensuring that there are always enough resources to serve the incoming traffic, even during unexpected surges.
    
* **Cost-effective**: Auto scaling can help reduce costs by automatically removing excess capacity during low-traffic periods, ensuring you only pay for what you need.
    

**Q.6 How does the AWS Well-Architected Framework guide the design of resilient systems?**

**ANSWER:** The AWS Well-Architected Framework provides a set of principles and best practices to help design and operate reliable, secure, efficient, and cost-effective systems in the cloud. For resilience, it emphasizes the importance of:

* **Automatic Recovery**: Designing systems that can automatically recover from failures.
    
* **Testing Recovery Procedures**: Regularly testing how a system recovers from different failure scenarios.
    
* **Scaling Horizontally**: Adding more resources to handle increased load instead of upgrading the capacity of individual resources.
    
* **Stop Guessing Capacity**: Monitoring demand and system usage to make informed decisions about capacity needs.
    

### 6\. Summary

This article focuses on designing resilient cloud architectures in the Solutions Architect Track. Key topics include the importance of resilience, high availability vs. disaster recovery, AWS services and strategies for resilience, auto scaling, and the AWS Well-Architected Framework. The content covers practical methods, roleplaying exercises, and best practices for maintaining application performance and availability. It also highlights using AWS resources and sandbox environments for hands-on practice and closes with a Q&A section addressing core resilience components, load balancing, and disaster recovery strategies.