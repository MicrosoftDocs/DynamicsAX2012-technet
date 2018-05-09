---
title: Workflow with a manual decision
TOCTitle: Workflow with a manual decision
ms:assetid: cce4d322-7209-41e7-9610-dfddd05bb8b7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh538460(v=AX.60)
ms:contentKeyID: 39508889
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Workflow with a manual decision 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following figure shows an example of a workflow for an expense report. The workflow includes a manual decision.

![Workflow with manual decision](images/Dd362144.Workflow_WithManualDecision(AX.60).gif "Workflow with manual decision")

To understand how a document moves through this workflow, assume that Sam has submitted an expense report that totals USD 12,000 and has routed his receipts to the Adventure Works Expense Reports department for review. Members of the Expense Reports department monitor the queue. Suppose that Julie, a member of the department, has accepted the task of reviewing Sam's expense report and receipts. After Julie completes this task, the expense report is assigned to John.

John must decide whether the information on the expense report requires a call to Sam's manager. In this example, John has a question about a line item on the expense report. Therefore, he decides that a call to Sam’s manager is required. The expense report is then assigned to Aretha, John’s assistant.

Aretha calls Sam’s manager and determines that the line item that John had a question about is accurate and complies with corporate policies. Aretha marks her task as completed. The expense report is then assigned to the approvers in the approval process, as shown in the figure.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

