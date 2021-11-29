---
title: Release sales orders for picking
TOCTitle: Release sales orders for picking
ms:assetid: 42d580f1-5fb7-42f3-ab84-b414ddfdd47f
ms:mtpsurl: https://technet.microsoft.com/library/Aa496962(v=AX.60)
ms:contentKeyID: 36056875
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Release sales orders for picking 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

1.  Click **Inventory management** \> **Periodic** \> **Release sales order picking**.

2.  Complete the details on the query form that opens and then click **OK**.

3.  If you want to deduct from on-hand inventory next time, click **Select** to update displayed order lines. Select the **Deduct released for picking** check box. These are the items that are not reserved on the picking list or output order.

4.  Under the **Sales lines** tab, select an order line that contains the items that you want to ship.

5.  Enter the amount you want to ship in the **Activate now** field to a maximum of that in the **Activate remainder** field. This amount is automatically reserved.

6.  Click **Recalculate** to update the order line details.

7.  Repeat from step 4 through 6 for any remaining order lines.

8.  Click **Posting** \> **Picking list** to post the picking list.

  


