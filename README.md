# AWS Auto Scaling & Cost Optimization using Power BI

## Overview

A cloud infrastructure project developed as part of my M.Sc. IT final-year
project, focused on implementing AWS Auto Scaling and analyzing cloud
infrastructure performance and cost using Power BI.

## Objectives

- Automatically scale EC2 resources based on workload
- Improve application availability using Application Load Balancer
- Monitor infrastructure using AWS CloudWatch
- Perform load testing using Apache Benchmark
- Analyze CPU utilization and scaling activity
- Visualize infrastructure metrics using Power BI
- Analyze cloud cost optimization

## AWS Architecture

The project uses:

- Amazon EC2
- AWS Auto Scaling Groups
- Application Load Balancer
- AWS CloudWatch
- AWS Security Groups
- AWS Billing / Cost Monitoring

## Data & Analytics

Power BI dashboards were developed to analyze:

- CPU utilization
- Running EC2 instances
- Auto Scaling events
- Request count
- Network traffic
- Load Balancer activity
- Cloud infrastructure costs

## Load Testing

Apache Benchmark was used to generate concurrent requests and validate
Auto Scaling behavior.

Example:

ab -n 3000 -c 200 http://load-balancer-url/

## Results

The infrastructure successfully demonstrated:

- Automatic scale-out during high workload
- Automatic scale-in during low workload
- Traffic distribution through Application Load Balancer
- Real-time monitoring through CloudWatch
- Infrastructure analysis through Power BI
- Cost optimization through automated resource scaling

## Technologies

AWS | EC2 | Auto Scaling | Application Load Balancer |
CloudWatch | Power BI | Ubuntu | Nginx | React.js | Node.js |
Apache Benchmark | GitHub

## Project Author

Aman Chaudhary  
M.Sc. Information Technology
