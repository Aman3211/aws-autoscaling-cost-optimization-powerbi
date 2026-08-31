# AWS Auto Scaling & Cost Optimization using Power BI

A hands-on AWS cloud project demonstrating EC2 deployment, Application Load Balancing, Auto Scaling, CloudWatch monitoring, load testing, AWS cost analysis, and Power BI dashboard visualization.

---

## Project Overview

This project demonstrates the implementation and analysis of an AWS-based application environment.

The project focuses on:

- Deploying applications on Amazon EC2.
- Configuring an Application Load Balancer.
- Implementing EC2 Auto Scaling.
- Monitoring infrastructure using Amazon CloudWatch.
- Performing load testing using Apache Benchmark.
- Reviewing AWS billing and cost information.
- Analyzing infrastructure data using Microsoft Power BI.
- Creating dashboards for infrastructure and cost analysis.

---

## Project Objectives

- Understand AWS cloud infrastructure components.
- Deploy and manage EC2 instances.
- Configure Application Load Balancing.
- Implement automatic scaling based on workload.
- Monitor EC2 performance using CloudWatch.
- Generate workload using Apache Benchmark.
- Analyze AWS cost-related information.
- Visualize infrastructure and cost data using Power BI.
- Document the complete cloud implementation and analysis.

---

## Project Architecture

The project follows an AWS infrastructure and analytics workflow:

```text
User / Client
     |
     v
Application Load Balancer
     |
     v
EC2 Auto Scaling Group
     |
     +------------------+
     |                  |
     v                  v
EC2 Instance 1       EC2 Instance 2
     |
     v
Amazon CloudWatch
     |
     v
Monitoring Data
     |
     v
Power BI
     |
     v
Interactive Dashboards
