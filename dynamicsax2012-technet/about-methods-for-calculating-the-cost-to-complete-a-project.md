---
title: About methods for calculating the cost to complete a project
TOCTitle: About methods for calculating the cost to complete a project
ms:assetid: e58923cd-4fc6-44c3-8600-4b66361709f2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa573175(v=AX.60)
ms:contentKeyID: 37822165
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- cost to complete
- estimate
- forecasting
audience: Application User
ms.search.region: Global
---

# About methods for calculating the cost to complete a project 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you create an estimate, you can define how the cost to complete the project is calculated. The method that you choose is applied individually to each cost line in the cost estimate. In the **Cost estimate** form, you can change the method that is applied to a line while it has a status of **Created**.

## The cost to complete methods

You can choose from six methods to calculate the cost to complete a project. You select a method in the **Cost to complete method** field in the **Create estimate** form.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Cost to complete method</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Total cost - actual</strong></p></td>
<td><p>When you choose the <strong>Total cost - actual</strong> method, estimated costs must be entered manually. After the <strong>Total cost</strong> or <strong>Total quantity</strong> column in the <strong>Cost estimate</strong> form is completed, the actual costs are subtracted from the user-entered totals to arrive at the cost to complete the project.</p>
<p>Typically, tracking the progress of costs is not based, for example, on how many hotel stays and meals are recorded in each period. Instead, it is usually based on a comparison against the total amount of estimated hours.</p>
<p>This approach does not require a forecast model, and the total cost or total quantity can be manually edited. When a value is typed in one of the totals columns, the system compares this value against the actual transactions posted in that period, and decreases the value in the <strong>Quantity to complete</strong> or <strong>Cost to complete</strong> column.</p></td>
</tr>
<tr class="even">
<td><p><strong>Total budget - actual</strong></p></td>
<td><p>When you choose the <strong>Total budget - actual</strong> model, actual costs are compared against the forecast model that you select to determine the cost. This method uses a total budget model with forecasted transactions.</p>
<p>If necessary, you can adjust the budget model when the project is in progress to get a more accurate view of the project. If you adjust the forecast, follow this general process:</p>
<ol>
<li><p>Copy forecast transactions into another forecast model.</p></li>
<li><p>Compare forecast transactions with actual transactions.</p></li>
<li><p>Maintain, decrease, or increase the estimates for the next period.</p></li>
</ol>
<p>The system does not automatically decrease the forecasted estimates. Therefore, we recommend that you maintain an original forecast model on the Fixed-price project to establish a baseline to compare with when the project is completed.</p>
<div class="alert">

> [!NOTE]
> <P>Use at least two forecast models when you apply this approach. One model should contain the original forecast. For the other, you should copy forecast transactions from another model. In the <STRONG>Create estimate</STRONG> form, select a model in the <STRONG>Copy from model</STRONG> field. This method is valid for Fixed-price and Investment projects only.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Remaining budget</strong></p></td>
<td><p>The <strong>Remaining budget</strong> method uses a remaining budget model to arrive at the cost to complete the project.</p>
<p>When you use this method, the actual costs and the forecasted amounts in the remaining budget model are added together to get a total cost. Before you use this method, a remaining budget model must be set up to deduct transactions based on actual transactions that are recorded in the system. To do this, make sure that the check boxes are selected in the <strong>Automatic forecast reduction</strong> group in the <strong>Forecast models</strong> form. (Click <strong>Project management and accounting</strong> &gt; <strong>Setup</strong> &gt; <strong>Forecasts</strong> &gt; <strong>Forecast models</strong>.)</p>
<p>Typically, a remaining budget is copied from an original budget. As transactions are entered, the transactions on the remaining budget are decreased. As the project progresses, if you determine that the remaining budget must be adjusted, you can charge forecast transactions to the remaining budget.</p>
<div class="alert">

> [!NOTE]
> <P>The <STRONG>Remaining budget</STRONG> method can be applied only if a forecast model is attached to the estimate.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>As previous estimate</strong></p></td>
<td><p>When you use this method, you apply the same estimate method that was used in the previous period.</p>
<p>This method requires a forecast model if the previous period required a forecast model.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Set cost to complete to zero</strong></p></td>
<td><p>This method is typically used before the estimate project is eliminated. It matches the total estimates with the actual transactions that were posted and clears the <strong>Cost to complete</strong> column. The resulting percentage of completion is always 100 percent. The <strong>Forecasting</strong> check box is cleared for each cost line that you create, and the total estimate is copied from the previous cost estimate. The actual consumption for the estimate period is deducted from the cost to complete the project.</p>
<p>This method does not require a forecast model.</p></td>
</tr>
<tr class="even">
<td><p><strong>From cost template</strong></p></td>
<td><p>This method uses the cost to complete method that is set up in the cost template that is associated with the selected estimate project.</p></td>
</tr>
</tbody>
</table>


## See also

[Examples: Cost to complete methods](examples-cost-to-complete-methods.md)

  


