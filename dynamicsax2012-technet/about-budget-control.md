---
title: About budget control
TOCTitle: About budget control
ms:assetid: c8ce99a3-e2ed-4fc5-a822-dfa861309ad8
ms:mtpsurl: https://technet.microsoft.com/library/Hh242850(v=AX.60)
ms:contentKeyID: 36059323
author: Khairunj
ms.author: daxcpft
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- budget control
- about budget control
- budget checking
audience: Application User
ms.search.region: Global
---

# About budget control 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Budget control, including budget checking, is a method of ensuring that sufficient budget funds are available for planned or actual purchases. After you set up basic budgeting, you can set up budget control.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed in Microsoft Dynamics AX 2012 R3 Cumulative Update 8.</P>



You can set up basic budgeting and budget control based on the ledger for a legal entity. The ledger provides the chart of accounts, accounting and reporting currencies, and fiscal calendar. You can determine which financial dimensions from the chart of accounts will be available for budgeting and budget control. You can define budget intervals, time spans for budget cycles, budget thresholds, budget managers, budget groups, and the calculation that is used to check for available budget funds. The available budget funds can be verified when source documents and accounting journals are entered.

If you’re in the public sector and use general budget reservations, see also [About general budget reservations (Public sector)](about-general-budget-reservations-public-sector.md).


> [!NOTE]
> <P>General budget reservations are available only if the <STRONG>Public Sector</STRONG> configuration key is selected and if Microsoft Dynamics AX 2012 R3 Cumulative Update 8 is installed with the following hotfix: KB3047235</P>



## Budget control integration

Budget control is integrated with the following areas:

  - General ledger

  - Procurement and sourcing

  - Travel and expense

  - Project management and accounting

  - Fixed assets

  - Supply chain management

**Example: Budget control integrated with purchase order entry**

A purchasing agent creates a purchase order that has multiple lines and enters the first three lines. When the purchasing agent enters the fourth line, a message is displayed stating that the financial dimension value is over budget. The purchasing agent is not in a user group that is authorized to exceed the budget. The purchasing agent can complete the fourth line, enter additional lines, and save the purchase order in a **Draft** state. The purchasing agent then notifies a manager of the over-budget situation. The budget manager has the authority to exceed the budget funds available. The budget manager can open the purchase order and continue with the purchase order confirmation without changing any amounts or accounts. Subsequently, the budget manager can perform a budget transfer to increase the available budget for the value in the financial dimension that is over budget.

## Budget checking

Budget checking helps to ensure that budget funds are available. When you perform the budget check, the budget amount that is available before the current purchase is added to the value on the selected purchase requisition line. Also any new budget amount that is available after the purchase is computed.

**Example**

Main account 606300, Office supplies, is in an account structure and is a financial dimension value that is defined for budget control. A budget amount of 10,000.00 has been entered in main account 606300 by using a budget register entry. Purchase orders have been defined for budget control at line-item entry.

A purchasing agent creates a purchase order and enters an amount of 5,000.00 for ledger account 606300-OU\_1-OU\_4571-Conference/Seminar. A budget check is performed automatically and the result of the budget check is visible on the purchase order line. If the budget check is successful, showing that there are sufficient funds, the agent can confirm the purchase order.

  


