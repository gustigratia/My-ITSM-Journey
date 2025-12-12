---
layout: post
title: "Week 11 – ServiceNow Change Management & Problem Management Lab"
date: 2025-11-05
excerpt: "Hands-on ITSM activities in ServiceNow focusing on the full Change Management lifecycle and a collaborative Problem Management scenario."
---

## Week 11 — ServiceNow Change Management & Problem Management Lab

In Week 11, I practiced ITSM processes directly inside **ServiceNow**, moving from external documentation to platform-based workflows. This week consisted of two major parts:

1. **Individual Lab – Change Management (Normal Change)**  
2. **Group Activity – Problem Management**

The purpose was to understand how ITSM workflows operate in an enterprise environment, including cross-process relationships such as **Incident → Problem → Change → CI**.

---

## 1. Individual Lab – Change Management

As **“Student A – Change Manager”**, I completed the entire **Normal Change lifecycle** in ServiceNow. This included:

- Creating the Change Request  
- Completing and verifying approvals  
- Scheduling the change  
- Filling in implementation, test, and backout plans  
- Creating change tasks  
- Executing implementation and closure  
- Recording the Change ID  

### **Step 1 – Create the Change Request**

I created a Normal Change with these details:

- **Short Description:** Upgrade Wi-Fi Authentication System to Azure AD SSO  
- **Category:** Network  
- **Risk:** High  
- **Impact:** High  
- **Priority:** 2 – High  
- **Requested by:** Jarvis Galas  
- **Assigned to:** Fred Luddy  
- **Configuration Item:** CAROL3-GATEWAY  
- **Justification:** Reduce login failures and improve security  
- **Description:** Migration of Wi-Fi authentication to Azure AD Single Sign-On  

### **Step 2 – Approvals**

When the status changed to *Waiting for Approval*, I opened the approvers list and updated all entries to:

> **State: Approved**

I refreshed the page until all approvals were completed.

### **Step 3 – Scheduling the Change**

I completed the scheduling fields:

- **Planned Start:** 2025-11-10 22:00  
- **Planned End:** 2025-11-11 05:00  

Planning details included:

- **Implementation Plan:** Deploy Azure AD SSO during maintenance window and test using pilot users  
- **Test Plan:** Validate SSO login for selected students and monitor logs  
- **Backout Plan:** Revert to legacy RADIUS configuration if implementation fails  

I also checked the **Change Calendar** for any scheduling conflicts.

### **Step 4 – Implementation**

I created and completed several tasks, including:

- Backing up configuration  
- Deploying the SSO module  
- Testing authentication  

Each task was updated to:

> **Closed Complete**

Implementation notes:

> “Implementation completed successfully with no authentication errors.”

### **Step 5 – Review & Closure**

In the closure form, I documented:

- **Implementation Results:** Azure AD SSO upgrade applied successfully  
- **Lessons Learned:** User notification could be improved  
- **Close Code:** Successful  
- **Close Notes:** Change completed within the scheduled maintenance window  

I then officially closed the Change.

### **Step 6 – Final Change ID**

Final Change ID:

> **CHG0030001**

---

## 2. Group Activity – Problem Management

In the group activity, we created a **problem scenario** and developed a **Problem Record** that included:

- Root cause  
- Workaround  
- Permanent fix  
- Links to Incident, Change, and CI  
- A one-page summary report  

### **Problem Scenario**

- After a firmware upgrade on wireless controller **ny8500-nbxs08**, the campus network experienced an outage affecting the LMS, video conferencing, and email.  
- A **routing loop** and **VLAN misconfiguration** caused packet loss and session timeouts.

### **Root Cause**

- Configuration conflicts after firmware update  
- Unstable VLAN routing  
- Routing loop generating severe packet loss  

### **Workaround**

- Disable affected VLAN  
- Redirect traffic to a backup switch  

### **Permanent Fix**

- Reinstall firmware  
- Correct VLAN mappings  
- Revalidate routing table  

### **Linking to Change & CMDB**

We learned how the Problem should be:

- Linked to the initial Incident  
- Used to generate a Change for the firmware fix  
- Associated with the correct CI in the CMDB  

---

## Reflection

This week provided hands-on experience with how **Change Management** operates in a real enterprise platform like ServiceNow. From request creation to approval, scheduling, implementation, and closure — every step followed real-world ITSM workflows.

Through **Problem Management**, I gained insight into how a single configuration issue can lead to major service disruptions. Understanding root cause, workaround, and permanent fix helped illustrate how ITSM processes connect and support each other to maintain reliable IT services.

---

## Class Activity PDF

For a detailed breakdown of the activity, refer to the [PDF Class Activity](/My-ITSM-Journey/assets/Week11.pdf) embedded below:

<iframe src="/My-ITSM-Journey/assets/Week10.pdf" width="100%" height="600px"></iframe>
