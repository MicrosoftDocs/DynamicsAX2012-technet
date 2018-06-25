---
title: About project forecasts
TOCTitle: About project forecasts
ms:assetid: 1bb1eb17-2e0f-40a6-a6ce-d07eb84751d1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208457(v=AX.60)
ms:contentKeyID: 36056130
ms.date: 10/06/2014
mtps_version: v=AX.60
f1_keywords:
- project forecasts
---

# About project forecasts [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX provides two methods for projecting and controlling project costs and revenues: project forecasting and project budgeting.

When you use project forecasting, you can enter forecast transactions in forecast forms for each transaction type. Every attribute that is available for an actual transaction can be used for a forecast transaction; for example, line profitability, line attributes, workers, or descriptions. You can also project how long after you incur a cost that you will invoice a customer.

Project forecasting transactions are based on units and amounts.

Each project forecast must be associated with a forecast model. A forecast model, which is created in the **Forecast models** form, acts as a container for the forecast transactions. Forecast models can be designated as submodels for a model, which allows you to forecast by regions, time periods, or departments.

You can copy the forecast transactions in a model to create a new model, and also transfer the transactions to the general ledger. Because there is a one-to-one relationship between a forecast and a model, each forecast model makes up a separate budget for a project.

Forecast models can use forecast reduction as the control mechanism for projects. With forecast reduction, actual transactions reduce forecast transaction balances. However, because forecast reduction is applied to the highest project in the hierarchy, it provides a limited view of changes in the forecast. For example, if a worker is associated with a subproject, the actual transactions for the worker are posted to the parent project. Therefore, it may be difficult to determine which transaction in which subproject caused a reduction to the forecast amount. Because of this, it can be difficult to track the changes. We recommend that you create a copy of a forecast model specifically for use by forecast reduction so that you can use reports to view what was originally forecasted.

To use forecast reduction, forecast models must first be enabled in the **Forecast models** form.


> [!NOTE]
> <P>For each forecast transaction that is entered, a forecast model is automatically suggested. The default forecast model is set up in the <STRONG>Forecast</STRONG> area in the <STRONG>Project management and accounting parameters</STRONG> form.</P>



## Maintaining project forecasts

Project forecasts can be revised, copied, deleted, or transferred to a general ledger budget.

  - **Revise** – You can make revisions to a forecast transaction in the same forms where the original entries were made.
    

    > [!NOTE]
    > <P>There is no process control. Any worker with permission for a forecast form can make revisions without review.</P>



  - **Copy** or **delete** – When you copy forecast transactions, you copy the transaction lines of one forecast model to another forecast model. When you delete a forecast, you delete the forecast transactions from a forecast model. For more information, see [Copy forecast model transactions](copy-forecast-model-transactions.md) or [Delete forecast model transactions](delete-forecast-model-transactions.md).
    
    To limit the forecast transactions that you want to be copied or deleted, select specific transaction types and dates. This allows you to copy or delete specific parts of a forecast.

  - **Transfer** – When you transfer a project forecast to a general ledger budget, you transfer the forecast transactions of a forecast model to a general ledger budget. You can overwrite any previously transferred transactions in the general ledger budget to which you transfer your project forecast. For more information, see [Copy a forecast to a ledger](copy-a-forecast-to-a-ledger.md).

## See also

[About project budgets and forecasts](about-project-budgets-and-forecasts.md)

[Create forecast models for project budgets](create-forecast-models-for-project-budgets.md)

[Enter forecast transactions](enter-forecast-transactions.md)

[Transfer work breakdown estimates to project forecasts](transfer-work-breakdown-estimates-to-project-forecasts.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

