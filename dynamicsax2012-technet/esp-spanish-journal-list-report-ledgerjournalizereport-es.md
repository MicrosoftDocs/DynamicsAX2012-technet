---
title: (ESP) Spanish journal list report (LedgerJournalizeReport_ES)
TOCTitle: (ESP) Spanish journal list report (LedgerJournalizeReport_ES)
ms:assetid: 1a9c1868-52fd-44e2-a79d-e0b99f853de2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh352236(v=AX.60)
ms:contentKeyID: 36687861
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.LedgerJournalizeReport_ES
- (ESP)
- Spanish journal list report
---

# (ESP) Spanish journal list report (LedgerJournalizeReport\_ES) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Spanish journal list** report displays the Spanish journal list. This report contains all journalized transactions and is sorted by date and journal number. This report is used to review the status of general ledger processes. This report is typically used by chief executive officers, chief financial officers, compliance managers, accounting managers, accounting supervisors, and financial controllers.


> [!NOTE]
> <P>(ESP) This report is available only to legal entities whose primary address is in Spain.</P>



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
<td><p>LedgerJournalizeReport_ES</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\LedgerJournalizeReport_ES</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerJournalizeReport_ES</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Periodic</strong> &gt; <strong>Journals</strong> &gt; <strong>Ledger journal</strong>. Click <strong>Spanish journal list</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - GeneralJournalAccountEntry table

  - GeneralJournalEntry table

  - LedgerEntryJournalizing table

  - MainAccountLedgerDimensionView table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


