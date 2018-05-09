---
title: Create purchase delivery schedules
TOCTitle: Create purchase delivery schedules
ms:assetid: 971baf1c-400b-4cfc-b35e-bd00f52f91ba
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209412(v=AX.60)
ms:contentKeyID: 36058668
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- purchase
- procurement
- delivery schedule
- purchasing
- delivery schedules
---

# Create purchase delivery schedules 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To split up an order so that it can be delivered over a period of time, you would need to split up one order line. For example, you might split an order of 1,000 pieces of material so that 250 pieces are delivered each month for four months. You would also need to ensure that the deliveries are tracked in a schedule that is associated with the order.

Use this procedure to create a delivery schedule that allows you to split up one purchase order line into several deliveries.

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**. Click **Purchase order** to create a purchase order or double-click an existing purchase order to open it.
    
    \-or-
    
    Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. Click **Purchase order** to create a purchase order or double-click an existing purchase order to open it.

2.  In the **Purchase order** form, in the **Purchase order lines** list, select the order line to convert to a delivery schedule, or add an order line by clicking **Add line**.

3.  Click **Purchase order line** \> **Delivery schedule**. The **Delivery schedule** form is displayed, and the original order line details are transferred to the first delivery line in the new delivery schedule.

4.  In the **Quantity** field, change the quantity to that of the first delivery of goods.
    
    **Example**
    
    The delivery line has a quantity of 1000 (or what is transferred from the original order line), and the products should be delivered in four batches of 250. You change the **Quantity** field value from 1000 to 250. The **Total quantity** field displays 250, and the **Remaining quantity** field displays 750.

5.  In the **Delivery date** field, enter the date on which you expect to receive the products from the vendor.

6.  In the **Confirmed** field, enter the date on which it was confirmed that the products will be delivered.

7.  Enter all additional delivery lines, and then press CRTL+S to save the lines.
    
    **Example**
    
    You enter three more delivery lines with a quantity of 250 per line. You offset the delivery date by one month for each line. The **Total quantity** field displays 1000, and the **Remaining quantity** field displays 0.

8.  If the order line has charges associated with it, click the **Charges conversion** FastTab.

9.  On the **Charges conversion** FastTab, select **Copy gross amounts** to copy the fixed charges to all lines, or select **Allocate to delivery lines** to divide the charge among the lines.
    
    **Example: Copy gross amounts**
    
    A charge of 100.00 is associated with a purchase order line, and you create a delivery schedule that has three delivery lines. 100.00 is copied to all of the lines. In total, an amount of 300.00 will be allocated.
    
    **Example: Allocate to delivery lines**
    
    A charge of 100.00 is associated with a purchase order line, and you create a delivery schedule that has three delivery lines. The charge will be divided among the three lines. Two lines will be allocated a charge of 33.33, and one line will be allocated a charge of 33.34.
    

    > [!NOTE]
    > <P>Only fixed charges can be divided, whereas variable charges will still be copied to the lines.</P>



10. Click **OK** to save the delivery schedule and return to the purchase order.
    

    > [!NOTE]
    > <P>If a sales agreement or purchase agreement is associated with the original order line, the agreement reference is automatically carried over to the delivery schedule.</P>

    
    When you have completed the delivery schedule, the original order line is converted to an order line with multiple deliveries on the order form. The order line with multiple deliveries is the header for the delivery lines. This header indicates that the order line has a delivery schedule attached to it. Under the order line with multiple deliveries, you can see all the individual delivery lines in the delivery schedule.

## See also

[About delivery schedules](about-delivery-schedules.md)

[Delivery schedule - Purchase order (form)](https://technet.microsoft.com/en-us/library/hh227634\(v=ax.60\))

[Delete delivery schedules and delivery lines](delete-delivery-schedules-and-delivery-lines.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

