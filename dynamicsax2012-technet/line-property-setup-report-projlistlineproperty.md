---
title: Line property setup report (ProjListLineProperty)
TOCTitle: Line property setup report (ProjListLineProperty)
ms:assetid: db10439f-afef-40b8-af58-f0039d6f32da
ms:mtpsurl: https://technet.microsoft.com/library/Aa620113(v=AX.60)
ms:contentKeyID: 36941306
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ProjListLineProperty
---

# Line property setup report (ProjListLineProperty) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to analyze the setup of the line property in categories and projects.

Line properties are set up with one of the following relations:

  - **Table** – Applies to a specific category.

  - **Group** – Applies to a group of categories.

  - **All** – Applies to all categories.

When you enter a project transaction, the journal posting process applies the specified line property relation criteria. For more information, see [Ledger posting setup (form)](https://technet.microsoft.com/library/aa599270\(v=ax.60\)).

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
<td><p><strong>Direct</strong></p></td>
<td><p>Select whether to include ledger postings that are specifically assigned to a project.</p></td>
</tr>
<tr class="even">
<td><p><strong>Missing</strong></p></td>
<td><p>Select whether to include ledger postings to a project that are not specifically assigned to a project category.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Project ID</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Line property setup</strong> form, select a project to include on the report. To add more than one project ID, click <strong>Add</strong>. If you do not select a project ID, all projects are displayed on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Category</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Line property setup</strong> form, select the project category to include on the report. To add more than one category, click <strong>Add</strong>. If you do not select a project category, all categories are displayed on the report.</p></td>
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
<td><p>ProjListLineProperty</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProjListLineProperty</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProjListLineProperty</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Base data</strong> &gt; <strong>Setup</strong> &gt; <strong>Line property setup</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProjListLinePropertyDP.processReport

  - ProjCategory table

  - ProjListLinePropertyTmp table

  - ProjTable


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the ProjListLinePropertyDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


