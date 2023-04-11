---
title: Forecast positions by budget plan report (BudgetPlanHCMReport)
TOCTitle: Forecast positions by budget plan report (BudgetPlanHCMReport)
ms:assetid: ce8e38a9-cdc1-4f4c-a813-ec38899d92fb
ms:mtpsurl: https://technet.microsoft.com/library/JJ714211(v=AX.60)
ms:contentKeyID: 49651320
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.BudgetPlanHCMReport
---

# Forecast positions by budget plan report (BudgetPlanHCMReport) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This report displays details about forecast positions, sorted by budget plan. The report can be grouped and subtotaled by summary options, such as department, job, reporting-to position, position type, and compensation region.

This report is available only if Microsoft Dynamics AX 2012 R2 is installed.

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
<td><p><strong>Budget planning process</strong></p></td>
<td><p>Select a budget planning process for the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Budget plan scenario</strong></p></td>
<td><p>Select a budget plan scenario for the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>FTE scenario</strong></p></td>
<td><p>Select a budget plan scenario that is used to count full-time equivalents (FTEs).</p></td>
</tr>
<tr class="even">
<td><p><strong>Exceptions only</strong></p></td>
<td><p>Select this check box to include only the following exceptions on the report:</p>
<ul>
<li><p>Forecast positions that are not included in a budget plan</p></li>
<li><p>Forecast position FTE counts that are not included in a budget plan</p></li>
<li><p>Total FTE counts that are not equal to the FTE counts on the forecast positions</p></li>
</ul>
<p>Clear this check box to include all forecast positions on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Option 1</strong></p></td>
<td><p>Select an option to group and subtotal the report by department, job, reporting-to position, position type, or compensation region.</p></td>
</tr>
<tr class="even">
<td><p><strong>Option 2</strong></p></td>
<td><p>If a value is selected in the <strong>Option 1</strong> field, select an additional option to group and subtotal the report by.</p></td>
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
<td><p>BudgetPlanHCMReport</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\BudgetPlanHCMReport</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>BudgetPlanHCMReport</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Budgeting</strong> &gt; <strong>Reports</strong> &gt; <strong>Budget planning</strong> &gt; <strong>Forecast positions by budget plan</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - HcmPositionForecast table

  - HcmPositionForecastDetail table

  - OMOperatingUnit table

  - BudgetPlanLineSource table

  - BudgetPlanLine table

  - BudgetPlanScenario table

  - BudgetPlanHeader table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


