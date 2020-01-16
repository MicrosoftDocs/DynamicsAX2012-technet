---
title: Absence setup report (HcmAbsenceSetup)
TOCTitle: Absence setup report (HcmAbsenceSetup)
ms:assetid: 2e5f42b1-1f35-44c7-bd6e-94d3ca3c5f72
ms:mtpsurl: https://technet.microsoft.com/library/JJ841456(v=AX.60)
ms:contentKeyID: 50411095
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.HcmAbsenceSetup
---

# Absence setup report (HcmAbsenceSetup) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Print this report to see all employees who are assigned to each absence setup. The results are sorted by setup.

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
<td><p>HcmAbsenceSetup</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\HcmAbsenceSetup</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>HRMAbsenceSetup</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Human resources</strong> &gt; <strong>Reports</strong> &gt; <strong>Absence</strong> &gt; <strong>Absence setup</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DirPartyTable table

  - DirPerson table

  - HcmEmployment table

  - HcmEmploymentAbsenceSetup table

  - HcmWorker table

  - HRMAbsenceSetup table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[About absence administration](about-absence-administration.md)

  


