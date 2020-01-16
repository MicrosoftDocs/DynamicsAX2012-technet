---
title: Create or update a project by using Microsoft Project
TOCTitle: Create or update a project by using Microsoft Project
ms:assetid: bdc9791f-142a-4046-a99c-58e30b904e38
ms:mtpsurl: https://technet.microsoft.com/library/Dn528663(v=AX.60)
ms:contentKeyID: 59636745
author: Khairunj
ms.date: 10/06/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create or update a project by using Microsoft Project 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to use Microsoft Project to manage some aspects of a project that is created or maintained in Microsoft Dynamics AX. Projects can be created and managed in either program. The program that you use to manage a project does not have to be the same program that you use to create the project.

You can create a link between a project in Microsoft Dynamics AX and a corresponding project in Microsoft Project. You can then use Microsoft Project to create or update the work breakdown structure (WBS) of your project, and also create a WBS template that you can use in Microsoft Dynamics AX. You can also assign workers to projects in Microsoft Project by using the list of workers from Microsoft Dynamics AX. Additionally, this integration lets you create a WBS in Microsoft Project that can be used for a project quotation in Microsoft Dynamics AX.

If you are using Microsoft Dynamics AX 2012 R3 together with Microsoft Project Professional 2013, you can do the following:

  - In AX 2012 R3, you can use the **Open** button on the **Dynamics AX** tab in Microsoft Project to open the current project in Microsoft Dynamics AX. It is no longer necessary to open Microsoft Dynamics AX first in order to access the project.

  - In Microsoft Project Professional 2013, you can synchronize your task list from Microsoft Project with a task list in a collaboration workspace in SharePoint Online. You can then view or edit tasks while you are working in the collaboration workspace that is associated with your project.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



When you use the integration between Microsoft Dynamics AX and Microsoft Project, the system handles some updates automatically when changes occur that affect your project.

  - If you make changes to schedule dates after workers are already reserved for your project, corresponding updates in the workers’ assignments are made automatically.

  - If a worker who is reserved for a project leaves the company, the worker’s assignment is automatically removed from the project, and the worker’s name is no longer available in lists of workers who can be assigned to projects.

If issues occur while project updates are published from Microsoft Project to Microsoft Dynamics AX, you can troubleshoot the errors in Windows Event Viewer.

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Version</p></td>
<td><p>Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2</p></td>
</tr>
<tr class="even">
<td><p>Add-in programs</p></td>
<td><p>The following add-in program must be installed during the upgrade process to cumulative update 7 for Microsoft Dynamics AX 2012 R2 or to Microsoft Dynamics AX 2012 R3:</p>
<ul>
<li><p>Microsoft Project Add-In</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Microsoft Project version</p></td>
<td><p>You must have one of the following versions:</p>
<ul>
<li><p>Microsoft Project Professional 2013</p></li>
<li><p>Microsoft Project Standard 2013</p></li>
<li><p>Microsoft Project Standard 2010</p></li>
</ul>
<p>Note that task lists can be synchronized with a project in SharePoint Online only if you are using Microsoft SharePoint 2013 Products.</p>
<div class="alert">

> [!IMPORTANT]
> <P>For best results, we recommend that you use the 32-bit version of Microsoft Project Professional 2013. For information about issues that you might encounter when you use Microsoft Project Professional 2010 or Microsoft Project Standard 2010, and steps that you can take to avoid these issues, see the <A href="create-or-update-a-project-by-using-microsoft-project.md">Create or update a project by using Microsoft Project</A> section later in this topic.</P>
> <P></P>


</div></td>
</tr>
<tr class="even">
<td><p>Microsoft SharePoint</p></td>
<td><p>Optional. If you want to store Microsoft Project files in a SharePoint implementation, one of the following products must be available to your system administrators:</p>
<ul>
<li><p>Microsoft SharePoint Foundation 2010</p></li>
<li><p>Microsoft SharePoint Foundation 2013</p></li>
<li><p>Microsoft SharePoint Server 2010</p></li>
<li><p>Microsoft SharePoint Server 2013</p></li>
</ul>
<p>If you want to specify a collaboration workspace home page in SharePoint Online, you must install the SharePoint Server 2013 Client Components SDK on the computer where you are running Microsoft Dynamics AX.</p>
<p>Download the <a href="https://www.microsoft.com/en-us/download/details.aspx?id=35585">SharePoint Server 2013 Client Components SDK</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Related configuration tasks</p></td>
<td><p><a href="specify-options-for-microsoft-project-integration.md">Specify options for Microsoft Project integration</a></p>
<p>Optional: <a href="set-up-collaboration-workspaces.md">Set up collaboration workspaces</a></p></td>
</tr>
<tr class="even">
<td><p>Project management and accounting parameters</p></td>
<td><p>If you want to use Microsoft Project to help manage your Microsoft Dynamics AX projects, make sure that options for storing Microsoft Project MPP files have been set in the <strong>Microsoft Project integration</strong> group in the <strong>General</strong> area of the <strong>Project management and accounting parameters</strong> form.</p></td>
</tr>
</tbody>
</table>


## Integrate a project between Microsoft Dynamics AX and Microsoft Project

Provided that the prerequisites are met, you can create a link between Microsoft Dynamics AX and Microsoft Project so that you can use both programs to manage your project.

To integrate a project from Microsoft Dynamics AX, follow these steps:

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**.

2.  Create or open the project that you want to work with in Microsoft Project.

3.  On the **Plan** tab, in the **Activities** group, click **Open in Microsoft Project**.

To integrate a project from Microsoft Project, follow these steps:

1.  In Microsoft Project, open the project that you want to work with.

2.  On the **Dynamics AX** tab, on the **Action Pane**, click **Publish**.

3.  In the confirmation message box, click **Yes**.

4.  In the **Publish as a new project** form, in the **Project name** field, enter a name for the new project.

5.  Optional: If any basic project details require values that differ from the default values, modify the values.
    

    > [!TIP]
    > <P>If you want to create a new project contract to associate this project with, click <STRONG>New</STRONG>, and provide the details for the contract in the <STRONG>Create new contract</STRONG> form.</P>



6.  Click **OK**.

## Associate tasks in Microsoft Project with categories from Microsoft Dynamics AX

In Microsoft Dynamics AX, project activities can optionally be assigned to project categories. Before you transfer a WBS from Microsoft Project, you can assign the activities in the WBS to categories that are imported from Microsoft Dynamics AX.

To assign a task in Microsoft Project to a Microsoft Dynamics AX category, follow these steps:

1.  In Microsoft Project, open the linked project that you want to work with.

2.  On the **Task** tab, select the leaf task to assign a category to.

3.  In the **Category** column, select the category to assign to the task.

4.  Repeats steps 2 and 3 for each leaf task that you want to assign to a category.

5.  On the **Dynamics AX** tab, on the **Action Pane**, click **Publish**.

## Assign workers from Microsoft Dynamics AX to tasks in Microsoft Project

If you are managing a project in both Microsoft Dynamics AX and Microsoft Project, you can select workers who have profiles in Microsoft Dynamics AX when you make task assignments in Microsoft Project.

To assign Microsoft Dynamics AX workers to tasks in Microsoft Project, follow these steps:

1.  In Microsoft Project, open the linked project that you want to work with.

2.  On the **Dynamics AX** tab, click **Add Resources**.

3.  In the **Add workers from Microsoft Dynamics AX** form, select the workers that you want to be able to assign to tasks in the project, and then click **Add workers**.
    
    This step does not assign workers to tasks. This step only makes workers available for assignment in the next step.

4.  On the **Task** tab, in the row for a task that you want to assign a worker to, in the **Resource Names** column, select the worker or workers that you want to work on the task.
    

    > [!IMPORTANT]
    > <P>The <STRONG>Resource Names</STRONG> field has a character limit of 255 characters. You can’t add multiple workers if their names and identifiers together exceed 255 characters.</P>



5.  Repeat the previous step for each task that you want to assign a worker to.

6.  On the **Dynamics AX** tab, on the **Action Pane**, click **Publish**.

## Replace the WBS in a project in Microsoft Dynamics AX with a WBS from Microsoft Project

If you are already managing a project in Microsoft Dynamics AX, you can add the WBS from a project in Microsoft Project to the project in Microsoft Dynamics AX. This action updates all aspects of the WBS but does not change other elements of your project, such as the customer or the project contract. If the target project in Microsoft Dynamics AX already contains a WBS, the existing WBS is replaced. If the project does not yet have a WBS, this procedure creates it.

To copy a WBS from Microsoft Project to Microsoft Dynamics AX, follow these steps:

1.  In Microsoft Project, open the project that you want to work with.

2.  On the **Dynamics AX** tab, click the arrow under the **Publish** button, and then select **Replace Existing Project**.

3.  In the confirmation message box, click **Yes**.

4.  In the **Replace an existing project** form, select the legal entity and project to transfer the WBS to.

5.  Click **OK**.

## Optional: Save a WBS in Microsoft Project as a template that can be used in Microsoft Dynamics AX

You can save a WBS in Microsoft Project as a template that can be selected in Microsoft Dynamics AX. After you complete this procedure, the WBS template can be imported and applied in the **Work breakdown structure** form in Microsoft Dynamics AX.


> [!NOTE]
> <P>You can modify the WBS template in Microsoft Dynamics AX only if you first unlink the WBS template from Microsoft Project on the <STRONG>WBS</STRONG> tab in the <STRONG>Work breakdown structure</STRONG> form.</P>



To save a WBS in Microsoft Project as a template, follow these steps:

1.  In Microsoft Project, open the project that you want to work with.

2.  On the **Dynamics AX** tab, click **Publish**, and then select **Save as a Template**.

3.  In the confirmation message box, click **Yes**.

4.  In the **Publish as Template** form, select the legal entity to enable this template for, and then, in the **Template name** field, enter a name to identify the template.

5.  Click **Ok**.

## Optional: Create or update the WBS for a quotation

You can link a project quotation in Microsoft Dynamics AX to Microsoft Project. You can then create a WBS for the quotation in Microsoft Project. Alternatively, you can replace the WBS that the project in Microsoft Dynamics AX already contains with a WBS that you create in Microsoft Project.

To create or update the WBS for a quotation from Microsoft Dynamics AX in Microsoft Project, follow these steps:

1.  In Microsoft Dynamics AX: Click **Project management and accounting** \> **Common** \> **Quotations** \> **Project quotations**.

2.  Create or select the project quotation that you want to work with.

3.  On the **Project quotation** tab, in the **Maintain** group, click **Work breakdown structure**.

4.  On the **WBS** tab, in the **Microsoft Project** group, click **Open in Microsoft Project**.

5.  In Microsoft Project, create a WBS for the quotation.

6.  On the **Dynamics AX** tab, on the **Action Pane**, click **Publish**.


> [!TIP]
> <P>After the quotation is approved, you can transfer it to a new project. If you complete this task in Microsoft Dynamics AX, make sure that you select the <STRONG>Transfer WBS</STRONG> check box in the Transfer to Project Wizard.</P>



## Supported environment information and troubleshooting

For best results, we recommend that you use the 32-bit version of either Microsoft Project Professional 2013 or Microsoft Project Standard 2013 on any of the following operating systems:

  - Windows 7

  - Windows 8

  - Windows 8.1

  - Windows Server 2008 R2

  - Windows Server 2012

The following table shows issues that you might encounter when you use the Microsoft Dynamics AX Add-in for Microsoft Project together with either version of Microsoft Project 2010. For information about the environments in which you might encounter the issues, see the second table that follows.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Issue number</p></th>
<th><p>Description</p></th>
<th><p>Solution</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>1</p></td>
<td><p>When you are using the Microsoft Dynamics AX Add-in for Microsoft Project together with Microsoft Project 2010, Microsoft Project stops responding in the following situation:</p>
<ol>
<li><p>You open Microsoft Project 2010 by clicking <strong>Open in Microsoft Project</strong> in Microsoft Dynamics AX.</p></li>
<li><p>After the project is loaded in Microsoft Project, regardless of whether you make any changes, you close the project either by clicking <strong>File</strong> &gt; <strong>Close</strong> or by clicking the <strong>Close</strong> (X) button for the project.</p></li>
<li><p>You try to close the main Microsoft Project window. At this point, Microsoft Project stops responding and you cannot recover the application.</p></li>
</ol></td>
<td><p>To avoid this situation, always close the Microsoft Project 2010 program after you have finished working with a project that is integrated with Microsoft Dynamics AX, instead of closing only the project file. To recover after Microsoft Project has stopped responding, use Windows Task Manager to end the WINPROJ.exe process.</p></td>
</tr>
<tr class="even">
<td><p>2</p></td>
<td><p>When you are running Microsoft Project 2010 on Windows 7, COM errors or permissions errors can occur when you try to publish project information from Microsoft Project to Microsoft Dynamics AX.</p></td>
<td><p>To avoid this situation, always run Microsoft Project 2010 in Administrator mode.</p></td>
</tr>
<tr class="odd">
<td><p>3</p></td>
<td><p>When you are using the Microsoft Dynamics AX Add-in for Microsoft Project, and you are using a 64-bit version of Microsoft Project 2010 on Windows 8.1, a COM error occurs in the following situation: In Microsoft Dynamics AX, in the <strong>Projects</strong> form or the <strong>Work breakdown structure</strong> form, you click <strong>Open in Microsoft Project</strong>, but Microsoft Project is not already open.</p></td>
<td><p>To avoid this issue, open Microsoft Project 2010 before you click <strong>Open in Microsoft Project</strong> in Microsoft Dynamics AX.</p></td>
</tr>
</tbody>
</table>


The following table shows the environments in which you might encounter the issues that are described in the previous table.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Windows version</p></th>
<th><p>Microsoft Project version</p></th>
<th><p>Potential issues</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Windows 7</p></td>
<td><p>Microsoft Project 2010 64-bit</p></td>
<td><p>1, 2</p></td>
</tr>
<tr class="even">
<td><p>Windows 7</p></td>
<td><p>Microsoft Project 2010 32-bit</p></td>
<td><p>1, 2</p></td>
</tr>
<tr class="odd">
<td><p>Windows 8</p></td>
<td><p>Microsoft Project 2010 64-bit</p></td>
<td><p>1</p></td>
</tr>
<tr class="even">
<td><p>Windows 8</p></td>
<td><p>Microsoft Project 2010 32-bit</p></td>
<td><p>1</p></td>
</tr>
<tr class="odd">
<td><p>Windows 8.1</p></td>
<td><p>Microsoft Project 2010 64-bit</p></td>
<td><p>1, 3</p></td>
</tr>
<tr class="even">
<td><p>Windows 8.1</p></td>
<td><p>Microsoft Project 2010 32-bit</p></td>
<td><p>1</p></td>
</tr>
<tr class="odd">
<td><p>Windows Server 2008 R2</p></td>
<td><p>Microsoft Project 2010 64-bit</p></td>
<td><p>1</p></td>
</tr>
<tr class="even">
<td><p>Windows Server 2008 R2</p></td>
<td><p>Microsoft Project 2010 32-bit</p></td>
<td><p>1</p></td>
</tr>
<tr class="odd">
<td><p>Windows Server 2012</p></td>
<td><p>Microsoft Project 2010 64-bit</p></td>
<td><p>1</p></td>
</tr>
<tr class="even">
<td><p>Windows Server 2012</p></td>
<td><p>Microsoft Project 2010 32-bit</p></td>
<td><p>1</p></td>
</tr>
</tbody>
</table>


## Related tasks

[Specify options for Microsoft Project integration](specify-options-for-microsoft-project-integration.md)

[Create a project](create-a-project.md)

[Key tasks: Assign workers to projects based on availability](key-tasks-assign-workers-to-projects-based-on-availability.md)

[Create a work breakdown structure template for projects](create-a-work-breakdown-structure-template-for-projects.md)

[Create a work breakdown structure of tasks for a project](create-a-work-breakdown-structure-of-tasks-for-a-project.md)

  


