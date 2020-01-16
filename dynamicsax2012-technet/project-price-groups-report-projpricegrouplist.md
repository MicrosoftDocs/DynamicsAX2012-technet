---
title: Project price groups report (ProjPriceGroupList)
TOCTitle: Project price groups report (ProjPriceGroupList)
ms:assetid: 33302668-f6c9-40e1-b423-b0db62b81425
ms:mtpsurl: https://technet.microsoft.com/library/Hh527781(v=AX.60)
ms:contentKeyID: 37831990
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ProjPriceGroupList
---

# Project price groups report (ProjPriceGroupList) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view project transactions by price group. You can view the report for a specific project, project contract, or project price group.

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
<td><p>Select whether to include project transactions that you have not yet invoiced to customers.</p></td>
</tr>
<tr class="even">
<td><p><strong>Project contract</strong></p></td>
<td><p>Select whether to include project contracts on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Price group</strong></p></td>
<td><p>Select a specific price group. Only projects associated with the selected price group are displayed on the report.</p></td>
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
<td><p>ProjPriceGroupList</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProjPriceGroupList</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProjPriceGroupList</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Base data</strong> &gt; <strong>Prices</strong> &gt; <strong>Project price groups</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProjPriceGroupListDP.processReport

  - PriceDiscGroup table

  - TmpProjPriceGroupList table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the ProjPriceGroupListDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[About creating and using price groups](about-creating-and-using-price-groups.md)

[Assign a price group to a project, project contract, or customer](assign-a-price-group-to-a-project-project-contract-or-customer.md)

  


