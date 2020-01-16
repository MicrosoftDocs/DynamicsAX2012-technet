---
title: Payment proposal report (CustVendPaymProposal)
TOCTitle: Payment proposal report (CustVendPaymProposal)
ms:assetid: edd0959d-def2-4907-b17e-29a496d6b87e
ms:mtpsurl: https://technet.microsoft.com/library/Hh209727(v=AX.60)
ms:contentKeyID: 36060745
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustVendPaymProposal
---

# Payment proposal report (CustVendPaymProposal) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Payment proposal** report displays payment methods, payment amounts, discounts given, and account information for open customer invoices or open vendor invoices.

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
<td><p><strong>Payment</strong></p></td>
<td><p>Select this check box to display payment line details on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Invoice</strong></p></td>
<td><p>Select this check box to display invoice line details on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Grouping by</strong></p></td>
<td><p>Select how to group the information on the report.</p>
<ul>
<li><p><strong>Account</strong> – Group the information by customer account or vendor account.</p></li>
<li><p><strong>Bank</strong> – Group the information by the bank account of the payment.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Subtotal</strong></p></td>
<td><p>Select which column to calculate a subtotal for.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Customer account</strong> or <strong>Vendor account</strong></p></td>
<td><p>Select the range of customer accounts or vendor accounts to display on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Bank account</strong></p></td>
<td><p>Select the range of bank accounts to display on the report.</p></td>
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
<td><p>CustVendPaymProposal</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustVendPaymProposal</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustVendPaymProposal</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><ol>
<li><p>Click <strong>Accounts receivable</strong> &gt; <strong>Journals</strong> &gt; <strong>Payments</strong> &gt; <strong>Payment journal</strong>.</p>
<p>–or–</p>
<p>Click <strong>Accounts payable</strong> &gt; <strong>Journals</strong> &gt; <strong>Payments</strong> &gt; <strong>Payment journal</strong>.</p></li>
<li><p>Click <strong>Lines</strong>. Click <strong>Payment proposal</strong> &gt; <strong>Create payment proposal</strong>, and then click <strong>Payments</strong>.</p></li>
</ol></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustVendPaymProposalTmp table


> [!NOTE]
> <P>To determine where the data in the temp table comes from, view the cross-references for the CustVendPaymProposalController.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


