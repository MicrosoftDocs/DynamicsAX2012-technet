---
title: About flexible budgets
TOCTitle: About flexible budgets
ms:assetid: 0c73296f-fe24-42ec-aa9e-efde854aa8b9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa569755(v=AX.60)
ms:contentKeyID: 36055997
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- budgets
- budget
- flexible budget
- flexible budgets
audience: Application User
ms.search.region: Global
---

# About flexible budgets 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you create a flexible budget, you must create and set up a flexible budget model in the **Budget model** form.

After you set up a flexible budget model, you create a flexible budget in the **Flexible budgeting** form.


> [!NOTE]
> <P>There can be only one flexible budget per year and per budget model.</P>



Select the following fields in the **Flexible budgeting** form:

  - **Flexible budget model** – Select the budget model created in the **Budget model** form

  - **Fiscal year** – Select the first date in the new fiscal year.


> [!NOTE]
> <P>You can select only one flexible budget per year per budget model.</P>



  - **Locked** –The current flexible budget is not considered for the calculation.

  - **Calculated** –The calculation for this flexible budget was performed.

  - **Calculation version** – You must create and set up a new calculation version specifically for the flexible budget. It is important to select the following value types:
    
      - **Basic plan costs**
    
      - **Flexible plan costs**
    
      - **Target costs**

The **Flexible budgeting** form contains the following buttons:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Button</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Plan values</strong></p></td>
<td><p>Enter the plan values.</p></td>
</tr>
<tr class="even">
<td><p><strong>Workload</strong></p></td>
<td><p>Enter the percentage of load.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Calculation</strong></p></td>
<td><p>Run the plan calculation batch job.</p></td>
</tr>
<tr class="even">
<td><p><strong>Transfer balances</strong></p></td>
<td><p>Copy the actual costs in the flexible budget.</p></td>
</tr>
</tbody>
</table>


## See also

[About setting up a budget model for flexible budgets](about-setting-up-a-budget-model-for-flexible-budgets.md)

[Transfer actual costs in a flexible budget](transfer-actual-costs-in-a-flexible-budget.md)

[About budgeting on transactions and total amounts](about-budgeting-on-transactions-and-total-amounts.md)

[Run a calculation](run-a-calculation.md)

  


