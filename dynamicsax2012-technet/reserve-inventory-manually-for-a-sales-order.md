---
title: Reserve inventory manually for a sales order
TOCTitle: Reserve inventory manually for a sales order
ms:assetid: b34ab742-b096-41a0-a3c8-da9383432954
ms:mtpsurl: https://technet.microsoft.com/library/Aa571910(v=AX.60)
ms:contentKeyID: 44081029
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Reserve inventory manually for a sales order 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic applies to features in the **Inventory management** module. It does not apply to features in the [Warehouse management](warehouse-management.md) module.

When you reserve inventory manually, the reservation uses the following settings:

  - To consider the date of receipt of items when the items are reserved, select the **Date-controlled** check box in the **Item model groups** form. For more information, see [Set up date-controlled reservations](set-up-date-controlled-reservations.md).

  - If a warehouse is specified for the customer, the inventory is delivered from that warehouse.

To reserve inventory manually for a sales order, follow these steps.

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**. In the **General** area, in the **Reservation** field, select **Manual**.
    
    –or–
    
    Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. Double-click a sales order. On the **Action Pane**, in the **Show** group, click **Headier view**. On the **Setup** tab, in the **Reservation** field, select **Manual**.

2.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

3.  Depending on the method that you used to set the reservation to **Manual**, select any sales order, or select the sales order for which you selected manual reservation.

4.  Double-click the sales order. On the **Action Pane**, in the **Show** group, click **Line view**, and then click **Add line**.

5.  Enter an item quantity and other relevant information on the line.

6.  In the **Sales order lines** grid, click **Inventory** \> **Reservation**.

7.  To change inventory reservations on items that are not delivered, repeat steps 5 and 6.

8.  Select the warehouses from which inventory should be reserved. Then, in the **Reservation** field, enter the quantity to reserve.
    

    > [!NOTE]
    > <P>You cannot reserve more than the quantity that is entered on the sales order line.</P>
    > <P>If you increase the quantity on the sales order line, the reserved quantity is not changed accordingly. You must reserve the extra quantity manually. If you decrease the quantity on the sales order line, and the new quantity is less than the existing reserved quantity, the reserved quantity is decreased accordingly.</P>



## See also

[Set up manual or automatic inventory reservations](set-up-manual-or-automatic-inventory-reservations.md)

[Set up date-controlled reservations](set-up-date-controlled-reservations.md)

[Set up warehouse reservations](set-up-warehouse-reservations.md)

  


