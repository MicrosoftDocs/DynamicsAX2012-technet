---
title: View and maintain orders and statuses
TOCTitle: View and maintain orders and statuses
ms:assetid: d7a1d7c4-fe29-44e5-af36-3ea8c3f6acbe
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh271660(v=AX.60)
ms:contentKeyID: 36384292
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- CatProcureOrderList
- order status
- confirm receipt
- my orders
audience: Application User
ms.search.region: Global
---

# View and maintain orders and statuses 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **My orders** page to view and track the status of the orders that you have placed for items and services. You can view the status of the order as it is processed from a purchase request to order fulfillment and view the date on which the status was assigned to the order. After your order has been processed, you can confirm that you received the order.

The following table lists the statuses that are assigned to the order during the review process.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Order status</p></th>
<th><p>Purchase requisition or purchase order</p></th>
<th><p>Document status</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Request created</strong></p></td>
<td><p>Purchase requisition</p></td>
<td><p><strong>Draft</strong> or <strong>In review</strong></p></td>
<td><p>A purchase requisition has been created for selected items in your shopping cart. The purchase requisition may or may not have been submitted for review. If the purchase requisition has a status of <strong>Draft</strong>, you can modify the purchase requisition.</p></td>
</tr>
<tr class="even">
<td><p><strong>Request approved</strong></p></td>
<td><p>Purchase requisition</p></td>
<td><p><strong>Approved</strong> or <strong>Closed</strong></p></td>
<td><p>The review process is complete for the purchase requisition and the purchase requisition has been approved or closed. A status of <strong>Closed</strong> indicates that a purchase order has been generated for the purchase requisition.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Order created</strong></p></td>
<td><p>Purchase order</p></td>
<td><p><strong>Draft</strong> or <strong>In review</strong></p></td>
<td><p>A purchase order has been generated for the purchase requisition. The purchase order may or may not have been submitted for review.</p></td>
</tr>
<tr class="even">
<td><p><strong>Order approved</strong></p></td>
<td><p>Purchase order</p></td>
<td><p><strong>Approved</strong></p></td>
<td><p>The review process is complete for the purchase order and the purchase order is approved.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Sent to vendor</strong></p></td>
<td><p>Purchase order</p></td>
<td><p><strong>Confirm</strong></p></td>
<td><p>The purchase order has been sent to the vendor for fulfillment. If the order requires you to confirm that you received the product, a link is displayed that you can click to confirm the quantity of the products that you received.</p></td>
</tr>
<tr class="even">
<td><p><strong>Received</strong></p></td>
<td><p>Purchase order</p></td>
<td><p><strong>Received</strong></p></td>
<td><p>You have received the products that you requested.</p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>Depending on your role or the privileges that are assigned to you, you might need to go to your Employee services site before you complete the procedures in this topic.</P>



## View the status of your orders

1.  Click **Order Products** on the top link bar, and then click **My orders** on the Quick Launch.

2.  On the **My orders** page, review the list of your orders and the current status of the orders.

3.  To view the details about an order, in the **Name** column, click the order that you want to view.
    
      - For orders that have a status of **Request created** or **Request approved**, the **View purchase requisition** page opens. View the processing status for each purchase requisition line to identify which purchase requisition lines have been completely processed and which purchase requisition lines are still under review. The purchase requisition status is updated after all purchase requisition lines have completed the review process.
    
      - For orders that have a status of **Order created**, **Order approved**, **Sent to vendor**, or **Received**, the **View purchase order** page opens.

4.  If the order has a status of **Sent to vendor**, and you are required to confirm that you received the product, click the **Confirm receipt** link, and in the **Receive items** dialog box, enter the quantity of the items that you received.

5.  To reject the items or change the delivery date for the items, on the **My orders** page, click **My orders** \> **Product receipt confirmations** on the Quick Launch.

## See also

[Key tasks: Order items and services from a catalog](key-tasks-order-items-and-services-from-a-catalog.md)

[Check out products and create a purchase requisition](check-out-products-and-create-a-purchase-requisition.md)

  


