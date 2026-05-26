# Lab 6 – Scale and Load Balance Your Architecture

## Title

Scale and Load Balance Your Architecture

Author : S.AKASH


Reg no :212224213001


Date : 18-05-2026

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

1.Launch multiple servers.

2.Deploy the application on each server.

3.Create a load balancer.

4.Add servers to the load balancer.

5.Configure auto-scaling.

6.Test load distribution.

---

## Output Screenshots 
<img width="1918" height="962" alt="Screenshot 2026-05-16 140757" src="https://github.com/user-attachments/assets/79367f1c-c5d9-4941-bcaf-b336a1812921" />
<img width="1918" height="960" alt="Screenshot 2026-05-16 140956" src="https://github.com/user-attachments/assets/24e98a94-018b-44cf-ba0f-8700cc06362a" />
<img width="1908" height="957" alt="image" src="https://github.com/user-attachments/assets/7fb761ed-dcb6-4d1d-b6d7-eb9e7bfb2d4b" />
<img width="1913" height="911" alt="Screenshot 2026-05-16 142451" src="https://github.com/user-attachments/assets/f290bcc7-65bd-4913-8374-716b2a812753" />
<img width="1918" height="962" alt="Screenshot 2026-05-16 143526" src="https://github.com/user-attachments/assets/3fd3a78c-ee3d-4789-b8d6-e8b8cad9e603" />
<img width="1918" height="960" alt="Screenshot 2026-05-16 144036" src="https://github.com/user-attachments/assets/3e6faa23-2b5d-41fe-bca5-804bf66caa7e" />


---


## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.
