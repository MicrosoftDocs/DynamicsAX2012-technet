---
title: Create and reverse a preliminary budget (Public sector)
TOCTitle: Create and reverse a preliminary budget (Public sector)
ms:assetid: 0c0100f9-67c2-4f13-9b6e-7ff3c131f80e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208505(v=AX.60)
ms:contentKeyID: 36056244
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- preliminary budgets
---

# Create and reverse a preliminary budget (Public sector) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create preliminary budget register entries for a specific budget model and dimension values. After the actual budget is approved, you can create original budget register entries and reverse the preliminary budget entries. Before you create budget register entries for preliminary budget amounts, you must set up basic budgeting and configure budget control for a preliminary budget. For more information, see [Set up budgeting and budget control for a preliminary budget (Public sector)](set-up-budgeting-and-budget-control-for-a-preliminary-budget-public-sector.md).

## Create preliminary budget entries

1.  Click **Budgeting** \> **Common** \> **Budget register entries** \> **All budget register entries**.

2.  On the **Action Pane**, click **Budget register entry** to create a budget register entry.

3.  On the **Budget register entry** FastTab, select a budget model and a budget code for the preliminary budget type. Then save the entry.

4.  In the **Budget account entries** pane, click **Add line**.

5.  Enter a new date if you want to change the date from the one in the header. This date determines the fiscal period that the budget will be recorded to.

6.  Select an account structure, and then enter the financial dimension values.

7.  Enter the preliminary budget amount, budget amount type, and currency.

8.  On the **Action Pane**, click **Update budget balances**. Then click **OK**, or enter batch criteria.

9.  To view preliminary budget register entries and budget balances, select a budget account entry, and then click **Related information** \> **Budget register entries** \> **Budget balances**. The preliminary budget amounts are included in the revised budget.

10. To view additional information about preliminary budgets, select the following inquiries:
    
      - **Budget control statistics** (Click **Budgeting** \> **Inquiries** \> **Budget control statistics**.)
        
        Use this form to view the budget balances for a budget cycle and budget model. After purchase requisitions and purchase orders have been posted, you can view the budget reservations for encumbrances and pre-encumbrances.
    
      - **Ledger - actual vs. budget inquiry** (Click **Budgeting** \> **Inquiries** \> **Actual vs. budget**.)
        
        Use the form to view actual expenditures versus the sum for the budget register entries for the period. The **Preliminary budget** field contains a sum of all the preliminary budget register entries for the budget model and dimensions values.

## Create original budget entries and reverse preliminary budget entries

When you create an original budget entry and use the budget model and dimension values that contain preliminary budget amounts, the preliminary budget amounts can be reversed. For example, you could enter a preliminary budget amount of 2,500 in ledger account 50000. Later, if you enter an original budget amount of 10,000 in ledger account 50000, the preliminary budget amount of 2,500 would be reversed. The ledger account 50000 would have a budget amount of 10,000.

1.  Click **Budgeting** \> **Common** \> **Budget register entries** \> **All budget register entries**.

2.  On the **Action Pane**, click **Budget register entry** to create a budget register entry.

3.  On the **Budget register entry** FastTab, select a budget model and a budget code for the original budget type. Then save the entry.

4.  In the **Budget account entries** pane, click **Add line**.

5.  Enter a new date if you want to change the date from the one in the header. This date determines the fiscal period that the budget will be recorded to.

6.  Select an account structure and enter the financial dimension values.

7.  Enter the original budget amount, budget amount type, and currency.

8.  On the **Action Pane**, click **Update budget balances**.

9.  On the **Budget** tab on the **Process budget register entries** form, select the **Reverse preliminary budget** check box.
    
    You can reverse all preliminary budget entries or only the preliminary budget entries with the budget code that you specify.

10. To see the budget register entries for the original budget and for the reversal of the preliminary budget, select the budget account entry in the **Budget account entries** pane. Then click **Related information** \> **Budget register entries**.

11. To see the results of reversing the preliminary budget, open the preliminary budget register entry and select the budget account entry in the **Budget account entries** pane. Then click **Related information** \> **Budget register entries** \> **Reversed tracing**. For more information, see [Reversed tracing (form)](https://technet.microsoft.com/en-us/library/aa588189\(v=ax.60\)).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

