---
title: Create budget register entries
TOCTitle: Create budget register entries
ms:assetid: fc62428e-16ec-41fb-9126-59a6ea19b485
ms:mtpsurl: https://technet.microsoft.com/library/Hh227576(v=AX.60)
ms:contentKeyID: 36060092
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- budget transfers
- budget allocations
- allocate budget
- budget register entry
- posting definitions and budget register entries
- recurring budget amounts
- budget account entry
- transfer budget
audience: Application User
ms.search.region: Global
---

# Create budget register entries 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you can create budget amounts by entering budget register entries, you must define financial dimensions for Budgeting. You must also set up budget codes, budget models, exchange rates, and number sequences. If you plan to use Budgeting workflows, create the workflows, and then assign them to budget codes. If you plan to use budget control, configure budget control before you enter budget amounts. For more information, see [About basic budgeting](about-basic-budgeting.md) and [Define budget codes](define-budget-codes.md).


> [!NOTE]
> <P>This topic includes information about financial budgets. For information about budgets for projects, see <A href="about-project-budgets-and-forecasts.md">About project budgets and forecasts</A>.</P>



## Create a budget register entry

On the **Budget register entry** FastTab of the **Budget register entry** form, you enter information for the whole budget register entry. This information includes the budget model and budget code. In the **Budget account entries** grid, you enter information about the budget amounts for specific financial dimension values for each line.

1.  Click **Budgeting** \> **Common** \> **Budget register entries** \> **All budget register entries**.

2.  On the **Action Pane**, click **Budget register entry** to create a budget register entry.

3.  On the **Budget register entry** FastTab, select a budget model and a budget code.
    
    For example, to create an initial budget amount, you select budget model **Operations**, which identifies the budget, and budget code **InitalBud**, which you previously defined for the **Original budget** budget type.
    

    > [!NOTE]
    > <P>If workflow is activated for the budget code that you select, the budget register entry will be submitted to workflow.</P>



4.  You can select a reason code.

5.  If posting definitions are enabled, you can right-click in the **Posting definition** field, and then click **View details** to verify the posting definition. The posting definition that is displayed is the posting definition that is selected for the budget type or budget code in the **Transaction posting definitions** form. For more information, see [About posting definitions](about-posting-definitions.md).
    

    > [!NOTE]
    > <P>The <STRONG>Posting definition</STRONG> field is displayed only when the <STRONG>Use posting definitions</STRONG> and <STRONG>Enable budget appropriation</STRONG> check boxes are selected in the <STRONG>General ledger parameters</STRONG> form.</P>



6.  In the **Budget account entries** grid, click **Add line**.

7.  Enter a date. This date determines the period that the budget will be recorded to.

8.  Select an account structure.

9.  Enter the financial dimension values.

10. Enter the budget amount and the budget amount type. The default budget amount type is **Expense**. However, you can change the value to **Revenue** for revenue amount types.
    

    > [!NOTE]
    > <P>If you must increase a revenue account and an expense account at the same time, you must post a budget register entry that has a budget type of <STRONG>Revision</STRONG>.</P>



11. Select a currency.

12. On the **Action Pane**, click **Update budget balances**.

13. Click **OK**, or enter batch criteria.

## Create a budget transfer

You can create budget transfers by creating a budget register entry that has a budget code that is associated with the **Transfer** budget type. You decrease the budget of one or more financial dimension values, and then increase the budget of other financial dimension values by the same amount.

1.  Click **Budgeting** \> **Common** \> **Budget register entries** \> **All budget register entries**.

2.  On the **Action Pane**, click **Budget register entry**.

3.  On the **Budget register entry** FastTab, select a budget model and a budget code that is associated with the **Transfer** budget type.

4.  In the **Budget account entries** grid, click **Add line**. Enter the account structure and financial dimension values to transfer a budget amount from. Then enter a negative amount, such as -1000.00.

5.  Click **Add line** to add a line for the account structure and financial dimension values that you want to transfer the budget amount to. Then enter a positive amount, such as 1000.00.
    
    If multiple accounts must be used to increase the budget of the financial dimension values that are receiving the budget amount, add lines, and then enter a negative amount on each line.

6.  Click **Update budget balances**.
    
    If workflow is activated for the budget code that you selected for the budget transfer, a message informs you that the budget transfer request was submitted to workflow.

7.  If workflow is not activated, click **OK**, or enter batch criteria.

## Create a budget transfer when you are creating another entry

You can create a budget transfer when you are creating a budget register entry. For example, if you see that a manual budget reservation will exceed the budget, you can create a budget transfer to satisfy the over-budget condition. You can also create budget transfers from source documents such as purchase orders and invoices, and from accounting journals.

1.  Click **Budgeting** \> **Common** \> **Budget register entries** \> **All budget register entries**.

2.  On the **Action Pane**, click **Budget register entry** to create a budget register entry.

3.  On the **Budget register entry** FastTab, select a budget model and a budget code.
    

    > [!NOTE]
    > <P>You can create a transfer from any of the budget types, such as <STRONG>Original budget</STRONG> or <STRONG>Revision</STRONG>.</P>



4.  In the **Budget account entries** grid, click **Add line**. Then enter the date, account structure, financial dimension values, amount, and amount type.

5.  Save the line.

6.  Click **Create transfer** to open the **Create budget transfer** form.

7.  Verify the information at the top of the form. Then enter the from date, account structure, from financial dimension values, and amount.
    

    > [!IMPORTANT]
    > <P>To decrease the budget for the from financial dimension values, you must enter a negative amount. The amount that is transferred from one or more financial dimension values must equal the amount that is transferred to the selected financial dimension value. The transaction total at the bottom of the form must be 0 (zero). For more information, see <A href="https://technet.microsoft.com/library/hh242713(v=ax.60)">Create budget transfer (form)</A>.</P>



8.  Click **Update budget balances**.
    
    If workflow is activated for the budget code that you selected for the budget transfer, a message informs you that the budget transfer request was submitted to workflow.

9.  If workflow is not activated, click **OK**, or enter batch criteria.

## Allocate budget register entries

You can allocate budget register entries across periods or to financial dimensions.

Period allocation keys define the percentage of a budget register entry that is allocated to specific periods. Period allocation keys work with the fiscal year definition for the fiscal calendar that is associated with the ledger. For example, if the fiscal year starts on July 1 and ends on June 30, and the period allocation is **Fixed**, the allocation is applied from the current date through June 30. For more information, see [Period allocation categories (form)](https://technet.microsoft.com/library/aa582352\(v=ax.60\)).

Budget allocation terms define the percentage of a budget register entry that is allocated to specific financial dimension values. For example, a percentage of the travel budget can be allocated to various departments. For more information, see [Budget allocation terms (form)](https://technet.microsoft.com/library/hh209569\(v=ax.60\)).

1.  Click **Budgeting** \> **Common** \> **Budget register entries** \> **All budget register entries**.

2.  On the **Action Pane**, click **Budget register entry** to create a budget register entry.

3.  On the **Budget register entry** FastTab, select a budget model and a budget code.
    

    > [!NOTE]
    > <P>You can create allocations from any of the budget types, such as <STRONG>Original budget</STRONG> or <STRONG>Revision</STRONG>.</P>



4.  In the **Budget account entries** grid, click **Add line**. Then enter the date, account structure, financial dimension values, amount, and amount type.

5.  Save the line.

6.  Do one of the following:
    
      - To allocate across periods, click **Allocate across periods**. Select a period allocation key, and then click **Allocate**.
    
      - To allocate to financial dimensions, click **Allocate to dimensions**. Select a budget allocation term, and then click **Allocate**.

7.  In the **Budget account entries** grid, verify the new lines. A reversal entry is created for the budget account that you specified, and new budget account entries are created based on the allocation that you selected.

8.  Click **Update budget balances**.

9.  Click **OK**, or enter batch criteria.

## Create recurring budget amounts

For some expenses, such as rent, the budgeted amount is typically the same for each period. You can replicate a budget account entry to create a recurring budget amount.

1.  Click **Budgeting** \> **Common** \> **Budget register entries** \> **All budget register entries**.

2.  On the **Action Pane**, click **Budget register entry** to create a budget register entry.

3.  On the **Budget register entry** FastTab, select a budget model and a budget code.

4.  In the **Budget account entries** grid, click **Add line**. Then enter the financial dimension values, amount, and amount type.

5.  Click **Enter recurrence**.

6.  Enter the interval type, interval, and expiration date, and then click **Create**.

7.  In the **Budget account entries** grid, verify the new lines, and then click **Update budget balances**.

8.  Click **OK**, or enter batch criteria.

## See also

[About basic budgeting and budget control setup](about-basic-budgeting-and-budget-control-setup.md)

[Budget registry entry (form)](https://technet.microsoft.com/library/hh227354\(v=ax.60\))

[Examples: Budgeting and budget control](examples-budgeting-and-budget-control.md)

  


