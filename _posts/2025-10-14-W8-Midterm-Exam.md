---
layout: post
title: "Week 8 - Midterm Exam: IT Service Management"
date: 2025-10-15
excerpt: "For the Midterm Exam, I completed three challenges covering ITIL-based incident and request management in ServiceNow, data quality analysis, and practical simulation as a Service Desk Agent at Bank Nusantara Digital."
---

## Week 8 — Midterm Exam: IT Service Management

This week’s activity was the Midterm Exam for IT Service Management. It consisted of three main challenges that tested both conceptual understanding and hands-on application of ITIL principles using ServiceNow and real-world service data.

The exam was performed individually and covered data auditing, process simulation, and ITSM workflow execution. It integrated analytical, technical, and service-oriented problem-solving—similar to real IT operations environments.

---

## Challenge 1 — Online Assessment

The first challenge was a **closed-book online quiz** designed to evaluate theoretical understanding of IT Service Management concepts, ITIL processes, and ServiceNow functionalities. This section tested comprehension of ITIL lifecycle processes, including Incident, Problem, and Change Management, as well as metrics like SLA, urgency, and priority.

---

## Challenge 2 — Data Quality Audit for Bank Nusantara Digital

The second challenge simulated a scenario as an **IT Service Analyst** at *Bank Nusantara Digital*. The goal was to **audit and improve a helpdesk dataset** exported from ServiceNow that contained multiple data-quality issues.

### **Scenario**
The management suspected inconsistencies in ticket data such as missing fields, unrealistic resolution times, and incorrect priorities.  
I was tasked with auditing, correcting, and improving the dataset while maintaining ITIL alignment.

---

### **Dataset Overview**
![The Dataset](/My-ITSM-Journey/assets/midterm_dataset.jpg)

Each record represented a helpdesk ticket with these fields:  
`Ticket ID`, `Ticket Type`, `Category`, `Priority`, `Resolution Time (hrs)`, `Description`, `Department`, `Ticket Agent`, `Ticket User`

The dataset contained **15 records** covering incidents and requests across several departments like Corporate Finance, Retail Banking, Digital Services, and HR.

**Original Issues Identified:**
1. Mismatched ticket type and ID prefixes (e.g., “REQ013” labeled as Incident).  
2. Missing or incomplete category and resolution time values.  
3. Unrealistic resolution times (e.g., 145 hrs for a password reset).  
4. Inconsistent priority assignments (e.g., P5 incident resolved in 1 hr).  
5. Missing or unclear agent/user information.  

---

### **Improvements Made**
To improve the dataset:
- Filled missing values and standardized ticket types to match the ID prefix.  
- Adjusted unrealistic resolution times (e.g., 145 → 2 hrs, 210 → 2 hrs).  
- Corrected category mislabels based on description content.  
- Verified and aligned priorities with incident impact and urgency.  
- Ensured consistent naming and department mapping.

**Improved Dataset:**  
![Improved Dataset](/My-ITSM-Journey/assets/midterm_improved_dataset.jpg)

---

### **Analysis Summary**

1. **Errors Identified:**
   - Incorrect ticket-type assignments.  
   - Inconsistent priorities and resolution times.  
   - Missing descriptions and incomplete department info.

2. **Correction Actions:**
   - Fixed misclassified records.  
   - Normalized resolution times and aligned priorities with urgency.  
   - Completed missing fields based on contextual inference.

3. **Ideal Dataset Characteristics:**
   A good service desk dataset should include **complete, accurate, and logical information** for each ticket—covering ID, category, priority, resolution time, description, department, and assigned roles.

4. **Report to Manager:**
   > After auditing, 15 helpdesk records were standardized to improve data accuracy and ITIL compliance. The revised dataset corrects inconsistencies in ticket types, priorities, and resolution times, resulting in more reliable reporting metrics for service performance. This ensures that analytics and KPI monitoring reflect the true operational efficiency of our Service Desk team.

---


## Challenge 3 — ServiceNow Ticket Simulation

In the final challenge, I acted as a **Service Desk Agent** for *Bank Nusantara Digital*, simulating ITIL workflows in **ServiceNow PDI**.

### **Steps Performed**
1. **Created two users:**
   - `bank_user` → role: `user` (End User)  
   - `bank_agent` → role: `itil` (Service Desk Agent)  
   Password for both: **Yeswecan!7**

2. **Created four tickets:**
   - **Incident 1:** Network — ATM offline  
   - **Incident 2:** Hardware — Laptop won’t power on  
   - **Request 1:** Software/Application — SPSS installation  
   - **Request 2:** Account/Access — VPN access request  

3. **Resolution:**
   - Logged in as `bank_agent`, resolved all four tickets following ITIL best practices.  
   - Updated **state → Resolved** with proper work notes.  
   - Logged back in as `bank_user` to review and close tickets. 

---

## Reflection

This midterm exam combined both technical execution and analytical reasoning, mirroring how IT service teams handle real-world operations.  
Through this assessment, I learned how ITIL standards support data quality, ticket accuracy, and structured escalation in ServiceNow.

The integration of auditing, workflow creation, and ticket lifecycle management strengthened my understanding of Incident and Request Management as core ITSM functions. It also emphasized the importance of reliable data, communication between roles, and accountability in IT operations.

---
