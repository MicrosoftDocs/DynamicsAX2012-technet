---
title: Reserve an inventory batch for a batch order
TOCTitle: Reserve an inventory batch for a batch order
ms:assetid: 0a84018f-031e-41cf-a819-7b98fc18d54f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh352180(v=AX.60)
ms:contentKeyID: 36687811
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Reserve an inventory batch for a batch order [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to reserve an inventory batch from a batch formula line to use in a batch order. This procedure is applicable for both catch weight items and regular items.


> [!NOTE]
> <P>You can reserve batches from the formula lines when the batch order is in a status of <STRONG>Estimated</STRONG> or <STRONG>Released</STRONG>. If a batch order has the status <STRONG>Started</STRONG>, a picking list is generated and you can reserve from the picking list journal line.</P>



1.  Click **Production control** \> **Common** \> **Production orders** \> **All production orders**.

2.  Double-click the batch order for which the inventory is being reserved. The **Batch order** form is displayed.

3.  On the **Action Pane**, on the **Production order** tab, click **Order details** and then click **Formula**.

4.  In the **Formula lines-batch** form, click **Inventory** and then select **Reservation**.

5.  In the **Reservation** field, enter the quantity to be reserved to the batch order. For a catch weight item, use the **CW reservation** field.
    

    > [!TIP]
    > <P>To reserve a lot or a line to the batch order, use the <STRONG>Reserve lot</STRONG> button or the <STRONG>Reserve line</STRONG> button. The appropriate <STRONG>Reservation</STRONG> field is filled in for the current lot or the current on-hand inventory.</P>



## See also

[Batch order (form)](https://technet.microsoft.com/en-us/library/hh352323\(v=ax.60\))

[Formula lines-batch (form)](https://technet.microsoft.com/en-us/library/hh328711\(v=ax.60\))

[Reservation (form)](https://technet.microsoft.com/en-us/library/aa617039\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

