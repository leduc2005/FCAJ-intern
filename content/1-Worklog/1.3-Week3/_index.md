---
title: "3. Databases & Serverless Basics Lab"
date: 2026-07-13
weight: 3
chapter: false
pre: " <b> 1.3 </b> "
---

### Week 3: Databases & Serverless Basics Lab

**Duration:** 29/06/2026 – 05/07/2026

#### Objectives

* Compare and operate the two main database paradigms on AWS: Relational (RDS) and NoSQL (DynamoDB).
* Get introduced to Serverless architecture through AWS Lambda.

#### Tasks Performed

* **Database Hands-on (RDS & DynamoDB):**
  * Provisioned a MySQL database on RDS, connected to it via an EC2 instance, and practiced basic data ingestion.
  * Designed a NoSQL table on Amazon DynamoDB, experimenting with Partition Keys and Global Secondary Indexes (GSI).
  * Conducted load testing to compare the cost and performance of Provisioned vs. On-demand capacity modes in DynamoDB.
* **Serverless Basics (Lambda):**
  * Wrote and deployed a basic Lambda function using Python.
  * Learned to configure memory allocation, timeouts, and Environment Variables.
  * Explored the concept of Cold Starts and analyzed execution logs within CloudWatch.

#### Outcomes

* **Output:** Successfully designed the schema for the `ModerationHistory` DynamoDB table using On-demand billing (which will be integrated directly into our final project).
* Grasped the distinct cost advantages of DynamoDB for unpredictable workloads compared to RDS, while gaining initial experience in Serverless programming.
