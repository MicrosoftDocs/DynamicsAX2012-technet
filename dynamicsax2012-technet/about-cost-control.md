---
title: About cost control
TOCTitle: About cost control
ms:assetid: b7e41738-0330-4cd1-a008-335a036cba20
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg232438(v=AX.60)
ms:contentKeyID: 42117773
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- remaining budget
- variance
- cost control
- actual cost
- budgeted amounts
- committed cost
- total cost
- deviation
- monitor costs
---

# About cost control [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the **Cost control** form to help you monitor the costs that your organization incurs during a project. By comparing the original budgeted costs for the project with the current actual costs and the committed costs, you can determine whether the project is on track, over budget, or under budget.

In the **Project management and accounting parameters** form, you can configure some of the options and default values that appear in the **Cost control** form. For example, you can decide whether your cost control method is based on the total budget or remaining budget of a project. For more information about how to configure cost control parameters, see [Cost control (form)](https://technet.microsoft.com/en-us/library/hh242864\(v=ax.60\)).


> [!NOTE]
> <P>When you use the <STRONG>Cost control</STRONG> form to view the current status of projects costs, use the forecast models that were selected for the original and remaining budgets. If you select other forecast models when you calculate, the calculation results will not be accurate.</P>



## Viewing the remaining budgeted amounts

If you selected **Remaining budget** as the cost control method in the **Project management and accounting parameters** form, the **Cost control** form calculates the costs that have not been posted as actual or marked as committed. Specifically, the amounts in the columns on the **General** tab in the lower pane of the **Cost control** form are calculated in the following ways:

  - **Actual cost** – The total amount that has been spent on the project for the selected cost line. The actual cost amount is calculated in the **Ledger updates** form.

  - **Committed cost** – The additional amount of expenses that the legal entity has committed to pay. The specific committed cost amounts are calculated in the **Committed costs** form.

  - **Remaining budget** – The amount of the original budgeted amount that is still available for the selected cost line. The remaining budget amount is calculated in the **General ledger preview** form.

  - **Total cost** – The sum of the actual cost, committed cost, and remaining budget amounts.

On the **Deviation** tab in the **Cost control** form, you can view a comparison of the total expected cost with the original budget. This comparison shows any differences between these amounts so that you can see where the data does not match. The deviation amounts are calculated in the following ways:

  - **Original budget** – The amount that was originally budgeted for the selected cost line. The original budget amount is calculated in the **General ledger preview** form.

  - **Total cost** – The sum of the actual cost, committed cost, and remaining budget, as reported on the **General** tab.

  - **Deviation** – The difference between the total cost and the original budget.

  - **Variance based on quantity** – The total difference between the original forecast and the total forecast. This difference can be expressed mathematically as \[(Total forecast quantity) \* (Original average price – Total average price)\].
    

    > [!NOTE]
    > <P>The <STRONG>Variance based on quantity</STRONG> calculation applies only to project hours.</P>



  - **Variance based on price** – The total difference between the original forecast and the total forecast. This difference can be expressed mathematically as \[(Original forecast price) \* (Original forecast quantity – Total forecast quantity)\].
    

    > [!NOTE]
    > <P>The <STRONG>Variance based on price</STRONG> calculation applies only to project hours.</P>



## Viewing the total budgeted amounts

If you selected **Total budget** as the cost control method in the **Project management and accounting parameters** form, the **Cost control** form calculates the actual costs and total costs of the project to help you detect any difference between the two. Specifically, the amounts in the columns in the lower pane on the **General** tab of the **Cost control** form are arrived at in the following ways:

  - **Total budgeted cost** – The total budgeted amount for the selected cost line.

  - **Actual cost** – The total amount of costs that have been incurred on the project to date for the selected cost lines.

  - **Committed cost** – The total amount that has been committed for the selected cost line.

  - **Variance** – The difference between the sum of the actual and committed costs and the total cost. The variance shows whether additional costs must be specified for the total budget.

On the **Deviation** tab in the **Cost control** form, you can view the difference between the total budget and the original budget by referring to the following fields:

  - **Original budget** – The amount that was originally budgeted for the cost line. The original budget is calculated in the **General ledger preview** form.

  - **Total budgeted cost** – The total cost that was originally budgeted for the cost line. The total budgeted cost is calculated in the **General ledger preview** form.

  - **Deviation** – The deviation for the cost line is calculated by subtracting the total cost from the original budget.

  - **Variance based on quantity** – The total difference between the original budget and the total budget. This amount is calculated by subtracting the total budget hours from the original budget hours and then multiplying the difference by the original budgeted cost price. This difference can be expressed mathematically as \[(Original budgeted cost price) \* (Original budget hours – Total budget hours).
    

    > [!NOTE]
    > <P>The <STRONG>Variance based on quantity</STRONG> calculation applies only to project hours.</P>



  - **Variance based on price** – This amount is calculated by subtracting the total budget hours from the original budget hours and then multiplying the difference by the total number of hours consumed. This difference can be expressed mathematically as \[(Total consumed hours) \* (Original budget hours – Total budget hours)\].
    

    > [!NOTE]
    > <P>The <STRONG>Variance based on price</STRONG> calculation applies only to project hours.</P>



## See also

[Cost control (form)](https://technet.microsoft.com/en-us/library/hh242864\(v=ax.60\))

[Project management and accounting parameters (form)](https://technet.microsoft.com/en-us/library/aa599440\(v=ax.60\))

[Committed costs (form)](https://technet.microsoft.com/en-us/library/hh209516\(v=ax.60\))

[Ledger updates (form)](https://technet.microsoft.com/en-us/library/aa590206\(v=ax.60\))

[General ledger preview (form)](https://technet.microsoft.com/en-us/library/aa587482\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

