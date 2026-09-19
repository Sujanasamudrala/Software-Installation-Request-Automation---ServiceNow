# 🚀 Licensed Software Installation Request Automation

**ServiceNow | Service Catalog | Flow Designer | Workflow Automation | ITSM**

An end-to-end ServiceNow automation project that streamlines the process of requesting, approving, and fulfilling licensed software installation requests.

The solution replaces manual, email-based coordination with a standardized **Service Catalog request** and automated workflow, improving efficiency, transparency, and request tracking.

## 📌 Project Overview

Manual software installation requests can result in delays, incomplete information, inconsistent approvals, and poor visibility.

This project provides a centralized **ServiceNow solution** where employees can submit software installation requests through the Service Catalog, while ServiceNow automates notifications, approvals, and IT fulfillment.

## 🎯 Objectives

- Reduce manual effort and processing delays
- Standardize software installation requests
- Automate approval and notification processes
- Improve request visibility and tracking
- Enhance employee experience
- Support software licensing and IT governance

## 🔄 Workflow
Employee  
↓  
Service Catalog  
↓  
Software Installation Request  
↓  
REQ / RITM Creation  
↓  
Approval  
↓  
Email Notification  
↓  
Catalog Task (SCTASK)  
↓  
Software Support Team  
↓  
Request Completion

## 🛠️ Technologies & ServiceNow Components
| Component               | Purpose                        |
| ----------------------- | ------------------------------ |
| **ServiceNow**          | IT Service Management platform |
| **Service Catalog**     | Employee request interface     |
| **Flow Designer**       | Workflow automation            |
| **Catalog Variables**   | Capture request details        |
| **Send Email**          | Submission confirmation        |
| **Ask For Approval**    | Approval processing            |
| **Create Catalog Task** | IT fulfillment                 |
| **sc_request**          | Request record                 |
| **sc_req_item**         | Requested Item (RITM)          |
| **sc_task**             | Catalog Task                   |

## 📝 Service Catalog Variables
| Variable                  | Type             | Purpose                  |
| ------------------------- | ---------------- | ------------------------ |
| **Software**              | Single Line Text | Software required        |
| **Version**               | Single Line Text | Required version         |
| **License Justification** | Multi Line Text  | Reason for the request   |
| **Urgency**               | Choice           | Normal / High / Critical |

## Project Outcome
Successfully automated the licensed software request lifecycle in ServiceNow, enabling standardized submission, automated notification and approval, IT task creation, and centralized request tracking—reducing manual effort and improving transparency and efficiency.
