# Amazon CloudWatch

This section documents the Amazon CloudWatch monitoring performed as part of the **AWS Auto Scaling & Cost Optimization using Power BI** project.

CloudWatch was used to monitor the EC2 environment and observe CPU utilization before and after applying workload through load testing.

---

## Objectives

- Monitor EC2 CPU utilization.
- Observe application behavior under workload.
- Compare CPU utilization before and after load testing.
- Use monitoring data to understand workload changes and scaling behavior.

---

## CloudWatch Monitoring

### 1. CPU Utilization Before Load

The CPU utilization of the EC2 environment was observed before applying the load.

![CPU Before Load](cpu-before-load.png)

---

### 2. CPU Utilization After Load

CPU utilization was observed again after applying workload through load testing.

![CPU After Load](cpu-after-load.png)

---

## Monitoring Summary

The CloudWatch monitoring results provide visibility into EC2 CPU utilization and help demonstrate the effect of workload on the cloud infrastructure.

The monitoring data can be used alongside the Auto Scaling configuration to understand how changes in workload relate to changes in compute capacity.

---

## Technologies Used

- Amazon CloudWatch
- Amazon EC2
- EC2 Auto Scaling
- AWS Management Console
