---
title: Lead analysis report (smmLeadsAnalysis)
TOCTitle: Lead analysis report (smmLeadsAnalysis)
ms:assetid: cd6d9c9f-b565-41b0-bfc6-9ab2fe264224
ms:mtpsurl: https://technet.microsoft.com/library/Hh412255(v=AX.60)
ms:contentKeyID: 36916367
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.smmLeadsAnalysis
---

# Lead analysis report (smmLeadsAnalysis) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to analyze your organization's lead records.

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
<td><p><strong>Lead</strong></p></td>
<td><p>Select the parameters to view only certain lead records on the report. For example, you can select to view lead records that have a high priority but a low rating.</p></td>
</tr>
<tr class="even">
<td><p><strong>Demographics</strong></p></td>
<td><p>Select the parameters to report only on lead records that have specific segments, subsegments, or sales units.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Address</strong></p></td>
<td><p>Select the parameters to view only certain lead records, based on address components.</p></td>
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
<td><p>smmLeadsAnalysis</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\smmLeadsAnalysis</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>smmLeadAnalysis</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Sales and marketing</strong> &gt; <strong>Reports</strong> &gt; <strong>Sales management</strong> &gt; <strong>Lead analysis</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DynamicsAXOLAP

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


