# Load Testing

## Overview

Load testing was performed to simulate increased application workload and observe the behavior of the AWS infrastructure.

## Purpose

The purpose of load testing was to evaluate:

- Application performance
- EC2 resource utilization
- Load Balancer traffic distribution
- Auto Scaling behavior
- Infrastructure response to increased workload

## Testing Workflow

1. Generate application traffic
2. Monitor EC2 resource utilization
3. Observe CloudWatch metrics
4. Monitor Auto Scaling activity
5. Observe additional EC2 instances being launched when required
6. Observe traffic distribution through the Load Balancer

## Key Learning

The load testing exercise helped demonstrate how AWS compute, monitoring, load balancing, and Auto Scaling services work together under changing workloads.
