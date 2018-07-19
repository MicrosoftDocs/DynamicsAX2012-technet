---
title: (GBR) Print - UK report (RCSalesList_UK)
TOCTitle: (GBR) Print - UK report (RCSalesList_UK)
ms:assetid: 3bfe7ae8-e5a5-40e0-9803-57217a47b4db
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh335143(v=AX.60)
ms:contentKeyID: 36687354
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.RCSalesList_UK
---

# (GBR) Print - UK report (RCSalesList\_UK) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Print - UK** report is used to print the reverse charge sales list in the format required for the United Kingdom. This report is typically used by accounts receivable administrators, sales managers, and accounting managers.

In the **Reverse charge sales list** form, in the **Selection** field, you can select the type of information to display:

  - **Included** – Select this option to print or display the transactions that are included in the **Reverse charge sales list** report for the current reporting period.

  - **Reported** – Select this option to reprint a reverse charge sales list report that was printed previously. For example, you might use this option for a VAT audit. The information can be edited, marked as **Included**, and then included in the next report. You can also mark transactions as **Closed**.

  - **Closed** – Select this option to update all of the transactions to which the reverse charge has been applied. These transactions are marked as **Closed** to ensure that the report does not include the same transaction more than once. You cannot change the information in this form, but you can delete transactions.


> [!NOTE]
> <P>(GBR) This report is available only to legal entities whose primary address is in the United Kingdom.</P>



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
<td><p>Enter the starting date for the report interval.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong></p></td>
<td><p>Enter the ending date for the report interval.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Authority</strong></p></td>
<td><p>Select the account number of the sales tax authority.</p></td>
</tr>
<tr class="even">
<td><p><strong>Settlement period</strong></p></td>
<td><p>Select the identification number of the sales tax settlement period.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Approval number</strong></p></td>
<td><p>Enter the approval number issued by HM Revenue and Customs (HMRC).</p></td>
</tr>
<tr class="even">
<td><p><strong>Balance</strong></p></td>
<td><p>The status of the current transaction.</p></td>
</tr>
<tr class="odd">
<td><p><strong>List code</strong></p></td>
<td><p>The identification of the reverse charge sales list.</p></td>
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
<td><p>RCSalesList_UK</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\RCSalesList_UK</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RCSalesList_UK</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Periodic</strong> &gt; <strong>Sales tax payments</strong> &gt; <strong>United Kingdom</strong> &gt; <strong>Reverse charge sales list</strong>. Click <strong>Output</strong> &gt; <strong>Print - UK</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - RCSalesListTmp\_UK table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the RCSalesListDP_UK.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


