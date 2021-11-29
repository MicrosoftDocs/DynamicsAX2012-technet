---
title: Create store inventory documents
TOCTitle: Create store inventory documents
ms:assetid: 8facce8e-64e8-4fb9-9f68-2f32ce336056
ms:mtpsurl: https://technet.microsoft.com/library/Hh597171(v=AX.60)
ms:contentKeyID: 39519231
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create store inventory documents 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

This topic describes how to create purchase orders, transfer orders, and scheduled stock counts. For information about how to create unscheduled stock counts at a store, see Microsoft Dynamics AX for Retail POS Help or Enterprise Portal for Microsoft Dynamics AX Help.

## Create a purchase order

Use the following procedure to create a purchase order. This procedure is used only by retail organizations. For more information about purchase orders, see [Create and maintain purchase orders](create-and-maintain-purchase-orders.md).


> [!TIP]
> <P>You can receive purchase orders at a store by using either Retail POS or Enterprise Portal. For more information, see Retail POS Help and Enterprise Portal Help.</P>



1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  In the **New** group, click **Purchase order**.

3.  In the purchase order header, enter information about the vendor. You must enter a value in the **Vendor account** field.

4.  On the **General** tab, enter information about the purchase order. You must enter values in the **Invoice account** and **Currency** fields.

5.  Under **Storage dimensions**, in the **Warehouse** list, select the warehouse that receives the order.

6.  On the **Administration** tab, you must enter a value in the **Language** field.

## Create a transfer order

Use the following procedure to create a transfer order. This procedure is used only by retail organizations. For more information about transfer orders, see [About transfer orders](about-transfer-orders.md).


> [!TIP]
> <P>You can receive transfer orders at a store by using either Retail POS or Enterprise Portal. For more information, see Retail POS Help and Enterprise Portal Help.</P>



1.  Click **Inventory management** \> **Periodic** \> **Transfer orders**.

2.  Press CTRL+N to create a new transfer order.

3.  In the **From warehouse** and **To warehouse** fields, select the warehouses that send and receive the order.

4.  Click **Add** to add individual products, or click **Add products** to add groups or categories of products.

## Create a scheduled stock count

Use the following procedure to create a scheduled stock count. This procedure is used only by retail organizations. For more information about stock counts, see [Inventory counting](inventory-counting.md).

Unscheduled stock counts can be created at a store. For more information, see Retail POS Help.

1.  Click **Inventory management** \> **Journals** \> **Item counting** \> **Counting**.

2.  Press CTRL+N, select the **Warehouse** check box, and then click **OK**.

3.  In the **Name** field, select **Inventory counting journal**.

4.  Click **Lines**. Then click **Add** to add individual products, or click **Add products** to add groups or categories of products.

5.  Click **Validate** to update quantities, and then click **Post** to post the stock count.

## See also

[About working with store inventory](about-working-with-store-inventory.md)

  


