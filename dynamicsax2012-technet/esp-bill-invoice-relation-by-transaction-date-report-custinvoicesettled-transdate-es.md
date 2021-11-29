---
title: (ESP) Bill-Invoice relation by transaction date report (CustInvoiceSettled_TransDate_ES)
TOCTitle: (ESP) Bill-Invoice relation by transaction date report (CustInvoiceSettled_TransDate_ES)
ms:assetid: d0d5ead9-f7c3-40fc-8f15-c9393de90684
ms:mtpsurl: https://technet.microsoft.com/library/Hh496452(v=AX.60)
ms:contentKeyID: 37072034
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustInvoiceSettled_TransDate_ES
---

# (ESP) Bill-Invoice relation by transaction date report (CustInvoiceSettled\_TransDate\_ES) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Bill-Invoice relation by transaction date** report displays a list of invoices that are settled with bills of exchange. The invoices and their corresponding bills of exchange are grouped by transaction date and are displayed in the report. This report is typically used by accountants, collections managers, and financial controllers to check the status of the bills of exchange.


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
<td><p><strong>From customer</strong></p></td>
<td><p>Select the customer account that is used to generate the bill of exchange.</p></td>
</tr>
<tr class="even">
<td><p><strong>To customer</strong></p></td>
<td><p>Select the customer account for the recipient of the bill of exchange.</p></td>
</tr>
<tr class="odd">
<td><p><strong>From date</strong>(<strong>Posting date</strong>)</p></td>
<td><p>Select the starting posting date of the transactions to include in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong>(<strong>Posting date</strong>)</p></td>
<td><p>Select the ending posting date of the transactions to include in the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>From date</strong>(<strong>Due date</strong>)</p></td>
<td><p>Select the starting due date of the transactions.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong>(<strong>Due date</strong>)</p></td>
<td><p>Select the ending due date of the transactions.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Enable status</strong></p></td>
<td><p>Select these check boxes to include bills of exchange that have a specific status in the report. You can select up to three different statuses in the <strong>Status</strong> fields.</p></td>
</tr>
<tr class="even">
<td><p><strong>Status</strong></p></td>
<td><p>Select the status of the bill of exchange from the following options:</p>
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
> <P>You must select the <STRONG>Enable status</STRONG> check box for each of the <STRONG>Status</STRONG> fields to include the bill of exchange with the selected statuses in the report.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Method of payment</strong></p></td>
<td><p>Select a method of payment to include in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Bill ID</strong></p></td>
<td><p>Select the unique identifier for the bill of exchange.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Invoice number</strong></p></td>
<td><p>Select a specific invoice number to include in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Amount</strong></p></td>
<td><p>Enter the minimum transaction amount for transactions to be included in the report. The transaction amount is entered in the accounting currency.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Amount</strong></p></td>
<td><p>Enter the maximum transaction amount for transactions to be included in the report. The transaction amount is entered in the accounting currency.</p></td>
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
<td><p>CustInvoiceSettled_TransDate_ES</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustInvoiceSettled_TransDate_ES</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustInvoiceSettledTransDate_ES</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Reports</strong> &gt; <strong>Bill of exchange</strong> &gt; <strong>Bill-Invoice relation by transaction date</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustInvoiceSettled\_TransDateTmp\_ES table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the CustInvoiceSettled_TransDateDP_ES.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


