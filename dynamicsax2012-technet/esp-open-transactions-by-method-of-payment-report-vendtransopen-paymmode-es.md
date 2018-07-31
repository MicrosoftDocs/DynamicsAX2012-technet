---
title: (ESP) Open transactions by method of payment report (VendTransOpen_PaymMode_ES)
TOCTitle: (ESP) Open transactions by method of payment report (VendTransOpen_PaymMode_ES)
ms:assetid: 8015b9d1-7ef7-4823-8404-d9cc6c8adb63
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh496448(v=AX.60)
ms:contentKeyID: 37072030
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.VendTransOpen_PaymMode_ES
- (ESP)
- Open transactions by methods of payment
- transactions methods of payment
- VendTransOpen_PaymMode_ES
---

# (ESP) Open transactions by method of payment report (VendTransOpen\_PaymMode\_ES) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Open transactions by method of payment** report displays open vendor transactions that are grouped by vendor, due date, risk date, posting date, and method of payment. This report can be used to specify the criteria for including open vendor transactions based on the methods of payment that you select in the **Method of payment 1**, **Method of payment 2**, **Method of payment 3**, and **Method of payment 4** fields.


> [!NOTE]
> <P>You can select up to four different methods of payment to sort the transactions that appear on this report.</P>



This report is used to check and maintain the status of promissory notes and vendor payments. This report is typically used by chief financial officers, accounting managers, accounting supervisors, financial controllers, accounts payable payments clerks, and accountants.


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
<td><p><strong>From vendor</strong></p></td>
<td><p>Select the account number of the vendor who is making the payment.</p></td>
</tr>
<tr class="even">
<td><p><strong>To vendor</strong></p></td>
<td><p>Select the account number of the vendor who is receiving the payment.</p></td>
</tr>
<tr class="odd">
<td><p><strong>From date</strong>(<strong>Due date</strong>)</p></td>
<td><p>Select the starting date of the due date range to include in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong>(<strong>Due date</strong>)</p></td>
<td><p>Select the ending date of the due date range to include in the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>From date</strong>(<strong>Risk date</strong>)</p></td>
<td><p>Select the starting date of the time limit period for the bank to provide feedback about vendor payments.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong>(<strong>Risk date</strong>)</p></td>
<td><p>Select the ending date of the time limit period for the bank to provide feedback about vendor payments.</p></td>
</tr>
<tr class="odd">
<td><p><strong>From date</strong>(<strong>Posting date</strong>)</p></td>
<td><p>Select the starting date of the posting period to include in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong>(<strong>Posting date</strong>)</p></td>
<td><p>Select the ending date of the posting period to include in the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Enable status</strong></p></td>
<td><p>Select this check box to include bills of exchange that have a specific status in the report. You can select the status in the <strong>Agreed with</strong> field.</p></td>
</tr>
<tr class="even">
<td><p><strong>Agreed with</strong></p></td>
<td><p>Select the status of the bill of exchange. A bill of exchange can have one of the following statuses:</p>
<ul>
<li><p><strong>None</strong> – No bill of exchange is drawn. The bill of exchange has not been posted.</p></li>
<li><p><strong>Drawn</strong> - The bill of exchange has been posted in a draw bill of exchange journal.</p></li>
<li><p><strong>Redrawn</strong> - A bill of exchange that was previously protested has been redrawn in a redraw bill of exchange journal.</p></li>
<li><p><strong>Protested</strong> - A bill of exchange that was not honored by the bank has been protested in a protest bill of exchange journal.</p></li>
<li><p><strong>Honored</strong> - The bill of exchange has been settled. The settlement may occur before you receive confirmation from the bank.</p></li>
<li><p><strong>Remitted</strong> - The bill of exchange has been posted in a remittance journal.</p></li>
<li><p><strong>Invoiced</strong> – The bill of exchange has been invoiced.</p></li>
<li><p><strong>Invoice remitted</strong> – The bill of exchange has been invoiced and remitted.</p></li>
</ul>
<div class="alert">

> [!NOTE]
> <P>You must select the <STRONG>Enable status</STRONG> check box to include the bill of exchange with the selected status in the report.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Bank</strong></p></td>
<td><p>Select the bank account number.</p></td>
</tr>
<tr class="even">
<td><p><strong>Method of payment 1</strong></p></td>
<td><p>Select a method of payment that is used to make vendor payments. The payments that use the selected method of payment are included in the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Method of payment 2</strong></p></td>
<td><p>Select a method of payment that is used to make vendor payments. The payments that use the selected method of payment are included in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Method of payment 3</strong></p></td>
<td><p>Select a method of payment that is used to make vendor payments. The payments that use the selected method of payment are included in the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Method of payment 4</strong></p></td>
<td><p>Select a method of payment that is used to make vendor payments. The payments that use the selected method of payment are included in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Posting profile</strong></p></td>
<td><p>Select the posting profile to process the payment.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Note ID</strong></p></td>
<td><p>Select the unique key to identify promissory notes. The key is used when creating new promissory notes.</p></td>
</tr>
<tr class="even">
<td><p><strong>Invoice number</strong></p></td>
<td><p>The identification number of the invoice.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Voucher</strong></p></td>
<td><p>The voucher number in the ledger.</p></td>
</tr>
<tr class="even">
<td><p><strong>Amount</strong></p></td>
<td><p>The transaction amount in the accounting currency.</p></td>
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
<td><p>VendTransOpen_PaymMode_ES</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendTransOpen_PaymMode_ES</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendTransOpenPaymMode_ES</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Reports</strong> &gt; <strong>Promissory notes</strong> &gt; <strong>Open transactions by method of payment</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - VendTransOpen\_PaymMode\_TmpES table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the VendTransOpen_PaymMode_DPES.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


