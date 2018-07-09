---
title: Category validation report (ProjValCategory)
TOCTitle: Category validation report (ProjValCategory)
ms:assetid: 8d233abe-5416-46d7-b44d-57d296cf9630
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa587657(v=AX.60)
ms:contentKeyID: 37820220
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ProjValCategory
---

# Category validation report (ProjValCategory) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Your organization may restrict which project categories are assigned to a project by enabling category validation on the project. Use this report to display a list of the projects for which category validation is enabled.

## How to filter the data on this report

When you generate this report, the following default parameters are displayed. You can use these parameters to filter the data that will be displayed on the report. For more information, see [Filter the data on a report](filter-the-data-on-a-report.md).

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Include project types</strong></p></td>
<td><p>Select the types of projects that you want to include on the report. You must select at least one project type.</p></td>
</tr>
<tr class="even">
<td><p><strong>Include transaction types</strong></p></td>
<td><p>Select the transaction types that you want to include on the report. You must select at least one transaction type.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Validation</strong></p></td>
<td><p>Select a summary in which to display the report, from the following options:</p>
<ul>
<li><p><strong>Project</strong> – List categories for which validation is set up in the associated projects.</p></li>
<li><p><strong>Worker</strong> – List categories in which validation is set up for associated workers.</p></li>
<li><p><strong>Project/employee</strong> – List categories for which a combination of projects and workers have validation set up.</p></li>
<li><p><strong>Employee/project</strong> – Lists projects for which a combination of workers and categories have validation set up.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Category</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Category validation</strong> form, select a project category to include on the report. To add more than one category, click <strong>Add</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Transaction type</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Category validation</strong> form, select a transaction type to include on the report. To add more than one transaction type, click <strong>Add</strong>.</p></td>
</tr>
</tbody>
</table>


## How to work with reports

The following topics explain how to print a report and how to filter and sort the data on a report.

  - [Print or email a report](print-or-email-a-report.md)

  - [Filter the data on a report](filter-the-data-on-a-report.md)

  - [Sort the data on a report](sort-the-data-on-a-report.md)

## Details of this report

The following table explains where to find the report in the Application Object Tree (AOT) and how to navigate to the report in the Microsoft Dynamics AX client.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Detail</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Name of report in the AOT</p></td>
<td><p>ProjValCategory</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProjValCategory</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProjListValCategory</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Base data</strong> &gt; <strong>Validation</strong> &gt; <strong>Category validation</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProjValCategoryDP.processReport

  - ProjCategory table

  - ProjValProjectTmp


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the ProjValCategoryDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

