---
title: (CHE) DebitDirect (CH) report (CustOutPaymOrderCH_DebitDirect)
TOCTitle: (CHE) DebitDirect (CH) report (CustOutPaymOrderCH_DebitDirect)
ms:assetid: 61305999-891b-4620-887b-460603698462
ms:mtpsurl: https://technet.microsoft.com/library/Hh527129(v=AX.60)
ms:contentKeyID: 37823180
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustOutPaymOrderCH_DebitDirect
---

# (CHE) DebitDirect (CH) report (CustOutPaymOrderCH\_DebitDirect) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **DebitDirect (CH)** report prints a payment order for customer payments when you post a payment journal. This report is typically used by accounts receivable payments clerks to maintain customer payments.


> [!NOTE]
> <P>(CHE) This report is available only to legal entities whose primary address is in Switzerland.</P>



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
<td><p><strong>Bank account</strong></p></td>
<td><p>The bank account number for the transaction.</p></td>
</tr>
<tr class="even">
<td><p><strong>Due date</strong></p></td>
<td><p>Select the due date of the transaction.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Order number</strong></p></td>
<td><p>Enter the order number.</p></td>
</tr>
<tr class="even">
<td><p><strong>Payment advice from quantity of invoices</strong></p></td>
<td><p>Enter the minimum number of invoices that must be generated before payment advice is printed.</p></td>
</tr>
<tr class="odd">
<td><p><strong>File name</strong></p></td>
<td><p>Select the file name and path where the documents are stored.</p></td>
</tr>
<tr class="even">
<td><p><strong>Control report</strong></p></td>
<td><p>Select this check box to print a control report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Payment order</strong></p></td>
<td><p>Select this check box to print a bank payment order.</p></td>
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
<td><p>CustOutPaymOrderCH_DebitDirect</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustOutPaymOrderCH_DebitDirect</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustOutPaymOrderReportCH_DebitDirect</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Journals</strong> &gt; <strong>Payments</strong> &gt; <strong>Payment journal</strong>. Click <strong>Lines</strong>. In the <strong>Journal voucher</strong> form, click <strong>Functions</strong> &gt; <strong>Generate payments</strong>. In the <strong>Generate payments</strong> form, in the <strong>Export format</strong> field, select <strong>DebitDirect (CH)</strong>. In the <strong>Bank account</strong> field, select a bank account, and then click <strong>Dialog</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustOutPaymOrderCHTmp\_DebitDirect table


> [!NOTE]
> <P>To find out where the data in the temp table comes from, view the cross-references for the CustOutPaymOrderCHDP_DebitDirect.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


