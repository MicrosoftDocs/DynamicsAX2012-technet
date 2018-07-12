---
title: Fixed-price projects - closing profiles report (ProjClosingProfile)
TOCTitle: Fixed-price projects - closing profiles report (ProjClosingProfile)
ms:assetid: 1016b6e9-3cdc-4dc2-afd8-beb90a2955fa
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa498697(v=AX.60)
ms:contentKeyID: 37820202
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ProjClosingProfile
---

# Fixed-price projects - closing profiles report (ProjClosingProfile) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When your company completes large fixed-price projects, the costs, revenue, and profit margin are posted to the financial accounts in accordance with the completed contract method. Use this report to view the costs, revenue, and profit margin of estimate projects that are expected to close by a date that you specify.


> [!NOTE]
> <P>The report is only applicable for projects that are fixed-price projects, that are referred to as estimate projects, or that are posted according to the completed contract method.</P>



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
<td><p><strong>Project</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Fixed-price projects - closing profiles</strong> form, in the <strong>Criteria</strong> field, select a project to include on the report. To add more than one project, click <strong>Add</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>End date</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Fixed-price projects - closing profiles</strong> form, in the <strong>Criteria</strong> field, select an ending date for projects to include on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Revenue recognition accounting rule</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Fixed-price projects - closing profiles</strong> form, in the <strong>Criteria</strong> field, select a revenue recognition rule for projects to include on the report.</p></td>
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
<td><p>ProjClosingProfile</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProjClosingProfile</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProjClosingProfile</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Estimates</strong> &gt; <strong>Fixed-price</strong> &gt; <strong>Fixed-price projects - closing profiles</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProjClosingProfile table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


