---
title: Create forecast models for project budgets
TOCTitle: Create forecast models for project budgets
ms:assetid: 6161f498-4877-4c12-8dd6-5e132b5a3054
ms:mtpsurl: https://technet.microsoft.com/library/Hh209179(v=AX.60)
ms:contentKeyID: 36057654
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- project
- budget
- project budget
- budget control
- project budget control
- budget forecast
- budget forecast model
- budget model
- original budget
- remaining budget
audience: Application User
ms.search.region: Global
---

# Create forecast models for project budgets 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A project that is subject to budget control uses two types of budgets: the original budget and the remaining budget. When you create a project budget, you must specify the original and remaining budget forecast models that were created in the **Forecast models** form. Project budgets based on the specified models are created when you commit the project budget.


> [!NOTE]
> <P>A forecast model that is used for budget control cannot have a submodel, and it cannot be used as a submodel.</P>



1.  Click **Project management and accounting** \> **Setup** \> **Forecasts** \> **Forecast models**.

2.  In the **Forecast models** form, click **New** to create a new forecast model, and then enter a model ID number and a name for it.

3.  To prevent changes from being made to the forecast lines that the forecast model is associated with, select the **Stopped** check box.

4.  If the forecast lines that the model is associated with should generate cash flow forecasts in the general ledger, select the **Cash flow forecasts** check box.

5.  In the **Budget type** field, select one of the following options:
    
      - **Original budget** – Use this model type for the original budget amounts that are committed when the initial budget is created and approved.
    
      - **Remaining budget** – Use this model type for the remaining budget amounts during the life of the project. The balances in this forecast model are reduced by actual transactions and increased or decreased by budget revisions.
    
      - **Carry-forward** – Use this model type for carry-forward budget amounts for the project. Carry-forward is an optional process that can be run to transfer unused budget amounts from one fiscal year to another.

6.  Optional: On the **Project** FastTab, select the options that you want to use for the invoice date or for forecasting WIP.


> [!IMPORTANT]
> <P>After the record is saved, the budget type cannot be changed.</P>



## See also

[Forecast models (form)](https://technet.microsoft.com/library/aa620573\(v=ax.60\))

[Copy forecast model transactions](copy-forecast-model-transactions.md)

[Set up a forecast model](set-up-a-forecast-model.md)

[About setting up a project budget](about-setting-up-a-project-budget.md)

[Configure project budget control](configure-project-budget-control.md)

[Create and submit an original project budget](create-and-submit-an-original-project-budget.md)

  


