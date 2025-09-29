---
theme: minima
layout: post
title: "Week 5-Problem Management"
date: 2025-09-23
excerpt: "Explored the core concepts of problem management in ITIL, including its sub-processes, KPIs, and the relationship with incident management. Analyzed incident data from Kaggle to identify problems, conduct root cause analysis, and create a Known Error Database (KEDB)."
---

## Week 5 — Problem Management

This week, we focused on **Problem Management** in IT Service Management (ITSM), which is an ITIL process aimed at identifying and managing the root causes of incidents. The goal is to minimize the impact of incidents through proactive and reactive problem-solving, and to prevent future incidents by eliminating underlying issues.

---

## Q1 — Problem Management (ITIL Reference)

Questions answered using ITIL documentation as reference:

- **What is Problem Management?**  
  Problem Management is the process of identifying and managing the root causes of incidents. Its goal is to reduce the impact of incidents by eliminating underlying problems and preventing future occurrences.

- **What are the sub-processes of Problem Management?**  
  - **Problem Detection:** Identifying problems from recurring incidents.
  - **Problem Logging:** Recording problems in the problem management system.
  - **Problem Diagnosis:** Investigating the root cause of the problem.
  - **Workaround Identification:** Creating temporary solutions to mitigate the impact of the problem.
  - **Problem Resolution:** Finding and implementing permanent solutions to eliminate the problem.
  - **Problem Closure:** Closing the problem once a permanent solution is applied and documented.

- **What are the KPIs for Problem Management?**  
![Problem Management KPI](/My-ITSM-Journey/assets/kpiproblemmanagement.jpg)

- **What is a Known Error Database (KEDB)?**  
  A KEDB is a database that stores known problems and their associated solutions or workarounds. It helps reduce resolution time by providing solutions to recurring issues and aids in proactive problem management.

- **What is a Workaround?**  
  A workaround is a temporary solution that reduces the impact of a problem while a permanent solution is being developed.  
  **Example:** If an application crashes intermittently, a workaround might be to restart the application manually until a permanent fix is applied.

- **What’s the Link Between Incident and Problem Management?**  
  - **Incident Management** focuses on restoring service as quickly as possible, while **Problem Management** aims to identify and eliminate the underlying causes of incidents to prevent recurrence.
  - Incident data often drives Problem Management by highlighting patterns and recurring issues that need investigation.

---

## LAB 02 — Problem Identification (Group Work)

We analyzed an **Incident Dataset** from Kaggle to identify potential problems and perform root cause analysis. The task involved mapping incidents to possible underlying problems and developing solutions.

**Steps performed:**
1. **Identified Problems:** By analyzing incident data, we pinpointed recurring issues such as system crashes and network downtime.
2. **Root Cause Analysis:** We used the Fishbone diagram to perform a root cause analysis, focusing on issues like software bugs, network infrastructure, and user errors.
3. **KEDB Creation:** Based on the root causes, we created a Known Error Database (KEDB) with workarounds and potential solutions.

(Sheet available here: [Lab 02 - Dataset & Problem Identification](https://docs.google.com/spreadsheets/d/1qAxm7_lZ7a9W8bUnLrQwiaKAGMjxLlJh2YPF1ahViPU/edit?gid=224322737#gid=224322737))


**Root Cause Analysis Example:**  
![Fishbone Diagram](/My-ITSM-Journey/assets/fishbonediagram.jpg)

**KEDB Entry Example:**  
![Known Error Database](/My-ITSM-Journey/assets/kedb.jpg)

**Dataset used:** [IT Support Ticket Dataset on Kaggle](https://www.kaggle.com/datasets/parthpatil256/it-support-ticket-data)

---

## Reflection

This week, we gained a deeper understanding of Problem Management and its importance in ITIL. By analyzing real-world incident data, we identified how problem management processes can prevent recurring issues, improve service reliability, and reduce downtime. The lab work reinforced the value of creating a Known Error Database and performing thorough root cause analysis to enhance the effectiveness of IT service delivery.

--- 
