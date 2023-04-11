---
title: (ESP) Open cartera transactions report (CustBillOfExchangeOpenTrans_ES)
TOCTitle: (ESP) Open cartera transactions report (CustBillOfExchangeOpenTrans_ES)
ms:assetid: 8e37d1c7-0606-4108-9ada-8ca38692cc88
ms:mtpsurl: https://technet.microsoft.com/library/Bb220727(v=AX.60)
ms:contentKeyID: 36814941
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustBillOfExchangeOpenTrans_ES
---

# (ESP) Open cartera transactions report (CustBillOfExchangeOpenTrans\_ES) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Open cartera transactions** report displays cartera transactions grouped by bill of exchange ID, customer, or due date. This report is used to inquire into the status of bills of exchange. This report is typically used by collections agents, collections managers, clerks, accountants, accounting managers, and financial controllers.

You can use the **Grouping by** field to select how information is grouped in the report. Use the other fields on the **General** tab to select ranges of information to include in the report.


> [!NOTE]
> <P>(ESP) This report is available only to legal entities whose primary address is in Spain.</P>



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
<td><p><strong>Grouping by</strong></p></td>
<td><p>Select how to group the transactions on the report:</p>
<ul>
<li><p><strong>Bill ID</strong> – The transactions are sorted by using the bill of exchange ID. The report title is <strong>Open cartera transactions by bill</strong>.</p></li>
<li><p><strong>Due date</strong> – The transactions are sorted by using the transaction due date. The report title is <strong>Open cartera transactions by due date</strong>.</p></li>
<li><p><strong>Customer</strong> – The transactions are sorted by using the customer ID. The report title is <strong>Open cartera transactions by customer</strong>.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>From customer</strong></p></td>
<td><p>Select the starting customer account for the range of customer accounts that you want to include in the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To customer</strong></p></td>
<td><p>Select the ending customer account for the range of customer accounts that you want to include in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>From Bill ID</strong></p></td>
<td><p>Select the starting bill ID for the range of bill of exchange IDs that you want to include in the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To Bill ID</strong></p></td>
<td><p>Select the ending bill ID for the range of bill of exchange IDs that you want to include in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong>(<strong>Due date</strong>)</p></td>
<td><p>Select the starting due date for the range of due dates that you want to include in the report.</p>
<div class="alert">

> [!NOTE]
> <P>This field is available only when you select <STRONG>Due date</STRONG> or <STRONG>Customer</STRONG> in the <STRONG>Grouping by</STRONG> field.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong>(<strong>Due date</strong>)</p></td>
<td><p>Select the ending due date for the range of due dates that you want to include in the report.</p>
<div class="alert">

> [!NOTE]
> <P>This field is available only when you select <STRONG>Due date</STRONG> or <STRONG>Customer</STRONG> in the <STRONG>Grouping by</STRONG> field.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong>(<strong>Risk date</strong>)</p></td>
<td><p>Select the starting date of the time limit period for banks to provide feedback about customer payments.</p>
<div class="alert">

> [!NOTE]
> <P>This field is available only when you select <STRONG>Due date</STRONG> or <STRONG>Customer</STRONG> in the <STRONG>Grouping by</STRONG> field.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong>(<strong>Risk date</strong>)</p></td>
<td><p>Select the ending date of the time limit period for banks to provide feedback about customer payments.</p>
<div class="alert">

> [!NOTE]
> <P>This field is available only when you select <STRONG>Due date</STRONG> or <STRONG>Customer</STRONG> in the <STRONG>Grouping by</STRONG> field.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Open</strong></p></td>
<td><p>Select this check box to include open transactions in the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Voucher</strong></p></td>
<td><p>Enter or select a voucher to include in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Status</strong></p></td>
<td><p>Select a bill of exchange status to include in the report:</p>
<ul>
<li><p><strong>None</strong> – Include bills of exchange without a status.</p></li>
<li><p><strong>Drawn</strong> – Include bills of exchange that are drawn.</p></li>
<li><p><strong>Redrawn</strong> – Include bills of exchange that are redrawn.</p></li>
<li><p><strong>Protested</strong> – Include bills of exchange that are protested.</p></li>
<li><p><strong>Honored</strong> – Include bills of exchange that are settled.</p></li>
<li><p><strong>Remitted</strong> – Include bills of exchange that are remitted.</p></li>
<li><p><strong>Invoiced</strong> – Include bills of exchange that are invoiced.</p></li>
<li><p><strong>Invoice remitted</strong> – Include bills of exchange that have remitted invoices.</p></li>
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
<td><p>CustBillOfExchangeOpenTrans_ES</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustBillOfExchangeOpenTrans_ES</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustBillOfExchangeReport_ES</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Reports</strong> &gt; <strong>Bill of exchange</strong> &gt; <strong>Open cartera transactions</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustBillOfExchangeOpenTransTmp\_ES table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the CustBillOfExchangeOpenTransDP_ES.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


