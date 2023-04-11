---
title: 'Key tasks: Departments'
TOCTitle: 'Key tasks: Departments'
ms:assetid: 1ff7cc45-70e5-4c87-a148-e214aaea95ee
ms:mtpsurl: https://technet.microsoft.com/library/Hh208468(v=AX.60)
ms:contentKeyID: 36056157
author: tonyafehr
ms.date: 09/03/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Key tasks: Departments 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Departments are an important element of your organizational hierarchy. The following content contains procedures for common tasks associated with departments.

## What do you want to do?

Learn more about...

View department statistics

Create a department

Add a department to the department hierarchy

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About departments, jobs, and positions](about-departments-jobs-and-positions.md)

 

## View department statistics

The following resources provide information that can be useful when you plan your departmental structure.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Resource</p></th>
<th><p>Description</p></th>
<th><p>How to access</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Department hierarchy</p></td>
<td><p>Use the <strong>Hierarchy designer -</strong> form to view departments within a hierarchical structure. To view more specific information about a department, double-click the department in the hierarchy to open the <strong>Department</strong> form.</p>
<p>You also can use the hierarchy designer to modify the existing department hierarchy. For more information about the hierarchy designer, see <a href="create-or-modify-an-organization-hierarchy.md">Create or modify an organization hierarchy</a>.</p></td>
<td><p>Click <strong>Human resources</strong> &gt; <strong>Common</strong> &gt; <strong>Organization</strong> &gt; <strong>Departments</strong> &gt; <strong>Department hierarchy</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Position</strong> form</p></td>
<td><p>Use the <strong>Position</strong> form, filtered by department, to view a list of positions within a specific department.</p></td>
<td><ol>
<li><p>Click <strong>Human resources</strong> &gt; <strong>Common</strong> &gt; <strong>Organization</strong> &gt; <strong>Departments</strong> &gt; <strong>Departments</strong>.</p></li>
<li><p>Select a department to view positions for and then click <strong>Positions</strong>. The <strong>Position</strong> form is displayed and is filtered to list only positions within the department that you selected.</p></li>
</ol>
<p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Worker distribution statistics</strong> form</p></td>
<td><p>Use the <strong>Worker distribution statistics</strong> form to view gender, age, job, and worker type statistics by department.</p></td>
<td><p>Click <strong>Human resources</strong> &gt; <strong>Inquiries</strong> &gt; <strong>Workers</strong> &gt; <strong>Worker distribution statistics</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Departments</strong> report</p></td>
<td><p>Use the <strong>Departments</strong> report to view a list of the departments within your company or organization.</p></td>
<td><p>Click <strong>Human resources</strong> &gt; <strong>Reports</strong> &gt; <strong>Organization</strong> &gt; <strong>Departments</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Positions by department</strong> report</p></td>
<td><p>Use the <strong>Positions by department</strong> report to view a list of positions organized by department.</p></td>
<td><p>Click <strong>Human resources</strong> &gt; <strong>Reports</strong> &gt; <strong>Organization</strong> &gt; <strong>Positions by department</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>People by department</strong> report</p></td>
<td><p>Use the <strong>People by department</strong> report to view a list of people organized by the department that they work in.</p></td>
<td><p>Click <strong>Human resources</strong> &gt; <strong>Reports</strong> &gt; <strong>Organization</strong> &gt; <strong>People by department</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Number of workers</strong> report</p></td>
<td><p>Use the <strong>Number of workers</strong> report to view the number of workers within each department.</p></td>
<td><p>Click <strong>Human resources</strong> &gt; <strong>Reports</strong> &gt; <strong>Workers</strong> &gt; <strong>Number of workers</strong>.</p></td>
</tr>
</tbody>
</table>


For additional information about the reports listed in the previous table, see [Human resources reports](human-resources-reports.md).

Back to top

 

## Create a department

A department is a type of operating unit. For more information about how to create operating units, see [Create or modify an operating unit](create-or-modify-an-operating-unit.md).

1.  Click **Human resources** \> **Common** \> **Organization** \> **Departments** \> **Departments**.

2.  Click **New**.

3.  Enter a name for the department.

4.  Enter a department number.
    
    A default value might automatically be generated if a number sequence code is assigned to the **Organization number** reference in the **Number sequences** form.
    

    > [!NOTE]
    > <P>The remaining steps in this procedure are optional.</P>



5.  Enter a search name, such as an acronym for the department name, which you can use to search for the department in Enterprise Search. For more information, see [Enterprise Search](enterprise-search.md).

6.  Enter additional information about the department in the **Memo** field.

7.  Enter the Data Universal Numbering System (DUNS) number for the department.

8.  Select the person who manages the department.

9.  On the **Addresses** FastTab, add address information for the department. For example, add the mailing address for the building that the department is located in.

10. On the **Contact information** FastTab, add contact information. For example, add a telephone number for the service desk in the department.

Back to top

 

## Add a department to the department hierarchy

In the **Department** form, the **In hierarchy** check box is selected if a department is included in the department hierarchy. Complete the following procedure to add a department to the department hierarchy.

1.  Click **Human resources** \> **Common** \> **Organization** \> **Departments** \> **Department hierarchy**.

2.  On the **Action Pane**, click **Edit**.

3.  In the hierarchy, select the organization to add the department under.

4.  On the **Action Pane**, click **Insert** and then select **Department**.

5.  Select the department to add to the hierarchy and then click **OK**.

6.  To save the hierarchy as a draft hierarchy that you can work on later, click **Save as draft**.
    
    To publish the hierarchy, click **Publish and close**, enter the effective date and time zone for the changes to take effect, and then click **Publish**.

Back to top

## Find form help

[Operating units (form)](https://technet.microsoft.com/library/hh208817\(v=ax.60\))

[Hierarchy designer (form)](https://technet.microsoft.com/library/hh209547\(v=ax.60\))

## Find related tasks

[Key tasks: Jobs](key-tasks-jobs.md)

[Key tasks: New worker positions](key-tasks-new-worker-positions.md)

  


