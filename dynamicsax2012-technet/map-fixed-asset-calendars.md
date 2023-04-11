---
title: Map fixed asset calendars
TOCTitle: Map fixed asset calendars
ms:assetid: 213880ef-3752-481a-b71b-9e1dc1a498cc
ms:mtpsurl: https://technet.microsoft.com/library/Gg751366(v=AX.60)
ms:contentKeyID: 35132574
author: tonyafehr
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- map
- upgrade
- fiscal calendar
- Map fiscal calendar
- fixed asset calendar
---

# Map fixed asset calendars 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you upgrade to Microsoft Dynamics AX 2012, you must use the **Upgrade fixed asset calendars** form to upgrade existing fixed asset calendars to fiscal calendars that can be shared by multiple legal entities.

You can then use the **Ledger** form in Microsoft Dynamics AX 2012 to select a fiscal calendar.

If you are upgrading to Microsoft Dynamics AX 2012 R2 or AX 2012 R3, you must identify a data partition when performing this task. If you have configured multiple partitions, the procedure must be repeated for each partition. For more information about data partitions and upgrade, see [Configure partitions](configure-partitions.md).


> [!NOTE]
> <P>When you upgrade fixed asset calendars, each new fiscal calendar must have a unique name.</P>



1.  In the **Partition key** field, select a partition for preprocessing.

2.  Review the list of companies that use fixed asset calendars, and then review the names of the fixed asset calendars in the **Calendar name** column.
    
      - If all the calendar names in the **Calendar name** column are unique, you do not need to make any changes.
    
      - If two or more calendars have the same name in the **Calendar name** column, a new name must be assigned so that each calendar name is unique. For each duplicate calendar name, a new name is suggested in the **New name** column. You can change these suggested names.

3.  When you are finished, click **Set to ready for upgrade** to upgrade the fixed asset calendars to fiscal calendars.

## Example

Both Legal entity A and Legal entity B have fixed asset calendars named RBA01 (Reducing Balance Asset 1). Your task is to upgrade the fixed asset calendars to fiscal calendars. In the **New name** column, you change the names of the calendars to RBA01-A and RBA01-B. After you upgrade the calendars, the calendars are shared and can be used by any legal entity or by multiple legal entities.

  


