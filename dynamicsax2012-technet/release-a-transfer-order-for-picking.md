---
title: Release a transfer order for picking
TOCTitle: Release a transfer order for picking
ms:assetid: d011fcc3-fc67-4041-af41-c297a9f4d18f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa550995(v=AX.60)
ms:contentKeyID: 36059484
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Release a transfer order for picking 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

1.  Click **Inventory management** \> **Periodic** \> **Release transfer order picking**.

2.  Complete the details on the query form that opens, and then click **OK**.

3.  To deduct from the on-hand inventory the next time that you click **Select** to update the displayed order lines, select the **Deduct released for picking** check box. The resulting order lines are the items that are not reserved on the picking list or output order.

4.  On the **Transfer order line** tab, select an order line that contains the items that you want to ship.

5.  In the **Activate now** field, enter the amount that you want to ship. This amount is automatically reserved. The amount that you enter cannot be more than the value in the **Activate remainder** field.

6.  Click **Recalculate** to update the details of the order line.

7.  Repeat from steps 4 through 6 for each order line that remains.

8.  Click **Release for pick** to open the **Posting picking list** form and to post the picking list.

9.  Close the form to save your changes.

  


