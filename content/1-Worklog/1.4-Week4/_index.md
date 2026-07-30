---
title: "4. Deep-dive Serverless & API Gateway"
date: 2026-07-13
weight: 4
chapter: false
pre: " <b> 1.4 </b> "
---

### Week 4: Deep-dive Serverless & API Gateway

**Duration:** 06/07/2026 – 12/07/2026

#### Objectives

* Build and expose a real-world HTTP endpoint using a fully Serverless architecture.
* Master the integration between Amazon API Gateway and AWS Lambda.
* Understand security best practices and performance optimization (e.g., mitigating cold starts).

#### Tasks Performed

* **AWS Lambda Optimization:**
  * Experimented with memory allocation (from 128MB up to 1024MB) to measure its impact on billed duration and overall cost.
  * Analyzed the Cold Start vs. Warm Start phenomenon using the `REPORT` feature in CloudWatch Logs.
* **API Gateway Configuration:**
  * Set up Amazon API Gateway as the "front door" for the Lambda function.
  * Configured Resources, HTTP Methods (POST), Deployment Stages, and specifically handled CORS errors to allow frontend browser requests.
  * Tested the live API endpoint using `curl` and Postman.
* **Security (IAM):** Instead of relying on broad full-access policies, I authored a custom Execution Role for Lambda adhering strictly to the principle of least privilege, granting only the necessary permissions to write logs and access specific DynamoDB tables.

#### Outcomes

* **Output:** Successfully deployed a public `/moderate` endpoint that returns JSON, fully observable via CloudWatch.
* Solidified my understanding of building Serverless Backends. The concepts mastered in this lab serve as the direct blueprint for coding the backend of our team's text moderation project.
