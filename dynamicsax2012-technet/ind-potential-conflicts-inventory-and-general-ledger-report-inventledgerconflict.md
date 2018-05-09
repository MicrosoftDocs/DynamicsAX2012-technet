---
title: (IND) Potential conflicts - inventory and general ledger report (InventLedgerConflict)
TOCTitle: (IND) Potential conflicts - inventory and general ledger report (InventLedgerConflict)
ms:assetid: 6810d44b-78f2-4164-b98f-df9e4d35a482
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ966247(v=AX.60)
ms:contentKeyID: 51439432
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- conflicts
- SSRS_Reports.Reports.InventLedgerConflict
- inventory
- potential conflicts
---

# (IND) Potential conflicts - inventory and general ledger report (InventLedgerConflict) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Potential conflicts – inventory and general ledger report displays the discrepancies between the inventory and general ledger transaction values for a selected period. If there are no discrepancies, the report displays matching values for the inventory transactions and the general ledger transactions. Accounting managers and supervisors use this report to reconcile physical inventory and financial inventory.

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
<td><p><strong>Date interval code</strong></p></td>
<td><p>Select a date interval code.</p></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong></p></td>
<td><p>Select the starting date of the period that the report is generated for.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong></p></td>
<td><p>Select the ending date of the period that the report is generated for.</p></td>
</tr>
<tr class="even">
<td><p><strong>Main account</strong></p></td>
<td><p>Select the ledger account number of the transactions that are included on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Exclude physical to ledger</strong></p></td>
<td><p>Select this check box to exclude physical inventory transactions that are posted to the ledger account from the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Exclude blank dimension values</strong></p></td>
<td><p>A selected check box indicates that transactions with empty dimension values are excluded from the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Dimension name</strong></p></td>
<td><p>Select the dimension name of the transactions that are included on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Item number</strong></p></td>
<td><p>The identification number of the item.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Reference</strong></p></td>
<td><p>The source of the transaction, for example, a sales order or transfer.</p></td>
</tr>
<tr class="even">
<td><p><strong>Lot ID</strong></p></td>
<td><p>The lot identification number of the item.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Voucher</strong></p></td>
<td><p>The voucher number of the transactions that are included on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Posting type</strong></p></td>
<td><p>The posting type of the transactions that are included on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Dimension value</strong></p></td>
<td><p>The dimension value of the transactions that are included on the report.</p></td>
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
<td><p>InventLedgerConflict</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\InventLedgerConflict</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>InventLedgerConflict</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Inventory management</strong> &gt; <strong>Reports</strong> &gt; <strong>Status</strong> &gt; <strong>Inventory value</strong> &gt; <strong>Potential conflicts - inventory and general ledger</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data on this report comes from

The data on this report comes from the following sources:

  - InventLedgerConflictTmpBalance table

  - InventLedgerConflictTmpConflictTmp table
    

    > [!NOTE]
    > <P>To find out where the data in the temp tables come from, view the cross-references for the InventLedgerConflictDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(IND) Create and post shipment orders for transactions](ind-create-and-post-shipment-orders-for-transactions.md)

[(IND) Post received orders for transactions](ind-post-received-orders-for-transactions.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

