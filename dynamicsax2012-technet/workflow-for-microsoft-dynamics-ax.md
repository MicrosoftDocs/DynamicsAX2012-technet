---
title: Workflow for Microsoft Dynamics AX
TOCTitle: Workflow
ms:assetid: fcc9b643-10f1-4a12-b233-ec29dad62b86
ms:mtpsurl: https://technet.microsoft.com/library/Gg723980(v=AX.60)
ms:contentKeyID: 35133336
author: tonyafehr
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- workflow
---

# Workflow for Microsoft Dynamics AX 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX provides workflow functionality that you can use to ensure that documents are processed and approved in a consistent and efficient manner. This article introduces you to the workflow system in Microsoft Dynamics AX and guides you through the process of configuring, extending, and using it.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/Gg723980.TopicIcon_Lifecycle(AX.60).png" title="Lifecycle" alt="Lifecycle" />
<p>Get started</p>
<p>Configure</p>
<p>Extend</p>
<p>Use</p>
<p>Troubleshoot</p>
<p>View technical reference</p></td>
</tr>
</tbody>
</table>


![Get started](images/Gg723980.LessColor_GetStarted(AX.60).png "Get started")

A workflow represents a business process. A workflow defines how a business document flows through the system by indicating who must process and approve it. Complete the following tasks to become familiar with the workflow system in Microsoft Dynamics AX.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>For more information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Learn about new features</p></td>
<td><p>Many new features have been added to the workflow functionality in Microsoft Dynamics AX 2012. For example:</p>
<ul>
<li><p>Workflow server components no longer have to be installed on a web server that is running Internet Information Services (IIS). Workflow server components are now automatically installed when you install the Application Object Server (AOS) for Microsoft Dynamics AX.</p></li>
<li><p>A workflow editor is now available. The workflow editor is a graphical user interface that you can use to create Microsoft Dynamics AX workflows by arranging workflow elements on a design surface. The process is similar to graphically modeling a business process by using Microsoft Visio.</p></li>
</ul>
<p>See the associated article to view the full list of new features.</p></td>
<td><p><a href="what-s-new-workflow-features.md">What's new: Workflow features</a></p></td>
</tr>
<tr class="even">
<td><p>Understand key concepts about the workflow system</p></td>
<td><p>The term <em>workflow</em> can be defined in two ways: as a system and as a business process.</p>
<ul>
<li><p><strong>Workflow is a system</strong> – Workflow is a system that is installed with Microsoft Dynamics AX and that runs on the AOS. The workflow system provides functionality that you can use to create individual workflows, or business processes.</p></li>
<li><p><strong>Workflow is a business process</strong> – A workflow represents a business process. It defines how a document flows, or moves, through the system by showing who must complete a task, make a decision, or approve a document.</p></li>
</ul>
<p>These articles explain key concepts and terms that you must understand to configure and use the workflow system.</p></td>
<td><p><a href="overview-of-the-workflow-system.md">Overview of the workflow system</a></p>
<p><a href="workflow-system-architecture.md">Workflow system architecture</a></p>
<p><a href="workflow-elements.md">Workflow elements</a></p>
<p><a href="workflow-participants.md">Workflow participants</a></p>
<p><a href="workflow-types.md">Workflow types</a></p>
<p><a href="workflow-actions.md">Workflow actions</a></p>
<p><a href="about-the-workflow-editor.md">About the workflow editor</a></p></td>
</tr>
<tr class="odd">
<td><p>See workflow examples</p></td>
<td><p>You can design and structure a workflow in many ways. These articles provide examples of workflows and explain how documents move through each workflow.</p></td>
<td><p><a href="workflow-with-users.md">Workflow with users</a></p>
<p><a href="workflow-with-roles.md">Workflow with roles</a></p>
<p><a href="workflow-with-multiple-users-in-a-task.md">Workflow with multiple users in a task</a></p>
<p><a href="workflow-with-multiple-users-in-an-approval-step.md">Workflow with multiple users in an approval step</a></p>
<p><a href="workflow-with-a-manual-decision.md">Workflow with a manual decision</a></p>
<p><a href="workflow-with-a-conditional-decision.md">Workflow with a conditional decision</a></p>
<p><a href="workflow-with-a-line-item-workflow-element.md">Workflow with a line-item workflow element</a></p></td>
</tr>
</tbody>
</table>


![Configure](images/Gg723980.LessColor_Configure(AX.60).png "Configure")

The following sections will help you configure the workflow system, create individual workflows, and configure the elements within a workflow.

## Configure the workflow system

Complete the following tasks to enable workflow functionality in Microsoft Dynamics AX.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>For more information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Specify the workflow execution account</p></td>
<td><p>Select a domain account to serve as the workflow execution account. The workflow execution account runs business logic for the application and accesses Microsoft Dynamics AX data.</p></td>
<td><p><a href="specify-the-workflow-execution-account.md">Specify the workflow execution account</a></p></td>
</tr>
<tr class="even">
<td><p>Select number sequences</p></td>
<td><p>An identification number is automatically assigned to every workflow that is created and every instance of a workflow that is generated. The identification numbers are based on number sequences. This article provides information that will help you create number sequences. It also describes how to specify which number sequence is used to generate IDs for workflows, and which number sequence is used to generate IDs for workflow instances.</p></td>
<td><p><a href="select-number-sequences-for-the-workflow-system.md">Select number sequences for the workflow system</a></p></td>
</tr>
<tr class="odd">
<td><p>Configure workflow batch jobs</p></td>
<td><p>The workflow system uses batch jobs to process messages, determine due dates for work items, and process notifications for line items. See these articles for step-by-step instructions that explain how to create a batch group and configure batch jobs.</p></td>
<td><p><a href="create-a-batch-group-for-the-workflow-system.md">Create a batch group for the workflow system</a></p>
<p><a href="run-the-workflow-infrastructure-configuration-wizard.md">Run the Workflow infrastructure configuration wizard</a></p></td>
</tr>
<tr class="even">
<td><p>Set up users for the workflow system</p></td>
<td><p>To make sure that Microsoft Dynamics AX users can participate in workflow processes, you must complete the following tasks:</p>
<ul>
<li><p><strong>Assign users to roles</strong> – Assign users to roles in Microsoft Dynamics AX. For more information, see <a href="assign-users-to-security-roles.md">Assign users to security roles</a>.</p></li>
<li><p><strong>Assign users to employee IDs</strong> – Assign each user to an employee ID by specifying <em>user relations</em>. For information about user relations, see <a href="configure-user-relations.md">Configure user relations</a>.</p></li>
</ul></td>
<td></td>
</tr>
<tr class="odd">
<td><p>Configure email settings</p></td>
<td><p>You can configure Microsoft Dynamics AX to send email messages to users when workflow-related events occur. For example, email messages can be sent to users when documents are assigned to them for approval. See the associated article to configure email settings for the workflow system.</p></td>
<td><p><a href="configure-email-settings-for-the-workflow-system.md">Configure email settings for the workflow system</a></p></td>
</tr>
<tr class="even">
<td><p>Configure work item queues</p></td>
<td><p>A manual task can be assigned to a <em>work item queue</em>, which is a collection of documents that require processing. Every work item queue must have users assigned to it who are responsible for monitoring the queue and processing the documents that are in it.</p></td>
<td><p><a href="create-a-work-item-queue.md">Create a work item queue</a></p>
<p><a href="create-a-work-item-queue-group.md">Create a work item queue group</a></p>
<p><a href="view-the-work-items-in-the-queues-that-you-administer.md">View the work items in the queues that you administer</a></p></td>
</tr>
</tbody>
</table>


## Configure workflows

Complete the following tasks to create and configure business processes, or workflows, in the workflow editor.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>For more information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create a workflow</p></td>
<td><p>Creating a workflow involves opening the workflow editor, dragging the workflow elements you want to use onto the canvas, and configuring properties. The associated article will walk you through this process.</p></td>
<td><p><a href="create-a-workflow.md">Create a workflow</a></p></td>
</tr>
<tr class="even">
<td><p>Configure the properties of a workflow</p></td>
<td><p>To configure the properties of a workflow, open the workflow in the workflow editor. Click the canvas of the workflow editor and then click <strong>Properties</strong> to open the <strong>Properties</strong> form. You’ll need to enter a name for the workflow, specify when the workflow should be used, and specify when notifications regarding this workflow should be sent to users.</p></td>
<td><p><a href="configure-the-properties-of-a-workflow.md">Configure the properties of a workflow</a></p></td>
</tr>
<tr class="odd">
<td><p>Specify default workflows</p></td>
<td><p>You can create multiple workflows of the same type. For example, you can have the following purchase requisition workflows:</p>
<ul>
<li><p><strong>Purchase Requisitions Denmark</strong> – This workflow is used when country/region = DK.</p></li>
<li><p><strong>Purchase Requisitions Spain</strong> – This workflow is used when country/region = ES.</p></li>
</ul>
<p>When you have multiple workflows of the same type, you must specify which workflow is the <em>default workflow</em>. Documents that do not meet any of the activation conditions are processed by the default workflow.</p></td>
<td><p><a href="indicate-that-a-workflow-is-the-default-workflow.md">Indicate that a workflow is the default workflow</a></p></td>
</tr>
</tbody>
</table>


## Configure the elements of a workflow

A workflow consists of *elements*, such as a task or an approval process. The information in the following table will help you learn more about the elements and configure them.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>For more information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Learn about the workflow elements</p></td>
<td><p>A workflow may consist of several types of elements. For example, a workflow may consist of a manual task, an approval, and a conditional decision. This article describes each type of element and explains why you’d want to use each element.</p></td>
<td><p><a href="workflow-elements.md">Workflow elements</a></p></td>
</tr>
<tr class="even">
<td><p>Configure an element</p></td>
<td><p>These articles explain how to configure the properties of each workflow element.</p></td>
<td><p><a href="configure-a-manual-task.md">Configure a manual task</a></p>
<p><a href="configure-an-automated-task.md">Configure an automated task</a></p>
<p><a href="configure-an-approval-process.md">Configure an approval process</a></p>
<p><a href="configure-a-manual-decision.md">Configure a manual decision</a></p>
<p><a href="configure-a-conditional-decision.md">Configure a conditional decision</a></p>
<p><a href="configure-a-parallel-activity.md">Configure a parallel activity</a></p>
<p><a href="configure-a-subworkflow.md">Configure a subworkflow</a></p>
<p><a href="configure-a-line-item-workflow.md">Configure a line-item workflow</a></p></td>
</tr>
</tbody>
</table>


![Extend](images/Gg723980.LessColor_Extend(AX.60).png "Extend")

Complete the tasks in the following table to add workflow functionality to a module in Microsoft Dynamics AX.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>For more information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Learn about the development process</p></td>
<td><p>Workflow is defined as the movement of documents or tasks through a work process. In Microsoft Dynamics AX, the focus of workflow is on approval and task-oriented workflows. The developer role in Microsoft Dynamics AX is primarily to add workflow to existing business documents or create new documents that support workflow. These topics describes what the workflow life cycle is and the developer role for a workflow in Microsoft Dynamics AX.</p></td>
<td><p><a href="https://technet.microsoft.com/library/cc967429(v=ax.60)">About Workflow Development</a></p>
<p><a href="https://technet.microsoft.com/library/cc967389(v=ax.60)">Developing a Workflow</a></p></td>
</tr>
<tr class="even">
<td><p>Review security considerations</p></td>
<td><p>Security in workflow is part of the standard security implementation in Microsoft Dynamics AX. This topic describes specific workflow security considerations.</p></td>
<td><p><a href="https://technet.microsoft.com/library/cc641033(v=ax.60)">Workflow Security</a></p></td>
</tr>
<tr class="odd">
<td><p>Create a workflow type</p></td>
<td><p>To add workflow support for a document in Microsoft Dynamics AX, you must create a workflow type. This section describes the procedures to create a workflow type in Microsoft Dynamics AX. The workflow type can then be used to create workflow configurations for the document the Microsoft Dynamics AX.</p></td>
<td><p><a href="https://technet.microsoft.com/library/cc637397(v=ax.60)">Workflow Type Checklist</a></p>
<p><a href="https://technet.microsoft.com/library/cc589698(v=ax.60)">How to: Create a Workflow Category</a></p>
<p><a href="https://technet.microsoft.com/library/hh457520(v=ax.60)">How to: Create a Query for a Workflow Type</a></p>
<p><a href="https://technet.microsoft.com/library/cc594095(v=ax.60)">How to: Create a New Workflow Type</a></p>
<p><a href="https://technet.microsoft.com/library/cc592495(v=ax.60)">How to: Create a Workflow Document Class</a></p>
<p><a href="https://technet.microsoft.com/library/cc583139(v=ax.60)">How to: Create a SubmitToWorkflow Class</a></p>
<p><a href="https://technet.microsoft.com/library/cc556363(v=ax.60)">How to: Associate a Workflow Document Class with a Workflow Type</a></p>
<p><a href="https://technet.microsoft.com/library/cc641259(v=ax.60)">Walkthrough: Creating a Workflow Type</a></p></td>
</tr>
<tr class="even">
<td><p>Enable workflow functionality in a module</p></td>
<td><p>To enable a Microsoft Dynamics AX workflow for a new or existing application module, you must complete a series of required steps and then, depending on application requirements, complete additional steps. This topic describes the required steps to add workflow to your application.</p></td>
<td><p><a href="https://technet.microsoft.com/library/cc603594(v=ax.60)">Requirements for Enabling Workflow in an Application Module</a></p>
<p><a href="https://technet.microsoft.com/library/cc592907(v=ax.60)">How to: Enable a State Model for a Workflow Document</a></p>
<p><a href="https://technet.microsoft.com/library/hh330384(v=ax.60)">How to: Enable Workflow Submission</a></p>
<p><a href="https://technet.microsoft.com/library/cc602813(v=ax.60)">How to: Enable a Form or List for Workflow</a></p>
<p><a href="https://technet.microsoft.com/library/cc624367(v=ax.60)">How to: Create a New Module with Workflow</a></p>
<p><a href="https://technet.microsoft.com/library/cc618309(v=ax.60)">How to: Activate a Workflow from a Workflow Type</a></p>
<p><a href="https://technet.microsoft.com/library/cc554429(v=ax.60)">How to: Activate a Workflow using the Configuration ID</a></p>
<p><a href="https://technet.microsoft.com/library/cc618781(v=ax.60)">How to: Activate a Workflow using the Sequence Number</a></p></td>
</tr>
<tr class="odd">
<td><p>Create tasks, automated tasks, and approvals</p></td>
<td><p>After you create a workflow type, you continue the process for creating a Microsoft Dynamics AX workflow by adding tasks, automated tasks, and approvals to the workflow type. A task is a workflow element with a single step defined in the Application Object Tree (AOT) that is used to implement task-based processes. An automated task is a workflow element used to invoke X++ code within the application without requiring user intervention. An approval is a specialized task that can have multiple steps defined in the AOT that is used to implement approval processes.</p>
<p>You create tasks, automated tasks, and approvals in separate AOT nodes and then, you can add them to the workflow type <strong>Supported Elements</strong> node. The same tasks and approvals can also be added to different workflow types.</p></td>
<td><p><a href="https://technet.microsoft.com/library/hh457521(v=ax.60)">Workflow Tasks</a></p>
<p><a href="https://technet.microsoft.com/library/hh457522(v=ax.60)">Workflow Automated Tasks</a></p>
<p><a href="https://technet.microsoft.com/library/hh457524(v=ax.60)">Workflow Approvals</a></p>
<p><a href="https://technet.microsoft.com/library/cc602158(v=ax.60)">How to: Associate an Action Menu Item with a Workflow Task or Approval Outcome</a></p>
<p><a href="https://technet.microsoft.com/library/cc604521(v=ax.60)">How to: Associate a Display Menu item with a Workflow Task or Approval</a></p>
<p><a href="https://technet.microsoft.com/library/cc654026(v=ax.60)">How to: Add a Task, Automated Task, or Approval to a Workflow Type</a></p></td>
</tr>
<tr class="even">
<td><p>Implement workflow events</p></td>
<td><p>Microsoft Dynamics AX workflow uses events to initiate business logic in your application. For example, the workflow type has a property event handler for business logic when a workflow is started. Workflow tasks and approvals have started and canceled property event handlers and also an event handler for each outcome type. This section describes workflow events and how to implement them in your application.</p></td>
<td><p><a href="https://technet.microsoft.com/library/cc588240(v=ax.60)">Workflow Events Overview</a></p>
<p><a href="https://technet.microsoft.com/library/cc606215(v=ax.60)">How to: Create a Workflow Event Handler</a></p>
<p><a href="https://technet.microsoft.com/library/cc623606(v=ax.60)">How to: Create a Workflow Task or Approval Event Handler</a></p></td>
</tr>
<tr class="odd">
<td><p>Create line-item workflows</p></td>
<td><p>Microsoft Dynamics AX lets you configure workflows for the line items in a document. For example, you can have a workflow for the line items in the purchase requisition document. The line items can use the same workflow, or they can each use a separate workflow. The following topics describe how to create a line-item workflow.</p></td>
<td><p><a href="https://technet.microsoft.com/library/hh528504(v=ax.60)">Line-item Workflow Checklist</a></p>
<p><a href="https://technet.microsoft.com/library/hh528502(v=ax.60)">How to: Create a Line-item Workflow</a></p></td>
</tr>
<tr class="even">
<td><p>Create a custom workflow provider</p></td>
<td><p>Workflow providers in Microsoft Dynamics AX provide application-specific data for a workflow at runtime. The application data provided can include the following:</p>
<ol>
<li><p>User IDs based on user groups.</p></li>
<li><p>Due dates based on employee or manager working days.</p></li>
<li><p>Specific user or manager IDs based on their maximum approval limits.</p></li>
<li><p>A queue to which a work item is to be assigned.</p></li>
</ol>
<p>The following topics describe the workflow providers in Microsoft Dynamics AX, the programming interface for each provider, and how to create a customized version of a provider.</p></td>
<td><p><a href="https://technet.microsoft.com/library/cc519521(v=ax.60)">Workflow Providers Overview</a></p>
<p><a href="https://technet.microsoft.com/library/hh528513(v=ax.60)">Workflow Provider Interfaces</a></p>
<p><a href="https://technet.microsoft.com/library/cc633997(v=ax.60)">How to: Create a Custom Workflow Provider</a></p></td>
</tr>
</tbody>
</table>


![Use](images/Gg723980.LessColor_Use(AX.60).png "Use")

The information in the following table will help users in your organization complete workflow-related tasks, such as submitting documents for approval, or reviewing the status of a document that was submitted for approval.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>For more information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Configure the workflow notification options</p></td>
<td><p>Notifications may be sent to you when workflow-related events occur. For example, a notification may be sent to you when a document is assigned to you for approval or when the workflow process is completed for a document that you submitted. You can specify how you want to receive workflow notifications.</p></td>
<td><p><a href="configure-the-workflow-notification-options.md">Configure the workflow notification options</a></p></td>
</tr>
<tr class="even">
<td><p>Submit a document for approval</p></td>
<td><p>To submit a document to the workflow system for processing, click the <strong>Submit</strong> button in the form that you are working in. For example, to submit a purchase requisition, click the <strong>Submit</strong> button in the <strong>Purchase requisitions</strong> form.</p></td>
<td><p><a href="submit-a-document.md">Submit a document</a></p></td>
</tr>
<tr class="odd">
<td><p>View the status and history of a document that you submitted</p></td>
<td><p>To view the status and history of a document that you submitted for processing, use the <strong>Workflow history</strong> form. Click <strong>Home</strong> &gt; <strong>Inquiries</strong> &gt; <strong>Workflow</strong> &gt; <strong>Workflow history</strong>.</p></td>
<td><p><a href="view-the-status-and-history-of-a-document-that-you-submitted.md">View the status and history of a document that you submitted</a></p></td>
</tr>
<tr class="even">
<td><p>Recall a document from the workflow process</p></td>
<td><p>To stop the workflow system from processing a document that was submitted, you must <em>recall</em> the document.</p></td>
<td><p><a href="recall-a-document-from-the-workflow-process.md">Recall a document from the workflow process</a></p></td>
</tr>
<tr class="odd">
<td><p>Respond to work items</p></td>
<td><p><em>Work items</em> are workflow-related tasks that are assigned to you. For example, you may have to approve a document, make a decision about a document, or complete a task that is associated with a document. These articles explain how to respond to the work items that are assigned to you.</p></td>
<td><p><a href="view-your-work-items-in-a-workflow.md">View your work items in a workflow</a></p>
<p><a href="act-on-a-task.md">Act on a task</a></p>
<p><a href="review-a-document-assigned-to-you-for-approval.md">Review a document assigned to you for approval</a></p>
<p><a href="complete-a-workflow-decision.md">Complete a workflow decision</a></p>
<p><a href="delegate-work-items-in-a-workflow.md">Delegate work items in a workflow</a></p></td>
</tr>
</tbody>
</table>


![Troubleshoot](images/Gg723980.LessColor_Troubleshoot(AX.60).png "Troubleshoot")

The following table points to troubleshooting resources.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>For more information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Troubleshoot common problems</p></td>
<td><p>This topic describes common problems that can occur when you develop and test a workflow in Microsoft Dynamics AX.</p></td>
<td><p><a href="https://technet.microsoft.com/library/cc616520(v=ax.60)">Troubleshooting Workflow in Microsoft Dynamics AX</a></p>
<p><a href="https://technet.microsoft.com/library/dd638052(v=ax.60)">How to: Debug X++ Code in Workflow</a></p></td>
</tr>
</tbody>
</table>


![View technical reference](images/Gg723980.LessColor_ViewTechRef(AX.60).png "View technical reference")

Microsoft SQL Server Reporting Services (SSRS) reports and a Microsoft SQL Server Analysis Services (SSAS) cube are available to help you monitor and manage workflows. Technical reference content is available that provides details about these reports and the cube.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>For more information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>View technical content about workflow reports (SSRS)</p></td>
<td><p>Microsoft Dynamics AX includes reports that can help you track the history and current status of business processes in your organization.</p></td>
<td><p><a href="workflow-automation-report-workflowautomationreport.md">Workflow automation report (WorkflowAutomationReport)</a></p>
<p><a href="workflow-elements-automation-report-workflowelementsautomationreport.md">Workflow elements automation report (WorkflowElementsAutomationReport)</a></p>
<p><a href="workflow-elements-performance-report-workflowelementsperformancereport.md">Workflow elements performance report (WorkflowElementsPerformanceReport)</a></p>
<p><a href="workflow-instance-by-status-report-workflowinstancebystatusreport.md">Workflow instance by status report (WorkflowInstanceByStatusReport)</a></p>
<p><a href="workflow-participants-performance-report-workflowparticipantperformancereport.md">Workflow participants performance report (WorkflowParticipantPerformanceReport)</a></p>
<p><a href="workflow-performance-report-workflowperformancereport.md">Workflow performance report (WorkflowPerformanceReport)</a></p>
<p><a href="workflow-tracking-report-workflowtrackingreport.md">Workflow tracking report (WorkflowTrackingReport)</a></p></td>
</tr>
<tr class="even">
<td><p>View technical content about the workflow cube (SSAS)</p></td>
<td><p>The workflow cube provides data that can help you track the performance and degree of automation associated with business processes in your organization, which will enable you to identify processes that have become inefficient.</p></td>
<td><p><a href="workflow-cube-workflowcube-for-microsoft-dynamics-ax-2012-r2-and-r3.md">Workflow cube (WorkflowCube) for Microsoft Dynamics AX 2012 R2</a></p>
<p><a href="workflow-cube-workflowcube-for-microsoft-dynamics-ax-2012-and-microsoft-dynamics-ax-2012-feature-pack.md">Workflow cube (WorkflowCube) for Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack</a></p></td>
</tr>
</tbody>
</table>

  


