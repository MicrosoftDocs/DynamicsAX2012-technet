---
title: (BRA) Create sales delivery schedules
TOCTitle: (BRA) Create sales delivery schedules
ms:assetid: 0d4f246e-c679-4f9c-a404-888d25ca4fd8
ms:mtpsurl: https://technet.microsoft.com/library/JJ710411(v=AX.60)
ms:contentKeyID: 49384304
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Brazil
---

# (BRA) Create sales delivery schedules 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can split an order line to deliver products to a customer in several deliveries. For example, you can split an order of 1,000 pieces of material into four deliveries. You can then deliver 250 pieces every month for four months. You can keep track of multiple deliveries in one schedule that is associated with a sales order or sales quotation.

Use this procedure to create a delivery schedule to split one order line into several deliveries.

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**. Click **Sales order** to create a sales order or double-click a sales order.
    
    –or–
    
    Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. Click **Sales order** to create a sales order or double-click a sales order.
    
    –or–
    
    Click **Sales and marketing** \> **Common** \> **Sales quotations** \> **All quotations**. Click **Sales quotation** to create a sales quotation or double-click a sales quotation.

2.  In the **Sales order** or **Sales quotation** form, select the line to create a delivery schedule or click **Add line** to add a line.

3.  For sales orders, select a sales order line on the **Sales order lines** FastTab, and then click **Sales order line** \> **Delivery schedule**. For sales quotations, select a sales quotation line on the **Lines** FastTab, and then click **Sales quotation line** \> **Delivery schedule**. The details of the selected original order line are transferred to the first delivery line in the delivery schedule created in the **Delivery schedule** form.
    

    > [!NOTE]
    > <P>The Código Fiscal de Operações e Prestações (CFOP) codes and tax information are also transferred from the original order line to the delivery lines.</P>



4.  In the **Quantity** field, update the quantity for the first delivery of items.

5.  Update dates in the following fields:
    
      - **Requested receipt date** – The date that the customer requested for receipt of the items.
    
      - **Requested ship date** – The date that the customer requested for shipment of the items.
    
      - **Confirmed receipt date** – The date that you confirmed for delivery of the items.
    
      - **Confirmed ship date** – The date that you confirmed for shipment of the items.

6.  Create additional delivery lines for the delivery schedule.

7.  To check the available requested ship and receipt dates, in the **Delivery date control** field, select the method of control. In the **Available ship and receipt dates** form, select a date, and then click **Update requested ship date** to update the requested ship and receipt dates.
    

    > [!NOTE]
    > <P>To review the available confirmed receipt and ship dates, and to transfer these dates to the delivery line, click <STRONG>Simulate delivery dates</STRONG> to open the <STRONG>Available ship and receipt dates</STRONG> form. Select the date that matches your requirements, and then click <STRONG>Update requested ship date</STRONG> to update the confirmed ship and receipt dates. For more information about the simulation of delivery dates, see <A href="set-up-delivery-date-control.md">Set up delivery date control</A>.</P>



8.  If miscellaneous charges are associated with the order line, expand the **More options** node to update miscellaneous charges.

9.  In the **Charges conversion** field group, select **Copy gross amounts** to copy the fixed charges to all lines. Alternatively, select **Allocate to delivery lines** to divide the charge among the lines.
    

    > [!NOTE]
    > <P>Only fixed charges can be divided, whereas variable charges are copied to the lines.</P>



10. Click **OK** to close the **Delivery schedule** form and return to the line details.
    
    If a sales or purchase agreement is associated with the original order line, the agreement reference is automatically transferred to the delivery schedule.

## See also

[Create sales or sales quotation delivery schedules](create-sales-or-sales-quotation-delivery-schedules.md)

  


