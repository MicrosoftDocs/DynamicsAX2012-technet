---
title: Specify which users can post to a period
TOCTitle: Specify which users can post to a period
ms:assetid: af2c490b-b01b-47f8-9b18-664d9ce5ed7b
ms:mtpsurl: https://technet.microsoft.com/library/Hh242712(v=AX.60)
ms:contentKeyID: 36058950
author: tonyafehr
ms.date: 05/01/2014
mtps_version: v=AX.60
f1_keywords:
- post to a period
- users post to a period
audience: Application User
ms.search.region: Global
---

# Specify which users can post to a period 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can specify which user groups can post to a period by using the **Ledger calendar** form. For example, at the start of a new period, you might want a group of users to finish posting financial transactions in the previous period, while other groups work only in the new period.

1.  Click **General ledger** \> **Setup** \> **Ledger**.

2.  Verify that a calendar is selected in the **Fiscal calendar** field.

3.  Click **Ledger calendar**.

4.  In the **Ledger calendar** form, select a fiscal year in the left pane.

5.  On the **Periods** FastTab, select the period to set up permissions for.

6.  Click the **Module access level** FastTab.

7.  In the **Name** column, select the module to set up permissions for.

8.  Select a value in the **Access level** field to indicate which users can post to the module for the period: all users, no users, or only users in a specific user group.
    

    > [!NOTE]
    > <P>If the value in the <STRONG>Period status</STRONG> field on the <STRONG>Periods</STRONG> FastTab is <STRONG>On hold</STRONG>, <STRONG>Closed</STRONG>, or <STRONG>Year closed</STRONG>, no users can post to that period. The period status takes precedence over the selections on the <STRONG>Module access level</STRONG> FastTab.</P>



9.  If you selected **User group** in the **Access level** field, select a value in the **User group** field to specify the user group that can post to the module for the period.

## See also

[About fiscal calendars, fiscal years, and periods](about-fiscal-calendars-fiscal-years-and-periods.md)

[Ledger calendar (form)](https://technet.microsoft.com/library/hh242506\(v=ax.60\))

  


