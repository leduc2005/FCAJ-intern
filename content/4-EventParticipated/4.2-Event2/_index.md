---
title: "Event 2"
date: 2026-07-13
weight: 2
chapter: false
pre: " <b> 4.2. </b> "
---

### FCAJ — Agentic AI Build Week: Demo & Pitch Day

&emsp;**Date:** 25/07/2026

&emsp;**Location:** In-person at AWS Vietnam Office

&emsp;**Role:** Participant

#### Event Content

This day marked the conclusion of the FCAJ Agentic AI Build Week—a hackathon where teams built Agentic AI products on AWS and pitched them to a live audience. The venue was packed with over 100 attendees. The format was highly practical: each team took the stage to present their chosen problem, demonstrated a live, working product built during the week, and faced a Q&A session from the judges. Together with Khoi (a member of my project team), I attended and closely followed the presentations.

Four standout teams presented:

| Team | Product | Idea in one sentence |
|---|---|---|
| **3KA** | S.H.E.P.H.E.R.D | Monitor human flow and detect congestion using live AI camera feeds |
| **Plan V** | Solution Architect AI Native App | An Agent that turns document requirements into draft architectures, diagrams, and IaC |
| **Dream AI**| Signal Scout | Track public signals to early-detect corporate strategy shifts |
| **One Team**| Ordering Without Leaving the Chat | Enable customers to place orders via conversational AI directly in their existing chat apps |

![Demo & Pitch Day atmosphere](/images/4-EventParticipated/event2-1.jpg)
*Demo & Pitch Day atmosphere*

Team 3KA's product utilized YOLO, ByteTrack combined with Amazon SageMaker and Bedrock Agent to create an autonomous monitor and a natural language operator copilot, solving the issue of slow response times at large venues. 

Plan V's product directly tackled the time-consuming bottlenecks faced by Solution Architects. Their Agent ingested natural language requirements to automatically draft architectural options, generate editable Draw.io diagrams, and export Infrastructure as Code (IaC) via Terraform along with cost estimates.

Signal Scout by Dream AI helped early-detect corporate strategy shifts from fragmented data, with every conclusion backed by specific data displayed on a self-service dashboard. Meanwhile, One Team's project left a strong impression with its API-first strategy, integrating the ordering function directly into existing chat applications rather than forcing users to download a new app.

![A presentation at the event](/images/4-EventParticipated/event2-2.jpg)
*A presentation at the event*

#### Lessons and value gained

The most useful takeaway for me was the cost breakdown slide by Dream AI (Signal Scout). They dissected each service (Bedrock tokens, AgentCore memory, WAF, DynamoDB) across three cost scenarios: minimum, average, and maximum. This was an incredibly transparent presentation method that I immediately adopted for estimating the costs of our team's text moderation project.

Plan V changed my understanding of the term "Agentic". This experience proved that an Agent is not merely invoking an LLM to process text, but can connect a long chain of complex business workflows. Additionally, 3KA's pitch delivered a very authentic sense of the time pressure inherent in a hackathon, sharing an honest perspective on moments when the product didn't work—highly relatable to our own project development reality. Finally, One Team's solution reinforced my confidence in our team project's direction: designing our moderation service as an API hidden beneath existing platforms is a far better approach than attempting to build an entirely new user interface.
