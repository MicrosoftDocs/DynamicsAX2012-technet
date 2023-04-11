---
title: Use cross docking to distribute products (Retail essentials)
TOCTitle: Use cross docking to distribute products (Retail essentials)
ms:assetid: b495a47d-7f05-4509-ab1f-3a627a5af34a
ms:mtpsurl: https://technet.microsoft.com/library/Dn736937(v=AX.60)
ms:contentKeyID: 62200414
author: tonyafehr
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Use cross docking to distribute products (Retail essentials) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to use cross-docking to create transfer orders from a purchase order in Retail essentials. The transfer orders distribute products from the receiving warehouse to stores, based on the quantities and rules that you specify. If the stores that are being distributed to are in another legal entity, sales orders and purchase orders are created.


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



To distribute products by using cross-docking, follow these steps:

1.  Click **Retail essentials** \> **Inventory management** \> **Cross docking**.
    
    –or–
    
    Click **Retail essentials** \> **Inventory management** \> **All purchase orders**. Open the purchase order to cross-dock, and then, on the **Action Pane**, on the **General** tab, click **Cross docking**.
    
    In the **Planned cross docking** form, on the **Lines** FastTab, the lines from the purchase order and the purchase quantities are displayed.

2.  On the **Warehouse** FastTab, select the stores to transfer products to. One transfer order is created for each store that you select.

3.  On the **Warehouse** FastTab, select one of the following distribution methods:
    
      - **Replenishment rules** – Distribute quantities based on replenishment rules.
    
      - **Location weight** – Distribute quantities based on the proportional weights that are assigned to the stores.
    
      - **Fixed quantity for all** – Distribute quantities equally among the stores.

4.  To update quantities, either manually insert quantities for the locations or insert the total quantity to distribute, and then click **Calculate quantities**.

5.  To create the transfer orders, click **Create order**.
    
    To view the transfer orders, select a store in the list, and then click **Order**.

## See also

[Set up replenishment rules (Retail essentials)](set-up-replenishment-rules-retail-essentials.md)

  


