---
title: (ITA) Fiscal journal report (LedgerFiscalJournal_IT)
TOCTitle: (ITA) Fiscal journal report (LedgerFiscalJournal_IT)
ms:assetid: 663f1bae-e45d-4e97-8733-a1608255fa6c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh335153(v=AX.60)
ms:contentKeyID: 36687365
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.LedgerFiscalJournal_IT
---

# (ITA) Fiscal journal report (LedgerFiscalJournal\_IT) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Fiscal journal** report is a legal report that includes posting details in the order in which they were posted. The line numbers are allocated continuously based on the posting date and are not fixed. The line numbers are allocated when the report is printed. This report is used to review the status of general ledger processes. This report is typically used by chief executive officers, chief financial officers, compliance managers, accounting managers, accounting supervisors, and financial controllers.


> [!NOTE]
> <P>(ITA) This report is available only to legal entities whose primary address is in Italy.</P>



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
<td><p><strong>From transaction date</strong></p></td>
<td><p>Enter the starting date of the interval for which to print the report. Because a fiscal journal is always printed for the calendar year, the fiscal year and the page numbering of the report start on January 1 of the year entered in the <strong>From date</strong> field. However, the <strong>From date</strong> to <strong>To date</strong> range applies, which means that only pages with transactions dated in the selected range are printed.</p>
<p>For example, if the <strong>From date</strong> is February 1, 2011, and 15 pages are printed during the period of January 1 to 31, 2011, the number of the first page of the report printed for a period beginning February 1 will be 16. If the <strong>From date</strong> is January 1, the first page of the report will be page 1.</p></td>
</tr>
<tr class="even">
<td><p><strong>To transaction date</strong></p></td>
<td><p>Enter the ending date of the interval for which to print the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>All year</strong></p></td>
<td><p>Select this check box to use automatic page numbering within the current fiscal year. Clear the check box to use the user-defined field setup in the <strong>Follow previous</strong> section.</p></td>
</tr>
<tr class="even">
<td><p><strong>Include current</strong></p></td>
<td><p>Select this check box to include transactions with a <strong>Current</strong> posting layer.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Include operations</strong></p></td>
<td><p>Select this check box to include transactions with an <strong>Operations</strong> posting layer.</p></td>
</tr>
<tr class="even">
<td><p><strong>Include tax</strong></p></td>
<td><p>Select this check box to include transactions with a <strong>Tax</strong> posting layer.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Follow previous</strong></p></td>
<td><p>Select the relevant check boxes to modify the <strong>Change to</strong> fields.</p>
<div>

> [!NOTE]
> <P>These fields are available only when the <STRONG>All year</STRONG> check box is not selected.</P>


</div>
<p></p></td>
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
<td><p>LedgerFiscalJournal_IT</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\LedgerFiscalJournal_IT</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerReport_FiscalJournal_IT</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>External</strong> &gt; <strong>Fiscal journal</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - LedgerFiscalJournalTmp\_IT table


> [!NOTE]
> <P>To find out where the data in the temp table comes from, view the cross-references for the LedgerFiscalJournalDP_IT.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

