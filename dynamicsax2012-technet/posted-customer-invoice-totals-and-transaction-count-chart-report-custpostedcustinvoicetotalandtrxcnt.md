---
title: Posted customer invoice totals and transaction count chart report (CustPostedCustInvoiceTotalAndTrxCnt)
TOCTitle: Posted customer invoice totals and transaction count chart report (CustPostedCustInvoiceTotalAndTrxCnt)
ms:assetid: 8aa7cf19-a516-4df3-b57e-c50630eba433
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh538455(v=AX.60)
ms:contentKeyID: 39508880
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustPostedCustInvoiceTotalandTrxCnt
---

# Posted customer invoice totals and transaction count chart report (CustPostedCustInvoiceTotalAndTrxCnt) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Posted customer invoice totals and transaction count** chart report to view, in graphical format, the total customer invoice amount that was posted by a specified user on a specified date.

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
<td><p><strong>Created by:</strong></p></td>
<td><p>Select the user to view information for. The report shows the total amount, by currency, that the selected user posted.</p></td>
</tr>
<tr class="even">
<td><p><strong>Date:</strong></p></td>
<td><p>Select the transaction date to view information for. The report shows the total amount, by currency, that the specified user posted on the selected date.</p></td>
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
<td><p>CustPostedCustInvoiceTotalandTrxCnt</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>\SSRS Reports\Reports\CustPostedCustInvoiceTotalandTrxCnt</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustPostedCustInvoiceTotalandTrxCnt</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Reports</strong> &gt; <strong>Statistics</strong> &gt; <strong>Invoice</strong> &gt; <strong>Posted customer invoice totals and transaction count chart</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustInvoiceJour table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


