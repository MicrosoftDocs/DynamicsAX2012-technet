---
title: (RUS) Pay-sheet of receipts and expenditure report (InventIncomeOutlay_RU)
TOCTitle: (RUS) Pay-sheet of receipts and expenditure report (InventIncomeOutlay_RU)
ms:assetid: 41ae59f5-9cf4-4e05-adfd-44dcecd69b27
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ992743(v=AX.60)
ms:contentKeyID: 51739429
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.InventIncomeOutlay_RU
---

# (RUS) Pay-sheet of receipts and expenditure report (InventIncomeOutlay\_RU) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Pay-sheet of receipts and expenditure report displays transactions that are related to the receipt, issue, and consumption of inventory items. The data on this report is grouped by the site and the warehouse where the items are stored. Accountants use this report to review the quantity and value of inventory items that are issued and received.

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
<td><p>Select this check box to exclude storno accounting transactions from the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Item number</strong></p></td>
<td><p>The identification number of the item.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Issue status</strong></p></td>
<td><p>The issue status of the item.</p></td>
</tr>
<tr class="even">
<td><p><strong>Receipt status</strong></p></td>
<td><p>The receipt status of the item.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Physical date</strong></p></td>
<td><p>The date of the physical transaction.</p></td>
</tr>
<tr class="even">
<td><p><strong>Site</strong></p></td>
<td><p>The identification code of the site where the items are stored.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Warehouse</strong></p></td>
<td><p>The identification code of the warehouse where the items are stored.</p></td>
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
<td><p>InventIncomeOutlay_RU</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\InventIncomeOutlay_RU</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>InventIncomeOutlay_RU</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Inventory management</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Pay-sheet of receipts and expenditure</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data on this report comes from

The data on this report comes from the following sources:

  - InventIncomeOutlayTmp\_RU table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the InventIncomeOutlayDP_RU.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Inventory registration (form)](https://technet.microsoft.com/en-us/library/aa615731\(v=ax.60\))

[Inventory transactions (form)](https://technet.microsoft.com/en-us/library/aa584374\(v=ax.60\))

  


