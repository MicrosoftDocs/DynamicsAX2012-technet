---
title: Place a period on hold
TOCTitle: Place a period on hold
ms:assetid: d6e49106-40ff-47df-8659-61efc91dd744
ms:mtpsurl: https://technet.microsoft.com/library/Aa499483(v=AX.60)
ms:contentKeyID: 36059539
author: Khairunj
ms.date: 05/01/2014
mtps_version: v=AX.60
f1_keywords:
- access level
- period status
- On hold
- project period
audience: Application User
ms.search.region: Global
---

# Place a period on hold 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can temporarily block postings to a period by changing its module level access, or by setting the period status to **On hold**.


> [!WARNING]
> <P>When you put a period on hold by changing the period status, all postings by all users are blocked in every module.</P>



### Put a period on hold by changing module level access

1.  Click **General ledger** \> **Setup** \> **Ledger**.

2.  Select a fiscal calendar, if one is not already specified for the ledger.

3.  Click **Ledger calendar**.

4.  In the left pane, select the fiscal year that includes the period that you want to put on hold.

5.  On the **Periods** FastTab, select the period that you want to put on hold.

6.  On the **Module access level** FastTab, select the name of the module for which you want to put the period on hold.

7.  In the **Access level** column, perform one of the following actions:
    
      - To change the status so that no users can make updates for the selected period, select **None**.
    
      - To change the status so that only a specific group can make updates for the selected period, select **User group**, and then select a group in the **User group** column.


> [!NOTE]
> <P>To re-enable postings to periods, reset the period status to <STRONG>All</STRONG>.</P>



### Put a period on hold by changing period status

1.  Click **General ledger** \> **Setup** \> **Ledger**. In the menu bar, click **Ledger calendar**.

2.  In the left pane, select the year that includes the period that you want to put on hold.

3.  In the **Periods** grid, select the period that you want to put on hold.

4.  In the **Period status** column, select **On hold**.


> [!NOTE]
> <P>You can reopen a period with an <STRONG>On hold</STRONG> status, but you cannot reopen a period with a <STRONG>Closed</STRONG> status.</P>



## See also

[Ledger calendar (form)](https://technet.microsoft.com/library/hh242506\(v=ax.60\))

[Fiscal calendars (form)](https://technet.microsoft.com/library/hh209283\(v=ax.60\))

[About fiscal calendars, fiscal years, and periods](about-fiscal-calendars-fiscal-years-and-periods.md)

[Key tasks: Fiscal calendars, fiscal years, and periods](key-tasks-fiscal-calendars-fiscal-years-and-periods.md)

  


