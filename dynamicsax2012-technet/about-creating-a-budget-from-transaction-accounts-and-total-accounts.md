---
title: About creating a budget from transaction accounts and total accounts
TOCTitle: About creating a budget from transaction accounts and total accounts
ms:assetid: 4e893d3b-7226-4c78-9912-63fc9310ac69
ms:mtpsurl: https://technet.microsoft.com/library/Aa497123(v=AX.60)
ms:contentKeyID: 39519134
author: Khairunj
ms.date: 11/20/2015
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About creating a budget from transaction accounts and total accounts 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create budgets based on transaction accounts and total accounts. Generally, these budgets involve expense accounts that have a main account type of **Profit and loss**.


> [!NOTE]
> <P>For information about total accounts in budget groups, see <A href="setup-overview-basic-budgeting-and-budget-control.md">Setup overview: basic budgeting and budget control</A>.</P>



## Creating a budget from both transaction accounts and total accounts

Typically, a budget is created from either transaction accounts or total accounts, but you can use both at the same time.

In the **Budget register entry details** form, a budget account entry for a total account displays only the budget amount that is entered directly on the total account.

When a budget is used in reporting, such as on a financial statement, the budget sum for the total account consists of the following:

  - The budgets that are created from each transaction ledger account in the interval of the total account.

  - The budget amount that is entered directly on the total account.

This lets you create separate budgets for the most significant transaction accounts in the interval of the total account, and then add the available budget amount to the total account.

## Creating a budget from either transaction accounts or total accounts

You can also create a budget from either transaction accounts or total accounts.

  - If you enter budget amounts for a total account, do not enter budget amounts for the transaction accounts that are included in the total interval.

  - If you enter budget amounts for the transaction accounts that are included in the total account interval, do not enter budget amounts for the total account.


> [!NOTE]
> <P>We recommend that you use Management Reporter for Microsoft Dynamics ERP to create, maintain, deploy, and view financial reports that include budget planning data. Management Reporter lets you design financial reports based on ledger accounts and financial dimensions, drill down to transaction-level detail, and use web-based report viewing. For more information about how to print financial reports by using Management Reporter, see <A href="https://go.microsoft.com/fwlink/?linkid=324762">Management Reporter for Microsoft Dynamics ERP</A>.</P>
> <P>You can use Management Reporter to report on budget planning data only if you have rollup 4 or later for Management Reporter 2012 installed.</P>


  


