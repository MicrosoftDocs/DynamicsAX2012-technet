---
title: About direct deliveries
TOCTitle: About direct deliveries
ms:assetid: 9b9d23eb-8a9c-4beb-bd06-e1427352436b
ms:mtpsurl: https://technet.microsoft.com/library/Aa571692(v=AX.60)
ms:contentKeyID: 39519254
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- direct delivery
- drop ship
- drop shipment
- BR - 00005
- direct deliveries
- drop shipping
audience: Application User
ms.search.region: Global
---

# About direct deliveries 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create deliveries for items that are sent directly to your customer from the vendor. This type of delivery saves delivery time and inventory carrying costs, because you do not hold the products in your warehouse before you ship them to the customer.

You can create direct deliveries from the **Sales order** form. Create a sales order and order lines. Then, on the **Action Pane**, on the **Sales order** tab, select **Direct delivery**. Specify the lines that must be handled as a direct delivery. A link is now created between the sales order lines for the direct delivery and the corresponding purchase order lines. For more information, see [Create direct deliveries](create-direct-deliveries.md).


> [!NOTE]
> <P>If a portion of the ordered quantity has already been delivered, then you must split the remaining quantity. Create a new line with the quantity that needs to be directly delivered and subtract that quantity from the quantity on the original line. For example, if the original quantity was 15 and five have been delivered, you must create a new line for the remaining quantity of 10, and then reduce the original quantity by that amount.</P>



After you have created the direct delivery link between the sales order lines and the purchase order lines, you can update the sales order by using a packing slip. Run either a packing slip update or an invoice update from the purchase order. You must invoice update the sales order from the **Sales order** form. The sales order cannot be invoice updated so that it has a larger quantity than the quantity that has been registered as received. For example, a sales order line has 10 pieces, but only 5 pieces from the sales order line have been updated by using a packing slip. If you select **All** in the **Quantity** list when you invoice update the sales order, only those items that have been physically received, or updated by using a packing slip, are invoice updated. The whole sales order line is not updated.

## Delivery date

When you update the **Requested receipt date** field on the sales order line, the **Delivery date** field on the corresponding purchase order line is also updated. Similarly, when you update the **Confirmed** field on the purchase order line, the **Confirmed receipt date** and **Confirmed ship date** fields on the corresponding sales order line are also updated.

## Delivery address

Typically, the delivery address for a purchase order is the company's address. However, when you create a direct delivery, the customer's address is entered as the delivery address. If you change the delivery address on a purchase order line that has a delivery type of **Direct delivery**, the delivery address on the corresponding sales order line is also updated. Similarly, if you change the delivery address on the sales order line, the delivery address on the purchase order line is also updated.

## Deleting order lines

If you want to delete a sales order line that has a delivery type of **Direct delivery**, a message is displayed that indicates that purchase order lines are attached to the line. If the sales order line has been partially delivered, you cannot delete the sales order line or the purchase order lines that are attached to it.

## Warehouse

When you create a direct delivery, the items that you sell never physically arrive at your warehouse. However, you must still specify a warehouse on the sales order line. Similarly, picking requirements might be specified on the item model group for the item. However, because the items never physically arrive at your warehouse, these requirements are ignored when the sales order is a direct delivery.

## See also

[Create direct deliveries](create-direct-deliveries.md)

  


