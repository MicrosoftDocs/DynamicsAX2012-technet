---
title: Fixed-price projects - profit and loss backlog report (ProjListEstimateprodBacklogPL)
TOCTitle: Fixed-price projects - profit and loss backlog report (ProjListEstimateprodBacklogPL)
ms:assetid: adeb6ddc-7716-4897-877d-99f1a7f0baae
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa589529(v=AX.60)
ms:contentKeyID: 37820227
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ProjListEstimateprodBacklogPL
---

# Fixed-price projects - profit and loss backlog report (ProjListEstimateprodBacklogPL) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to create a profit and loss backlog report. The profit and loss backlog provides an overview of how much profit remains to be posted to profit and loss accounts for the current estimate projects. The profit and loss backlog is created when the accumulated amount is subtracted from the total estimate amount.

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
<td><p><strong>Period code</strong></p></td>
<td><p>Select a period code for estimate projects. The period code that you select determines the estimate date range.</p></td>
</tr>
<tr class="even">
<td><p><strong>Estimate date</strong></p></td>
<td><p>Select an estimate date that you want to include on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Include eliminated projects</strong></p></td>
<td><p>Select whether to include projects that have previously been eliminated.</p></td>
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
<td><p>ProjListEstimate</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProjListEstimate</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProjListEstimateprodBacklogPL</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Estimates</strong> &gt; <strong>Backlog</strong> &gt; <strong>Fixed-price projects - profit and loss backlog</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProjListEstimateDP.processReport

  - ProjListEstimateTmp table

  - ProjWIPTable


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the ProjListEstimateDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


