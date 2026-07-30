---
title: "2. Compute, Networking & Storage Lab"
date: 2026-07-13
weight: 2
chapter: false
pre: " <b> 1.2 </b> "
---

### Week 2: Compute, Networking & Storage Lab

**Duration:** 22/06/2026 – 28/06/2026

#### Objectives

* Gain a deep understanding of Compute, Networking, and Storage services on AWS.
* Build a custom Virtual Private Cloud (VPC) and deploy EC2 virtual machines from scratch.
* Host and distribute static files using Amazon S3.

#### Tasks Performed

* **EC2 & EBS Hands-on:** Launched EC2 instances (both Linux and Windows) and connected via SSH/RDP. Practiced attaching, formatting, and mounting EBS volumes. Created snapshots for data backup and recovery, observing data persistence during stop/start cycles.
* **Networking (VPC) Hands-on:**
  * Designed and built a complete custom VPC environment.
  * Segmented the network into Public and Private Subnets. Configured Internet Gateways, NAT Gateways, and Route Tables to securely route traffic.
  * Secured resources using properly scoped Security Groups.
* **S3 Hands-on:** Created S3 buckets, uploaded objects, and configured Bucket Policies. Enabled Static Website Hosting to serve a simple HTML site. Experimented with Presigned URLs to share files securely and temporarily.

#### Outcomes

* **Output:** A fully functional, secure VPC architecture, a running EC2 instance, and a static website hosted directly on S3.
* Mastered core infrastructure skills required for complex architectures. The S3 Presigned URL mechanism will be directly reused to store and share the AI model artifacts for our final project.
