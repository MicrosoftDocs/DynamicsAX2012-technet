---
title: Create budget register entries (Public sector)
TOCTitle: Create budget register entries (Public sector)
ms:assetid: aa1c0df9-9c97-4f1f-99d8-ec80838c9898
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208569(v=AX.60)
ms:contentKeyID: 36056348
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- apportionment posting
- posting apportionments
audience: Application User
ms.search.region: Denmark, France
---

# Create budget register entries (Public sector) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the apportionment budget type to segregate apportionments from original budget amounts for a specific budget model and dimension values. Before you create budget register entries to enter amounts for the original budget and apportionments, you must set up basic budgeting and configure budget control for apportionments. For more information, see [Set up budgeting and budget control for apportionments (Public sector)](set-up-budgeting-and-budget-control-for-apportionments-public-sector.md).

## Create budget register entries

To distinguish between the original budget amount and the apportioned amount, create two budget register entries for a specific budget model and dimension values. Create one budget register entry using a budget code for the original budget type and create another budget register entry using a budget code for the apportionment budget type. The apportioned amount cannot exceed the original budget amount.

1.  Click **Budgeting** \> **Common** \> **Budget register entries** \> **All budget register entries**.

2.  On the **Action Pane**, click **Budget register entry** to create a budget register entry.

3.  On the **Budget register entry** FastTab, select a budget model and a budget code for the original budget type. Then save the entry.

4.  In the **Budget account entries** grid, click **Add line**.

5.  Enter a new date if you want to change the date from the one in the header. This date determines the fiscal period that the budget will be recorded to.

6.  Select an account structure and enter the financial dimension values.

7.  Enter the budget amount, budget amount type and currency.

8.  On the **Action Pane**, click **Update budget balances**. Then click **OK**, or enter batch criteria.
    

    > [!NOTE]
    > <P>To see the original budget and subsequent budget balances, select the budget account entry and click <STRONG>Related information</STRONG> &gt; <STRONG>Budget register entries</STRONG> &gt; <STRONG>Budget balances</STRONG>. For more information, see <A href="view-budget-activities-for-apportionments-public-sector.md">View budget activities for apportionments (Public Sector)</A>.</P>



9.  Repeat steps 2 – 8 using a budget code for the apportionment budget type. Use the same budget model, date, account structure, and dimension values that you used previously.

For more information, see [Create budget register entries](create-budget-register-entries.md).

  


