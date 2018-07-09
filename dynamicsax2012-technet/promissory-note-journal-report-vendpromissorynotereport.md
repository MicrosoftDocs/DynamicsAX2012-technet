---
title: Promissory note journal report (VendPromissoryNoteReport)
TOCTitle: Promissory note journal report (VendPromissoryNoteReport)
ms:assetid: ede350ed-7684-46a5-8542-82cf5dc2e5ae
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh538465(v=AX.60)
ms:contentKeyID: 39508894
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.VendPromissoryNoteReport
---

# Promissory note journal report (VendPromissoryNoteReport) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Promissory note journal** report to view information about promissory notes. This information includes the status and amount of each promissory note.

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
<td><p><strong>Settlements details</strong></p></td>
<td><p>Select this check box to print information about the invoices that the promissory notes are settled with. This information includes the invoice ID, vendor account, legal entity, voucher number, due date, total amount, and transaction currency.</p></td>
</tr>
<tr class="even">
<td><p><strong>Transaction details</strong></p></td>
<td><p>Select this check box to print information about the vouchers that are associated with promissory note transactions. This information includes the voucher number, posting profile, transaction date, deadline for feedback from the bank, and description.</p></td>
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
<td><p>VendPromissoryNoteReport</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>\SSRS Reports\Reports\VendPromissoryNoteReport</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendPromissoryNoteReport</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Reports</strong> &gt; <strong>Status</strong> &gt; <strong>Promissory note journal</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - VendPromissoryNoteReportTmp table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the VendPromissoryNoteReportDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

