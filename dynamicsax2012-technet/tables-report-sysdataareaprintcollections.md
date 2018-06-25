---
title: Tables report (SysDataAreaPrintCollections)
TOCTitle: Tables report (SysDataAreaPrintCollections)
ms:assetid: 0a763144-2a35-4c12-b87e-9d87fda47288
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh335131(v=AX.60)
ms:contentKeyID: 36687340
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.SysDataAreaPrintCollections
---

# Tables report (SysDataAreaPrintCollections) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Tables report returns all tables that are stored in the Microsoft Dynamics AX database.


> [!NOTE]
> <P>The report does not return tables that are stored in tempDB or in cache.</P>



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
<td><p>SysDataAreaPrintCollections</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRs Reports\Reports\SysDataAreaPrintCollections</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>SysDataAreaPrintCollections</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>System administration</strong> &gt; <strong>Reports</strong> &gt; <strong>Database</strong> &gt; <strong>Tables</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - SysDataAreaPrintCollectionsTmp


> [!NOTE]
> <P>To learn where the data in the temp table comes from, view the cross-references for the SysDataAreaPrintCollectionsDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

