---
title: "5. Containers & AI Services Lab"
date: 2026-07-13
weight: 5
chapter: false
pre: " <b> 1.5 </b> "
---

### Week 5: Containers & AI Services Lab

**Duration:** 13/07/2026 – 19/07/2026

#### Objectives

* Experience packaging applications into Container images and running them on AWS Lambda.
* Explore and evaluate AWS AI services (specifically Amazon Bedrock and SageMaker) as a foundation for the capstone project.

#### Tasks Performed

* **Docker & ECR Hands-on:**
  * Mastered the Docker build/tag/push workflow. Authored a multi-stage Dockerfile to optimize image size.
  * Pushed the resulting image to a private repository on Amazon Elastic Container Registry (ECR).
  * Deployed a Lambda function using the container image instead of a standard zip archive. Pre-tested the setup locally using the AWS Lambda Runtime Interface Emulator (RIE).
* **Exploring AI Services:**
  * Experimented with SageMaker notebooks and endpoints. Analyzed the cost implications of maintaining an always-on inference endpoint (SageMaker) versus a pay-per-request model (Lambda).
  * Invoked Amazon Bedrock (using the Claude Haiku model) programmatically via Python.
  * Conducted prompt engineering experiments for text classification, measuring both latency and cost per invocation.

#### Outcomes

* **Output:** A container image successfully hosted on ECR and running as a Lambda function, fully validated in a local environment.
* Finalized the AI architecture strategy for the team project: Our self-trained (and quantized) model will be packaged into a Lambda container to minimize costs, falling back to Amazon Bedrock only when the internal model yields low confidence scores.
