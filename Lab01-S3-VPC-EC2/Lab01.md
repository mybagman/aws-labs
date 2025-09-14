# Lab 01 – AWS S3, VPC & EC2 Hands-On

**Date:** 15 Sept 2025  
**Goal:** Gain hands-on experience with AWS storage, networking, and EC2 provisioning.

---

## Steps Completed

### 1. S3 Bucket
- Created an S3 bucket.  
- Configured access permissions for the bucket.  
- Set up the bucket to host a **static website**.

### 2. VPC (Virtual Private Cloud)
- Created a VPC capable of hosting both **public** and **private** instances.  
- Created **subnets** for the VPC (public and private).  
- Configured **route tables** for proper traffic routing.

### 3. EC2 Environment
- Created a **custom AMI**.  
- Created a **security group** for instance access and protection.  
- Built a **repeatable EC2 environment** using a **launch template**.

---

## Results
- S3 bucket is live as a static website with proper access configuration.  
- VPC is correctly set up with public and private subnets, and routing works as expected.  
- Launch template allows easy, repeatable deployment of EC2 instances with custom AMI and security groups.

---

## Notes / Lessons Learned
- Configuring S3 permissions and static websites requires careful attention to public access settings.  
- Understanding subnet and route table relationships is crucial for network design.  
- Launch templates and custom AMIs make EC2 deployments repeatable and consistent.  
- Security groups are essential for controlling inbound/outbound traffic to EC2 instances.
