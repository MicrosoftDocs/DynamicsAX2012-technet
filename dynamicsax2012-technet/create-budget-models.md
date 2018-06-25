---
title: Create budget models
TOCTitle: Create budget models
ms:assetid: 69c5ee29-fd52-481e-8b10-7bbdb0f3045f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa571172(v=AX.60)
ms:contentKeyID: 36057973
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- budget models
- budget models that are stopped
- budget models used in cash flow forecasts
- stopped budget models
- cash flow forecast budget models
---

# Create budget models [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the **Budget model** form to create various budget models. You can use a single budget model for all or some of the budgets, or you can create a budget model for each budget.


> [!NOTE]
> <P>This topic includes information about financial budgets. For information about budgets for projects, see <A href="about-project-budgets-and-forecasts.md">About project budgets and forecasts</A>.</P>



A budget model can contain many submodels, which you attach to the budget model on the **Submodel** FastTab. For example, you could create a budget that has submodels that represent the various departments of the legal entity.


> [!NOTE]
> <P>Budget models that are used as submodels cannot contain other submodels. Also, if you use budget control, you cannot use budget models that have submodels.</P>



In the **Budget model** form, you can select the following check boxes for budgets that are based on a specific budget model:

  - To indicate that the budget model and the budgets that are based on the model cannot be changed, select the **Stopped** check box.

  - To indicate that budgets that are created from the budget model are included in cash flow forecasting, select the **Cash flow forecasts** check box.

<!-- end list -->

1.  Click **Budgeting** \> **Setup** \> **Basic budgeting** \> **Budget models**.

2.  Click **New** to create a budget model.

3.  Enter an identifier and a name for the budget model.

4.  Enter other details about the model as needed, and add any submodels. For more information, see [Budget model (form)](https://technet.microsoft.com/en-us/library/aa586905\(v=ax.60\)).

## See also

[About basic budgeting and budget control setup](about-basic-budgeting-and-budget-control-setup.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

