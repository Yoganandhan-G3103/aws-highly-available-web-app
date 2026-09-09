# AWS Highly Available Web Application

This project demonstrates the design and deployment of a **highly available and scalable web application architecture on AWS**.

The application is deployed across multiple Availability Zones using an **Application Load Balancer and Auto Scaling Group** to provide high availability, fault tolerance, and automatic scaling.

## AWS Services Used

* Amazon VPC
* Amazon EC2
* Application Load Balancer (ALB)
* Auto Scaling Group (ASG)
* Internet Gateway
* NAT Gateway
* Route Tables
* Security Groups
* IAM

## Key Implementations

* Designed a custom VPC with public and private subnets across multiple Availability Zones.
* Configured Internet Gateway for internet connectivity to public resources.
* Configured NAT Gateway to provide controlled outbound internet access from private subnets.
* Created separate Security Groups for the **ALB and EC2 instances**.
* Configured an Application Load Balancer to distribute incoming traffic across EC2 instances.
* Created a Launch Template for consistent EC2 instance configuration.
* Configured an Auto Scaling Group to maintain the required number of healthy instances.
* Implemented health checks to automatically replace unhealthy EC2 instances.
* Tested application availability through the ALB DNS name.

## Project Objective

To gain hands-on experience in designing and implementing a **secure, highly available, fault-tolerant, and scalable web application architecture using AWS cloud services**.
