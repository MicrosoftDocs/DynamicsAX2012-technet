---
title: Picking list report (WMSPickingList_OrderPick)
TOCTitle: Picking list report (WMSPickingList_OrderPick)
ms:assetid: a94ac96c-821a-4bb1-9e69-04ee0ff8dd21
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209485(v=AX.60)
ms:contentKeyID: 36060173
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.WMSPickingList_OrderPick
---

# Picking list report (WMSPickingList\_OrderPick) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the **Picking list** report to print a list of picking information.

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
<td><p>Parameters</p></td>
<td><p>Use the check boxes in this field group to print available information for the picking list. The options are as follows:</p>
<p><strong>Activated</strong></p>
<p><strong>Canceled</strong></p>
<p><strong>Complete</strong></p>
<p><strong>Loaded</strong></p>
<p><strong>Picked</strong></p>
<p><strong>Registered</strong></p>
<p><strong>Staged</strong></p>
<p><strong>Started</strong></p></td>
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
<td><p>WMSPickingList_OrderPick</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\WMSPickingList_OrderPick</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>WMSPickingList_OrderPickCopySRS</p>
<p>WMSPickingList_OrderPickOriginalSRS</p>
<p>WMSPickingList_OrderPickSRS</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Inventory management</strong> &gt; <strong>Periodic</strong> &gt; <strong>Picking list registration</strong>. Click <strong>Print</strong> and then <strong>Picking list</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - WMSPickingList\_OrderPickTmp table


> [!NOTE]
> <P>To learn where the data in the temp table comes from, view the cross-references for the WMSPickingList_OrderPickDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


