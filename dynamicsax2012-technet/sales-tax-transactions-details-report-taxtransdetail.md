---
title: Sales tax transactions - Details report (TaxTransDetail)
TOCTitle: Sales tax transactions - Details report (TaxTransDetail)
ms:assetid: e8a8913b-28cb-48c5-9957-766be532b985
ms:mtpsurl: https://technet.microsoft.com/library/Aa592169(v=AX.60)
ms:contentKeyID: 43894492
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.TaxTransDetail
---

# Sales tax transactions - Details report (TaxTransDetail) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to show and print information about posted sales tax transactions for a specified time interval and sales tax code interval.

The transactions are listed by sales tax code. For each transaction, you can see the customer or vendor, the voucher number, the account that the sales tax base amount is posted to, the sales tax base amount (origin), the amount including sales tax, the sales tax amount, the sales tax charge, and the sales tax direction.

The amounts are summed for each tax code, and the amounts for sales tax directions **Sales tax receivable** and **Sales tax payable** are summed in a grand total.

Sales tax codes with other sales tax directions, such as **Use tax**, are also listed.

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
<td><p><strong>From date</strong></p></td>
<td><p>Enter the beginning of the date interval for the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong></p></td>
<td><p>Enter the ending date of the date interval for the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Include reversed</strong></p></td>
<td><p>Select this check box to include reversed transactions on the report.</p></td>
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
<td><p>TaxTransDetail</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>\SSRS Reports\Reports\TaxTransDetail</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TaxTransDetail</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Groupings</strong> &gt; <strong>Sales tax transactions - details</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustInvoiceJour table

  - CustTable table

  - CustTrans table

  - GeneralJournalAccountEntry table

  - MainAccountLedgerDimensionView table

  - TaxTrans table

  - TaxTransGeneralJournalAccountEntry table

  - TransactionReversalTrans table

  - VendInvoiceJour table

  - VendTable table

  - VendTrans table

  - TaxTransDetail\_BE table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


