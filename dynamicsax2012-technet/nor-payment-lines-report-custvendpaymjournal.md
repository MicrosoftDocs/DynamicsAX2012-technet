---
title: (NOR) Payment lines report (CustVendPaymJournal)
TOCTitle: (NOR) Payment lines report (CustVendPaymJournal)
ms:assetid: a917f40a-ae47-4cd5-8fdf-974213bafc07
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh433515(v=AX.60)
ms:contentKeyID: 36941296
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustVendPaymJournal
---

# (NOR) Payment lines report (CustVendPaymJournal) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Payment lines** report displays a summary of the vouchers that are generated for a customer payment or vendor payment, along with the payment status of the vouchers. This report is typically used by accounts payable payments clerks and accounts receivable payments clerks to maintain customer payments and vendor payments.

Before you can generate this report, you must set up a method of payment that uses the **BBS Direkte Remittering (NO)** or **TelePay 2,01 (NO)** return file format. You can select the required return file format in the **Return format** field in the **Methods of payment - customers** or **Methods of payment - vendors** form.


> [!NOTE]
> <P>(NOR) This report is available only to legal entities whose primary address is in Norway.</P>



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
<td><p><strong>Specification</strong></p></td>
<td><p>Select this check box to print the payment specifications of the vouchers.</p></td>
</tr>
<tr class="even">
<td><p><strong>Sum up currency/date</strong></p></td>
<td><p>Select this check box to print the sum of the payments by payment currency and payment date.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Journal batch number</strong></p></td>
<td><p>The ledger journal batch number that is used to generate the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Payment status</strong></p></td>
<td><p>The status of the payment. One of the following options is displayed:</p>
<ul>
<li><p><strong>None</strong> – The payment proposal has been generated.</p></li>
<li><p><strong>Sent</strong> – The payment or check has been generated.</p></li>
<li><p><strong>Received</strong> – The bank has received the payment file.</p></li>
<li><p><strong>Approved</strong> – The payment has been approved.</p></li>
<li><p><strong>Rejected</strong> – The payment has been rejected.</p></li>
<li><p><strong>Delete</strong> – A payment deletion file has been sent to Bankenes BetalingsSentral (BBS).</p></li>
<li><p><strong>Sent delete</strong> – A payment file that has a <strong>Delete</strong> status has been sent to the bank.</p></li>
<li><p><strong>Deleted</strong> – The payment file has been deleted.</p></li>
</ul></td>
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
<td><p>CustVendPaymJournal</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustVendPaymJournal</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustVendPaymReportJournalRun</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Journals</strong> &gt; <strong>Payments</strong> &gt; <strong>Payment transfer</strong>. Click <strong>Return file - customer</strong>. In the <strong>Load diskette with payments</strong> form, in the <strong>Method of payment</strong> field, select the method of payment that uses the return file format that is required to generate the report, and then click <strong>OK</strong>. Enter the required details, and then click <strong>Payment lines</strong>.</p>
<p>–or–</p>
<p>Click <strong>Accounts receivable</strong> &gt; <strong>Journals</strong> &gt; <strong>Payments</strong> &gt; <strong>Payment transfers</strong>. Click <strong>Return file - vendor</strong>. In the <strong>Load diskette with payments</strong> form, in the <strong>Method of payment</strong> field, select the method of payment that uses the return file format that is required to generate the report, and then click <strong>OK</strong>. Enter the required details, and then click <strong>Payment lines</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustVendPaymJournalTmp table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the CustVendPaymJournalDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

