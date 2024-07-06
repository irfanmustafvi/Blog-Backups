---
title: "Expert Tips for Cloud Practitioner Certification | Session 4"
seoTitle: "Cloud Practitioner Certification Tips - Session 4"
datePublished: Thu Jul 04 2024 19:50:55 GMT+0000 (Coordinated Universal Time)
cuid: cly7om745000009mggqg2dyw7
slug: expert-tips-for-cloud-practitioner-certification-session-4
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1720119146130/0df69719-bf0f-4f27-a16b-4e36b2cefb41.jpeg
tags: aws, devops, linkedin, aws-certified-solutions-architect-associate, aws-cloud-practitioner, besa

---

### 1.Introduction

This session from the Cloud Practitioner Track focuses on Domain 4. It covers important topics like metrics, monitoring, optimizing cloud costs, and the skills needed for technical professionals. It highlights the importance of monitoring performance, resource usage, system health, and security. The session introduces AWS CloudWatch as a tool for monitoring system and business metrics and explains how alarms can trigger automated actions based on set metric thresholds.

### **2.Monitoring Services and Observability Status**

* Monitoring plays a crucial role in overseeing systems to detect problems in real-time. Within AWS, monitoring and observability are separate but complementary concepts that ensure the integrity and efficiency of cloud services. Monitoring focuses on identifying problems, while observability provides a deeper understanding of those issues, enabling root-cause analysis. This is especially valuable for complex distributed systems, where pinpointing the source of problems can be challenging. For optimal cloud operations, both monitoring and observability are essential, ensuring the health and performance of AWS cloud services. Monitoring involves collecting and analyzing data to understand the state of the systems. It helps detect and alert on specific conditions, such as high CPU usage or failed requests. AWS CloudWatch is a primary tool for monitoring, providing logs, metrics, and alarms.
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1720120113437/a2f6369a-b461-4c74-b527-c36e30810ed2.jpeg align="center")

* Observability goes beyond basic monitoring. It offers a deeper understanding of system behavior by analyzing logs, metrics, and traces. This helps user determine not only "what" happened but also "why" it happened. This leads to more efficient problem-solving and system optimization. AWS X-Ray works with CloudWatch by providing tracing capabilities, making the flow of requests through your applications clear.
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1720122346330/82f3f022-b306-4a03-9779-937622109119.jpeg align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1720122378171/aec2f17a-6d96-4e83-b7d9-157d01f46f73.jpeg align="center")

### **3.Types of Metrics and CloudWatch Dashboard with Alarms**

* System metrics are measurable data that show how well a system's infrastructure is performing. This includes servers, databases, and load balancers. They track things like CPU workload, memory usage, disk activity, and network traffic. These metrics are crucial for keeping applications running smoothly, as they provide insights into the system's performance and its ability to meet application needs. By monitoring these metrics, you can quickly spot issues, optimize resource use, ensure smooth operation, and prevent disruptions. For example, high CPU usage might indicate a need to scale up or tweak the application to handle the load better. Monitoring system metrics helps you make informed decisions to keep applications healthy.
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1720121646708/992bbe6b-7a1b-4ed5-980d-f06693b71b82.jpeg align="center")

* Business metrics are essential for tracking the operational performance of cloud applications. They provide insights into how well the cloud infrastructure supports business goals, by monitoring key indicators like sales, user engagement, and service availability. For example, an e-commerce website might track website traffic, conversion rates, and transaction volumes to ensure optimal performance and customer satisfaction. By analyzing these metrics, businesses can make data-driven decisions to enhance services, optimize resources, and stay competitive. Focusing solely on system metrics does not paint a complete picture of business operations, highlighting the significance of considering business metrics as well.
    
* AWS offers "CloudWatch," a service that enables users to monitor their AWS services (including RDS and EFS) by tracking and collecting metrics (variable measurements over time, like CPU usage). With CloudWatch, users can define alarms to automate actions (like resource scaling) based on these metrics. While AWS handles infrastructure monitoring for managed services like RDS and EFS, users can still monitor performance and set customized alarms via CloudWatch. CloudWatch also provides pre-built and customizable dashboards where users can review and analyze their metrics in a centralized location.
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1720121725195/21a16997-c1d3-46a1-a94e-2fc0f691641e.jpeg align="center")

### **4.Cost Considerations**

* Monitoring costs vary between standard and custom metrics in CloudWatch. Standard metric data collection is usually free for most services, with a few exceptions where charges may apply. These metrics are automatically enabled. Custom metrics are not free and incur charges based on several factors:
    
    * How often the metrics are collected?
        
    * How long the metrics are stored?
        
    * How much data is sent to CloudWatch?
        
    * The number of requests sent to CloudWatch's API
        
    * The amount of time the data is retained
        

* Optimized Monitoring Cost Management
    
    * **Store logs in Amazon S3**: Logs can be kept indefinitely in S3, giving you full control over retention periods.
        
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1720122028542/d572c835-a768-4dc6-ae0e-a525cf0061f0.jpeg align="center")
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1720122212928/76148b22-ebe9-457c-a379-b4bb5e36182e.jpeg align="center")
    
    * **Set up lifecycle policies**: Manage retention periods and associated costs for S3-stored logs using lifecycle policies.
        
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1720122085208/654fa81a-8e42-4e42-9ebe-1ebd7045747b.jpeg align="center")
    
    * **Tag your resources**: Tagging resources helps track and allocate costs. Use AWS Config rules to ensure all resources are properly tagged.
        

### **5.Additional Resources**

* Mention the availability of workshop studios for hands-on practice. Workshop studios are available for practical experience, and all participants are encouraged to use these resources for learning. Additionally, workshop studios help in understanding metrics collection and actions.
    
* Encouraging viewers to use and understanding AWS tools and services, emphasizing the value of practical experience in addition to theoretical knowledge. It highlights AWS Educate and Cloud Quest as resources for free hands-on labs and gamified learning experiences, respectively. The speaker encourages viewers to engage with these platforms to gain confidence and prepare for AWS certification exams.
    
* Exam Tips are provided for the benefit of viewers. The instructors suggested studying with a colleague or friend. And they recommended thorough review of practice test answers. They also highlighted the importance of understanding correct answers for added learning benefits.
    
* At the end of the session, a practice quiz is launched to enhance participants' understanding. This is highly appreciated by the viewers and also increases audience engagement.
    

### 6\. Summary

This session from the Cloud Practitioner Track covers important aspects of Domain 4, focusing on metrics, monitoring, and optimizing cloud costs with AWS tools like CloudWatch and X-Ray. It discusses the necessity of monitoring system performance and resource usage, understanding system behavior, and leveraging business and system metrics to maintain optimal cloud operations. Cost considerations for monitoring services are addressed, along with strategies for efficient cost management. Hands-on practice through workshop studios and AWS learning resources are encouraged, with exam tips and a practice quiz offered to enhance understanding and engagement.