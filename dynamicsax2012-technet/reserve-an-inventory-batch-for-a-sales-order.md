---
title: Reserve an inventory batch for a sales order
TOCTitle: Reserve an inventory batch for a sales order
ms:assetid: 95e4aadd-42d4-4220-ae07-8f8e6f04dfd0
ms:mtpsurl: https://technet.microsoft.com/library/Hh352305(v=AX.60)
ms:contentKeyID: 36687933
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Reserve an inventory batch for a sales order 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to reserve on-hand inventory batches for a sales order. This procedure is applicable for both catch weight items and for regular items.

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Double-click the sales order for which inventory is being reserved. The **Sales order** form is displayed.

3.  On the **Sales order lines** FastTab, select the sales order line for the item.
    

    > [!NOTE]
    > <P>The item you select must be batch controlled. An item is batch controlled if the batch number dimension is active on the item's tracking dimension group.</P>
    > <UL>
    > <LI>
    > <P>Click <STRONG>Product information management</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>Dimension groups</STRONG> &gt; <STRONG>Tracking dimension groups</STRONG>. Then select the <STRONG>Active</STRONG> check box for the <STRONG>Batch number</STRONG> line.</P></LI></UL>



4.  Click **Inventory** and then select **Batch reservation**.

5.  In the **Reservation** field, enter the quantity to be reserved to the sales order. For a catch weight item, use the **CW reservation** field.

6.  To reserve a lot or a line to the sales order, click **Reserve lot** or **Reserve line**. The **Reservation** field is filled in for the current lot or the current on-hand inventory.

## See also

[Batch reservation (form)](https://technet.microsoft.com/library/hh208645\(v=ax.60\))

[Sales orders (form)](https://technet.microsoft.com/library/aa585863\(v=ax.60\))

  


