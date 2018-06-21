---
title: Worker validation report (ProjValEmployee)
TOCTitle: Worker validation report (ProjValEmployee)
ms:assetid: d10950e7-42eb-436e-87dc-129bcc88cdea
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa599274(v=AX.60)
ms:contentKeyID: 37832033
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ProjValEmployee
---

# Worker validation report (ProjValEmployee) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To control how project transactions are recorded, you can limit the values that are available in journals and timesheets for workers, projects, and categories. You can also set up rules to prevent posting of transactions that violate the validation rules. Use this report to display a list of the projects for which worker validation is enabled.

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
<td><p><strong>Parameters</strong></p></td>
<td><p>Select the types of projects that you want to include on the report. You must select at least one project type.</p></td>
</tr>
<tr class="even">
<td><p><strong>Validation</strong></p></td>
<td><p>Select a summary to display on the report from the following options:</p>
<ul>
<li><p><strong>Project</strong> - Display projects for which worker validation is enabled.</p></li>
<li><p><strong>Category</strong> - Display categories for which worker validation is enabled.</p></li>
<li><p><strong>Project/category</strong> - Display projects and then categories in which worker validation is enabled.</p></li>
<li><p><strong>Category/project</strong> - Display categories and then projects in which worker validation is enabled.</p></li>
</ul></td>
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
<td><p>ProjValEmployee</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProjValEmployee</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProjListValEmployee</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Base data</strong> &gt; <strong>Validation</strong> &gt; <strong>Worker validation</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProjValEmployeeDP.processReport

  - DirPerson table

  - HcmWorker table

  - ProjValProjectTmp table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the ProjValEmployeeDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

