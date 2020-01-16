---
title: About project budgets
TOCTitle: About project budgets
ms:assetid: 10f628e9-910d-4758-8ceb-f150d3d1561d
ms:mtpsurl: https://technet.microsoft.com/library/Hh242139(v=AX.60)
ms:contentKeyID: 36056030
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- project budgets
audience: Application User
ms.search.region: Global
---

# About project budgets 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX supports two methods for projecting and controlling project costs and revenues: project budgeting and project forecasting. By using project budgeting, you can enter estimated revenues and costs for a project and then use it to control actual project transactions. Project budgeting is a simpler method than forecasting, although it does integrate with forecast models. It uses a single entry form for original budget details and for revisions, and it allows projections based only on amount, category, or activity.

In project budgeting, all original budgets and revisions must be sent to project workflow for approval. Workflow gives you increased control over the process and creates a change history record.

Project budgeting resembles general ledger budgeting but can be set up more quickly and easily. Many of the options in general ledger budgeting, such as number sequences or currency, do not have to be set up separately for projects.

Project budgets are automatically associated with two forecast models, one for original budget and one for remaining budget. This is so that reports that are based on forecast models can use budget data. When a project budget is committed, the system creates forecast transactions based on the associated models, which are used for reporting and control purposes.


> [!TIP]
> <P>For more information about how to create forecast models, see <A href="create-forecast-models-for-project-budgets.md">Create forecast models for project budgets</A>.</P>



Budget control is used in project budgeting to make it possible for actual and budgeted transactions to be compared. You set up and enable project budget control individually for each project. If you use the default settings, budget checking is performed when transactions are posted. If you prefer to have budget checking done before transactions are posted, you can set up budget checking for specific transaction types. When actual transactions are entered, the balance amounts in the remaining budget are reduced. This creates an audit trail for each event, which makes it easier to track revisions.

## See also

[About project budgets and forecasts](about-project-budgets-and-forecasts.md)

[Manage project forecasts](manage-project-forecasts.md)

[About setting up a project budget](about-setting-up-a-project-budget.md)

  


