---
title: Import a demand forecast to Microsoft Dynamics AX
TOCTitle: Import a demand forecast to Microsoft Dynamics AX
ms:assetid: f8dd92bc-41ec-414d-bf41-ae505f71f0cc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497859(v=AX.60)
ms:contentKeyID: 62200189
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.ReqDemPlanImportForecastDialog
- MsDynAx060.Forms.ReqDemPlanImportForecastDialog
- demand planning
- demand forecasting, demand forecast, demand forecasts, sales forecast, sales forecasts, baseline forecast, historical forecast, adjusted forecast
audience: Application User
ms.search.region: Global
---

# Import a demand forecast to Microsoft Dynamics AX 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to import a demand forecast to Microsoft Dynamics AX 2012 R3. When you import the forecast to specific companies and forecast models, the demand forecast data becomes input for the requirements calculation in master planning.


> [!NOTE]
> <P>The procedure to import a demand forecast is the same, regardless of whether you have made adjustments to the forecast. For information about making adjustments to the forecast, see <A href="adjust-a-demand-forecast-in-excel.md">Adjust a demand forecast in Excel</A>.</P>



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


## Import a demand forecast

To import a demand forecast to AX 2012 R3, follow these steps:

1.  Click **Master planning** \> **Periodic** \> **Demand forecasting** \> **Import forecast**.

2.  On the **General** tab, in the **Import settings** field group, the **Start** field contains the start date of the most recent baseline forecast. The **End** field contains the end date of the forecast, based on the forecast bucket and forecast horizon that are defined in the **Create statistical baseline forecast** form. These are the default settings, but you can change them.

3.  Select the **Save the manual adjustments made to the baseline demand forecast** check box to make sure that adjustments to the demand forecast are saved after it has been imported.
    
    If you don’t select this check box, the adjustments are deleted after the forecast is imported. You can use this setting to discard all manual adjustments that have been made to the demand forecast.

4.  In the grid, use the **Add** and **Remove** buttons to select the companies and corresponding forecast models to which the demand forecast will be imported. By default, all companies for which there is forecast data in the cube are displayed. For each company, the **Inventory forecast model** that is defined for the static master plan in the **Master plans** form is also displayed by default. If you select a company for which there is no demand forecast data in the cube, a warning message is displayed.

5.  Click **OK** to import the demand forecast.

## View the demand forecast in AX 2012 R3

To view the demand forecast, follow these steps:

1.  Click **Inventory management** \> **Inquiries** \> **Forecast** \> **Demand forecast**.
    
    You can also open the demand forecast from one of the following locations.
    
      - Click **Product information management** \> **Common** \> **Released products**. Select a released product, and on the **Action Pane**, on the **Plan** tab, click **Demand forecast**.
    
      - Click **Inventory management** \> **Periodic** \> **Forecast** \> **Entry** \> **Item groups**. Select an item group, and then click **Demand**.
    
      - Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**. Select a customer. On the **Action Pane**, on the **Customer** tab, click **Forecast**, and then select **Forecast**.
    
      - Click **Accounts receivable** \> **Setup** \> **Customers** \> **Customer groups**. Select a customer group, and then click **Forecast**.

2.  In the **Demand forecast** form, on the **Filter** tab, select the criteria to display the demand forecast. For example, select a specific customer group and customer.

## Related tasks

[Set up demand forecasting](set-up-demand-forecasting.md)

[Create a baseline forecast](create-a-baseline-forecast.md)

[View a demand forecast in Excel](view-a-demand-forecast-in-excel.md)

[Adjust a demand forecast in Excel](adjust-a-demand-forecast-in-excel.md)

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

  


