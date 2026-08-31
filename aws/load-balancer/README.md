# Application Load Balancer

This section documents the Application Load Balancer (ALB) implementation completed as part of the **AWS Auto Scaling & Cost Optimization using Power BI** project.

The Application Load Balancer was used to distribute incoming application traffic across the available EC2 instances and support the scalable application architecture.

---

## Objectives

- Create and configure an Application Load Balancer.
- Create and configure a Target Group.
- Register EC2 instances with the Target Group.
- Configure the ALB to route application traffic.
- Verify that the application is accessible through the load balancer.

---

## Load Balancer Implementation

### 1. Target Group

A Target Group was configured to manage the EC2 instances that receive traffic from the Application Load Balancer.

![Target Group](target-group.png)

---

### 2. ALB Configuration

The Application Load Balancer was created and configured to work with the target group and EC2 infrastructure.

![ALB Created Configuration](alb-created-configuration.png)

---

### 3. ALB Working

The Application Load Balancer was verified as operational and successfully serving application traffic.

![ALB Working](alb-working.png)

---

## Implementation Summary

The Application Load Balancer provides the traffic distribution layer of the project.

The implementation includes:

- Application Load Balancer
- Target Group
- EC2 target registration
- Traffic routing
- Application availability verification

The ALB works together with the EC2 and Auto Scaling components to provide a scalable application infrastructure.

---

## Technologies Used

- Amazon EC2
- Application Load Balancer (ALB)
- Target Groups
- EC2 Auto Scaling
- AWS Management Console
