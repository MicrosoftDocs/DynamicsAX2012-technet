---
title: About main account types
TOCTitle: About main account types
ms:assetid: 1b1dfcdb-0504-4134-9469-7ea7cfc68142
ms:mtpsurl: https://technet.microsoft.com/library/Aa572637(v=AX.60)
ms:contentKeyID: 37832494
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- chart of accounts
- main accounts
- chart of account
- main account
- account type
- main account type
audience: Application User
ms.search.region: Global
---

# About main account types 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following main account types determine how a main account is used in the chart of accounts. You must select a main account type when you create a main account in the **Main accounts - chart of accounts: %1** form.

  - **Profit and loss**, **Revenue**, and **Expense** – These main accounts are used as posting accounts. **Profit and loss** accounts are used to record revenue and expenses. The sum of all operating accounts determines the year-end results. **Revenue** and **Expense** main accounts have the same function as **Profit and loss** main accounts.

  - **Balance sheet**, **Asset**, **Liability**, and **Equity** – These main accounts are used as transaction accounts to record the amounts that a legal entity owns or owes. If you use **Asset**, **Liability**, and **Equity** main accounts, the accounts can have more specification, and you can more precisely structure reports about the balance of the legal entity.

  - **Total** – These main accounts are used to add account intervals. Configure the **Total** main account type by using the **Sales tax totals** form, which displays the total of the group balances for all account intervals.

  - **Reporting** – These main accounts are used for financial statement reporting.

  - **Common** – These main accounts are for accounts that are used in banks or financial institutions in China. Accounts that have a **Common** main account type are recorded as assets if the balance is positive and as liabilities if the balance is negative. An example of an account that has the **Common** main account type is a currency hedging account.

## See also

[Main accounts - chart of accounts (form)](https://technet.microsoft.com/library/hh209695\(v=ax.60\))

  


