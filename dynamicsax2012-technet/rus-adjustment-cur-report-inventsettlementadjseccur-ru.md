---
title: (RUS) Adjustment (cur.) report (InventSettlementAdjSecCur_RU)
TOCTitle: (RUS) Adjustment (cur.) report (InventSettlementAdjSecCur_RU)
ms:assetid: 6f16bce5-6e13-4fed-876d-712d785b7538
ms:mtpsurl: https://technet.microsoft.com/library/Dn126096(v=AX.60)
ms:contentKeyID: 52075231
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.InventSettlementAdjSecCur_RU
---

# (RUS) Adjustment (cur.) report (InventSettlementAdjSecCur\_RU) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Adjustment (cur.) report displays information about the cost adjustments of inventory items in the reporting currency. Accountants generate this report to analyze the values of cost adjustment transactions before the recalculation of cost values during the closing of the inventory.

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
<td><p><strong>Exclude storno</strong></p></td>
<td><p>Select this check box to exclude storno transactions from the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Item number</strong></p></td>
<td><p>The identification number of the inventory item that the adjustment report is printed for.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Date</strong></p></td>
<td><p>The posting date of the inventory settlement transaction.</p></td>
</tr>
<tr class="even">
<td><p><strong>Voucher</strong></p></td>
<td><p>The voucher number that the adjustment report is printed for.</p></td>
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
<td><p>InventSettlementAdjSecCur_RU</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\InventSettlementAdjSecCur_RU</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>InventSettlementAdjSecCur_RU</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Inventory management</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Adjustment (cur.)</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data on this report comes from

The data on this report comes from the following sources:

  - TmpInventSettlementAdjSecCur\_RU table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the InventSettlementAdjSecCurDP_RU.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(RUS) Adjustment of on-hand inventory (modified form)](https://technet.microsoft.com/library/jj923554\(v=ax.60\))

[(RUS) Inventory adjustments](rus-inventory-adjustments.md)

  


