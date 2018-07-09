---
title: (RUS) Register of payment orders printing report (BankPaymentOrderJour_RU)
TOCTitle: (RUS) Register of payment orders printing report (BankPaymentOrderJour_RU)
ms:assetid: f42cd9ea-7e8f-4851-a3f0-d556f40b9fe2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ992748(v=AX.60)
ms:contentKeyID: 51739435
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.BankPaymentOrderJour_RU
---

# (RUS) Register of payment orders printing report (BankPaymentOrderJour\_RU) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2_

The Register of payment orders printing report displays information about bank payment orders that are issued and received by a legal entity for a period that you specify. Accountants can generate this report daily to review payment order statuses.

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
<td><p>Select the starting date of the period that the report is generated for.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong></p></td>
<td><p>Select the ending date of the period that the report is generated for.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Payment order status</strong></p></td>
<td><p>Select a payment order status for which to generate the report, from the following options:</p>
<ul>
<li><p><strong>All</strong> – Print all of the generated payment orders.</p></li>
<li><p><strong>Created</strong> – Print only the payment orders that are created and have a status of <strong>Sent</strong> or <strong>Received</strong>.</p></li>
<li><p><strong>Rejected</strong> – Print only the payment orders that have a status of <strong>Rejected</strong>.</p></li>
<li><p><strong>Approved</strong> – Print only the payment orders that have a status of <strong>Approved</strong>.</p></li>
<li><p><strong>Posted</strong> – Print only the payment orders that are posted to ledger accounts.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Currency code</strong></p></td>
<td><p>Select the currency code to generate the report for.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Account</strong></p></td>
<td><p>Select the bank account number to generate the report for.</p></td>
</tr>
<tr class="even">
<td><p><strong>Electronic payment</strong></p></td>
<td><p>Select the type of payment to generate the report for.</p></td>
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
<td><p>BankPaymentOrderJour_RU</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\BankPaymentOrderJour_RU</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>BankPaymentOrderJourReport_RU</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Inquiries</strong> &gt; <strong>Payment order register</strong>. Click <strong>Print</strong> &gt; <strong>Print registry of payment orders.</strong>.</p>
<p>–or–</p>
<p>Click <strong>Accounts receivable</strong> &gt; <strong>Inquiries</strong> &gt; <strong>Payment order register</strong>. Click <strong>Print</strong> &gt; <strong>Print registry of payment orders.</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data on this report comes from

The data on this report comes from the following sources:

  - BankPaymentOrderJour\_RU table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(RUS) Registry of payment orders](rus-registry-of-payment-orders.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

