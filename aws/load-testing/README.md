# Load Testing

This section documents the load testing performed as part of the **AWS Auto Scaling & Cost Optimization using Power BI** project.

Apache Benchmark (AB) was used to generate workload against the deployed application and observe how the AWS infrastructure responds to increased traffic.

---

## Objectives

- Generate workload against the deployed application.
- Test the application under increased traffic.
- Observe the response of the AWS infrastructure to workload.
- Support the validation of the Auto Scaling configuration.
- Generate workload that can be observed through Amazon CloudWatch monitoring.

---

## Load Testing

### 1. Apache Benchmark Command

Apache Benchmark (`ab`) was used to generate HTTP requests against the application.

![Apache Benchmark Command](ab-load-test)

---

## Load Testing Process

The load testing process involved generating requests against the deployed application using Apache Benchmark.

The generated workload increased the activity on the application infrastructure, which could then be observed through Amazon CloudWatch monitoring.

---

## Monitoring and Scaling

The workload generated during load testing was used along with:

- Amazon EC2
- Application Load Balancer
- EC2 Auto Scaling
- Amazon CloudWatch

This helped observe how the infrastructure responds to changes in workload and supports the overall Auto Scaling analysis.

---

## Technologies Used

- Apache Benchmark (AB)
- Amazon EC2
- Application Load Balancer
- EC2 Auto Scaling
- Amazon CloudWatch
- AWS Management Console
