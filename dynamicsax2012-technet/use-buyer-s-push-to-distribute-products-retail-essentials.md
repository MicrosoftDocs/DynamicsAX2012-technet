---
title: Use buyer's push to distribute products (Retail essentials)
TOCTitle: Use buyer's push to distribute products (Retail essentials)
ms:assetid: a8573328-1448-46b9-8ece-d281529437ab
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn736930(v=AX.60)
ms:contentKeyID: 62200407
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Use buyer's push to distribute products (Retail essentials) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to use buyer’s push to distribute products between retail locations. Buyer's push creates transfer orders that are used to distribute products from a warehouse to stores. The quantity that is distributed is either entered manually or calculated automatically by using the same methods that are used for cross-docking. You can create transfer orders for a single item or many items.


> [!NOTE]
> <P>If the stores being distributed to are in another legal entity, sales orders and purchase orders are created.</P>




> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



To create a buyer’s push, use the following steps:

1.  Click **Retail essentials** \> **Inventory management** \> **Buyer's push**.

2.  In the **Buyer's push** form, press CTRL+N or click **New**, and then, in the **Description** field, type a description.

3.  In the **Site** field, select the site location of the warehouse to transfer the products from.

4.  In the **Warehouse** field, select the warehouse to transfer products from.

5.  On the **Lines** FastTab, click **Add** to add a single product to the transfer order, or click **Add products** to add multiple products.

6.  On the **Warehouse** FastTab, select one of the following distribution methods:
    
      - **Replenishment rules** – Distribute quantities based on replenishment rules.
    
      - **Location weight** – Distribute quantities based on the proportional weights that are assigned to the stores.
    
      - **Fixed quantity for all** – Distribute quantities equally among the stores.

7.  To update quantities, either manually insert quantities for the locations or insert the total quantity to distribute, and then click **Calculate quantities**.

8.  To create the transfer orders, click **Create order**.
    
    To view the transfer orders, select a store in the list, and then, on the **Warehouse** FastTab, click **Order**.

## See also

[Use cross docking to distribute products (Retail essentials)](use-cross-docking-to-distribute-products-retail-essentials.md)

[Replenish inventory overview (Retail essentials)](replenish-inventory-overview-retail-essentials.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

