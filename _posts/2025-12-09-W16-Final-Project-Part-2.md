---
layout: post
title: "Week 16 – Knowledge Management (Final Project Part 2)"
date: 2025-12-09
excerpt: "In the second part of the Final Project, Knowledge Management was implemented in ServiceNow by converting real incidents, problems, and changes into actionable Knowledge Articles for both end users and IT support."
---

## Week 16 — Knowledge Management (Final Project Part 2)

Week 16 continues the Final Project by focusing on **Knowledge Management**. While Week 15 covered Incident, Problem, and Change Management, this week emphasized documenting operational experience into reusable knowledge within ServiceNow.

The goal is simple:  
**to ensure recurring issues do not need to be solved from scratch by either end users or IT support teams.**

---

# Knowledge Management in ITSM

Knowledge Management plays a crucial role in capturing operational experience and turning it into organizational knowledge. In ITSM, an effective knowledge base helps:

- accelerate incident resolution,  
- reduce recurring incidents,  
- standardize handling across teams,  
- and provide clear guidance to end users.

In Week 16, Knowledge Management was implemented directly using the **ServiceNow Knowledge Base**, not just as a theoretical concept.

---

# Types of Knowledge Articles

This week introduced two main types of Knowledge Articles:

## 1. Standard Knowledge Articles
Designed for **end users** such as doctors, nurses, and clinic staff.  
These articles are:

- simple,  
- easy to understand,  
- written in non-technical language,  
- and focused on guiding users through immediate actions.

## 2. Known Error Articles
Designed for **Service Desk and IT Support** teams.  
They contain:

- technical details,  
- root causes,  
- context of the recurring issue,  
- and documented workarounds.

These articles help IT staff identify and resolve known errors more efficiently.

---

# Implementation Results — Knowledge Articles Created

## A. Standard Knowledge Articles

Based on real incidents from Final Project Part 1, three Standard Knowledge Articles were created:

### **1. How to Report an EHR System Issue Properly**
Explains how users should report EHR issues so the Service Desk can respond quickly and accurately.

Linked incidents:

- INC0010004 – Login Failures  
- INC0010006 – Five-Minute Outage  
- INC0010007 – EHR running very slow  
- INC0010008 – Database not responding  
- INC0010009 – EHR Freezes During Patient Care  

---

### **2. How to Avoid Session Timeouts in the EHR**
Provides simple steps for preventing session timeouts during busy hours.

Linked incidents:

- INC0010004 – Login Failures  
- INC0010009 – EHR Freezes During Patient Care  

---

### **3. How to Use the EHR During Temporary System Slowness**
Gives guidance on how to safely use the EHR when performance becomes slow or unstable.

Linked incidents:

- INC0010006 – Five-Minute Outage  
- INC0010007 – EHR running very slow  

---

All Standard Articles:

- used the Standard Template,  
- had correct categories,  
- were linked to Part 1 incidents,  
- and were published in the Knowledge Base.

---

## B. Known Error Articles

For IT teams, three **Known Error Articles** were created to document recurring technical issues.

### **1. EHR Login Failures for Multiple Users**
Explains the repeated login failures, including root cause and workaround.

Linked to:

- Incident: INC0010004  
- Problem: PRB0040003  
- CI: EHR Application Server, EHR Database Server, EHR Service  

---

### **2. “Database Not Responding” Error in EHR**
Documents the recurring database connection error experienced during usage.

Linked to:

- Incident: INC0010008  
- CI: EHR Application Server, EHR Database Server, EHR Service  

---

### **3. Short EHR Outage During High Load**
Explains the brief EHR outage that occurred under heavy load.

Linked to:

- Incident: INC0010006  
- CI: EHR Application Server, EHR Database Server, EHR Service  

---

These Known Error Articles help IT Support recognize recurring issues immediately, reducing troubleshooting time and improving service consistency.

---

# Workflow Summary

The Week 16 workflow included:

1. Using the same ServiceNow PDI as Final Project Part 1  
2. Creating **six Knowledge Articles** (3 Standard, 3 Known Error)  
3. Applying the correct templates for each article type  
4. Linking the articles to relevant:  
   - Incidents  
   - Problems (when applicable)  
   - Configuration Items  
5. Publishing all articles for organizational use  

---

# Reflection

Week 16 demonstrated that resolving incidents is only part of the ITSM lifecycle. Without proper documentation, knowledge remains isolated and cannot support future operations.

By converting real operational experiences into Knowledge Articles, ITSM becomes:

- more efficient,  
- more consistent,  
- and more sustainable.  

Knowledge Management ensures that solutions live beyond individual incidents and contribute to continuous service improvement.

---

## Final Report Part 2 PDF

For a detailed breakdown of the activity, refer to the [PDF Final Report](/My-ITSM-Journey/assets/FP2.pdf) embedded below:

<iframe src="/My-ITSM-Journey/assets/FP2.pdf" width="100%" height="600px"></iframe>
