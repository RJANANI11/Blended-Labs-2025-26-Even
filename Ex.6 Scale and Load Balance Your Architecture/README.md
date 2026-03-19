# Lab 6 – Scale and Load Balance Your Architecture

## Title

Scale and Load Balance Your Architecture

Author : JANANI R  
Reg no : 212224040126   
Date :20-03-26

---

## Objective

The objective of this lab is to understand how to design a scalable and highly available architecture on AWS using Auto Scaling and Elastic Load Balancing. This experiment focuses on distributing incoming traffic across multiple EC2 instances, automatically scaling resources based on demand, and validating fault tolerance.

---

## Prerequisites

* Basic knowledge of Amazon EC2 and VPC
* Completion of previous labs (IAM, EC2, EBS, Database Server)
* AWS Academy Lab access
* Stable internet connection

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Elastic Load Balancer (ELB / ALB)
* Auto Scaling Groups (ASG)
* Amazon CloudWatch

---

## Tasks Performed

### Task 1: Review Existing Architecture

Students review the existing EC2-based application architecture created in previous experiments.

### Task 2: Create a Launch Template

Students create a launch template that defines the EC2 instance configuration including AMI, instance type, security group, and user data.

### Task 3: Create an Auto Scaling Group

Students create an Auto Scaling Group using the launch template and configure minimum, maximum, and desired instance capacity.

### Task 4: Configure an Application Load Balancer

Students create an Application Load Balancer and configure target groups for routing traffic to EC2 instances.

### Task 5: Register Auto Scaling Group with Load Balancer

Students attach the Auto Scaling Group to the target group of the load balancer.

### Task 6: Configure Scaling Policies

Students configure scaling policies based on CPU utilization using Amazon CloudWatch alarms.

### Task 7: Test Load Balancing and Scaling

Students test the setup by generating traffic and observing automatic scaling and load distribution.

---

## Workflow (To be filled by Student)

Describe step-by-step how you performed this experiment in your own words.
1.Create an Amazon Machine Image (AMI) from a running instance.

2.Create a load balancer.

4.Create a launch template and an Auto Scaling group.

5.Automatically scale new instances 

6.Create Amazon CloudWatch alarms and monitor performance of your infrastructure.


## Output Screenshots 
<img width="1917" height="1018" alt="Screenshot 2026-03-20 001559" src="https://github.com/user-attachments/assets/be4a300b-1344-4121-93a2-887d2f53791a" />
<img width="1918" height="990" alt="Screenshot 2026-03-20 002713" src="https://github.com/user-attachments/assets/2f2028ca-5529-4c18-9eb1-f8c3c0eeb5d8" />
<img width="1919" height="1133" alt="Screenshot 2026-03-20 004258" src="https://github.com/user-attachments/assets/b0dcf690-c7d1-451b-ab4d-6e5c44f9970f" />
<img width="1913" height="1012" alt="Screenshot 2026-03-20 005624" src="https://github.com/user-attachments/assets/372009b2-8b9d-46f0-80a0-d90a248c85a9" />






## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.
