---
title: (FRA) Open promissory notes report (VendPromissoryNoteOpenTrans_FR)
TOCTitle: (FRA) Open promissory notes report (VendPromissoryNoteOpenTrans_FR)
ms:assetid: eec78883-e085-4736-87a8-ec360c06744f
ms:mtpsurl: https://technet.microsoft.com/library/Bb220772(v=AX.60)
ms:contentKeyID: 36956719
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.VendPromissoryNoteOpenTrans_FR
---

# (FRA) Open promissory notes report (VendPromissoryNoteOpenTrans\_FR) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the Open promissory notes report to view a list of open promissory notes to be drawn on French bank accounts. The vendor transactions are grouped by methods of payment. For each transaction, the report includes the transaction date, note identification number, document number, vendor account number and name, bank information, and due date. This report is used by chief financial officers, accountants, accounting managers, accounting clerks, accounting supervisors, and financial controllers to inquire about open promissory notes.


> [!NOTE]
> <P>(FRA) This report is available only to legal entities whose primary address is in France.</P>



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
<td><p><strong>Method of payment</strong></p></td>
<td><p>The method of payment that determines which transactions to include in the report. The information in this field is determined by your selections when you create a query.</p></td>
</tr>
<tr class="even">
<td><p><strong>Note ID</strong></p></td>
<td><p>The identification code of the promissory note to be included in the report. The information in this field is determined by your selections when you create a query.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Due date</strong></p></td>
<td><p>The due date that determines which transactions to include in the report. The information in this field is determined by your selections when you create a query.</p></td>
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
<td><p>VendPromissoryNoteOpenTrans_FR</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendPromissoryNoteOpenTrans_FR</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendPromissoryNoteOpenTrans_FR</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Vendor</strong> &gt; <strong>Open promissory notes</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - VendPromissoryNoteOpenTrans\_FR table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


