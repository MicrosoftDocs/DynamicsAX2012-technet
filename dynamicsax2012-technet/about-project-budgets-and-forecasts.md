---
title: About project budgets and forecasts
TOCTitle: About project budgets and forecasts
ms:assetid: dae2dcbe-edd8-495f-a710-078cc6d2f115
ms:mtpsurl: https://technet.microsoft.com/library/Hh227405(v=AX.60)
ms:contentKeyID: 36059663
author: tfehr
ms.author: daxcpft
ms.date: 10/06/2014
mtps_version: v=AX.60
f1_keywords:
- project
- budget
- project budget
- budget control
- forecast reduction
audience: Application User
ms.search.region: Global
---

# About project budgets and forecasts 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX provides two ways to manage and control your projects: project forecasts and project budgets.

You can use forecasting if your organization has an operational perspective and focuses on revenues and costs derived from specific transactions. You can use budgeting if your organization focuses more on the financial amounts.

Both methods have their advantages. We recommend that your organization consider the following points before selecting a method.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p></p></th>
<th><p>Forecasting</p></th>
<th><p>Budgeting</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Period allocation</p></td>
<td><p>Forecasting allows for no explicit period allocation. Therefore, the forecast, and the control of the forecast, is based on the life of the project. Forecasts are based on a specific date. Therefore, you must infer the period from the date.</p></td>
<td><p>In project budgeting, you can allocate transactions over the total project or a fiscal period. If you allocate over a period, you can choose to carry forward unused amounts to the next fiscal period.</p></td>
</tr>
<tr class="even">
<td><p>Viewing transactions</p></td>
<td><p>Forecast transactions can be viewed in the forecast forms, where you see the forecasts for the whole company for all projects, regardless of the hierarchy. To focus on a particular project, you must filter the data.</p></td>
<td><p>In project budgeting, you can view budgeted transactions for a single project hierarchy in the <strong>Project budget balances</strong> form. This means that you can view transaction details for a parent project or its subprojects.</p></td>
</tr>
<tr class="odd">
<td><p>Transaction variables</p></td>
<td><p>Forecast transactions can be entered using every attribute that exists for an actual transaction. This allows for greater detail in the forecast. For example, you can enter details for quantities, workers, items, or line properties.</p></td>
<td><p>Budget details can only be entered using amounts, categories, and activities.</p></td>
</tr>
<tr class="even">
<td><p>Security</p></td>
<td><p>Forecasting is based on entering transactions in the forecast forms, and involves no process-control mechanism. Any worker with permissions for a forecast form can revise information without approval.</p></td>
<td><p>Project budgeting uses workflow, which enables change management and makes it possible to keep a history of the revisions.</p></td>
</tr>
<tr class="odd">
<td><p>Entry types</p></td>
<td><p>Forecast transaction entries are based on number of units and cost and sales unit prices.</p></td>
<td><p>Budget details are based on amounts and split between costs and revenues.</p></td>
</tr>
<tr class="even">
<td><p>Forms</p></td>
<td><p>Forecast transactions are entered in the five forecast forms:</p>
<ul>
<li><p><strong>Hour forecasts</strong></p></li>
<li><p><strong>Expense forecasts</strong></p></li>
<li><p><strong>Item forecasts</strong></p></li>
<li><p><strong>Fee forecasts</strong></p></li>
<li><p><strong>On-account forecasts</strong></p></li>
</ul></td>
<td><p>All budget details are entered in the <strong>Project budget</strong> form.</p></td>
</tr>
<tr class="odd">
<td><p>Forecast models</p></td>
<td><p>Because each forecast must be associated with a model, you can create multiple forecast models and you can set up submodels.</p></td>
<td><p>Project budgeting limits the forecast models that are used for budgeting. Fewer forecast models can help increase consistency in projections.</p></td>
</tr>
<tr class="even">
<td><p>Cost overruns</p></td>
<td><p>When you use forecasts, you can only allow or disallow entry of transactions that would cause a cost overrun.</p></td>
<td><p>Project budgeting provides additional control options for users. Warnings and overruns may be allowed.</p></td>
</tr>
<tr class="odd">
<td><p>Control</p></td>
<td><p>Forecast control is performed by using forecast reduction. Actual amounts are subtracted from forecast transaction balances without any audit trail. This can make it more difficult to trace where the actual transactions occurred.</p></td>
<td><p>In project budget control, actual amounts are subtracted from amounts in the remaining budget. This allows for a clearer audit trail.</p></td>
</tr>
</tbody>
</table>


## Forecast models

Both project forecasts and project budgets use forecast models to contain the projected transaction amounts. The forecast models are created in the **Forecast models** form.

Forecast models have a single-layer hierarchy, which means that one project forecast must be associated with one forecast model. If you use project forecasting, you can identify models as submodels, which lets you create forecasts by department, time period, or region. For example, a forecast model could be created for a year, and then submodels could be created for the Northeast, Southeast, Northwest, and Southwest region forecasts that are submitted by regional heads. By choosing different options in Microsoft Dynamics AX reports, you can view information by total forecast or by submodel.

Project budgets must be associated with an original budget forecast model and a remaining budget forecast model. Project budgets can also be associated with a carry-forward budget model if you have projects that extend over one year and carry forward remaining budget amounts at year-end to the following year. When the original budget for a project is approved, forecast transactions are created automatically, based on the associated original budget model and remaining budget model.

## See also

[About setting up a project budget](about-setting-up-a-project-budget.md)

[Configure project budget control](configure-project-budget-control.md)

[Create and submit an original project budget](create-and-submit-an-original-project-budget.md)

[Create forecast models for project budgets](create-forecast-models-for-project-budgets.md)

[Forecast models (form)](https://technet.microsoft.com/library/aa620573\(v=ax.60\))

[Project budget (form)](https://technet.microsoft.com/library/hh227438\(v=ax.60\))

  


