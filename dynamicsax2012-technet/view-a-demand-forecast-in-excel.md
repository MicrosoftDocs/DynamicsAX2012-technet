---
title: View a demand forecast in Excel
TOCTitle: View a demand forecast in Excel
ms:assetid: 0e32c008-f2db-47e5-903b-aa1626251900
ms:mtpsurl: https://technet.microsoft.com/library/Dn497713(v=AX.60)
ms:contentKeyID: 62200034
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- ReqDemPlanCreateForecastDialog
- demand forecasting, demand forecast, demand forecasts, sales forecast, sales forecasts, forecasting setup, baseline forecast, historical forecast, adjusted forecast
- demand planning
audience: Application User
ms.search.region: Global
---

# View a demand forecast in Excel 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to view a demand forecast in an Excel file. You perform this task after you have created a baseline forecast, and it has been saved and stored in a Microsoft SQL Server Analysis Services cube.

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Setup</p></td>
<td><p>Demand forecasting has been set up. For more information, see <a href="set-up-demand-forecasting.md">Set up demand forecasting</a>.</p></td>
</tr>
<tr class="even">
<td><p>Data</p></td>
<td><p>A baseline forecast has been created. For more information, see <a href="create-a-baseline-forecast.md">Create a baseline forecast</a>.</p></td>
</tr>
</tbody>
</table>


## View a demand forecast

To view a demand forecast, follow these steps:

1.  Open the demand forecast file. You can do this in the following ways:
    
      - After you generate a baseline forecast, and the Infolog informs you that the baseline forecast has been created, double-click the Infolog or click **Open Excel file**.
    
      - After a baseline forecast has been created, browse to the location that you specified in the **Excel demand forecast file path** field. This field is located in the **Demand forecasting parameters** form and the **Create statistical baseline forecast** form.

2.  In the Excel file, click **Enable Content**. This enables the content in the **PivotTable** report, so that you can modify it. You only need to do this step the first time that you open the Excel file.

3.  In the **Forecast information** sheet, view a summary of the parameters that were used to create the baseline forecast.

4.  In the **Forecast table** sheet, view the forecasted quantities. The cells are color-coded according to the following rules:
    
      - Forecasted quantities are not highlighted.
    
      - Historical quantities are highlighted in gray.
    
      - Forecasted quantities that are frozen are highlighted in yellow.

5.  In the **Forecast table** sheet, in the **PivotTable Field List**, specify how to filter and display the forecast data that is stored in the cube. For example, you can display only the forecasted quantities, or you can display both the forecasted quantities and the historical data. The historical data is displayed as actual demand.

For more information about how to use PowerPivot tools, see [How to Use the SQL Server Data Mining Add-ins with PowerPivot for Excel](https://go.microsoft.com/fwlink/?linkid=335792) and [Analytics in Microsoft Dynamics AX](analytics-in-microsoft-dynamics-ax.md).

## Next step

After you view and analyze the demand forecast, you can adjust the forecasted quantities. For more information, see [Adjust a demand forecast in Excel](adjust-a-demand-forecast-in-excel.md).

## Related tasks

[Set up demand forecasting](set-up-demand-forecasting.md)

[Create a baseline forecast](create-a-baseline-forecast.md)

[Adjust a demand forecast in Excel](adjust-a-demand-forecast-in-excel.md)

[Import a demand forecast to Microsoft Dynamics AX](import-a-demand-forecast-to-microsoft-dynamics-ax.md)

[Calculate past forecast accuracy](calculate-past-forecast-accuracy.md)

[Remove outliers from historical transaction data when calculating a demand forecast](remove-outliers-from-historical-transaction-data-when-calculating-a-demand-forecast.md)

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Expand the <strong>Trade</strong> license key, expand the <strong>Inventory forecast</strong> configuration key, and then select the <strong>Demand forecasting</strong> (ReqDemandPlanning) configuration key.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Production planner</p></td>
</tr>
</tbody>
</table>


## See also

[Business process: demand forecasting](business-process-demand-forecasting.md)

  


