---
title: Workflow elements
TOCTitle: Workflow elements
ms:assetid: 244f32e8-6f95-4f86-bfe5-57b8aa6f667d
ms:mtpsurl: https://technet.microsoft.com/library/Dd309626(v=AX.60)
ms:contentKeyID: 35132582
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Workflow elements 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A workflow consists of *elements*. The following sections describe each type of element.

## Tasks

A task is a unit of work that must be performed. There are two types of tasks that can be added to a workflow: a manual task or an automated task.

## Manual task

A manual task is a unit of work that must be performed by a user. For example, an expense report workflow may have manual tasks that require the assigned users to:

  - Review the receipts that are submitted with an expense report.

  - Call an employee's manager.

For information about how to configure a manual task, see [Configure a manual task](configure-a-manual-task.md). To see an example workflow that uses a manual task, see [Workflow with multiple users in a task](workflow-with-multiple-users-in-a-task.md).

## Automated task

An automated task is a unit of work that must be performed by the system. It requires no human interaction. For example, a sales order workflow may have automated tasks that require the system to:

  - Perform a credit check.

  - Create a customer record for the customer, if one does not already exist.

For information about how to configure an automated task, see [Configure an automated task](configure-an-automated-task.md). To see an example workflow that uses an automated task, see [Workflow with a conditional decision](workflow-with-a-conditional-decision.md).

## Approval processes

An approval process is a process that consists of separate steps. At each approval step, the user can:

  - Approve the document.

  - Reject the document.

  - Request a change to the document.

  - Assign the document to another user for approval.

For information about how to configure an approval process and the steps within it, see [Configure an approval process](configure-an-approval-process.md) and [Configure an approval step](configure-an-approval-step.md). To see an example workflow that uses an approval process, see [Workflow with multiple users in an approval step](workflow-with-multiple-users-in-an-approval-step.md).

## Line-item workflow elements

A workflow can be created to process documents, or the line items on a document. For example, assume that you have created an approval workflow for timesheets. (We will refer to this workflow as the *document workflow*.) You can add a line-item workflow element to that document workflow. When the line-item element is executed, each line item on the document is submitted for processing. You may want all of the line items to be processed by the same line-item workflow, or you may want each line item to be processed by a different line-item workflow.

Suppose that an employee has submitted a timesheet that resembles the following figure.

![Workflow with line items](images/Dn507093.Workflow_LineItemWorkflow(AX.60).gif "Workflow with line items")

In this scenario, you may want to create the following line-item workflows:

  - **Line-item workflow 1** – This workflow is used to process line items where the project ID = 1111.

  - **Line-item workflow 2** – This workflow is used to process line items where the project ID = 2222.

  - **Line-item workflow 3** – This workflow is used to process line items where the project ID = 3333.

For information about how to configure line-item workflow elements, see [Configure a line-item workflow](configure-a-line-item-workflow.md). To see an example workflow that uses a line-item workflow element, see [Workflow with a line-item workflow element](workflow-with-a-line-item-workflow-element.md).

## Flow-control elements

The following elements enable you to design workflows that have alternate branches or branches that run at the same time.

## Manual decision

A manual decision is a point at which a workflow divides into two branches. A user must make a decision, and this decision determines which branch is used to process the document that was submitted.

For information about how to configure a manual decision, see [Configure a manual decision](configure-a-manual-decision.md). To see an example workflow that uses a manual decision, see [Workflow with a manual decision](workflow-with-a-manual-decision.md).

## Conditional decision

A conditional decision is a point at which a workflow divides into two branches. The system decides which branch to use by evaluating the submitted document to determine whether it meets specified conditions.

For information about how to configure a conditional decision, see [Configure a conditional decision](configure-a-conditional-decision.md). To see an example workflow that uses a conditional decision, see [Workflow with a conditional decision](workflow-with-a-conditional-decision.md).

## Parallel activity

A parallel activity is a workflow element that includes two or more workflow branches that run at the same time.

For information about how to configure a parallel activity, see [Configure a parallel activity](configure-a-parallel-activity.md).

## Subworkflow

A subworkflow is a workflow that runs in the context of another workflow.

For information about how to configure a subworkflow, see [Configure a subworkflow](configure-a-subworkflow.md).

  


