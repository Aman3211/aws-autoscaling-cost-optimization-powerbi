# EC2 Auto Scaling

## Overview

Amazon EC2 Auto Scaling automatically adjusts the number of EC2 instances based on workload requirements.

## Purpose in This Project

Auto Scaling was used to dynamically adjust compute capacity according to application workload.

This helps maintain application availability while avoiding unnecessary compute resources during periods of lower demand.

## Scaling Workflow

Application workload
→ CloudWatch metrics
→ Auto Scaling policy
→ EC2 instances scale out or scale in

## Key Configuration

- Auto Scaling Group configured
- Minimum capacity defined
- Desired capacity defined
- Maximum capacity defined
- Scaling policy configured
- EC2 instances managed by the Auto Scaling Group

## Key Learning

I learned how Auto Scaling dynamically manages EC2 capacity and how scaling policies can respond to changes in workload.
