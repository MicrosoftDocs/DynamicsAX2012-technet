---
title: About item reservations for orders
TOCTitle: About item reservations for orders
ms:assetid: 0f083678-98c4-4ff7-937b-de26d072cb9b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496414(v=AX.60)
ms:contentKeyID: 36056014
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- auto reservation
- automatic reservation
- manual reservation
- reserve inventory
- reserve manually
---

# About item reservations for orders [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In the **Reservation** field in the **Accounts receivable parameters** form, you can select to reserve items automatically when you create a sales order line, or to reserve items manually on the individual order line.

If you select **Automatic**, items are always reserved automatically when you create an order line. If you select **Manual**, you must manually reserve items for the individual order line.

The method of reservation is the same for all orders and items. You cannot specify manual reservation for some items and automatic reservation for others. Likewise, you cannot specify manual reservation for some orders, customers, and locations, and automatic reservation for other orders, customers, and locations.

If you mix item types, and some are appropriate for manual reservation whereas others are appropriate for automatic reservation, you should select manual reservation.

Typically, the individual legal entity’s business structure determines whether inventory items are reserved automatically or manually. For more information, see the following recommendations.

## Automatic reservation

Automatic item reservation is recommended in the following circumstances:

  - You want to ensure that units are always reserved for orders when the order line is created, so the items are available on the delivery date.

  - Items are standard inventory items, meaning they are not produced for, adjusted to, or purchased for one specific order. Any quantity of on-hand items can be picked for an order.

  - Deliveries from vendors are uncertain, and there is no ongoing receipt of goods. You might want to ensure that the items are reserved and delivered in the same order in which the order lines are created.

  - The selection from inventory is optional, meaning you do not need to pick a specific batch and serial number for an item until the delivery date.


> [!NOTE]
> <P>Items are reserved in the same order in which the order lines are created, independent of the delivery date. This means that even though there might be items available, the items cannot be delivered because they are reserved for orders with a later delivery date.</P>
> <P>If you use process manufacturing logistics and items are FEFO controlled, automatic reservations are made for the best before date and expiration dates as follows:</P>
> <UL>
> <LI>
> <P><STRONG>Expiration date</STRONG> – Items are not reserved if the current date is the expiration date.</P>
> <LI>
> <P><STRONG>Best before date</STRONG> – Items are reserved until midnight on the best before date.</P></LI></UL>
> <P>For more information, see <A href="https://technet.microsoft.com/hh328695">(PM) Item model groups (form)</A> and <A href="https://technet.microsoft.com/en-us/library/hh227546(v=ax.60)">Best before as of date (form)</A>.</P>



## Manual reservation

Manual item reservation is recommended in the following circumstances:

  - You do not typically make item reservations when you create order lines.

  - Orders for delivery are marked manually, such as when items that are ordered by specific customers or special orders should be processed first.

  - Items are produced for, adjusted to, or purchased for specific orders. A specific unit of the on-hand item number must be picked for an order.

  - Items are not reserved in the same order in which the order lines are created.

  - A specific batch and serial number should be picked for each order.

  - A limited number of on-hand items should be split between orders that are manually selected.

## See also

[Item model groups (form)](https://technet.microsoft.com/en-us/library/aa577092\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

