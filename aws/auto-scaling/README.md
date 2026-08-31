# AWS Auto Scaling

This section documents the Auto Scaling implementation completed as part of the **AWS Auto Scaling & Cost Optimization using Power BI** project.

Amazon EC2 Auto Scaling was used to automatically adjust the number of EC2 instances based on workload and scaling conditions.

---

## Objectives

- Create an Auto Scaling Group (ASG).
- Configure an EC2 Launch Template.
- Define scaling policies.
- Configure scale-out behavior.
- Configure scale-in behavior.
- Maintain application availability by dynamically adjusting EC2 capacity.

---

## Auto Scaling Implementation

### 1. Launch Template

A Launch Template was configured to define the EC2 instance configuration used by the Auto Scaling Group.

![Launch Template](launch-template.png)

---

### 2. Auto Scaling Group Created

An Auto Scaling Group was created to manage the EC2 instances and maintain the required capacity.

![Auto Scaling Group](asg-created.png)

---

### 3. Scaling Policy

A scaling policy was configured to control when additional EC2 instances should be launched or existing instances should be removed based on workload conditions.

![Scaling Policy](scaling-policy.png)

---

### 4. Scale-Out

The scale-out process increases the number of EC2 instances when additional compute capacity is required.

![Scale Out](scale-out.png)

---

### 5. Scale-In

The scale-in process reduces the number of EC2 instances when additional capacity is no longer required.

![Scale In](scale-in.png)

---

## Implementation Summary

The Auto Scaling component provides dynamic compute capacity for the application.

The implementation includes:

- EC2 Launch Template
- Auto Scaling Group
- Scaling Policy
- Scale-Out configuration
- Scale-In configuration

This helps the application respond to changing workloads while avoiding unnecessary EC2 capacity.

---

## Technologies Used

- Amazon EC2
- EC2 Launch Template
- EC2 Auto Scaling
- Auto Scaling Groups
- Scaling Policies
