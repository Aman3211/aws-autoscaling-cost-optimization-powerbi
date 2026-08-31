# Application Load Balancer

## Overview

The Application Load Balancer distributes incoming application traffic across multiple targets.

## Purpose in This Project

The Load Balancer acts as the entry point for application traffic and distributes requests across the EC2 instances managed by Auto Scaling.

## Architecture Role

Client
→ Application Load Balancer
→ EC2 Instances

## Key Configuration

- Application Load Balancer configured
- Target group created
- EC2 instances registered as targets
- Health checks configured
- Traffic distributed across healthy instances

## Key Learning

I learned how an Application Load Balancer distributes application traffic and performs health checks to route requests to healthy targets.
