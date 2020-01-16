---
title: Use buyer's push to distribute products
TOCTitle: Use buyer's push to distribute products
ms:assetid: b692cb8a-8026-45d3-abd3-cea51437778c
ms:mtpsurl: https://technet.microsoft.com/library/Hh597218(v=AX.60)
ms:contentKeyID: 39519290
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Use buyer's push to distribute products 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

This topic explains how to use buyer’s push to create transfer orders. *Buyer's push* is a process in which products are purchased by a centralized purchasing department (the buyer) and then distributed (pushed) to stores. The quantity that is distributed is either entered manually or calculated automatically. You can create transfer orders for a single item or many items.


> [!NOTE]
> <P>If the stores that are being distributed to are in another legal entity, sales orders and purchase orders are created.</P>



1.  Click **Retail** \> **Common** \> **Replenishment** \> **Buyer's push**.

2.  Press Ctrl+N or click **New**, and then, in the **Description** field, enter a description.

3.  In the **Site** field, select a site, and then in the **Warehouse** field, select the warehouse to transfer products from.

4.  On the **Lines** FastTab, click **Add** to add a single product to the transfer order, or click **Add products** to add multiple products.
    
    To remove a product, select the check box of the product to remove, and then click **Remove**.

5.  Do one of the following:
    
      - To specify a total quantity for the transfer orders, enter the quantity in the **Additional quantity to push** field. The quantity must be less than the quantity in the **Remaining available quantity to push** field. The quantity that you enter is distributed proportionately among the products.
    
      - To manually specify a quantity for each product, enter each quantity in the **Pushed quantity** column. The quantity must be less than the quantity in the **On hand** column.
    

    > [!NOTE]
    > <P>Alternatively, you can specify quantities manually on some of the lines, and then enter a number in the <STRONG>Additional quantity to push</STRONG> field for the remaining lines.</P>



6.  On the **Warehouse** FastTab, select one of the following distribution methods:
    
      - **Replenishment rules** – Distribute quantities based on replenishment rules.
    
      - **Location weight** – Distribute quantities based on the proportional weights that are assigned to the stores.
    
      - **Fixed quantity for all** – Distribute quantities equally among the stores.

7.  If you selected **Location weight** or **Fixed quantity for all**, you can select a hierarchy of stores in the **Replenishment hierarchy** field. These are the stores that will receive the transferred products.
    
    If you selected **Replenishment rules**, the replenishment rules determine which stores will receive the transferred products.

8.  To distribute the products to only the stores that have the products in their assortments, select the **Respect assortments** check box.
    
    Regardless of the distribution method you select, one transfer order is created for each store.

9.  To update quantities, click **Calculate quantities**.

10. To create the transfer orders, click **Create order**.

11. To view the orders, on the **Warehouse** FastTab, select a store in the list, and then click **Order**.

## See also

[Replenish inventory overview](replenish-inventory-overview.md)

  


