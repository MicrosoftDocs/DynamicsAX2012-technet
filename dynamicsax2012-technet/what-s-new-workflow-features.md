---
title: "What's new: Workflow features"
TOCTitle: Workflow features
ms:assetid: 379dee01-56e9-4f06-9f5d-403f4322e58e
ms:mtpsurl: https://technet.microsoft.com/library/Dn507093(v=AX.60)
ms:contentKeyID: 59623181
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# What's new: Workflow features 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following features have been added to the workflow functionality in Microsoft Dynamics AX 2012.

## Simplified installation

Workflow server components no longer have to be installed on a web server that is running Internet Information Services (IIS). Workflow server components are now automatically installed when you install Microsoft Dynamics AX Application Object Server (AOS).

## Upgrade information

Workflows that were created in Microsoft Dynamics AX 2009 are not upgraded. Before you upgrade to AX 2012, we recommend that you either process or recall all business documents that have been submitted for processing. For information about how to recall a document, see [Cancel a workflow instance](cancel-a-workflow-instance.md).

## Workflow editor

The workflow editor is a graphical user interface (GUI) that you can use to create Microsoft Dynamics AX workflows by arranging workflow elements on a design surface. The process resembles the process for graphically modeling a business process by using Microsoft Visio. You can add, delete, and reposition elements that represent the tasks and approvals that make up the workflow. You can also add flow-control elements, such as manual and automated decisions. Therefore, you can create complex workflows that exactly model the business processes that you want to automate. For more information, see [About the workflow editor](about-the-workflow-editor.md).

## Flow-control elements

Several new elements have been added to help you design workflows. You can use these elements to design workflows that have alternate branches or branches that run at the same time. The following list describes these elements:

  - **Conditional decision** – A point at which a workflow divides into two branches. The system determines which branch is used to process the document that was submitted by evaluating whether the document meets specified conditions.

  - **Manual decision** – A point at which a workflow divides into two branches. A user must make a decision, and this decision determines which branch is used to process the document that was submitted.

  - **Parallel activity** – A workflow element that includes two or more branches that run at the same time.

For more information about the elements that you can use to control the flow of documents through a workflow, see [Workflow elements](workflow-elements.md).

## Automated tasks

You can now add automated tasks to workflows. An automated task runs business logic and requires no human interaction. For example, an automated task can perform a credit check, run a report, or update a record.

Before you can add an automated task to a workflow, a software developer must create the automated task. For information about how to create an automated task, see [How to: Create a Workflow Automated Task](https://technet.microsoft.com/library/gg864388\(v=ax.60\)). After the automated task is created, you can add it to a workflow and configure it. For more information, see [Configure an automated task](configure-an-automated-task.md).

## Line-item workflows

A workflow can be created to process documents or the line items on a document. For example, assume that you have created an approval workflow for timesheets. (We will refer to this workflow as the *document workflow*.) You can add a line-item workflow element to that document workflow. When the line-item element is executed, each line item on the document is submitted for processing. All the line items can be processed by the same line-item workflow, or each line item can be processed by a different line-item workflow.

For example, suppose that an employee submits a timesheet that resembles the following figure.

![Workflow with line items](images/Dn507093.Workflow_LineItemWorkflow(AX.60).gif "Workflow with line items")

In this scenario, you might want to create the following line-item workflows:

  - **Line-item workflow 1** – This workflow is used to process line items where the project ID is 1111.

  - **Line-item workflow 2** – This workflow is used to process line items where the project ID is 2222.

  - **Line-item workflow 3** – This workflow is used to process line items where the project ID is 3333.

For information about how to configure line-item workflow elements, see [Configure a line-item workflow](configure-a-line-item-workflow.md). To see an example of a workflow that uses a line-item workflow element, see [Workflow with a line-item workflow element](workflow-with-a-line-item-workflow-element.md).

## Work item queues

In AX 2009, you could assign a workflow task to a user, role, or organizational hierarchy. In AX 2012, you can also assign a workflow task to a work item queue, which is a collection of documents that require processing. A queue must have users assigned to it, and the users are responsible for monitoring the queue and processing the documents that are in it.

You can specify which users are assigned to a queue. A user who is assigned to a queue can complete any of the tasks in the queue. For more information, see [Configure work item queues](configure-work-item-queues.md).

## Workflows and your organizational structure

In AX 2009, each workflow could be used only for a specific company. In AX 2012, a workflow can be used as follows:

  - Across all organizations

  - For a specific organization, such as a particular legal entity

For more information about the types of workflows that you can create and the organizational structures that workflows can be associated with, see [Workflow types](workflow-types.md).

## Notifications

Notifications might be sent to you when workflow-related events occur. The following improvements have been made to the notification system:

  - **Workflow-specific notifications** – Email templates can be used to generate and send workflow notifications. You can now create and use a specific email template for each workflow. Therefore, you can customize the messages so that they are appropriate for each workflow. For more information, see [Configure email settings for the workflow system](configure-email-settings-for-the-workflow-system.md).

  - **Grouped notifications** – In AX 2012, you can create workflows for the line items on a document. Because line-item workflows might generate more email notifications, you can configure the system to group the notifications about line items into a single notification. For more information, see [Configure the workflow notification options](configure-the-workflow-notification-options.md).

## Performance analysis reports

AX 2012 includes an online analytical processing (OLAP) cube for workflows. By using this cube, you can generate reports that show how a workflow performs. Therefore, you can identify bottlenecks in processes. You can also determine whether a workflow is adding efficiency to the business processes and compare the automated workflow to the manual processes that the workflow replaced. The analysis is focused on the amount of work that was done by the workflow and the time that was required to perform the business tasks that make up the workflow. By using these reports, you can modify your workflows and increase their performance. For more information, see [View workflow performance reports](view-workflow-performance-reports.md).

## Workflow history

You can view the history and status of an active or completed workflow and its elements. The workflow history includes data about new workflow features, such as advanced flow controls, automated tasks, line-item workflows, and work item queues. You can view this data either in the Microsoft Dynamics AX client or on Enterprise Portal for Microsoft Dynamics AX. For more information, see [View the status and history of a document](view-the-status-and-history-of-a-document.md).

## Workflow for document management

You can attach a URL to a transaction and configure a workflow to route paper-based document files for review. The document file web service has been added, and can be used to retrieve document file metadata and route the data to the appropriate parties by using workflow. You can enter document data, and the document file can be attached to the new transaction. In this manner, an audit trail is created for the original document. These enhancements can make document handling easier for geographically dispersed companies that want to maintain their paper-based documents in one location.

For more information, see [Using document management](using-document-management.md).

  


