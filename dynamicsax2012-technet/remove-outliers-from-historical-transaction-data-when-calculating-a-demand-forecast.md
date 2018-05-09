---
title: Remove outliers from historical transaction data when calculating a demand forecast
TOCTitle: Remove outliers from historical transaction data when calculating a demand forecast
ms:assetid: 78156831-8a36-4421-8b7c-be1de68e8e10
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn715969(v=AX.60)
ms:contentKeyID: 62200097
ms.date: 05/01/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.SysQueryForm
- demand forecast
- Forms.ReqDemPlanOutlierQuerySetup
- demand planning
- baseline forecast, historical forecast, adjusted forecast
- demand forecasting
- demand forecasts, sales forecast, sales forecasts, forecast accuracy
- Forms.ReqDemPlanOutlierQueryPreview
---

# Remove outliers from historical transaction data when calculating a demand forecast 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to exclude outliers from the historical data that are used to calculate a demand forecast. Outliers are data that are not considered to be part of the overall pattern of demand, for example, sales transactions that result from a clearance sale do not represent typical demand. Because outliers can affect forecast accuracy, it can be useful to exclude them from the calculation. In Microsoft Dynamics AX 2012 R3 demand forecasting, you can exclude outliers to improve forecast accuracy. Perform this optional task by using a query to select the specific transactions that you want to exclude.

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
<td><p>Demand forecasting is set up. For more information, see <a href="set-up-demand-forecasting.md">Set up demand forecasting</a>.</p></td>
</tr>
<tr class="even">
<td><p>Data</p></td>
<td><p>A baseline forecast has been created. For more information, see <a href="create-a-baseline-forecast.md">Create a baseline forecast</a>.</p></td>
</tr>
</tbody>
</table>


## Remove outliers

To remove outliers from historical transactional data, follow these steps:

1.  Click **Master planning** \> **Setup** \> **Demand forecasting** \> **Outlier removal**.

2.  Click **New** to create a query that defines which transactions to exclude from the historical data.

3.  Select the company for which the query applies, and then enter a name and description. The **Query date** field is filled with today’s date.

4.  Select the **Active** check box to exclude the transactions that are found by the query, from the historical data. This setting will take effect when you create a baseline forecast.

5.  Click **Edit query**. In the **Outlier removal query** form you can add, remove, and select the criteria that define which transactions will be excluded when the baseline forecast is calculated. For example, select a particular item or order transaction that you want to exclude.
    
    To create a query that is based on an existing query, select it, and then click **Duplicate**. You can use the query as it is. The **Query date** field identifies the version. Optionally, you can modify the name and description, and then click **Edit query** to modify the criteria.

6.  Click **OK** to run the query.

7.  Click **Display transactions**. The **Outlier transactions** form lists the transactions that meet the criteria that is defined in the query and that will be excluded from the historical data when the demand forecast is calculated.

## Next step

After you’ve removed the outliers from the forecast calculation, you create the demand forecast. For more information, see [Create a baseline forecast](create-a-baseline-forecast.md).

## Related tasks

[Set up demand forecasting](set-up-demand-forecasting.md)

[Create a baseline forecast](create-a-baseline-forecast.md)

[View a demand forecast in Excel](view-a-demand-forecast-in-excel.md)

[Adjust a demand forecast in Excel](adjust-a-demand-forecast-in-excel.md)

[Import a demand forecast to Microsoft Dynamics AX](import-a-demand-forecast-to-microsoft-dynamics-ax.md)

[Calculate past forecast accuracy](calculate-past-forecast-accuracy.md)

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

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

