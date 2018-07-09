---
title: Create a baseline forecast
TOCTitle: Create a baseline forecast
ms:assetid: a5f3a790-6f2f-4a18-9711-61a262392fd8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497811(v=AX.60)
ms:contentKeyID: 62200130
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- demand forecasting, demand forecast, demand forecasts, sales forecast, sales forecasts, forecasting setup, baseline forecast, historical forecast, adjusted forecast
- Forms.ReqDemPlanCreateForecastDialog
- demand planning
---

# Create a baseline forecast [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to create a baseline forecast by using Microsoft Dynamics AX 2012 R3 demand forecasting. A baseline forecast is an estimate of future demand that is based on historical demand. When you set up the parameters for demand forecasting, you define the types of demand transactions for which to collect historical data. When you create a baseline forecast, you define the period during which to collect historical data. The data is then loaded into a Microsoft SQL Server Analysis Services cube where the baseline forecast is calculated and stored. You can view the demand forecast by using an Excel file.

When you create a baseline forecast, you must first specify the parameters and filters that are used in the calculation. For example, you can create a baseline forecast that estimates demand based on transaction data from the past year for a specific company, for the coming month, and for a selected group of items.

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
<td><ul>
<li><p>Demand forecasting is set up. For more information, see <a href="set-up-demand-forecasting.md">Set up demand forecasting</a>.</p></li>
<li><p>Forecast models are set up. For more information, see <a href="set-up-a-forecast-model.md">Set up a forecast model</a>.</p></li>
<li><p>Unit conversions are defined for the unit that is used for demand forecasting. For more information, see <a href="https://technet.microsoft.com/en-us/library/hh209285(v=ax.60)">Unit conversions (form)</a>.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Data</p></td>
<td><p>There is enough historical transaction data for the items for which demand forecast is calculated.</p></td>
</tr>
</tbody>
</table>


## Create a baseline forecast

To create a baseline forecast, follow these steps:

1.  Click **Master planning** \> **Periodic** \> **Demand forecasting** \> **Generate statistical baseline forecast**.

2.  In the **Historical horizon** field group, select a start date and end date. These dates define the period during which data from historical transactions is collected and used to calculate the baseline forecast.

3.  In the **Baseline forecast start date** field group, select a start date for the forecast. This field contains the start date of the new forecast bucket by default, but you can change it.

4.  In the **Filters** field group, click **Select** to open a query where you can select the filter criteria to apply when the forecast is calculated. For example, you can select a specific intercompany planning group for which to calculate the forecast.
    
    The use of filters also improves performance.

5.  In the **Forecast bucket** field, select a time unit for which forecast is calculated. For example, you can calculate a weekly forecast or a monthly forecast.

6.  In the **Forecast horizon** field, enter a number of forecast buckets for which to calculate the forecast. For example, if you select a forecast bucket of a month, and enter a forecast horizon of 12, forecast is calculated for 12 months.

7.  In the **Freeze time fence** field, enter a number of forecast buckets during which the forecast is frozen, and users may not modify it.

8.  In the **Manual adjustments** field group, select the **Transfer manual adjustments to the demand forecast** check box to apply the manual adjustments that were made to previous demand forecasts, to the new forecast.

9.  In the **Demand forecast identification** field group, enter a name for the forecast.

10. The **Excel demand forecast file path** field contains the location for saving the demand forecast file that is specified in the **Demand forecasting parameters** form by default, but you can override it.

11. Click **OK** to generate the forecast.

12. Double-click the Infolog that is displayed, to open and view the forecast.

## Next step

After you create a baseline forecast, you can view it by using an Excel file. For more information, see [View a demand forecast in Excel](view-a-demand-forecast-in-excel.md).

## Related tasks

[Set up demand forecasting](set-up-demand-forecasting.md)

[View a demand forecast in Excel](view-a-demand-forecast-in-excel.md)

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

[Microsoft Time Series Technical Reference](http://msdn.microsoft.com/en-us/library/bb677216.aspx)

[Analytics in Microsoft Dynamics AX](analytics-in-microsoft-dynamics-ax.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

