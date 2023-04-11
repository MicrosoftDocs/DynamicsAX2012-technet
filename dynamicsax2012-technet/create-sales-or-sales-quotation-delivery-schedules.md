---
title: Create sales or sales quotation delivery schedules
TOCTitle: Create sales delivery schedules
ms:assetid: 6533a61a-b0c7-4c19-b836-f370be7a91e7
ms:mtpsurl: https://technet.microsoft.com/library/Hh242446(v=AX.60)
ms:contentKeyID: 36057739
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- sales
- delivery schedule
- delivery schedules
audience: Application User
ms.search.region: Global
---

# Create sales or sales quotation delivery schedules 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Sometimes, you want to split up an order line, and deliver products to a customer over several months. For example, you might split an order of 1,000 pieces of material so that 250 pieces are delivered each month for four months. You can keep track of multiple deliveries in one schedule that is associated with a sales order or sales quotation.

Use this procedure to create a delivery schedule that lets you split one order line into several deliveries.

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. Click **Sales order** to create a sales order or double-click an existing sales order to open it.
    
    –or–
    
    Click **Sales and marketing** \> **Common** \> **Sales quotations** \> **All quotations**. Click **Sales quotation** to create a sales quotation or double-click an existing sales quotation to open it.

2.  In the **Sales order** or **Sales quotation** form, select the line to convert to a delivery schedule, or add a line by clicking **Add line**.

3.  For sales orders, in the **Sales order lines** list, click **Sales order line** \> **Delivery schedule**. For sales quotations, in the **Lines** list, click **Sales quotation line** \> **Delivery schedule**. The **Delivery schedule** form is displayed, and the original order line details are transferred to the first delivery line in the new delivery schedule.

4.  In the **Quantity** field, change the quantity to that of the first delivery of goods.
    
    **Example**
    
    The delivery line has a quantity of 1000 (transferred from the original order line), and the products should be delivered in four batches of 250. You change the **Quantity** field value from 1000 to 250. The **Total quantity** field displays 250, and the **Remaining quantity** field displays 750.

5.  Enter values in the following fields:
    
      - **Requested receipt date** – The requested receipt date when the customer wants to receive the goods.
    
      - **Requested ship date** – The requested ship date when the customer wants the goods to be shipped.
    
      - **Confirmed receipt date** – The confirmed receipt date when you will be able to meet the customer’s requested receipt date.
    
      - **Confirmed ship date** – The confirmed ship date when you will be able to meet the customer’s requested ship date and mode of delivery, and ship the goods to the customer.

6.  Enter all additional delivery lines, and then press CTRL+S to save the lines.
    
    **Example**
    
    You enter three more delivery lines with a quantity of 250 per line. You offset the delivery date by one month for each line. The **Total quantity** field displays 1000, and the **Remaining quantity** field displays 0.

7.  If the order line has charges associated with it, click the **Charges conversion** FastTab.

8.  On the **Charges conversion** FastTab, select **Copy gross amounts** to copy the fixed charges to all lines, or select **Allocate to delivery lines** to divide the charge among the lines.
    
    **Example: Copy gross amounts**
    
    A charge of 100.00 is associated with a regular order line, and you create a delivery schedule that has three delivery lines. 100.00 is copied to all of the lines. In total, an amount of 300.00 is allocated.
    
    **Example: Allocate to delivery lines**
    
    A charge of 100.00 is associated with a regular order line, and you create a delivery schedule that has three delivery lines. The charge will be divided among the three lines. Two lines will be allocated a charge of 33.33, and one line will be allocated a charge of 33.34.
    

    > [!NOTE]
    > <P>Only fixed charges can be divided, whereas variable charges will still be copied to the lines.</P>



9.  To automatically calculate the ship date when you select a receipt date, select the method of calculation in the **Delivery date control** field.
    

    > [!NOTE]
    > <P>To review the available receipt and ship dates and transfer them to the order again, click <STRONG>Simulate delivery dates</STRONG> and revise the dates. The <STRONG>Available ship and receipt dates</STRONG> form is displayed. In the <STRONG>Available ship and receipt dates</STRONG> form, select the date that matches your requirements, and then click <STRONG>Update requested ship date</STRONG>. For information about the simulation of delivery dates, see <A href="set-up-delivery-date-control.md">Set up delivery date control</A>. The procedure for selecting dates is the same for both requested and confirmed dates.</P>



10. Click **OK** to save the delivery schedule and return to the line details.
    

    > [!NOTE]
    > <P>If a sales agreement or purchase agreement is associated with the original order line, the agreement reference is automatically carried over to the delivery schedule.</P>

    
    When you have completed the delivery schedule, the original order line is converted to an order line with multiple deliveries on the order form. The order line with multiple deliveries is the header for the delivery lines. The header indicates that the order line has a delivery schedule attached to it. Under the order line with multiple deliveries, you can see all the individual delivery lines in the delivery schedule.

## See also

[About delivery schedules](about-delivery-schedules.md)

[Delete delivery schedules and delivery lines](delete-delivery-schedules-and-delivery-lines.md)

[Update delivery schedules](update-delivery-schedules.md)

[Delivery schedule - Sales order (form)](https://technet.microsoft.com/library/hh209246\(v=ax.60\))

[Delivery schedule - Sales quotation (form)](https://technet.microsoft.com/library/hh209450\(v=ax.60\))

  


