---
title: Post completed store inventory documents
TOCTitle: Post completed store inventory documents
ms:assetid: f853e617-9de3-4aeb-9b1a-a06024755ad3
ms:mtpsurl: https://technet.microsoft.com/library/Hh597296(v=AX.60)
ms:contentKeyID: 39519381
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Post completed store inventory documents 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

After a purchase order or transfer order has been received, and a stock count has been completed, you can validate and post the documents.


> [!NOTE]
> <P>The procedures in this topic describe one way to post purchase orders, transfer orders, and stock counts. However, your business may have different or alternate steps for these procedures.</P>



## Post a purchase order

1.  Click **Retail** \> **Common** \> **Replenishment** \> **Purchase orders**.

2.  Select the purchase order to post, and then click **Purchase order**.

3.  In the purchase order header, enter information about the vendor. You must enter a value in the **Vendor account** field.

4.  On the **General** tab, enter information about the purchase order. You must enter values in the **Invoice account** and **Currency** fields.

5.  Under **Storage dimensions**, in the **Warehouse** list, select the warehouse that receives the order.

6.  On the **Administration** tab, you must enter a value in the **Language** field.

## Post a transfer order

1.  Click **Inventory management** \> **Periodic** \> **Transfer orders**.

2.  Press CTRL+N to create a new transfer order.

3.  In the **From warehouse** field, select the warehouse that sends the products. In the **To warehouse** field, select the warehouse that receives the products.

4.  Click **Add** to add individual products, or click **Add products** to add groups or categories of products.

## Post a stock count

1.  Click **Inventory management** \> **Journals** \> **Item counting** \> **Counting**.

2.  Press CTRL+N, select the **Warehouse** check box, and then click **OK**.

3.  In the **Name** field, select **Inventory counting journal**.

4.  Click **Lines**. Then click **Add** to add individual products, or click **Add products** to add groups or categories of products.

5.  Click **Validate** to update quantities, and then click **Post** to post the stock count.

## See also

[About working with store inventory](about-working-with-store-inventory.md)

  


