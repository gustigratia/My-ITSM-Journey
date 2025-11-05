---
theme: minima
layout: post
title: "Week 10 - Change, Release, and Configuration Management"
date: 2025-10-28
excerpt: "In this week’s lab, I explored three critical ITIL processes — Change Management, Release & Deployment Management, and Configuration & Asset Management — through a case study of the Campus Wi-Fi Authentication Upgrade and the new Online Course Registration Portal (OCRP) deployment."
---


## Week 10 — Change, Release, and Configuration Management

This week, our group explored the Service Transition phase of ITIL, focusing on how changes are controlled, deployed, and tracked within an organization.  
We collaborated to create documentation and records for **Change Management**, **Release Management**, and **Configuration Management** based on real IT service scenarios.

---

## 1. Change Management  
Our group created a **Request for Change (RFC)** document for the **Campus Wi-Fi Authentication Upgrade (RFC2025-WIFI-01)**.  
The document included:
- General information (change ID, owner, initiator, and priority).  
- A **business case** explaining the migration to Azure AD Single Sign-On (SSO).  
- **Impact and risk analysis**, including rollback and mitigation plans.  
- A **deployment schedule** for pilot testing, full rollout, and post-monitoring.  
- A **CAB decision** approving the change.

This part helped us understand how formal change requests are evaluated and approved in ITIL environments.

---


## 2. Release & Deployment Management  
We then created a **Release Plan** for the **Online Course Registration Portal (OCRP)** deployment, linked to the Wi-Fi SSO upgrade.  
The release plan contained:
- The **release ID (REL-2025-01)** and its dependency on the approved RFC.  
- Description of the new system and its integration with Azure AD.  
- Implementation roles (application lead, database admin, network engineer, QA tester).  
- A **rollout timeline** covering development, testing, pilot release, and post-review.

This task demonstrated how release processes ensure smooth transitions from testing to production.

---

## 3. Configuration & Asset Management  
Finally, we updated **Configuration Item (CI)** records in the **CMDB** after the Wi-Fi and OCRP implementations.  
Each CI (Authentication Gateway, Application Server, and OCRP Portal) was updated with:
- Version numbers, responsible teams, and current status.  
- Relationships between CIs (e.g., OCRP runs on the Application Server).  
- References to the related RFC and Release IDs.

This activity showed how accurate CMDB data supports better control and traceability in IT operations.

---

## Reflection  
This group task provided hands-on experience with ITIL Service Transition.  
By working together on the **RFC**, **Release Plan**, and **Configuration Records**, we learned how these processes connect — ensuring changes are authorized, deployed safely, and properly documented.  
It highlighted how collaboration, documentation accuracy, and clear workflows are essential for maintaining reliable IT services.

---

## Class Activity PDF

For a detailed breakdown of the activity, refer to the [PDF Class Activity](/My-ITSM-Journey/assets/Week10.pdf) embedded below:

<iframe src="/My-ITSM-Journey/assets/Week10.pdf" width="100%" height="600px"></iframe>


