---
title: Calculate past forecast accuracy
TOCTitle: Calculate past forecast accuracy
ms:assetid: da3a953f-77b2-4f2d-a08f-fc7cc8dcaa89
ms:mtpsurl: https://technet.microsoft.com/library/Dn715984(v=AX.60)
ms:contentKeyID: 62200167
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.SysOperationTemplateForm
- demand planning
- demand forecasting, demand forecast, demand forecasts, forecast accuracy, demand forecast accuracy, historical forecast
audience: Application User
ms.search.region: Global
---

# Calculate past forecast accuracy 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to calculate the accuracy of past demand forecasts against past actual demand. In Microsoft Dynamics AX 2012 R3, forecast accuracy is measured by using these key performance indicators: mean absolute deviation (MAD) and mean absolute percentage error (MAPE).

When you calculate forecast accuracy you define the period during which historical data is collected. You can also select criteria to filter the data. For example, you can filter the data for a particular company or item allocation key. After you’ve calculated the forecast accuracy, view the results in a Microsoft Excel file.

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


## Calculate past forecast accuracy

To calculate forecast accuracy, follow these steps:

1.  Click **Master planning** \> **Periodic** \> **Demand forecasting** \> **Calculate demand forecast accuracy**.

2.  Complete the following fields.
    
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
    <td><p><strong>Forecast bucket</strong></p></td>
    <td><p>Select the forecast bucket to use when forecast accuracy is calculated.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Start of historical horizon</strong></p></td>
    <td><p>Select the start date of the period during which historical data is collected.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>End of historical horizon</strong></p></td>
    <td><p>Select the end date of the period during which historical data is collected.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Excel demand forecast file path</strong></p></td>
    <td><p>This field contains, by default, the location for saving the demand forecast file that is specified in the <strong>Demand forecasting parameters</strong> form, but you can override it. For example, reuse the path but rename the file to ForecastAccuracy.</p></td>
    </tr>
    </tbody>
    </table>


3.  In the **Filters** field group, click **Select** to open a query where you can select the filter criteria to apply when the forecast accuracy is calculated. For example, you can calculate the forecast accuracy for a specific item allocation key.
    
    The use of filters also improves performance.

4.  Click **OK** to run the calculation.

## View the demand forecast accuracy sheet in Excel

To view the **Forecast accuracy** in Excel, follow these steps:

1.  Open the demand forecast accuracy file. You can do this in the following ways:
    
      - After you calculate forecast accuracy, and a message informs you that the demand forecast accuracy was calculated, double-click the message or click **Open Excel file**.
    
      - Browse to the location that you specified in the **Excel demand forecast file path** field.

2.  In the Excel file, click **Enable Content**. This enables the content in the **PivotTable** report, so that you can modify it. You only have to do this step the first time that you open the Excel file.

3.  In the **Forecast accuracy** sheet, in the **PivotTable Field List**, select **Released products \> Released product** to display the following columns:
    
      - **Error absolute** – The difference between the historical demand quantity and the adjusted forecast quantity.
    
      - **Forecast error percentage** – The error absolute quantity expressed as a percentage of the adjusted forecast quantity.

## Related tasks

[Set up demand forecasting](set-up-demand-forecasting.md)

[Create a baseline forecast](create-a-baseline-forecast.md)

[View a demand forecast in Excel](view-a-demand-forecast-in-excel.md)

[Adjust a demand forecast in Excel](adjust-a-demand-forecast-in-excel.md)

[Import a demand forecast to Microsoft Dynamics AX](import-a-demand-forecast-to-microsoft-dynamics-ax.md)

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
<td><p>To perform this task, you must be a member of the Production planner security role.</p></td>
</tr>
</tbody>
</table>


## See also

[Business process: demand forecasting](business-process-demand-forecasting.md)

  


