# Lab 6 – Scale and Load Balance Your Architecture

## Title

Scale and Load Balance Your Architecture

Author : SAVISH R

Reg no :212224230257

Date :19-03-2026

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


1.Logged in to the AWS Management Console and opened Amazon EC2.

2.Reviewed the existing EC2 architecture created in the previous labs.

3.Created a Launch Template with AMI, instance type, and security group configuration.

4.Created an Auto Scaling Groups using the launch template and set the minimum, maximum, and desired instances.

5.Created an Application Load Balancer to distribute incoming traffic.

6.Attached the Auto Scaling Group to the target group of the load balancer.

7.Configured scaling policies based on CPU usage using Amazon CloudWatch alarms.

8.Tested the architecture by generating traffic and observed automatic scaling and load balancing.
---

## Output Screenshots 


<img width="1916" height="1032" alt="cc 6a" src="https://github.com/user-attachments/assets/e37e8326-f164-4e36-99e5-0c5e181e2b2b" />

<img width="1918" height="1026" alt="cc 6c" src="https://github.com/user-attachments/assets/25179247-5cb8-40e7-9205-328973d81fc1" />

<img width="1916" height="876" alt="cc 6e" src="https://github.com/user-attachments/assets/31f3ba4b-58bb-4f6d-a13a-c4335ca66e1c" />

<img width="1915" height="682" alt="cc 6f" src="https://github.com/user-attachments/assets/4fc1c5f4-ee92-45e6-a620-5c1240ce6a6b" />

<img width="1918" height="1023" alt="cc 6g" src="https://github.com/user-attachments/assets/06716c4e-a2a4-4c72-a77c-b267aa7b3822" />



---


## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.
