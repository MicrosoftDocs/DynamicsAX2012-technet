---
title: Posting restrictions by user report (LedgerJournalPostControlByUser)
TOCTitle: Posting restrictions by user report (LedgerJournalPostControlByUser)
ms:assetid: ef6747a9-13ec-47dc-b435-79a51c760cf2
ms:mtpsurl: https://technet.microsoft.com/library/Hh527789(v=AX.60)
ms:contentKeyID: 37832043
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.LedgerJournalPostControlByUser
---

# Posting restrictions by user report (LedgerJournalPostControlByUser) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view posting restriction information for users. This information includes the user name, journal type, and journal name. Posting restrictions determine whether specific users or user groups can post only journals that they create. For more information, see [Set up posting restrictions](set-up-posting-restrictions.md).

This report displays only journal names for which posting restrictions are defined.

The information on this report is sorted first by user and then by journal type. You can also print a **Posting restrictions by journal type** report, on which information is sorted first by journal type and then by journal name.

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
<td><p><strong>Users to include</strong></p></td>
<td><p>Select the type of user information to include.</p>
<div class="alert">

> [!NOTE]
> <P>The same user might appear on the report for some journal names but not others. For example, a user is restricted in the <STRONG>Vend_inv</STRONG> journal name for the <STRONG>AP</STRONG> user group, but is not restricted in the <STRONG>Vend_pay</STRONG> journal name for the <STRONG>AP</STRONG> user group. If you view the report when <STRONG>Users with no posting restrictions</STRONG> is selected, the <STRONG>Vend_pay</STRONG> journal name appears on the report for the user, but the <STRONG>Vend_inv</STRONG> journal name does not.</P>


</div></td>
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
<td><p>LedgerJournalPostControlByUser</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\LedgerJournalPostControlByUser</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerJournalPostControlByUser</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Base data</strong> &gt; <strong>Various</strong> &gt; <strong>Posting restrictions by user</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - LedgerJournalPostControlTmp table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the LedgerJournalPostControlDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Posting restrictions by journal type report (LedgerJournalPostControlByJournalType)](posting-restrictions-by-journal-type-report-ledgerjournalpostcontrolbyjournaltype.md)

  


