---
title: Record level security report (SysRecordLevelSecurity)
TOCTitle: Record level security report (SysRecordLevelSecurity)
ms:assetid: 70bc6b81-4699-45a4-84a8-8b719a502e39
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh335155(v=AX.60)
ms:contentKeyID: 36687367
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Record level security report (SysRecordLevelSecurity) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This report displays information about the record-level security filters that are set up in Microsoft Dynamics AX.

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
<td><p>Company</p></td>
<td><p>Select the company (DataAreaID) for which you want to view record-level security filters.</p></td>
</tr>
<tr class="even">
<td><p>Table ID</p></td>
<td><p>Select the table for which you want to view record-level security filters.</p></td>
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
<td><p>SysRecordLevelSecurity</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\SysRecordLevelSecurity</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>SysRecordLevelSecurity</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>System administration</strong> &gt; <strong>Reports</strong> &gt; <strong>Security</strong> &gt; <strong>Record level security</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - SysRecordLevelSecurityTmp


> [!NOTE]
> <P>To find out where the data in the temp table comes from, view the cross-references for the SysRecordLevelSecurityDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


