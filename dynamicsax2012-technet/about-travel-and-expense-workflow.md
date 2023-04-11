---
title: About Travel and expense workflow
TOCTitle: About Travel and expense workflow
ms:assetid: a9faf429-98fe-4958-9528-abf239298f60
ms:mtpsurl: https://technet.microsoft.com/library/Gg243082(v=AX.60)
ms:contentKeyID: 39519272
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About Travel and expense workflow 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the workflow system in Microsoft Dynamics AX to set up a review process for expense reports in **Travel and expense**. You can set up a work flow to determine who approves expense reports based on any of the following criteria:

  - The employee reporting hierarchy and predefined approval limits

  - Financial dimensions and project responsibility

  - Assignment to specific users or user groups

Workflow approvals can be created for expense reports, travel requisitions, cash advances, credit card disputes, and value-added tax (VAT) recovery.

**Example**

The following process is an example of the expense management workflow for an expense report.

1.  An employee creates and saves an expense report.

2.  The employee submits the expense report for approval. The approver is identified based on the rules that were defined when the workflow was set up.

3.  The approver receives notification that an expense report is ready for approval. The approver reviews the expense report and verifies that the following conditions are met:
    
      - The expenses do not violate any expense policies. If an expense does violate a policy, the approver verifies that a valid business justification is included in the report.
    
      - Electronic receipts are attached to the expense report.

4.  The approver approves the expense report.

5.  The expense report is assigned to the accounts payable coordinator for posting.
    
      - If automatic posting is configured, the expense report is processed for payment and the status of the expense report is updated.
    
      - If automatic posting is not configured, the accounts payable coordinator verifies that all original receipts have been submitted, and that the receipts align with the expenses on the expense report. All tax codes entered on the expense report must also be verified as correct. After these requirements are verified, the expense report is posted.

After the expense report is posted, payment is authorized for the expense report and the employee is reimbursed.

  


