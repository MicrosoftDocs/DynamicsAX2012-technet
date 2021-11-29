---
title: Set up transfer order parameters
TOCTitle: Set up transfer order parameters
ms:assetid: 384333bb-782e-45c8-ae69-3a28a9b7981b
ms:mtpsurl: https://technet.microsoft.com/library/Aa570138(v=AX.60)
ms:contentKeyID: 44080968
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up transfer order parameters 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you can use the **Transfer orders** form, you must set up the parameters for transfer orders.

1.  Click **Inventory management** \> **Setup** \> **Inventory breakdown** \> **Warehouses**.

2.  Create a warehouse that has a **Transit** type.

3.  Associate the originating warehouse of the transfer order with the transit warehouse.
    

    > [!TIP]
    > <P>The originating warehouse is the warehouse that you select in the <STRONG>From warehouse</STRONG> field in the <STRONG>Transfer orders</STRONG> form.</P>



4.  Click **Inventory management** \> **Setup** \> **Inventory and warehouse management parameters**.

5.  Set up number sequences for transfer orders. For information about how to set up number sequences, see [Set up number sequences](set-up-number-sequences.md).

6.  Click **Transport**. In the **Picking route status** field, select the appropriate value:
    
      - Select **Completed** to generate orders that have a picking status of **Completed**. This option is useful if picking processes are handled by one person.
    
      - Select **Activated** to generate orders that have a picking status of **Activated**. When this option is used, the picking process must be manually activated. Additionally, the picking process must be manually completed to change the status of the orders to **Completed**.

7.  To reserve items for transfer at the warehouse that is specified as the originating warehouse, select the **Reserve items automatically** check box.
    

    > [!TIP]
    > <P>In most situations, you should select this check box. However, if you create the transfer order a long time before the actual transfer occurs, you might clear this check box so that the inventory can be used for other orders in the meantime.</P>



8.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

9.  To calculate the ship date based on the receipt date, click **Shipments**, and then select the **Delivery date control** check box.

## See also

[About delivery dates](about-delivery-dates.md)

[About warehouses](about-warehouses.md)

[Accounts receivable parameters (form)](https://technet.microsoft.com/library/aa576993\(v=ax.60\))

[Inventory and warehouse management parameters (form)](https://technet.microsoft.com/library/aa587658\(v=ax.60\))

  


