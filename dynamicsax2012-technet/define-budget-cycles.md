---
title: Define budget cycles
TOCTitle: Define budget cycles
ms:assetid: 0367b6cb-7c9f-4733-b5f9-c337babdd09a
ms:mtpsurl: https://technet.microsoft.com/library/Hh242103(v=AX.60)
ms:contentKeyID: 36055938
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- budget cycles
- cycles for budgets
audience: Application User
ms.search.region: Global
---

# Define budget cycles 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Budget cycle time spans** form to specify the fiscal year or the number of periods for the budget cycles that are associated with the budget cycle time span. Budget cycle time spans are associated with fiscal calendars to determine the length of each budget cycle.

Like fiscal calendars, budget cycles can be shared across legal entities.


> [!NOTE]
> <P>When you configure budget control, you assign a budget model to budget cycles. This determines the budget amounts for budget control and is specific to the ledger for the legal entity that you are configuring budget control for. For more information, see <A href="set-up-budget-control.md">Set up budget control</A>.</P>



1.  Click **Budgeting** \> **Setup** \> **Budget control** \> **Budget cycles**.

2.  Click **New** and enter a name for the budget cycle time span.

3.  Select a fiscal calendar to associate with the budget cycle time span.

4.  In the **Length of budget cycle** field, select **Specify number of periods** or **Map to fiscal year**.
    
    If you select **Specify number of periods**, enter the number of accounting periods for the budget cycle. If you select **Map to fiscal year**, the budget cycle time span uses the fiscal year that is defined by the starting and ending periods for the budget cycle.

5.  Click **Add**. Enter the name of the first period in the budget cycle time span and enter the date when that period starts. The ending date for the budget cycle is determined automatically based on the number of fiscal periods in the budget cycle time span.

## See also

[Budget cycle time spans (form)](https://technet.microsoft.com/library/hh227604\(v=ax.60\))

  


