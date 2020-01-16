---
title: Project/category validation report (ProjValProjCategory)
TOCTitle: Project/category validation report (ProjValProjCategory)
ms:assetid: 5f3a43db-ab9f-4e7b-93d7-a89e03188fa9
ms:mtpsurl: https://technet.microsoft.com/library/Aa584405(v=AX.60)
ms:contentKeyID: 37832005
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ProjValProjCategory
---

# Project/category validation report (ProjValProjCategory) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To control how project transactions are recorded, you can limit the values that are available in journals and timesheets for workers, projects, and categories. You can also set up groups of rules to prevent posting of transactions that violate the validation rules. Use this report to view a list of the categories and projects included in validation groups.

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
<td><p>Select how you want to display the first column on the report from the following options:</p>
<ul>
<li><p><strong>Project</strong> – Display projects for which validation is enabled for associated workers.</p></li>
<li><p><strong>Category</strong> – Display categories for which validation is enabled for associated workers.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Project/category</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Project validation category assignments</strong> form, select the project categories to include on the report. To add more than one category, click <strong>Add</strong>.</p></td>
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
<td><p>ProjValProjCategory</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>\SSRS Reports\Reports\ProjValProjCategory</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProjListValProjCategory</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Base data</strong> &gt; <strong>Validation</strong> &gt; <strong>Project/category validation</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProjValProjCategoryDP.processReport

  - ProjValProjCategorySetUp table

  - ProjValProjCategoryTable

  - ProjValProjectTmp table

  - 


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the ProjValProjCategoryDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


