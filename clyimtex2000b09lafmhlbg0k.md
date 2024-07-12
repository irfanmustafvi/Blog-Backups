---
title: "Solutions Architect Track - Network Observability | Session 8"
datePublished: Fri Jul 12 2024 11:46:00 GMT+0000 (Coordinated Universal Time)
cuid: clyimtex2000b09lafmhlbg0k
slug: solutions-architect-track-network-observability-session-8
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1720778480671/b75e4d20-94fa-4305-b3b9-a882816749de.jpeg
tags: aws, devops, 2articles1week, aws-certified-solutions-architect-associate, devops-articles, aws-cloud-practitioner, aws-cloud-project-bootcamp

---

### 1\. Introduction and Overview:

This session is about network observability for the Solutions Architect Track. It explains why network observability is important, the difference between monitoring and observability, and the AWS services that help with network observability.

* **<mark>Role Play and Network Observability</mark>:** Role play between an AWS technical person and a customer, discussing network complexity and observability needs, followed by an introduction to network observability concepts.
    
* **<mark>AWS Network Observability Services</mark>:** Explanation of AWS network components like VPC and subnets, the importance of understanding AWS-specific network modifications, and an introduction to AWS services for network observability.
    
* **<mark>Monitoring vs. Observability</mark>:** Differences between monitoring and observability: Monitoring is reactive, while observability is proactive. Observability is crucial for root cause analysis.
    
* **<mark>Components of Network Observability</mark>:** Collection of metrics and logs, monitoring with alarms and dashboards, and analysis with traffic mirroring and reachability analyzer.
    

### 2\. Collection of Data & Analysis

The network observability is focusing on collecting and analyzing network data. It explains near real-time data collection, customization options, and using AWS services for monitoring and logging.

* **<mark>Near real-time data collection</mark>:** Data collection is near real-time with a slight delay, has no performance impact on the system, and is aggregated every 1 minute.
    
* **<mark>Customization options</mark>:** Network observability focuses on near real-time data collection with customizable options for log formats, field selection, and enrichment using AWS services, all without impacting system performance.
    
* **<mark>Boundary VPC concept</mark>:** Centralizes communication for monitoring, simplifies control and monitoring, and is a custom term, not an AWS service.
    
* **<mark>Creating and managing flow logs</mark>:** Steps to create flow logs in AWS include using CloudWatch Logs for data storage and creating roles and policies for permissions.
    

### 3\. Network Logs in Observability

Network Observability is more focusing on AWS services like flow logs, traffic mirroring, and visualization tools. It explains how to capture, analyze, and visualize network traffic for better monitoring and troubleshooting.

* **<mark>Understanding flow logs</mark>:** Use the documentation and enrich the logs, and proper flow of log structure can be applied.
    
* **<mark>Integration and visualization</mark>:** Using Kibana, you can create dashboards to identify top IP sources and destinations and build visualizations for analysis.
    
* **<mark>Traffic mirroring</mark>:** Traffic mirroring involves replicating packets for analysis, which is useful for content inspection and threat monitoring.
    
* **<mark>Filtering and targeting</mark>:** Customizing data capture involves using filters to focus on specific traffic and choosing options for target instances and load balancing.
    
* **<mark>Practical demonstration</mark>:** Setting up traffic mirroring in AWS involves using TCP dump for packet capture and creating and managing mirror sessions.
    

### 4\. Usage of AWS Services

Here, various AWS services and their applications in different scenarios are elaborated, focusing on solutions for complex analytics, security models, content delivery, and network scaling.

1. **<mark>AWS Services for Analytics</mark>**
    
    * Amazon Redshift for complex queries
        
    * DynamoDB not suitable for financial data
        
    * Importance of analytical capabilities
        
2. **<mark>Security Models in AWS</mark>**
    
    * Use of security groups and NACLs
        
    * Compliance with regulations
        
    * Importance of logging and monitoring
        
3. **<mark>Content Delivery Solutions</mark>**
    
    * CloudFront for static content delivery
        
    * Route 53 as a DNS service
        
    * Other services like S3 Transfer Acceleration
        
4. **<mark>Network Scaling Solutions</mark>**
    
    * AWS Transit Gateway for centralized management
        
    * Comparison with AWS Direct Connect
        
    * Importance of effective network scaling
        

### 5\. QnA Challenges

Here are challenges to clear the theme of session and that might consider asking about the Network Observability.

**Q.1 What are the main differences between network monitoring and network observability?**

**ANSWER:** Network monitoring and network observability are distinct concepts as: **<mark>Network Monitoring</mark>**: Network monitoring is a reactive approach that focuses on identifying issues after they occur and involves setting up alarms and dashboards to track metrics.

**<mark>Network Observability</mark>**: Network observability is a proactive approach that aims to understand why issues occur and prevent them in the future by combining monitoring with root cause analysis and anomaly detection.

**Q.2 Which AWS services are highlighted for network observability, and what are their specific use cases?**

**AMSWER:** AWS services highlighted for network observability and their specific use cases, those help collectively in monitoring, analyzing, and optimizing network performance and security: like following services,

1. **<mark>VPC Flow Logs</mark>**: VPC Flow Logs capture IP traffic information within a VPC and are useful for identifying top traffic sources and destinations.
    
2. **<mark>AWS Network Manager</mark>**: AWS Network Manager manages and monitors global networks, making it ideal for organizations with multiple AWS accounts and regions.
    
3. **<mark>Network Access Analyzer</mark>**: Analyzes network configurations to help identify potential security risks and misconfigurations.
    
4. **<mark>Traffic Mirroring</mark>**<mark>: </mark> Mirrors network traffic to analysis appliances, useful for deep packet inspection and troubleshooting.
    
5. **<mark>CloudWatch</mark>**: Collects and monitors metrics and logs by providing dashboards, alarms, and insights for network performance and security.
    

**Q.3 How can network observability help in troubleshooting network issues and optimizing performance?**

**ANSWER:** Network observability can significantly aid in troubleshooting and optimizing performance by providing detailed insights into network behavior and traffic patterns. Here are some key points from the video:

1. **<mark>Troubleshooting and Performance Issues</mark>**: Helps identify and resolve network problems by monitoring traffic and performance metrics, providing visibility into network traffic for quick identification of anomalies and issues.
    
2. **<mark>Cost Optimization</mark>**: Monitors traffic to understand cost implications, optimize network usage, and identify high-traffic sources to manage and control costs.
    
3. **<mark>Security and Compliance</mark>**: Enhances network security by monitoring for unusual traffic patterns and potential threats, while ensuring compliance with security policies by tracking network access and behavior.
    
4. **<mark>Scalability and Network Management</mark>**: Assists in planning network scaling and segmentation based on traffic analysis, providing insights for upgrading network infrastructure to meet performance demands.
    

**Q.4 What are some common network observability challenges?**

**ANSWER:** Here are some common network observability challenges. These challenges require effective tools and strategies to ensure network reliability, security, and cost-efficiency.

1. **<mark>Complexity of expanding networks</mark>:** Increasing workloads and accounts, expanding into other regions, and managing on-premises and cloud connections.
    
2. **<mark>Monitoring and troubleshooting</mark>:** Ensuring reliability and security involves identifying misconfigurations in security groups or network ACLs and handling high network charges.
    
3. **<mark>Understanding network traffic</mark>:** Identifying top traffic sources, analyzing traffic patterns and protocols, and detecting anomalous behavior.
    
4. **<mark>Cost optimization</mark>:** Monitoring traffic to control costs and understanding cost contributions from network traffic.
    

**Q.5 How can I improve my network's observability on AWS?**

**ANSWEER**: To enhance network’s observability on AWS, follow these steps. These steps will help ensure network is reliable, secure, and cost-effective.

1. **<mark>Enable VPC Flow Logs</mark>**: Capture IP traffic information at the VPC, subnet, or instance level to monitor who is talking to whom and what kind of traffic is being transferred.
    
2. **<mark>Use AWS CloudWatch</mark>**: Set up metrics and logs to monitor network performance, create alarms for threshold breaches, and use dashboards for a comprehensive view.
    
3. **<mark>Analyze Traffic</mark>**: Utilize services like Traffic Mirroring, Reachability Analyzer, and CloudWatch Logs Insights to understand network behavior and identify anomalies.
    
4. **<mark>Implement Security Measures</mark>**: Monitor network security by identifying unusual traffic patterns, potential DDoS attacks, and unauthorized access attempts.
    
5. **<mark>Optimize Costs</mark>**: Monitor and analyze network traffic to understand cost implications and optimize resource usage.
    

### 6\. Summary

> The article discusses network observability within the AWS ecosystem, covering its importance, differences from network monitoring, and AWS services that facilitate network observability. It details the collection and analysis of network data, focusing on near real-time data collection, flow logs, and traffic mirroring. The document also explores AWS services for analytics, security, content delivery, and network scaling, and includes a Q&A section addressing challenges and best practices for improving network observability on AWS.