---
title: 'Examples: Cost to complete methods'
TOCTitle: 'Examples: Cost to complete methods'
ms:assetid: c40745f0-3290-4efc-9f38-8e9104b3ca0e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa550721(v=AX.60)
ms:contentKeyID: 43894516
ms.date: 10/15/2014
mtps_version: v=AX.60
f1_keywords:
- cost to complete
audience: Application User
ms.search.region: Global
---

# Examples: Cost to complete methods 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX provides six cost-to-complete methods that you can select in the **Create estimate** form. The method that you select is used to distribute the values of an estimate for a project. For more information, see [Create estimate (class form)](https://technet.microsoft.com/en-us/library/aa553468\(v=ax.60\)).

The **As previous estimate** method uses the method that was selected for the previous estimate period. The **From cost template** method uses the method that was specified as the default for the cost template in the **Estimate template** form. For more information, see [Estimate template (form)](https://technet.microsoft.com/en-us/library/aa598446\(v=ax.60\)).

This topic illustrates how each of the other four cost-to-complete methods affects the estimates for a project. The first two tables provide the data assumptions for the estimate examples. The remaining tables provide examples of estimates that are posted in the month of August and consumed in September.

## Estimate assumptions

## Estimate posted in August

<table style="width:100%;">
<colgroup>
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Cost line</p></th>
<th><p>Transaction type</p></th>
<th><p>Forecasting</p></th>
<th><p>Actual</p></th>
<th><p>Cost to complete</p></th>
<th><p>Total</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Development</p></td>
<td><p>Hour</p></td>
<td><p>Yes</p></td>
<td><p>70,000</p></td>
<td><p>30,000</p></td>
<td><p>100,000</p></td>
</tr>
<tr class="even">
<td><p>Test</p></td>
<td><p>Hour</p></td>
<td><p>No</p></td>
<td><p>60,000</p></td>
<td><p>20,000</p></td>
<td><p>80,000</p></td>
</tr>
<tr class="odd">
<td><p>Subcontractor</p></td>
<td><p>Expense</p></td>
<td><p>Yes</p></td>
<td><p>25,000</p></td>
<td><p>5,000</p></td>
<td><p>30,000</p></td>
</tr>
<tr class="even">
<td><p>Travel</p></td>
<td><p>Expense</p></td>
<td><p>No</p></td>
<td><p>10,000</p></td>
<td><p>2,000</p></td>
<td><p>12,000</p></td>
</tr>
<tr class="odd">
<td><p>Hardware</p></td>
<td><p>Item</p></td>
<td><p>No</p></td>
<td><p>80,000</p></td>
<td><p>0</p></td>
<td><p>80,000</p></td>
</tr>
<tr class="even">
<td><p>Software</p></td>
<td><p>Item</p></td>
<td><p>Yes</p></td>
<td><p>35,000</p></td>
<td><p>7,000</p></td>
<td><p>42,000</p></td>
</tr>
<tr class="odd">
<td><p>Totals</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>280,000</p></td>
<td><p>64,000</p></td>
<td><p>344,000</p></td>
</tr>
</tbody>
</table>


## Consumed cost in September

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Cost line</p></th>
<th><p>Transaction type</p></th>
<th><p>Actual transactions in September</p></th>
<th><p>Forecast transactions in the forecast model</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Development</p></td>
<td><p>Hour</p></td>
<td><p>20,000</p></td>
<td><p>12,000</p></td>
</tr>
<tr class="even">
<td><p>Test</p></td>
<td><p>Hour</p></td>
<td><p>16,000</p></td>
<td><p>5,000</p></td>
</tr>
<tr class="odd">
<td><p>Subcontractor</p></td>
<td><p>Expense</p></td>
<td><p>3,000</p></td>
<td><p>3,000</p></td>
</tr>
<tr class="even">
<td><p>Travel</p></td>
<td><p>Expense</p></td>
<td><p>1,000</p></td>
<td><p>2,000</p></td>
</tr>
<tr class="odd">
<td><p>Hardware</p></td>
<td><p>Item</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
</tr>
<tr class="even">
<td><p>Software</p></td>
<td><p>Item</p></td>
<td><p>8,000</p></td>
<td><p>0</p></td>
</tr>
<tr class="odd">
<td><p>Totals</p></td>
<td><p></p></td>
<td><p>48,000</p></td>
<td><p>22,000</p></td>
</tr>
</tbody>
</table>


## Cost to complete methods

## Method: Total cost – actual

<table style="width:100%;">
<colgroup>
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Cost line</p></th>
<th><p>Transaction type</p></th>
<th><p>Forecasting</p></th>
<th><p>Actual</p></th>
<th><p>Cost to complete</p></th>
<th><p>Total</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Development</p></td>
<td><p>Hour</p></td>
<td><p>Yes</p></td>
<td><p>90,000</p></td>
<td><p>10,000</p></td>
<td><p>100,000</p></td>
</tr>
<tr class="even">
<td><p>Test</p></td>
<td><p>Hour</p></td>
<td><p>No</p></td>
<td><p>76,000</p></td>
<td><p>4,000</p></td>
<td><p>80,000</p></td>
</tr>
<tr class="odd">
<td><p>Subcontractor</p></td>
<td><p>Expense</p></td>
<td><p>Yes</p></td>
<td><p>28,000</p></td>
<td><p>2,000</p></td>
<td><p>30,000</p></td>
</tr>
<tr class="even">
<td><p>Travel</p></td>
<td><p>Expense</p></td>
<td><p>No</p></td>
<td><p>11,000</p></td>
<td><p>1,000</p></td>
<td><p>12,000</p></td>
</tr>
<tr class="odd">
<td><p>Hardware</p></td>
<td><p>Item</p></td>
<td><p>No</p></td>
<td><p>80,000</p></td>
<td><p>0</p></td>
<td><p>80,000</p></td>
</tr>
<tr class="even">
<td><p>Software</p></td>
<td><p>Item</p></td>
<td><p>Yes</p></td>
<td><p>43,000</p></td>
<td><p>-1,000</p></td>
<td><p>42,000</p></td>
</tr>
<tr class="odd">
<td><p>Totals</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>328,000</p></td>
<td><p>16,000</p></td>
<td><p>344,000</p></td>
</tr>
</tbody>
</table>


## Method: Total budget – actual

<table style="width:100%;">
<colgroup>
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Cost line</p></th>
<th><p>Transaction type</p></th>
<th><p>Forecasting</p></th>
<th><p>Actual</p></th>
<th><p>Cost to complete</p></th>
<th><p>Total</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Development</p></td>
<td><p>Hour</p></td>
<td><p>Yes</p></td>
<td><p>90,000</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Test</p></td>
<td><p>Hour</p></td>
<td><p>No</p></td>
<td><p>76,000</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Subcontractor</p></td>
<td><p>Expense</p></td>
<td><p>Yes</p></td>
<td><p>28,000</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Travel</p></td>
<td><p>Expense</p></td>
<td><p>No</p></td>
<td><p>11,000</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Hardware</p></td>
<td><p>Item</p></td>
<td><p>No</p></td>
<td><p>80,000</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Software</p></td>
<td><p>Item</p></td>
<td><p>Yes</p></td>
<td><p>43,000</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Totals</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>328,000</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


## Method: Remaining budget

<table style="width:100%;">
<colgroup>
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Cost line</p></th>
<th><p>Transaction type</p></th>
<th><p>Forecasting</p></th>
<th><p>Actual</p></th>
<th><p>Cost to complete</p></th>
<th><p>Total</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Development</p></td>
<td><p>Hour</p></td>
<td><p>Yes</p></td>
<td><p>90,000</p></td>
<td><p>12,000</p></td>
<td><p>102,000</p></td>
</tr>
<tr class="even">
<td><p>Test</p></td>
<td><p>Hour</p></td>
<td><p>No</p></td>
<td><p>76,000</p></td>
<td><p>5,000</p></td>
<td><p>81,000</p></td>
</tr>
<tr class="odd">
<td><p>Subcontractor</p></td>
<td><p>Expense</p></td>
<td><p>Yes</p></td>
<td><p>28,000</p></td>
<td><p>3,000</p></td>
<td><p>31,000</p></td>
</tr>
<tr class="even">
<td><p>Travel</p></td>
<td><p>Expense</p></td>
<td><p>No</p></td>
<td><p>11,000</p></td>
<td><p>2,000</p></td>
<td><p>13,000</p></td>
</tr>
<tr class="odd">
<td><p>Hardware</p></td>
<td><p>Item</p></td>
<td><p>No</p></td>
<td><p>80,000</p></td>
<td><p>0</p></td>
<td><p>80,000</p></td>
</tr>
<tr class="even">
<td><p>Software</p></td>
<td><p>Item</p></td>
<td><p>Yes</p></td>
<td><p>43,000</p></td>
<td><p>0</p></td>
<td><p>43,000</p></td>
</tr>
<tr class="odd">
<td><p>Totals</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>328,000</p></td>
<td><p>64,000</p></td>
<td><p>350,000</p></td>
</tr>
</tbody>
</table>


## Method: Set cost to complete to zero

<table style="width:100%;">
<colgroup>
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Cost line</p></th>
<th><p>Transaction type</p></th>
<th><p>Forecasting</p></th>
<th><p>Actual</p></th>
<th><p>Cost to complete</p></th>
<th><p>Total</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Development</p></td>
<td><p>Hour</p></td>
<td><p>Yes</p></td>
<td><p>90,000</p></td>
<td><p>0</p></td>
<td><p>90,000</p></td>
</tr>
<tr class="even">
<td><p>Test</p></td>
<td><p>Hour</p></td>
<td><p>No</p></td>
<td><p>76,000</p></td>
<td><p>0</p></td>
<td><p>76,000</p></td>
</tr>
<tr class="odd">
<td><p>Subcontractor</p></td>
<td><p>Expense</p></td>
<td><p>Yes</p></td>
<td><p>28,000</p></td>
<td><p>0</p></td>
<td><p>28,000</p></td>
</tr>
<tr class="even">
<td><p>Travel</p></td>
<td><p>Expense</p></td>
<td><p>No</p></td>
<td><p>11,000</p></td>
<td><p>0</p></td>
<td><p>11,000</p></td>
</tr>
<tr class="odd">
<td><p>Hardware</p></td>
<td><p>Item</p></td>
<td><p>No</p></td>
<td><p>80,000</p></td>
<td><p>0</p></td>
<td><p>80,000</p></td>
</tr>
<tr class="even">
<td><p>Software</p></td>
<td><p>Item</p></td>
<td><p>Yes</p></td>
<td><p>43,000</p></td>
<td><p>0</p></td>
<td><p>43,000</p></td>
</tr>
<tr class="odd">
<td><p>Totals</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>328,000</p></td>
<td><p>0</p></td>
<td><p>328,000</p></td>
</tr>
</tbody>
</table>


## See also

[About methods for calculating the cost to complete a project](about-methods-for-calculating-the-cost-to-complete-a-project.md)

[About estimates](about-estimates.md)

  


