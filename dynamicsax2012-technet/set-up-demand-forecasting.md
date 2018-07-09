---
title: Set up demand forecasting
TOCTitle: Set up demand forecasting
ms:assetid: 7d928df8-d612-4d63-9949-0abf7956109a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497793(v=AX.60)
ms:contentKeyID: 62200105
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.ForecastItemAllocation
- Forms.ReqDemPlanDefaultAlgorithmParameters
- MsDynAx060.Forms.ForecastItemAllocation
- Forms.ReqDemPlanForecastParameters
- MsDynAx060.Forms.ReqDemPlanDefaultAlgorithmParameters
- Forms.ReqIntercompanyPlanningGroupSetup
- MsDynAx060.Forms.ReqDemPlanForecastParameters
- MsDynAx060.Forms.ReqIntercompanyPlanningGroupSetup
- demand planning
- demand forecasting, demand forecast, demand forecasts, sales forecast, sales forecasts, forecasting setup, baseline forecast, historical forecast, adjusted forecast, forecast dimension, forecast dimensions, item allocation key, item allocation keys, inter
---

# Set up demand forecasting [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes the setup tasks that you must perform before you can use demand forecasting. These tasks include setting up the following data and parameters:

  - Select the items to include in the demand forecast.

  - Assign items to the demand forecast of a specific company.

  - Define the level of detail to use in the demand forecast.

  - Set up the parameters to use in demand forecasting.

  - Optional: Modify the default parameters of the forecast algorithm.

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
<td><p>Data</p></td>
<td><p>Intercompany planning groups are configured.</p></td>
</tr>
</tbody>
</table>


## Select the items to include in the demand forecast

Demand forecasting uses the item allocation key to calculate forecast at the aggregated item level. Item allocation keys make it easier to manage multiple items, and manage the grouping of items that share the same forecast setup. To include an item in a demand forecast, you must assign it to an item allocation key. For example, an item allocation key is created for TVs, and the different model numbers and sizes that are sold and forecasted are assigned to this item allocation key.

To assign an item to an item allocation key, follow these steps:

1.  Click **Inventory management** \> **Setup** \> **Forecast** \> **Item allocation keys**.

2.  Create or select an item allocation key. For more information, see [Item allocation keys (form)](https://technet.microsoft.com/en-us/library/aa590322\(v=ax.60\)).

3.  Click **Assign items**.

4.  In the **Available items** list, select the item that you want to assign, and then use the arrow buttons to move the item to **Assigned items**. An item can be assigned to only one item allocation key. When an item has been assigned, it is no longer available.

5.  Repeat these steps for all items that you want to include in the demand forecast.


> [!NOTE]
> <P>During demand forecasting, the item allocation percentages that assign a part of an aggregate forecast to individual items are not used. Item allocation percentages do not affect the demand forecast.</P>



## Assign items to the demand forecast of a specific company

Demand forecast is calculated for all companies that are part of an intercompany planning group. Demand forecast is calculated, by default, for all items that are assigned to all item allocation keys and for all companies. Therefore, to specify which item allocation keys to forecast per company, you must assign the item allocation keys to the company. You do this in the setup of the intercompany planning group that the company is a member of.

To assign an item allocation key to a member of an intercompany planning group, follow these steps:

1.  Click **Master planning** \> **Setup** \> **Intercompany planning groups**.

2.  Select the intercompany planning group and the intercompany planning group member to which you want to assign item allocation keys.

3.  Click **Item allocation keys**.

4.  In the **Unassigned item allocation keys** list, select the key that you want assign, and then use the arrow buttons to move the key to **Assigned item allocation keys**.

5.  Repeat these steps for all intercompany planning groups for which you want to assign item allocation keys.

## Define the level of detail to use in the demand forecast

Use forecast dimensions to specify the level of detail for which a baseline forecast is generated. The forecast dimensions for item allocation key, company, and site are always used by default. In addition, you can assign forecast dimensions, such as warehouse or customer account, to create a greater level of detail in the demand forecast. Defining forecast dimensions is part of the initial setup for demand forecasting. However, you can modify the forecast dimensions at any time and then regenerate a baseline forecast to apply them.

To assign forecast dimensions, follow these steps:

1.  Click **Master planning** \> **Setup** \> **Demand forecasting** \> **Demand forecasting parameters**.

2.  Click **Forecast dimensions**.

3.  In the **Available forecast dimensions** list, select the dimension that you want to assign, and then use the arrow buttons to move the dimension to **Assigned forecast dimensions**.

## Set up the parameters to use in demand forecasting

Select the parameters to apply when baseline forecasts are generated. The parameter setup is global and applies for all companies that are members of the specified intercompany planning group.

1.  Click **Master planning** \> **Setup** \> **Demand forecasting** \> **Demand forecasting parameters**.

2.  In the **Demand forecast unit** field, select the unit to use for forecast quantities. This field is required because demand forecasts are generated based on quantities of items. Also, make sure that there is a conversion rule defined for the forecast unit and the item unit. For more information, see [Unit conversions (form)](https://technet.microsoft.com/en-us/library/hh209285\(v=ax.60\)).

3.  In the **Excel demand forecast file path** field, enter the file path location that is used to save the Excel demand forecast file.

4.  In the **Include these historical transaction types to generate the statistical baseline forecast** field group, select the types of historical transactions to include when the baseline forecast is calculated. For example, select the **Production line** check box to calculate the dependent demand for BOM line requirements. The items on lower BOM levels must be assigned to an item allocation key to be included in the forecast generation.
    
    If you do not select any transaction types, there is no history with which to calculate the demand forecast.

5.  On the **Forecast algorithm parameters** FastTab, in the **Forecast generation strategy** field, select one of the following options. This field is required.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Option</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>SSAS time series forecasting methods</strong></p></td>
    <td><p>Use the Microsoft SQL Server Analysis Services Time Series algorithm to calculate a statistical baseline forecast. For more information about Microsoft SQL Server Analysis Services, see <a href="http://msdn.microsoft.com/en-us/library/bb677216.aspx">Microsoft Time Series Technical Reference</a>. For more information about using cubes in Microsoft Dynamics AX, see <a href="analytics-in-microsoft-dynamics-ax.md">Analytics in Microsoft Dynamics AX</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Copy over historical demand</strong></p></td>
    <td><p>Use historical demand data to calculate a baseline forecast. This option does not use the Microsoft SQL Server Analysis Services Time Series algorithm.</p></td>
    </tr>
    </tbody>
    </table>


6.  If you select the **SSAS time series forecasting methods** option in the **Forecast generation strategy** field, you must select the Microsoft SQL Server Analysis Services cubes in the **Demand forecast cube** and **Demand forecast accuracy cube** fields. These cubes are used to analyze the historical demand transaction data and generate the statistical baseline forecast.

7.  Select the **Do not allow gaps in historical data** check box to fill any gaps in the historical data with 0 (zero) before the data is passed to the SQL Server Analysis Services. Gaps are forecast buckets that do not contain historical data. For example, a month during which there are no sales for a specific product. For better system performance, clear this check box.

8.  On the **Item allocation keys** tab, you can define demand forecasting parameters that are specific to a particular item allocation key. For example, for an item allocation key that is created for TVs, you can forecast only sales demand.

## Optional: Modify the default parameters of the forecast algorithm

In the **Demand forecasting parameters** form, if you select the **SSAS time series forecasting methods** option in the **Forecast generation strategy** field, statistical baseline forecasts are calculated by using the forecast algorithm parameters that are available as standard functionality in Microsoft SQL Server Analysis Services. However, you can modify the default parameter setup to align it with business realities and company objectives. For example, you can add or remove parameters that are used in the forecast algorithm, and you can modify the default values of the parameters.


> [!WARNING]
> <P>This task is appropriate for users who have knowledge about statistical forecasting and SQL Server Analysis Services time series algorithms.</P>



To configure the default parameters for the forecast algorithm, follow these steps:

1.  Click **Master planning** \> **Setup** \> **Demand forecasting** \> **Forecasting algorithm parameters**.

2.  Use the **Add** and **Remove** buttons to add and remove parameters.

3.  In the **Value** field, enter a new value for a parameter.

4.  If you want to return to the default settings, use the **Restore** button.


> [!NOTE]
> <P>You can override the settings in the following locations:</P>
> <UL>
> <LI>
> <P><STRONG>Demand forecasting parameters</STRONG> form &gt; <STRONG>Forecast algorithm parameters</STRONG> FastTab.</P>
> <LI>
> <P><STRONG>Demand forecasting parameters</STRONG> form &gt; <STRONG>Item allocation keys</STRONG> &gt; <STRONG>Forecast algorithm parameters</STRONG> FastTab.</P></LI></UL>



## Next step

After you set up demand forecasting, you can create a baseline forecast. For more information, see [Create a baseline forecast](create-a-baseline-forecast.md).

## Related tasks

[Create a baseline forecast](create-a-baseline-forecast.md)

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
<td><ul>
<li><p>System administrator – set up the Microsoft SQL Server Analysis Services cubes</p></li>
<li><p>Production planner – set up demand forecasting</p></li>
</ul></td>
</tr>
</tbody>
</table>


## See also

[Business process: demand forecasting](business-process-demand-forecasting.md)

[Item allocation keys (form)](https://technet.microsoft.com/en-us/library/aa590322\(v=ax.60\))

[Unit conversions (form)](https://technet.microsoft.com/en-us/library/hh209285\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

