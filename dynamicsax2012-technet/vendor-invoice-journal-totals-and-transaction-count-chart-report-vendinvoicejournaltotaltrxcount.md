---
title: Vendor invoice journal totals and transaction count chart report (VendInvoiceJournalTotalTrxCount)
TOCTitle: Vendor invoice journal totals and transaction count chart report (VendInvoiceJournalTotalTrxCount)
ms:assetid: f15f5ed2-453c-4cb2-ba90-e1837537db6b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh538466(v=AX.60)
ms:contentKeyID: 39508895
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.VendInvoiceJournalTotalTrxCount
---

# Vendor invoice journal totals and transaction count chart report (VendInvoiceJournalTotalTrxCount) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Vendor invoice journal totals and transaction count chart** report to view the total vendor invoice amount and the number of transactions for a specified invoice journal, in graphical form.

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
<td><p><strong>Posted:</strong></p></td>
<td><p>Select this check box to include only posted transactions on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Invoice register</strong></p></td>
<td><p>Select this check box to include transactions from the invoice register.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Invoice journal</strong></p></td>
<td><p>Select this check box to include transactions from the invoice journal.</p></td>
</tr>
<tr class="even">
<td><p><strong>Journal number:</strong></p></td>
<td><p>Select the journal number to create the report for.</p></td>
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
<td><p>VendInvoiceJournalTotalTrxCount</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>\SSRS Reports\Reports\VendInvoiceJournalTotalTrxCount</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendVendorInvoiceJourTotalsandTrxCount</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Reports</strong> &gt; <strong>Statistics</strong> &gt; <strong>Invoice</strong> &gt; <strong>Vendor invoice journal totals and transaction count chart</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - LedgerJournalTrans table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

