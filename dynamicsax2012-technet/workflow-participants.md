---
title: Workflow participants
TOCTitle: Workflow participants
ms:assetid: 14ec4766-5cba-4620-8c73-479f8e86d1a9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd309598(v=AX.60)
ms:contentKeyID: 35410560
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Workflow participants 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic explains the various participants in the workflow system. The following figure shows the workflow for an expense report and identifies the participants.

![Workflow with manual decision](images/Dd362144.Workflow_WithManualDecision(AX.60).gif "Workflow with manual decision")

## System administrator

The Microsoft Dynamics AX system administrator sets up and maintains the workflow system. The system administrator can create any type of workflow and view the status of any workflow instance.

## Workflow owner

A workflow owner is responsible for a particular workflow. For example, if the controller, Linda, is the owner of the expense report workflow, she can configure and modify the expense report workflow. She also receives messages if errors occur when an expense report workflow is processed.

## Originator

An originator submits a document for processing and approval. For example, in the previous figure, Sam is the originator of the expense report.

## Task assignee

A task assignee must complete a task that is related to a document that was submitted for processing. A task can be assigned to multiple people or to a work item queue that is monitored by several people. However, only one person can complete a task.

For example, assume that Sam has submitted an expense report and has routed his receipts to the Adventure Works Expense Reports department for review. Members of the Expense Reports department monitor the queue. Suppose that Julie, a member of the department, has accepted the task of reviewing Sam's expense report and receipts. After Julie completes this task, the expense report moves to the next step in the workflow.

## Decision maker

A decision maker answers a question that is related to a document that was submitted for processing. The answer to the question is typically **Yes** or **No**, or **True** or **False**. The answer that the decision maker selects determines which branch of the workflow is used.

For example, assume that Sam’s expense report is assigned to John. John must decide whether the information on the expense report requires a call to Sam's manager. If John decides that a call is required, the expense report is assigned to Aretha, who must call Sam's manager. If John decides that a call is not required, the expense report is assigned to Frank for approval.

## Approver

An approver reviews and approves, or rejects, a document that was submitted for processing. If the approver approves the document, the document moves to the next step in the workflow, if there is another step. If the approver rejects the document, the document is sent back to the originator. The originator can then change and resubmit the document.

For example, Frank, Sue, and Ann are approvers.

## Delegate

A delegate can act on behalf of another person. For example, an approver who plans to be out of the office for a long time can delegate his or her workflow responsibilities to another approver in the workflow.

For example, if Sue is going on vacation for several weeks, she can delegate her responsibilities to Frank or Ann.

  


