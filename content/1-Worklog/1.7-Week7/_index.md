---
title: "7. Project Backend Execution, Testing & Submission"
date: 2026-07-13
weight: 7
chapter: false
pre: " <b> 1.7 </b> "
---

### Week 7: Project Backend Execution, Testing & Submission

**Duration:** 27/07/2026 – 31/07/2026

#### Objectives

* Fully deploy the Backend infrastructure for the Toxic Text Moderation Platform.
* Coordinate end-to-end (E2E) testing to ensure seamless system operation.
* Clean up resources to prevent unexpected billing and submit the final report on time.

#### Tasks Performed

* **Backend Development:**
  * Received the quantized AI model from the data team, packaged it into a container image, and pushed it to ECR.
  * Deployed API Gateway and AWS Lambda. Authored the Python logic to execute local inference within Lambda, including a fallback mechanism to invoke Amazon Bedrock if the internal model's confidence was too low.
  * Integrated the Lambda function with DynamoDB to securely store moderation history.
* **Testing & Integration:**
  * Collaborated with the team to connect the Backend to the React Frontend (hosted on AWS Amplify).
  * Fired continuous test cases (in both Vietnamese and English) to trace the data flow, debugging issues related to timeouts and IAM permissions.
  * Enabled CloudWatch metrics and configured alarms to monitor system health and errors.
* **Report Finalization:** Authored the bilingual internship report using a static site generator (Hugo) and deployed it to GitHub Pages for submission. Finally, performed a comprehensive teardown of all provisioned AWS resources to lock in costs at near-zero.

#### Outcomes

* **Output:** A robust, auto-scaling Serverless Backend capable of rapid natural language processing. The personal internship report was successfully published, and the system was safely decommissioned upon project completion.
