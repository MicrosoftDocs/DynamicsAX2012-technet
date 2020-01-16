---
title: Use cross docking to distribute products
TOCTitle: Use cross docking to distribute products
ms:assetid: 160a6fb3-cae1-41ce-a642-921e43fca77d
ms:mtpsurl: https://technet.microsoft.com/library/Hh580575(v=AX.60)
ms:contentKeyID: 39519054
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Use cross docking to distribute products 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

This topic explains how to use cross-docking to create transfer orders from a purchase order. Cross docking distributes products from the receiving warehouse to stores, based on the quantities and rules that you specify.


> [!TIP]
> <P><EM>Cross docking</EM> is a distribution practice in which items flow from receiving to shipping, with limited or no storage required. Typically, trucks arrive at one side of a loading dock, and then their shipments are unloaded, reorganized, and loaded onto departing trucks on the other side.</P>




> [!NOTE]
> <P>If the stores that the products are being distributed to are in another legal entity, sales orders and purchase orders are created.</P>



1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Double-click the purchase order to cross-dock.

3.  On the **Action Pane**, on the **Retail** tab, in the **Functions** group, click **Cross docking**.
    
    The **Lines** FastTab in the **Planned cross docking** form displays each purchase order line from the purchase order, together with the purchased quantities.

4.  Do one of the following:
    
      - To specify a total quantity for the transfer orders, enter the quantity in the **Additional cross docking quantity** field. The quantity must be less than the quantity in the **Remaining available cross docking quantity** field. The quantity that you enter is distributed proportionately among the products.
    
      - To manually specify a quantity for each product, enter each quantity in the **Cross docking quantity** column. The quantity must be less than the on-hand quantity. To view the on-hand quantity, click **On hand**.
    

    > [!NOTE]
    > <P>You can specify quantities manually in some of the lines, and then enter a number in the <STRONG>Additional cross docking quantity</STRONG> field for the remaining lines.</P>



5.  On the **Warehouse** FastTab, select one of the following distribution methods:
    
      - **Replenishment rules** – Distribute quantities based on replenishment rules.
    
      - **Location weight** – Distribute quantities based on the proportional weights that are assigned to the stores.
    
      - **Fixed quantity for all** – Distribute quantities equally among the stores.

6.  If you selected **Location weight** or **Fixed quantity for all**, you can select a hierarchy of stores in the **Replenishment hierarchy** field. These are the stores that will receive the transferred products.
    
    If you selected **Replenishment rules**, the replenishment rules determine which stores will receive the transferred products.

7.  To distribute the products only to the stores that have the products in their assortments, select the **Respect assortments** check box.

8.  Whichever distribution method you select, one transfer order is created for each store.

9.  To update quantities, click **Calculate quantities**.

10. To create the transfer orders, click **Create order**.
    
    To view the orders, select a store in the list on the **Warehouse** FastTab, and then click **Order**.

## See also

[Replenish inventory overview](replenish-inventory-overview.md)

  


