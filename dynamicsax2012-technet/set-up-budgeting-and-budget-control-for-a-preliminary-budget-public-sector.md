---
title: Set up budgeting and budget control for a preliminary budget (Public sector)
TOCTitle: Set up budgeting and budget control for a preliminary budget (Public sector)
ms:assetid: 3b0504aa-52f3-4003-9ff5-be06a21939b2
ms:mtpsurl: https://technet.microsoft.com/library/Hh208522(v=AX.60)
ms:contentKeyID: 36056268
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- preliminary budgets
audience: Application User
ms.search.region: Denmark, France
---

# Set up budgeting and budget control for a preliminary budget (Public sector) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create a temporary, preliminary budget while the actual budget is being reviewed and approved. If you use budget control, you can select source documents and accounting journals to evaluate for budget control while you use the preliminary budget. You can track the preliminary budget amounts using separate budget codes for the preliminary budge type, and after the approved budget is adopted, the preliminary budget amounts can be reduced as the approved budget amounts are increased.

After you set up basic budgeting and budget control, use the following procedures to add information about preliminary budgets to basic budgeting and budget control. For more information, see [About basic budgeting](about-basic-budgeting.md) and [Set up budget control](set-up-budget-control.md).

## Define budget codes for the preliminary budget type

You can define one or more budget codes for the preliminary budget type. If you want to track different categories of preliminary budget register entries, you can define multiple budget codes for the preliminary budget type. The budget codes for the original budget type should be defined during the setup for basic budgeting. Use budget codes for the preliminary budget type when you enter budget register entries for the preliminary budget amounts. Use budget codes for the original budget type when you enter budget register entries for the original budget amounts.

1.  Click **Budgeting** \> **Setup** \> **Basic budgeting** \> **Budget codes**.

2.  Click **New** and enter an identifier and description.

3.  Select the preliminary budget type.

For more information, see [Define budget codes](define-budget-codes.md).

## Configure budget control for preliminary budgets

1.  Click **Budgeting** \> **Setup** \> **Budget control** \> **Budget control configuration**.

2.  Click **Budget funds available** and select the **Preliminary budget** check box. For more information, see “Define the calculation that determines the budget funds that are available” in [Set up budget control](set-up-budget-control.md).
    

    > [!IMPORTANT]
    > <P>When preliminary budgets are included in the budget funds available calculation, it is important to reverse the preliminary budget register entries when the original budget register entries are recorded in the budget balances. If the budget register entries with preliminary budget codes are not reversed, then both the preliminary budget and original budget types are added, which will overstate the available balance.</P>



3.  Click **Select source documents** and select the **Purchase requisitions** check box. For more information, see “Select source documents for budget control” in [Set up budget control](set-up-budget-control.md).
    

    > [!NOTE]
    > <P>When you select the <STRONG>Purchase requisitions</STRONG> check box, the <STRONG>Purchase orders</STRONG> and <STRONG>Vendor invoices</STRONG> check boxes are automatically selected.</P>



After you set up basic budgeting and budget control for the preliminary budget, you can create budget register entries for the preliminary budget type. For more information, see [Create and reverse a preliminary budget (Public sector)](create-and-reverse-a-preliminary-budget-public-sector.md).

  


