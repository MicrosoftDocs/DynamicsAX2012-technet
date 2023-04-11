---
title: Return an item ordered from a sales agreement
TOCTitle: Return an item ordered from a sales agreement
ms:assetid: 27056300-0566-453e-9a7f-40c0aa439f52
ms:mtpsurl: https://technet.microsoft.com/library/JJ683225(v=AX.60)
ms:contentKeyID: 49684847
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Return an item ordered from a sales agreement 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to return a product that has been ordered from a sales agreement between your organization and its customer.

When a customer returns a product that has been ordered from a sales agreement, Microsoft Dynamics AX can find and automatically update the related sales agreement commitment to reflect the change in quantity or amount. By creating a return order based on the original sales order that is linked to a sales agreement, you establish a relation between the sales agreement commitment, the sales order line, and the return order invoice.


> [!NOTE]
> <P>A return order can be linked to only one sales agreement. If your customer returns more than one product that has been ordered from more than one sales agreement, you must create a new return order for each product and create a link to the corresponding sales agreement.</P>



1.  Click Click **Sales and marketing** \> **Common** \> **Return orders** \> **All return orders**.

2.  Click **Return order** to create a new return order.

3.  On the Action Pane, click **Find sales order** to open the **Find sales order** form and view the sales orders that have been created for the specified customer account.

4.  Use the available search criteria to find the invoiced sales order for the returned product, or select the invoiced sales order in the list on the **Invoice** tab.

5.  In the lower pane, you can view the sales order lines for the selected sales order. Select the line that contains the returned item and update the quantity to be returned in the **Quantity to return** field. Click **OK**. A new return order line is created, and the related sales agreement commitment is updated.

Returned items represent a negative quantity. Therefore, when the related sales agreement is updated to reflect returned items, the quantity or amount on the sales agreement commitment can have a negative value.

If you do not want to deduct the returned item quantity from the sales agreement commitment, you can use the **Remove link** control in the **Return order - RMA number: %1, %2** form to remove the link between the return order and the sales agreement commitment. If needed, you can click **Create link** to establish the link again.

## See also

[Return orders (form)](https://technet.microsoft.com/library/hh803010\(v=ax.60\))

[About sales agreements](about-sales-agreements.md)

[Create an item replacement order](create-an-item-replacement-order.md)

[About intercompany orders and return orders](about-intercompany-orders-and-return-orders.md)

  


