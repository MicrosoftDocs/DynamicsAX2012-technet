---
title: Worker resource scheduling
TOCTitle: Worker resource scheduling
ms:assetid: 3f8d1c12-8932-4ada-893d-e6c542f661d2
ms:mtpsurl: https://technet.microsoft.com/library/Dn783210(v=AX.60)
ms:contentKeyID: 62835103
author: Khairunj
ms.date: 09/10/2014
mtps_version: v=AX.60
f1_keywords:
- resource scheduling
- assign workers
- schedule workers
- project schedule
- project team
audience: Application User
ms.search.region: Global
---

# Worker resource scheduling 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX 2012 provides the capability to schedule workers for a project either based on its requirements and schedule, or based on the skills and availability of workers. The worker scheduling tools in AX 2012 are designed to help you quickly find the most qualified workers who are available to work on the tasks and activities in a project. These tools also let you easily see how you can best utilize those workers during the project based on their available capacity.

This article introduces you to resources to help you understand how worker resource scheduling for projects works in Microsoft Dynamics AX 2012, what general setting choices you must make for projects to support resource scheduling, and how to search for and select the workers whose time you want to book for your projects.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/Gg723980.TopicIcon_Lifecycle(AX.60).png" title="Lifecycle" alt="Lifecycle" />
<p>Understand the fundamentals</p>
<p>Choose general options, options for workers, and options for all projects</p>
<p>Schedule workers for projects</p></td>
<td><img src="images/Dn507140.TopicIcons_Resources(AX.60).png" title="Resources" alt="Resources" />
<p><a href="http://go.microsoft.com/fwlink/?linkid=268038%26amp%3bclcid=0x409">Worker resource scheduling in Microsoft Dynamics AX 2012 R2</a> (white paper)</p>
<p><a href="http://www.microsoft.com/en-us/download/details.aspx?id=43112">Worker resource scheduling in Microsoft Dynamics AX 2012 R3</a> (white paper)</p>
<p><a href="https://www.youtube.com/watch?v=cp33redl9es">Microsoft Dynamics AX 2012 R3 for Service Industries demo: Staff for success</a> (video)</p>
<p><a href="create-or-update-a-project-by-using-microsoft-project.md">Create or update a project by using Microsoft Project</a> (article)</p>
<p><a href="http://community.dynamics.com/ax/b/dynamicsaxtipoftheday/archive/2014/01/23/assign-workers-to-projects-visually-using-the-worker-reservation-screen.aspx">Assign Workers To Projects Visually Using The Worker Reservation Screen</a> (blog post)</p></td>
</tr>
</tbody>
</table>


## Understand the fundamentals

To help you understand the fundamental concepts of worker scheduling before you begin staffing projects, see the resources in the following table.

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
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Learn about worker resource scheduling.</p></td>
<td><p>Get a high-level overview of the worker resource scheduling capabilities in Microsoft Dynamics AX 2012, and view a list of prerequisites that must be met before you can use the worker resource scheduling tools.</p></td>
<td><p><a href="about-resource-management-for-projects.md">About resource management for projects</a></p></td>
</tr>
<tr class="even">
<td><p>Learn about hour redistribution in AX 2012 R3.</p></td>
<td><p>Understand how hours are redistributed among workers when you remove one or more resources from a task assignment.</p></td>
<td><p><a href="about-redistributing-manually-assigned-hours-for-a-work-breakdown-structure-in-ax-2012-r3.md">About redistributing manually assigned hours for a work breakdown structure in AX 2012 R3</a></p></td>
</tr>
</tbody>
</table>


Back to top

## Choose general options, options for workers, and options for all projects

To understand how to choose system-wide and individual worker options that must be in place before you can schedule workers to project, see the resources in the following table.

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
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Set up resource scheduling options for all projects.</p></td>
<td><p>Select the working calendar that will be used as the default for the projects you manage and specify how closely workers’ skills and availability must match your search requirements before they are shown in available worker lists.</p></td>
<td><p><a href="https://technet.microsoft.com/library/aa599440(v=ax.60)">Project management and accounting parameters (form)</a></p></td>
</tr>
<tr class="even">
<td><p>Set up worker attributes.</p></td>
<td><p>In versions of Microsoft Dynamics AX 2012 earlier than cumulative update 7 for Microsoft Dynamics AX 2012 R2, you can provide information about a worker that is used to help match the worker to available jobs when you search for available resources. This includes information about education, skills, certifications, project experience, and various other attributes you might want to make relevant to a project role.</p></td>
<td><p><a href="set-up-worker-attributes.md">Set up worker attributes</a></p></td>
</tr>
<tr class="odd">
<td><p>Specify an individual worker’s project options.</p></td>
<td><p>Make settings in an individual worker’s profile that determines how the worker’s project work is recorded, such as their period code, default project categories, and category and project validation.</p></td>
<td><p><a href="manage-workers-in-projects.md">Manage workers in projects</a></p></td>
</tr>
<tr class="even">
<td><p>Set up basic project scheduling details.</p></td>
<td><p>Before you can begin assigning workers to a project, certain types of project information must be specified first in the <strong>Projects</strong> form.</p>
<p>In versions of Microsoft Dynamics AX 2012 earlier than cumulative update 7 for Microsoft Dynamics AX 2012 R2, this information is specified on the <strong>Scheduling and resource assignment</strong> FastTab. In cumulative update 7 for Microsoft Dynamics AX 2012 R2 and later versions, this information is specified on the <strong>Project team and scheduling</strong> FastTab.</p></td>
<td><p><a href="https://technet.microsoft.com/library/aa585245(v=ax.60)">Projects (form)</a></p></td>
</tr>
</tbody>
</table>


Back to top

## Schedule workers for projects

In all versions of Microsoft Dynamics AX 2012 you can schedule workers for project in two ways:

  - View a project schedule and find available, qualified workers to assign to its tasks

  - View a worker’s availability and find a project the worker is qualified for

In some later versions of Microsoft Dynamics AX 2012, you can choose from additional methods for assigning workers to projects. The following table contains links to resources that describe how to do this.

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
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Staff a project based on the skills and availability of workers.</p></td>
<td><p>You can review the capacity of each project worker in your organization, determine whether the worker is being adequately utilized, and then assign the worker to a project or activity based on the project requirements and the worker’s qualifications.</p>
<p>This task is applicable to all versions of Microsoft Dynamics AX 2012.</p></td>
<td><p><a href="key-tasks-assign-workers-to-projects-based-on-availability.md">Key tasks: Assign workers to projects based on availability</a></p></td>
</tr>
<tr class="even">
<td><p>Staff a project based on the project’s requirements.</p></td>
<td><p>You can begin by viewing the requirements of a project and, when in that view, search for and assign qualified workers to project tasks.</p>
<ul>
<li><p>The steps for performing these tasks vary somewhat among the different major versions of Microsoft Dynamics AX 2012. Refer to the links in the <strong>More information</strong> column for version-specific instructions.</p></li>
</ul></td>
<td><p><a href="key-tasks-create-a-schedule-based-on-a-project-in-microsoft-dynamics-ax-2012.md">Key tasks: Create a schedule based on a project in Microsoft Dynamics AX 2012</a></p>
<p><a href="key-tasks-create-a-schedule-based-on-a-project-in-microsoft-dynamics-ax-2012-r2.md">Key tasks: Create a schedule based on a project in Microsoft Dynamics AX 2012 R2</a></p>
<p><a href="key-tasks-create-a-schedule-based-on-a-project-in-ax-2012-r3-or-ax-2012-r2-cu7.md">Key tasks: Create a schedule based on a project in AX 2012 R3 or AX 2012 R2 CU7</a></p></td>
</tr>
<tr class="odd">
<td><p>Assign a specific worker to a project.</p></td>
<td><p>You can bypass the process of searching for available workers based on how well they meet search criteria and directly assign a particular worker that you want to work on a task.</p>
<p>Applies to:</p>
<ul>
<li><p>cumulative update 7 for Microsoft Dynamics AX 2012 R2</p></li>
<li><p>Microsoft Dynamics AX 2012 R3</p></li>
</ul></td>
<td><p><a href="reserve-a-specific-worker-for-a-project.md">Reserve a specific worker for a project</a></p></td>
</tr>
<tr class="even">
<td><p>Schedule workers directly from a work breakdown structure (WBS).</p></td>
<td><p>Instead of scheduling workers’ time for a project before assigning them to tasks in a WBS, you can schedule their time and assign them to WBS tasks simultaneously in the <strong>Work breakdown structure</strong> form.</p>
<p>Applies to:</p>
<ul>
<li><p>AX 2012 R3</p></li>
</ul></td>
<td><p><a href="assign-workers-to-tasks-manually-in-a-work-breakdown-structure-in-ax-2012-r3.md">Assign workers to tasks manually in a work breakdown structure in AX 2012 R3</a></p></td>
</tr>
</tbody>
</table>


Back to top

  


