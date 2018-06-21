---
title: Fixed-price projects - profit and loss report (ProjListEstimateWonFixedPriceProjPL)
TOCTitle: Fixed-price projects - profit and loss report (ProjListEstimateWonFixedPriceProjPL)
ms:assetid: fca45824-5faa-4c24-afb6-3e3c19f27270
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa634935(v=AX.60)
ms:contentKeyID: 37832045
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ProjListEstimateWonFixedPriceProjPL
---

# Fixed-price projects - profit and loss report (ProjListEstimateWonFixedPriceProjPL) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to analyze the profit or loss for fixed-price projects for a specified date range.

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
<td><p>Select the period code of the fixed-price projects that you want to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Estimate date</strong></p></td>
<td><p>Select a transaction date. Only hours for fixed-price projects as of the selected date are displayed on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Estimate</strong></p></td>
<td><p>Select the estimate column that you want the report to use from the following options:</p>
<ol>
<li><p><strong>Estimate</strong> – Display values for the current period.</p></li>
<li><p><strong>Accumulated</strong> – Display values for all periods previous to the estimate date.</p></li>
<li><p><strong>Total</strong> – Display values for all periods.</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p><strong>Select</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>ProjListEstimate</strong> form, click <strong>Add</strong>. In the <strong>Criteria</strong> field, select an estimate project to display on the report. To add another estimate project, click <strong>Add</strong>.</p></td>
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
<td><p>ProjListEstimateWonFixedPriceProjPL</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Estimates</strong> &gt; <strong>Fixed-price</strong> &gt; <strong>Fixed-price projects - profit and loss</strong>.</p></td>
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

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

