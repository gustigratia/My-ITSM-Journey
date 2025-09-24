---
theme: minima
layout: post
title: "Week 4-Service Desk & Incident Management"
date: 2025-09-16
excerpt: "Learned about ITIL V3 service desk and incident management. Answered theory questions, mapped incident sub-processes, and analyzed helpdesk ticket data from Kaggle against ITIL standards."
---

## Week 4 — Service Desk and Incident Management

This week we focused on **service desk** and **incident management** in IT Service Management (ITSM). The service desk is the **Single Point of Contact (SPOC)** for users, while incident management is the process of handling incidents from detection to resolution. Both concepts are core to ITIL V3.

---

## Q1 — Service Desk (ITIL V3 Reference)

Questions answered using ITIL V3 Wiki as reference:

- **What is service desk?**  
  A primary function in ITSM that manages communication between users and the IT provider.

- **Service desk vs. help desk?**  
  - Service Desk: Supports employees with service requests and incident resolution, traditionally tied to IT infrastructure but broader in scope.
  - Help Desk: Provides answers to both employees and customers about products or services, mainly addressing IT-related issues or user difficulties.

- **Types of service desk:**  
  - Local Service Desk: On-site, for small centralized organizations.
  - Centralized Service Desk: All requests handled from one central location.
  - Virtual Service Desk: Operates online, ideal for remote teams.
  - Hybrid Service Desk: Combines local and virtual support.
  - Follow-the-Sun Service Desk: 24/7 global coverage across time zones.
  - Outsourced Service Desk: Managed by third-party vendors to reduce internal costs and bring specialized expertise. 

- **Processes supported:** Register incidents to ensure accurate tracking, Process service requests (e.g., devices, app access), Resolve incidents immediately via first-level support, Analyze and fix incidents at second-level support, escalate to Problem Management if needed, Monitor and escalate unresolved incidents to meet SLAs, Proactively inform users about ongoing disruptions, Close and evaluate incidents, ensuring quality resolution and lessons learned, Maintain a knowledge base to improve efficiency, Produce incident reports to support service improvement.
  
- **Key KPIs:**  
| KPI                        | Description |
|-----------------------------|-------------|
| Number of Repeated Incidents | Measures the number of incidents that recur after initial resolution, indicating unresolved underlying problems. |
| Incidents Resolved Remotely  | Shows the number of incidents resolved without on-site interaction, indicating efficiency of remote support. |
| Number of Escalations        | Measures how many incidents must be escalated to higher-level support because they cannot be resolved at the first level. |
| Number of Incidents          | The total number of incidents recorded within a given period, reflecting the volume of support requests received. |
| Average Initial Response Time | The average time taken to provide the first response to an incident reported by a user. |
| Incident Resolution Time     | The average time required to resolve an incident from the moment it is reported until it is closed. |
| First Time Resolution Rate   | The percentage of incidents resolved during the first interaction without escalation or further intervention. |
| Resolution within SLA        | The percentage of incidents resolved within the time agreed in the Service Level Agreement (SLA). |
| Incident Resolution Effort   | The total resources or effort required to resolve incidents, including staff time and energy used by the support team. |


- **Service desk vs. incident management:**  
| Aspect                  | Service Desk                                                   | Incident Management                                    |
|--------------------------|---------------------------------------------------------------|--------------------------------------------------------|
| Definition               | A function that provides a single point of contact for users. | A process to manage the incident lifecycle.            |
| Main Focus               | Provides general support and handles service requests.        | Identifies, analyzes, and resolves incidents.          |
| Responsibilities         | Incident logging, user communication, and escalation.         | Resolves incidents and prevents further impact.        |
| Involvement with Other Processes | Interacts with various other ITIL processes.              | Focuses on incident identification and resolution.     |


---


## Q2 — Incident Management Sub-Processes

We mapped entities involved in each sub-process of Incident Management:

- **Logging:** incident record, user info  
- **Categorization:** service category, priority level  
- **Prioritization:** impact, urgency  
- **Escalation:** functional escalation, hierarchical escalation  
- **Resolution & Recovery:** resolution detail, workaround  
- **Closure:** user confirmation, resolution documentation  

<iframe src="/My-ITSM-Journey/assets/checklistsps.pdf" width="100%" height="600px">
  Your browser does not support PDFs. Please <a href="/My-ITSM-Journey/assets/checklistsps.pdf">download the PDF</a> to view it.
</iframe>


---

## LAB 01 — Helpdesk Data Analysis (Group Work)

We analyzed an **IT support ticket dataset** from Kaggle. Goal: identify **gaps** compared to ITIL service desk processes.

**Key gaps found:**  
- No clear incident classification aligned with ITIL.  
- Missing fields for priority and urgency.  
- Incomplete resolution documentation.

(Sheet available here: [Lab 01 - Helpdesk Data](https://docs.google.com/spreadsheets/d/19MLkx6_1Mz87RWibuqxLOfT8qrDAjMk1t30g__Ued2w/edit?gid=224322737#gid=224322737))


---

## Reflection

The week highlighted how ITIL V3 structures incident handling and user interaction. The service desk provides the **people-facing bridge**, while incident management standardizes the **process side**. The dataset activity showed how real-world helpdesk data often misses ITIL’s rigor, underlining the importance of proper classification, prioritization, and closure practices.

---
