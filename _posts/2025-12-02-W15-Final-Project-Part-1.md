---
layout: post
title: "Week 15 – Final Project Part 1: Incident, Problem, and Change Management"
date: 2025-12-03
excerpt: "This week marks the beginning of the Final Project, focusing on an end-to-end ITIL workflow involving Incident, Problem, and Change Management using a ServiceNow case scenario."
---

## Week 15 — Final Project Part 1: Incident, Problem, and Change Management

Week 15 is the beginning of the **Final Project** for the IT Service Management course. In this first part, I implemented **Incident Management**, **Problem Management**, and **Change Management** in a fully connected workflow using ServiceNow.

The goal was to demonstrate how a service disruption is recorded as an Incident, analyzed as a Problem, and permanently resolved through a Change — with all records clearly linked and traceable.

---

# Project Scenario — EHR Service Outage

The case study focuses on a critical service disruption at **Northstar Health Clinics**, involving the Electronic Health Record (EHR) system — a core service used directly in patient care.

The reported issues included:

- EHR pages loading extremely slowly during peak hours  
- Multiple users unable to log in  
- “Database not responding” errors  
- Short service outages lasting several minutes  
- EHR freezing during clinical activities  

These disruptions occurred repeatedly and had significant impact on clinic operations.

---

# Configuration Item (CI) Preparation

Before logging any incidents, I created several Configuration Items (CIs) in the ServiceNow PDI because they did not exist by default.

The CIs created were:

- **EHR Service (Business Service)**  
- **EHR Application Server**  
- **EHR Database Server**

These CIs were used consistently throughout the Incident, Problem, and Change records to ensure full traceability across processes.

---

# Incident Management Implementation

Multiple incidents were created based on end-user reports from the clinic.  
Examples of incidents logged:

- Slow EHR performance  
- Database connection failures  
- Login issues during peak hours  
- EHR freezing mid-usage  
- Temporary EHR outages  

Each incident included:

- Caller  
- Impact and Priority  
- Assignment Group  
- Related CI  
- Work notes documenting investigation and actions taken  

One high-impact incident was escalated to **Application Support – EHR** due to severity.

The primary goal during this stage was **restoring service as quickly as possible** while gathering data about recurring symptoms.

---

# Problem Management Implementation

Because the incidents showed consistent and repeating patterns, I created a **Problem record** to analyze the underlying cause.

In the Problem record:

- All related incidents were linked  
- Impact on the EHR Service was clearly documented  
- Urgency was set to high because the service is mission-critical  

## Root Cause Analysis
The analysis revealed the underlying cause:

- **Resource exhaustion on the EHR Application Server during peak usage hours**

## Workaround
A temporary workaround was identified:

- Restart the EHR system  
- Limit high-usage activities during peak hours  

## Proposed Permanent Fix
A long-term solution was defined:

- **Reconfiguration and optimization of the EHR Application Server**

This Problem record served as the basis for the Change request.

---

# Change Management Implementation

To apply the permanent fix, I created a **Normal Change Request** in ServiceNow.

The Change included:

- Detailed change description  
- Risk and impact analysis  
- Scheduled implementation window  
- Implementation plan  
- Test plan  
- Back-out plan  

## Change Tasks
Several change tasks were created:

- Backup server configuration  
- Apply the optimized configuration  
- Perform functional and performance testing  

Each task followed the standard workflow and was completed successfully.

## Change Closure
After implementation:

- The EHR system was validated  
- No further related incidents were reported  
- The Change was closed with a **Successful** status  

This marked the completion of the permanent fix.

---

# Process Integration — End-to-End Workflow

The Final Project demonstrated how ITIL practices support one another:

- **Incident Management** records and restores service  
- **Problem Management** investigates root cause  
- **Change Management** implements a permanent solution  

All records were connected through the same CI, forming a fully traceable ITSM workflow in ServiceNow.

---

# Change Record & PDI Reference

Final Project Change details:

- **Change Number:** CHG0030005  
- **Change Type:** Normal Change  
- **Affected CI:** EHR Application Server  
- **Related Problem:** Recurring EHR slowness and login failures  

All work — approvals, scheduling, implementation, tasks, and closure — was completed in the same ServiceNow instance.

**ServiceNow PDI:**  
https://dev292954.service-now.com/  
Group 3 – Final Project MLTI

---

# Reflection

This project clearly showed how **Incident**, **Problem**, and **Change Management** work together as an integrated workflow. By linking all records to the same CI and applying a controlled Change, the service disruption could be resolved permanently.

Working through the full cycle in ServiceNow helped me understand how structured processes prevent recurring issues and improve service reliability across an organization.

---

## Final Project Part 1 PDF

For a detailed breakdown of the activity, refer to the [PDF Final Project](/My-ITSM-Journey/assets/FP1.pdf) embedded below:

<iframe src="/My-ITSM-Journey/assets/FP1.pdf" width="100%" height="600px"></iframe>
