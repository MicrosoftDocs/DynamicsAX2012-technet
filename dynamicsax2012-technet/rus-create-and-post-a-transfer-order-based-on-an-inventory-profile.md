---
title: (RUS) Create and post a transfer order based on an inventory profile
TOCTitle: (RUS) Create and post a transfer order based on an inventory profile
ms:assetid: 794bb713-5802-402f-a89f-436eada4646a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ733244(v=AX.60)
ms:contentKeyID: 49685211
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Create and post a transfer order based on an inventory profile [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create and post transfer orders based on the inventory profile. The inventory profile on the purchase order line must belong to the kind of activity that is selected in the purchase order, unless the kind of activity is **Unspecified**.

1.  Click **Inventory management** \> **Periodic** \> **Transfer orders**.

2.  Create a transfer order. For more information see [Set up transfer order lines](set-up-transfer-order-lines.md).

3.  Click the **Setup** tab, and then, in the **Kind of activity** field, select **Basic**, **Commission agent**, **Principal's agent**, or **Bailee** as the profile type.

4.  In the **Inventory profile** field, select the inventory profile that the item is transferred from.

5.  In the **To inventory profile** field, select the inventory profile that the item is transferred to.

6.  Select the **Use compatible inventory profiles** check box to use inventory profiles on order lines. These order lines must be compatible with the inventory profile that is specified in the order.

7.  Post the transfer order.
    

    > [!NOTE]
    > <P>You can view the transfer order transactions in the <STRONG>Transfer order history</STRONG> form. Use the <STRONG>On-hand</STRONG> form to view the related transactions for the inventory profile that is selected in the <STRONG>Kind of activity</STRONG> field.</P>



## See also

[(RUS) Transfer orders (modified form)](https://technet.microsoft.com/en-us/library/jj733409\(v=ax.60\))

[(RUS) Transfer order shipment (modified form)](https://technet.microsoft.com/en-us/library/jj733191\(v=ax.60\))

[On-hand movement (form)](https://technet.microsoft.com/en-us/library/aa574933\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

