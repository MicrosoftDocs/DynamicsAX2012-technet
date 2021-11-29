---
title: Create flex groups for time and attendance
TOCTitle: Create flex groups for time and attendance
ms:assetid: 8831b6b7-558c-4f94-a28d-5ac220e7c8a2
ms:mtpsurl: https://technet.microsoft.com/library/Aa498224(v=AX.60)
ms:contentKeyID: 36058442
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create flex groups for time and attendance 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If a worker is allowed to work flexible hours, the worker must be connected to a flex group. Flex groups are selected for workers when they are set up as time registration workers.

1.  Click **Human resources** \> **Setup** \> **Time and attendance** \> **Groups** \> **Flex groups**.

2.  Press CTRL+N or click **New** to create a new flex group.

3.  Fill out the **Flex group ID** and **Description** fields.

4.  In the **Flex minimum** field, insert the lowest acceptable limit of a worker’s flex balance (the value must be a negative number or zero).

5.  In the **Flex maximum** field, insert the highest acceptable limit of a worker's flex balance (the value must be positive).

6.  To adjust the flex balance automatically when the balance reaches the minimum or maximum levels, select the **Adjust flex minimum** and/or **Adjust flex maximum** check boxes. If you select those check boxes, you must also select either the **Minimum pay type** or the **Maximum pay type**.


> [!NOTE]
> <P>You can multiply the adjustment pay type with a factor by inserting a number in the <STRONG>Pay type factor</STRONG> fields.</P>



## Flex balance based on pay types

If you select the **Based on pay types** check box, the flex balance is calculated based on the generated pay for the pay types that are selected in the **Flex+** and **Flex-** fields.

## See also

[About time registration workers](about-time-registration-workers.md)

  


