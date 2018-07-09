---
title: "What's new: Master planning features"
TOCTitle: Master planning features
ms:assetid: b024fa61-fc2c-4a44-ad0b-abc93f1e2f4d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527210(v=AX.60)
ms:contentKeyID: 59623339
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# What's new: Master planning features [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

We have changed and added functionality in the [Master planning](master-planning.md) area for Microsoft Dynamics AX 2012. For more information, see the tables that apply to your version of the product.

## What’s new in AX 2012

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Forecast items on any level in the product structure.</p></td>
<td><p>You can now forecast items at both the final product level and the subassembly level. Therefore, subassemblies can be produced based on forecasts, and the final product assembly can be produced based on customer orders. Forecast reduction also occurs at the appropriate level in the product.</p>
<p>For more information, see <a href="set-up-a-forecast-model.md">Set up a forecast model</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R3

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Demand forecasting</p></td>
<td><p>Demand forecasting is a set of tools that enable you to estimate future demand and create demand forecasts based on historical transaction data. The demand forecasting process includes the following tasks:</p>
<ul>
<li><p>Complete the prerequisite setup tasks before you can use demand forecasting. For more information, see <a href="set-up-demand-forecasting.md">Set up demand forecasting</a>.</p></li>
<li><p>Create a baseline forecast from historical demand data that is gathered and loaded in a Microsoft SQL Server Analysis Services cube. For more information, see <a href="create-a-baseline-forecast.md">Create a baseline forecast</a>.</p></li>
<li><p>Open the demand forecast file, and use the PivotTable tools in Excel to filter and display the forecast data that is stored in the cube. For more information, see <a href="view-a-demand-forecast-in-excel.md">View a demand forecast in Excel</a>.</p></li>
<li><p>Optional: Make manual adjustments to the forecasted quantities in the demand forecast file. For more information, see <a href="adjust-a-demand-forecast-in-excel.md">Adjust a demand forecast in Excel</a>.</p></li>
<li><p>Import a demand forecast to Microsoft Dynamics AX so specific companies and forecast models can use the forecast data as input to master planning. For more information, see <a href="import-a-demand-forecast-to-microsoft-dynamics-ax.md">Import a demand forecast to Microsoft Dynamics AX</a>.</p></li>
<li><p>Optional: Calculate the accuracy of past demand forecasts against past actual demand to improve forecast accuracy. For more information, see <a href="calculate-past-forecast-accuracy.md">Calculate past forecast accuracy</a>.</p></li>
<li><p>Optional: Remove outliers from the historical data to improve demand forecast accuracy. For more information, see <a href="remove-outliers-from-historical-transaction-data-when-calculating-a-demand-forecast.md">Remove outliers from historical transaction data when calculating a demand forecast</a>.</p></li>
</ul>
<p>The AX 2012 R3 demand forecasting features are fully integrated with Microsoft Dynamics AX and the existing forecast functionality. These features include:</p>
<ul>
<li><p>Item allocation keys. For more information, see <a href="https://technet.microsoft.com/en-us/library/aa590322(v=ax.60)">Item allocation keys (form)</a>.</p></li>
<li><p>Intercompany planning groups. For more information, see <a href="about-intercompany-master-scheduling.md">About intercompany master scheduling</a>.</p></li>
<li><p>Master planning. For more information, see <a href="master-planning.md">Master planning</a>.</p></li>
<li><p>Forecast models. For more information, see <a href="https://technet.microsoft.com/en-us/library/aa620573(v=ax.60)">Forecast models (form)</a>.</p></li>
<li><p>Demand forecasts. For more information, see <a href="https://technet.microsoft.com/en-us/library/aa499758(v=ax.60)">Demand forecast (form)</a>.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Forecast reduction for a customer or customer group</p></td>
<td><p>You can specify whether a customer forecast is included in the overall forecast. This setting determines how actual demand reduces the forecasted demand. You can use this setting to ensure that master planning covers the supply of items that are purchased by specific customers.</p>
<ul>
<li><p>If a customer forecast is included in the overall forecast, actual customer demand reduces both the customer forecast and the overall forecast. Master planning generates planned orders to cover only the overall forecast quantity.</p></li>
<li><p>If a customer forecast is not included in the overall forecast, actual customer demand reduces only the customer forecast. Master planning generates planned orders to cover both the overall forecast quantity and the forecast for each customer quantity.</p></li>
</ul>
<p>The <strong>Include customer forecast in the demand forecast</strong> check box is located in the <strong>Coverage groups</strong> form.</p></td>
</tr>
<tr class="odd">
<td><p>Start time for production scheduling</p></td>
<td><p>You can select the start time to schedule production orders. The start time can be the start of the calendar work day or the current time. The current time option is used with the delivery date control and capable to promise (CTP) feature.</p>
<p>The <strong>Scheduling start time</strong> field is located in the <strong>Master planning parameters</strong> form.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

