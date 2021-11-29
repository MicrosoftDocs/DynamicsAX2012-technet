---
title: Workflow actions
TOCTitle: Workflow actions
ms:assetid: ff86d512-f01e-4089-93b1-1a5810587ed8
ms:mtpsurl: https://technet.microsoft.com/library/Dd362144(v=AX.60)
ms:contentKeyID: 35133354
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Workflow actions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A workflow can involve several groups of people: the originator, task assignees, decision makers, and approvers. For example, in the following expense report workflow, Sam is the originator; the members of the queue are task assignees; John is a decision maker; and Frank, Sue, and Ann are approvers.

![Workflow with manual decision](images/Dd362144.Workflow_WithManualDecision(AX.60).gif "Workflow with manual decision")

The following sections explain the workflow actions that each of these groups of people can take.

## Actions that an originator can take

The originator starts a workflow instance by submitting a document for processing. For example, in order for Sam to submit his expense report, he must click the **Submit** button on the **Expense report** form.

## Actions that a task assignee can take

A task can be assigned to multiple people or to a work item queue that is monitored by several people. However, only one person can complete a task.

Using the workflow illustrated in the previous figure, assume that Sam has submitted an expense report and has routed his receipts to his organization's Expense Reports department for review. The members of the Adventure Works Expense Reports department monitor the queue. Suppose that Julie, a member of the department, has accepted the task of reviewing Sam's expense report and receipts. She can take one of the following actions: complete, reject, delegate, request change, reassign, or release.


> [!NOTE]
> <P>The actions available vary, depending on how the software developer designed the task.</P>



## Complete

When a user completes a task, the document that was submitted for processing is assigned to the next user in the workflow, if there is one. If no additional processing is required, the workflow process ends.

For example, assume that Julie, a member of the Adventure Works Expense Reports department, has accepted the task of reviewing Sam’s expense report and receipts. After Julie completes the task, the expense report is assigned to John.

## Reject

When a user rejects a document, the workflow process ends.

For example, assume that Julie, a member of the Adventure Works Expense Reports department, has accepted the task of reviewing Sam’s expense report and receipts. If Julie rejects the document, the workflow process ends.

Sam can resubmit the expense report, with or without changes. If Sam resubmits the expense report, the workflow process starts at the manual task.

## Delegate

When a user delegates a task, the task is assigned to another user.

For example, assume that Julie, a member of the Adventure Works Expense Reports department, has accepted the task of reviewing Sam's expense report and receipts. Julie delegates this task to Tim, her assistant.

Tim then acts on behalf of Julie. This means that when Tim completes the task, the expense report is assigned to John, just as if Julie had completed the task.

## Request change

When a user requests a change to a document that was submitted, the document is sent back to the originator.

For example, assume that Julie, a member of the Adventure Works Expense Reports department, has accepted the task of reviewing Sam's expense report and receipts. Julie notices some errors on the expense report and requests changes to the report. The expense report is sent back to Sam.

Sam can resubmit the expense report, with or without changes. If Sam resubmits the expense report, a member of the queue must review the report and the receipts again.

## Reassign

The members of a work item queue can reassign documents that are in the queue to another queue.

For example, assume that Julie, a member of the Adventure Works Expense Reports department, is monitoring the queue. To help balance workload, she can reassign the expense report, and the receipts included with it, to another queue.

## Release

If a member of a work item queue has accepted a task and then later decides that she cannot complete the task, she can release the document back to the work item queue.

For example, assume that Julie, a member of the Adventure Works Expense Reports department, has accepted the task of reviewing Sam's expense report and receipts. If Julie decides that she is not able to complete the task, she can release the document. The expense report is returned to the queue so that other members of the Adventure Works Expense Reports department can complete the task.

## Actions that a decision maker can take

When a document is assigned to a decision maker, it is typically because a question must be answered by the decision maker. The answer to the question is typically **Yes** or **No**, or **True** or **False**. If the decision maker does not select one of those choices, the decision maker can delegate the decision.

## \[Choice 1\] or \[Choice 2\]

A decision maker has to answer a question that is related to the document. The answer to the question is typically **Yes** or **No**, or **True** or **False**. The answer that the decision maker selects determines which workflow branch is used to process the document.

For example, assume that Sam's expense report is assigned to John. John must decide whether the information that is contained in the expense report requires a call to the employee's manager. If John decides that a call is required, the expense report is assigned to Aretha, who must call the employee's manager. If John decides that a call is not required, the expense report is assigned to Frank for approval.

## Delegate

When a decision maker delegates a decision, the document is assigned to another user who must make the decision.

For example, assume that Sam's expense report is assigned to John. John delegates the decision to Maria, his assistant.

Maria then acts on behalf of John. If Maria decides that a call is required, the expense report is assigned to Aretha, who must call the employee's manager. If Maria decides that a call is not required, the expense report is assigned to Frank for approval.

## Actions that an approver can take

When a document is assigned to an approver, the approver can take one of the following actions: approve, reject, delegate, or request change.

## Approve

When an approver approves a document, the document is assigned to the next user in the workflow, if there is one. If no additional processing is required, the workflow process ends.

For example, assume that Sam has submitted an expense report for USD 6,000 and that it is assigned to Frank. When Frank approves the document, it is assigned to Sue for approval. When Sue approves it, the workflow process ends.

## Reject

When an approver rejects a document, the workflow process ends.

For example, assume that Sam has submitted an expense report for USD 12,000 and that it is assigned to Sue. If Sue rejects the expense report, the workflow process ends.

Sam can resubmit the expense report, with or without changes. If Sam resubmits the expense report, the workflow process starts at the approval process.

## Delegate

When an approver delegates a document, the document is assigned to another user for approval.

For example, assume that Sam has submitted an expense report for USD 12,000 and that it is assigned to Frank. Frank delegates the expense report to Ann.

Ann then acts on behalf of Frank. This means that when Ann approves the document, the document is assigned to Sue for approval, just as if Frank had approved it. After Sue approves the document, it is sent to Ann for approval.

## Request change

When an approver requests a change to a document, the document is sent back to the originator.

For example, assume that Sam has submitted an expense report for USD 12,000 and that it is assigned to Sue. If Sue requests a change, the expense report is sent back to Sam.

Sam can resubmit the expense report, with or without changes. If Sam resubmits the expense report, it is sent to Frank for approval because Frank is the first approver in the approval process.

  


