# Load Testing

This section documents the load testing performed as part of the **AWS Auto Scaling & Cost Optimization using Power BI** project.

The purpose of load testing was to generate application traffic and observe how the AWS infrastructure responds to increased workload. The generated workload can be correlated with EC2 monitoring data collected through Amazon CloudWatch.

## Objective

The main objectives of the load testing activity were:

- Generate HTTP requests against the deployed application.
- Create controlled workload on the application infrastructure.
- Observe application and EC2 behavior under increased traffic.
- Support validation of the Auto Scaling configuration.
- Compare infrastructure monitoring data before and after workload generation.

## Tool Used

### Apache Benchmark (AB)

**Apache Benchmark (`ab`)** was used to generate HTTP requests against the application.

Apache Benchmark is a command-line HTTP server benchmarking tool used to send multiple requests to an application and observe its response behavior.

## Load Testing Architecture

```text
                    Load Generation
                          |
                          v
                Apache Benchmark (ab)
                          |
                          | HTTP Requests
                          v
              Application Load Balancer
                          |
                          v
                Target Group / EC2
                          |
                 +--------+--------+
                 |                 |
                 v                 v
              EC2 Instance     EC2 Instance
                 |                 |
                 +--------+--------+
                          |
                          v
                   Amazon CloudWatch
                          |
                          v
                 CPU Utilization Data
