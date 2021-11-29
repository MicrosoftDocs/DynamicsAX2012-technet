---
title: Update quantity on purchase orders and sales orders
TOCTitle: Update quantity on purchase orders and sales orders
ms:assetid: 7fbeaa75-2c00-4723-a21f-a3b4375b14da
ms:mtpsurl: https://technet.microsoft.com/library/Hh209299(v=AX.60)
ms:contentKeyID: 36058337
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Update quantity on purchase orders and sales orders 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use these procedures to allocate a quantity to be updated with a packing slip or a product receipt on a sales order or a purchase order.

## Update the quantity on sales orders or purchase orders

1.  For sales orders: Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    –or–
    
    For purchase orders: Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Double-click the sales order or purchase order.

3.  On the sales order, in the **Sales order lines** list, click **Add line** to add an order line, or select the order line to update the quantity on.
    
    –or–
    
    On the purchase order, in the **Purchase order lines** list, click **Add line** to add an order line, or select the order line to update the quantity on.

4.  In the **Deliver now** field for the sales order or the **Receive now** field for the purchase order, enter the quantity to update with a packing slip or product receipt. Do this for each order line that is affected.

5.  On the sales order, click the **Pick and pack** tab on the Action Pane, and then click **Packing slip**. The **Packing slip posting** form is displayed.
    
    –or–
    
    On the purchase order, click the **Receive** tab on the Action Pane. Then click **Product receipt posting**. The **Posting product receipt** form is displayed.
    

    > [!WARNING]
    > <P>If the purchase order is not confirmed, you must confirm it before you can click the <STRONG>Product receipt posting</STRONG> button. To confirm the purchase order, click <STRONG>Confirm</STRONG> on the <STRONG>Purchase</STRONG> tab on the Action Pane.</P>



6.  In the **Packing slip posting** or the **Posting product receipt** form, click the **Parameters** tab. For the sales order, select **Deliver now** in the **Quantity** field. For the purchase order, select **Receive now quantity** in the **Quantity** field. Verify that the order lines have been transferred correctly. A check mark means they are ready to be updated.

7.  Click **OK** to update the packing slip or product receipt, and return to the sales order or purchase order.
    

    > [!NOTE]
    > <P>For more information about posting, see <A href="https://technet.microsoft.com/library/aa550287(v=ax.60)">Sales posting (form)</A> or <A href="https://technet.microsoft.com/library/aa587152(v=ax.60)">Purchase posting (form)</A>.</P>



## Update the quantity on sales orders or purchase orders that have delivery schedules

1.  For sales orders: Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    –or–
    
    For purchase orders: Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Double-click the sales order or purchase order.

3.  On the sales order, in the **Sales order lines** list, click **Add line** to add an order line, or select the order line to update the quantity on.
    
    –or–
    
    On the purchase order, in the **Purchase order lines** list, click **Add line** to add an order line, or select the order line to update the quantity on.

4.  Click **Sales order line** \> **Delivery schedule** or **Purchase order line** \> **Delivery schedule** to create a sales or purchase delivery schedule, or to open the existing delivery schedule to update the quantities on.
    

    > [!NOTE]
    > <P>For information about how to create a delivery schedule, see <A href="create-sales-or-sales-quotation-delivery-schedules.md">Create sales or sales quotation delivery schedules</A> or <A href="create-purchase-delivery-schedules.md">Create purchase delivery schedules</A>.</P>



5.  In the delivery schedule, update the quantity in the **Quantity** field, and then click **OK** to save the changes and return to the sales order or purchase order.

6.  Follow steps 5 through 7 in the previous procedure to complete the quantity update with a packing slip or product receipt update.

## See also

[About delivery schedules](about-delivery-schedules.md)

  


