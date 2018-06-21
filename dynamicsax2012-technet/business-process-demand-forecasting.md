---
title: 'Business process: demand forecasting'
TOCTitle: 'Business process: demand forecasting'
ms:assetid: b697648d-244f-4873-9b32-669f62ea215b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497821(v=AX.60)
ms:contentKeyID: 62200143
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- demand forecasting, demand forecast, demand forecasts, sales forecast, sales forecasts, forecasting setup, baseline forecast, historical forecast, adjusted forecast
- Forms.ReqDemPlanCreateForecastDialog
- Forms.ReqDemPlanForecastGenerationLog
- Forms.ReqDemPlanImportForecastDialog
- Forms.ReqDemPlanOutlierQuerySetup
- demand planning
---

# Business process: demand forecasting [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Microsoft Dynamics AX 2012 R3 demand forecasting is a set of tools that enable you to estimate future demand and create demand forecasts based on historical transaction data.

## Business process: demand forecasting

Use the information in the following table to create demand forecasts.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Topic</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><a href="set-up-demand-forecasting.md">Set up demand forecasting</a></p></td>
<td><p>Complete the prerequisite setup tasks before you can use demand forecasting.</p></td>
</tr>
<tr class="even">
<td><p><a href="create-a-baseline-forecast.md">Create a baseline forecast</a></p></td>
<td><p>Create a baseline forecast from historical demand data that is gathered and loaded in a Microsoft SQL Server Analysis Services cube.</p></td>
</tr>
<tr class="odd">
<td><p><a href="view-a-demand-forecast-in-excel.md">View a demand forecast in Excel</a></p></td>
<td><p>View a demand forecast in Excel. Open the demand forecast file, and use the PivotTable tools in Excel to filter and display the forecast data that is stored in the cube.</p></td>
</tr>
<tr class="even">
<td><p><a href="adjust-a-demand-forecast-in-excel.md">Adjust a demand forecast in Excel</a></p></td>
<td><p>Optional: Make manual adjustments to the forecasted quantities in the demand forecast file.</p></td>
</tr>
<tr class="odd">
<td><p><a href="import-a-demand-forecast-to-microsoft-dynamics-ax.md">Import a demand forecast to Microsoft Dynamics AX</a></p></td>
<td><p>Import a demand forecast to Microsoft Dynamics AX so specific companies and forecast models can use the forecast data as input to master planning.</p></td>
</tr>
<tr class="even">
<td><p><a href="calculate-past-forecast-accuracy.md">Calculate past forecast accuracy</a></p></td>
<td><p>Optional: Calculate the accuracy of past demand forecasts against past actual demand to improve forecast accuracy.</p></td>
</tr>
<tr class="odd">
<td><p><a href="remove-outliers-from-historical-transaction-data-when-calculating-a-demand-forecast.md">Remove outliers from historical transaction data when calculating a demand forecast</a></p></td>
<td><p>Optional: Remove outliers from the historical data to improve demand forecast accuracy.</p></td>
</tr>
</tbody>
</table>


## Integration with Microsoft Dynamics AX

The AX 2012 R3 demand forecasting features are fully integrated with Microsoft Dynamics AX and the existing forecast functionality. These features include:

  - Item allocation keys. For more information, see [Item allocation keys (form)](https://technet.microsoft.com/en-us/library/aa590322\(v=ax.60\)).

  - Intercompany planning groups. For more information, see [About intercompany master scheduling](about-intercompany-master-scheduling.md).

  - Master planning. For more information, see [Master planning](master-planning.md).

  - Forecast models. For more information, see [Forecast models (form)](https://technet.microsoft.com/en-us/library/aa620573\(v=ax.60\)).

  - Demand forecasts. For more information, see [Demand forecast (form)](https://technet.microsoft.com/en-us/library/aa499758\(v=ax.60\)).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

