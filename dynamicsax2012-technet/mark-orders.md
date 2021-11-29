---
title: Mark orders
TOCTitle: Mark orders
ms:assetid: 6833362a-719d-4990-800a-e2964ab2ceb8
ms:mtpsurl: https://technet.microsoft.com/library/Aa571161(v=AX.60)
ms:contentKeyID: 44080991
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Mark orders 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you mark orders, you indicate that specific lots of items are the items that will be processed for the orders.

The system suggests the inventory transactions for issues and receipts that should be marked, based on the inventory dimensions that are tracked financially.

  - The **Site** dimension and the product dimensions are always tracked financially.

  - The **Warehouse**, **Batch number**, and **Serial number** dimensions can be tracked financially. In the **Storage dimension groups** and **Tracking dimension groups** forms, select the **Financial inventory** check box to financially track these dimensions.

For example, if the **Warehouse** dimension is tracked financially for a transaction, only transactions for items in the same warehouse are suggested for marking. If the **Warehouse** dimension is not tracked financially, the **Warehouse** dimension is disregarded. In this case, transactions are suggested for marking based on the **Site** dimension.

1.  Open the sales order, purchase order, transaction, production order, or inventory journal from which to mark orders.
    
      - Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. Select a sales order. On the **Action Pane**, on the **Maintain** tab, click **Edit**.
    
      - Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**. Select a purchase order. On the **Action Pane**, on the **Maintain** tab, click **Edit**.
    
      - Click **Product information management** \> **Common** \> **Released products**. Select a released product. On the **Action Pane**, on the **Manage inventory** tab, in the **View** group, click **Transactions**.
    
      - Click **Production control** \> **Common** \> **Production orders** \> **All production orders**. Select a production order. On the **Action Pane**, on the **Maintain** tab, click **Edit**.
    
      - Click **Inventory management** \> **Journals** \> **Item transactions**. Click **Movement**, **Inventory adjustment**, or **Bills of materials**, and then click **Lines** to open a journal lines form.

2.  Select a sales order line, purchase order line, inventory transaction, journal transaction, or production line.

3.  Click **Inventory** \> **Marking**.
    
    The **Marking** form lists the inventory transactions for the selected sales order line, purchase order line, inventory transaction, journal transaction, or production line.

4.  In the **Mark on** section of the form, mark transactions by using one of the following methods:
    
      - In the **Mark now** field, enter the number of items to mark.
    
      - Select the **Set mark now** check box. The **Mark now** field automatically displays the available number of items.
    
      - Click **Auto** to automatically suggest orders for marking. This option is useful if you have many order lines to mark.

5.  Click **Apply** to update the marking and keep the form open. Alternatively, click **OK** to update the marking and close the form.

## See also

[Marking (form)](https://technet.microsoft.com/library/aa575831\(v=ax.60\))

[Lot (form)](https://technet.microsoft.com/library/aa619125\(v=ax.60\))

  


