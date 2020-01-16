---
title: Adjust a demand forecast in Excel
TOCTitle: Adjust a demand forecast in Excel
ms:assetid: ab708055-6c4a-405f-9a1e-a8671ff49240
ms:mtpsurl: https://technet.microsoft.com/library/Dn497814(v=AX.60)
ms:contentKeyID: 62200136
author: Khairunj
ms.date: 04/25/2014
mtps_version: v=AX.60
f1_keywords:
- ReqDemPlanCreateForecastDialog
- demand forecasting, demand forecast, demand forecasts, sales forecast, sales forecasts, forecasting setup, baseline forecast, historical forecast, adjusted forecast
- demand planning
audience: Application User
ms.search.region: Global
---

# Adjust a demand forecast in Excel 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to adjust forecast quantities. After you have created a baseline forecast, you can adjust the forecasted quantities in response to business realities or plans. You can also use the demand forecast as it is, without adjusting the forecasted quantities.

You adjust forecast quantities manually by modifying the values in an Excel file, and then publishing the changes to the cube. There are two ways to adjust forecast quantities:

  - Make adjustments to specific forecast quantities. For example, if the forecast bucket is a month, increase the forecasted quantities for the months of June, July, and August.
    
    In addition to making adjustments at the item level, you can also make adjustments at an aggregated level. A weighted allocation is then used to distribute the change proportionally to the item level. For example, if you increase the forecasted quantity of an item allocation key by 600, and there are 3 items assigned to the item allocation key, an additional quantity of 200 is then proportionally distributed to each item. Each item quantity is increased so that it still represents the same percentage of the new aggregated value.

  - Make percentage adjustments to an overall forecast. For example, to implement a business growth plan, increase the value of the demand forecast by 10 percent. This increase is then applied to all of the forecasted quantities in the demand forecast.

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


## Make adjustments to specific forecast quantities

To make adjustments to specific forecast quantities, follow these steps:

1.  Open the Excel demand forecast file. You can do this in the following ways:
    
      - After you generate a baseline forecast, and the Infolog informs you that the baseline forecast has been created, double-click the Infolog or click **Open Excel file**.
    
      - After a baseline forecast has been created, browse to the location that you specified in the **Excel demand forecast file path** field. This field is located in the **Demand forecasting parameters** form and the **Create statistical baseline forecast** form.

2.  In the Excel file, click **Enable Content**. This enables the content in the **PivotTable** report, so that you can modify it. You only need to do this step the first time that you open the Excel file.

3.  If the **PivotTable** report is read-only, open **PivotTable Tools**, click the **Options** tab, and in the **Tools** field group, select **What-If Analysis** \> **Enable What-If Analysis**.

4.  In the **Forecast table** sheet, in the **PivotTable Field List**, filter for **Demand forecast**, and then select **Forecasted quantity**. These settings let you modify the values in the demand forecast.

5.  In the **PivotTable** report, in the **Comments** column, enter a comment for future reference. For example, enter a comment that states you have adjusted the forecasted quantities for the months of June, July, and August.

6.  In the **PivotTable** report, select one or multiple cells, and then modify the values. For example, for the months of June, July, and August, increase the quantities by 100.
    

    > [!TIP]
    > <P>When you modify values in the <STRONG>PivotTable</STRONG> report, a small red triangle appears in the lower-right corner of the cell. This indicates that these values have been modified but not yet published to the cube.</P>



7.  In the **PivotTable Field List**, select **Adjusted quantity** to display the **Adjusted quantity** column in the demand forecast. The adjusted quantity contains the difference between the original forecasted quantity and the modified quantity. The difference can be expressed by using both positive and negative values. For example, if you decrease the forecast quantity for the months of June, July, and August by 50, the adjusted quantity for these months is -50.

8.  After you finish adjusting the forecast quantities, you must publish the changes to the cube to save them. Select any cell in the **PivotTable** report. Go to **Pivot Table Tools**. On the **Options** tab, click **What-If-Analysis**, and then click **Publish Changes**.

9.  Save and close the Excel demand forecast file.


> [!IMPORTANT]
> <P>If you want to apply the manual adjustments to subsequent iterations of the demand forecast, you must select the <STRONG>Save the manual adjustments made to the baseline demand forecast</STRONG> check box in the <STRONG>Import adjusted demand forecast</STRONG> form when you import the demand forecast to Microsoft Dynamics AX 2012 R3. For more information, see <A href="import-a-demand-forecast-to-microsoft-dynamics-ax.md">Import a demand forecast to Microsoft Dynamics AX</A>.</P>
> <P>If you want to apply the manual adjustments to the next baseline forecast that you create, you must select the <STRONG>Transfer manual adjustments to the demand forecast</STRONG> check box. This check box is in the <STRONG>Create statistical baseline forecast</STRONG> form in the <STRONG>Manual adjustments</STRONG> field group. For more information, see <A href="create-a-baseline-forecast.md">Create a baseline forecast</A>.</P>



## Make percentage adjustments to an overall forecast

To make percentage adjustments to an overall forecast, follow these steps:

1.  Open the Excel demand forecast file. You can do this in the following ways:
    
      - After you generate a baseline forecast, and the Infolog informs you that the baseline forecast has been created, double-click the Infolog or click **Open Excel file**.
    
      - After a baseline forecast has been created, browse the location that you specified in the **Excel demand forecast file path** field. This field is located in the **Demand forecasting parameters** form and the **Create statistical baseline forecast** form.

2.  In the Excel file, click **Enable Content**. This enables the content in the **PivotTable** report, so that you can modify it. You only need to do this step the first time that you open the Excel file.

3.  If the **PivotTable** report is read-only, open **PivotTable Tools**, click the **Options** tab, and in the **Tools** field group, select **What-If Analysis** \> **Enable What-If Analysis**.

4.  In the **Forecast table** sheet, in the **PivotTable Field List**, filter for **Demand forecast**, and then select **Forecasted quantity**. These settings let you modify the values in the demand forecast.

5.  In the **PivotTable** report, in the **Comments** column, enter a comment for future reference. For example, enter a comment that states you have adjusted the forecasted quantities for the months of June, July, and August.

6.  In the **PivotTable** report, select the cell for the **Grand Total** row and the **Grand Total** column, and then modify the value. For example, to increase an overall forecast by 10 percent, increase the value in the **Grand Total** cell by 10 percent. If the original value is 600, increase it to 660.
    

    > [!TIP]
    > <P>When you modify values in the <STRONG>PivotTable</STRONG> report, a small red triangle appears in the lower-right corner of the cell. This indicates that these values have been modified but not yet published to the cube.</P>



7.  In the **PivotTable Field List**, select **Adjusted quantity** to display the **Adjusted quantity** column in the demand forecast. The adjusted quantity value contains the difference between the baseline forecast quantity and the modified quantity. The difference can be expressed by using both positive and negative values.

8.  After you finish adjusting the forecast quantities, you must publish the changes to the cube to save them. Select any cell in the **PivotTable** report. Go to **Pivot Table Tools**. On the **Options** tab, click **What-If-Analysis**, and then click **Publish Changes**.

9.  Save and close the Excel demand forecast file.


> [!IMPORTANT]
> <P>If you want to apply the manual adjustments to subsequent iterations of the demand forecast, you must select the <STRONG>Save the manual adjustments made to the baseline demand forecast</STRONG> check box in the <STRONG>Import adjusted demand forecast</STRONG> form when you import the demand forecast to Microsoft Dynamics AX 2012 R3. For more information, see <A href="import-a-demand-forecast-to-microsoft-dynamics-ax.md">Import a demand forecast to Microsoft Dynamics AX</A>.</P>
> <P>If you want to apply the manual adjustments to the next baseline forecast that you create, you must select the <STRONG>Transfer manual adjustments to the demand forecast</STRONG> check box. This check box is in the <STRONG>Create statistical baseline forecast</STRONG> form, in the <STRONG>Manual adjustments</STRONG> field group. For more information, see <A href="create-a-baseline-forecast.md">Create a baseline forecast</A>.</P>



## Next step

After you have adjusted a demand forecast, you import it to Microsoft Dynamics AX. For more information, see [Import a demand forecast to Microsoft Dynamics AX](import-a-demand-forecast-to-microsoft-dynamics-ax.md).

## Related tasks

[Set up demand forecasting](set-up-demand-forecasting.md)

[Create a baseline forecast](create-a-baseline-forecast.md)

[View a demand forecast in Excel](view-a-demand-forecast-in-excel.md)

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

  


