---
title: Set up budgeting and budget control for apportionments (Public sector)
TOCTitle: Set up budgeting and budget control for apportionments (Public sector)
ms:assetid: 2ace20d3-6775-4120-9132-50af75c8e57c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208519(v=AX.60)
ms:contentKeyID: 36056265
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- apportionment budget transactions
- transactions for budget apportionments
audience: Application User
ms.search.region: Denmark, France
---

# Set up budgeting and budget control for apportionments (Public sector) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Apportionments are the portion of the original budget that have been approved for spending. For example, a public sector organization might have an original budget of 1,000,000 but only have authority to spend 150,000 in the first quarter of the fiscal year. You could record an original budget register entry for 1,000,000 for the fiscal year. Then you could record an apportionment budget register entry for 150,000 for the first three months of the year. Only the 150,000 that was apportioned could be spent during the first quarter.


> [!NOTE]
> <P>You cannot apportion more than the original budget amount for the dimensions values.</P>



After you set up basic budgeting and budget control, follow the steps in these procedures to add information about apportionments to basic budgeting and budget control. For more information, see [About basic budgeting](about-basic-budgeting.md) and [Set up budget control](set-up-budget-control.md).

## Define budget codes for the apportionment budget type

You can define one or more budget codes for the apportionment budget type. The budget codes for the orginal budget type should be defined during the setup for basic budgeting. Use budget codes for the apportionment budget type when you enter budget register entries for the apportioned budget amounts. Use budget codes for the original budget type when you enter budget register entries for the original budget amounts.

1.  Click **Budgeting** \> **Setup** \> **Basic budgeting** \> **Budget codes**.

2.  Click **New** and enter an identifier and description.

3.  Select the apportionment budget type.

For more information, see [Define budget codes](define-budget-codes.md).

## Configure budget control for apportionments

1.  Click **Budgeting** \> **Setup** \> **Budget control** \> **Budget control configuration**.

2.  Click **Budget funds available** and select the **Use only apportioned amount** check box. For more information, see “Define the calculation that determines the budget funds that are available“ in [Set up budget control](set-up-budget-control.md).
    

    > [!IMPORTANT]
    > <P>When you select the <STRONG>Use only apportioned amount</STRONG> check box, the other check boxes under <STRONG>Amounts to sum</STRONG> become disabled and the budget funds available calculation includes only apportioned amounts in the amounts to sum. Typically, you would include <STRONG>Actual expenditures</STRONG>, <STRONG>Budget reservations for encumbrances</STRONG>, <STRONG>Budget reservations for unconfirmed encumbrances</STRONG>, and <STRONG>Budget reservations for pre-encumbrances</STRONG> in the amounts to subtract.</P>



3.  Click **Select source documents** and select the **Purchase requisitions** check box. For more information, see “Select source documents for budget control“ in [Set up budget control](set-up-budget-control.md).
    

    > [!NOTE]
    > <P>When you select the <STRONG>Purchase requisitions</STRONG> check box, the <STRONG>Purchase orders</STRONG> and <STRONG>Vendor invoices</STRONG> check boxes are automatically selected.</P>



After you define budget codes for basic budgeting and configure budget control for apportionments, you can create budget register entries for the original budget and apportionment budget types. For more information, see [Create budget register entries (Public sector)](create-budget-register-entries-public-sector.md).

  


