---
title: Workflow with multiple users in a task
TOCTitle: Workflow with multiple users in a task
ms:assetid: 1a433b99-2c30-44e9-817b-8f9d6554e106
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg751359(v=AX.60)
ms:contentKeyID: 35132565
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Workflow with multiple users in a task [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following figure shows an example of a workflow for an expense report. The workflow includes a task that is assigned to three people: Ivan, Kim, and Dean.

![Workflow that has a task element](images/Gg751359.Workflow_MultipleUsersInTask(AX.60).gif "Workflow that has a task element")

A task can be assigned to multiple people. However, only one person can complete a task.

Assume that Sam has submitted an expense report totaling USD 7,000 and has routed his receipts to Kim for review. Kim must first accept the task. By accepting the task, Kim indicates that she intends to complete it. (The task is then removed from Ivan's work list and Dean's work list.)

After Kim has finished reviewing the receipts, she marks the task as complete. The expense report is then assigned to Frank, and then to Sue, for approval.

Because the total amount is not more than USD 10,000, Ann does not have to approve the expense report. Therefore, after Sue approves the expense report, the workflow ends.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

