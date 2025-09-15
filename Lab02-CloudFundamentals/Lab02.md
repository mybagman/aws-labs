# Lab 02 – AWS Cloud Fundamentals

**Date:** 16 Sept 2025  
**Goal:** Gain foundational experience with networking, storage, replication, and scaling on AWS.

---

## Steps Completed

### 1. Networking & Security
- Configured **network security** for resources to ensure proper access controls.

### 2. Storage & Replication
- Created an **S3 bucket**.  
- Enabled **cross-region replication** for resilience and availability.

### 3. Compute & Scaling
- Created a **launch template** for repeatable EC2 deployments.  
- Built an **Auto Scaling group** to handle variable workloads.  
- Configured an **Application Load Balancer (ALB)** to distribute traffic across multiple instances.

---

## Results
- Secure network configurations applied successfully.  
- S3 bucket now replicates objects to another AWS region, increasing durability.  
- Auto Scaling group and ALB work together to automatically manage EC2 instances and balance load.  

---

## Notes / Lessons Learned
- Cross-region replication requires proper IAM role setup between source and destination buckets.  
- Launch templates simplify EC2 provisioning and are more efficient than configuring instances manually.  
- Auto Scaling + ALB provides both resilience and performance, which are critical in production environments.  