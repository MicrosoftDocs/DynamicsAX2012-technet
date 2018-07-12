---
title: 'Key tasks: Consolidate purchase requisitions'
TOCTitle: 'Key tasks: Consolidate purchase requisitions'
ms:assetid: 7d1c7a88-9a03-48fb-9949-6207a37de651
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209279(v=AX.60)
ms:contentKeyID: 36058293
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- purchase requisition
- purchase requisitions
- consolidation
audience: Application User
ms.search.region: Global
---

# Key tasks: Consolidate purchase requisitions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

By consolidating purchase requisition lines from multiple purchase requisitions, you can increase your negotiating power with your vendors. As a result, you may be able to achieve better pricing, lower shipping and handling costs, and reduce overhead costs.

During the approval process, purchase requisitions are evaluated against purchasing rules that you define. Purchase requisitions are either automatically processed into purchase orders, or held for manual processing and demand consolidation. To consolidate purchase requisition lines, complete the following tasks:

1.  Evaluate the purchase requisition lines, and group the lines into consolidation opportunities.

2.  Update the vendor, price, requested date, or quotation data for lines items on the purchase requisition.

3.  Create purchase orders for the consolidated lines items on the purchase requisition.


> [!NOTE]
> <P>Public sector entities that use commitments to manage budget reservations cannot create purchase orders from purchase requisitions. For more information, see <A href="fra-about-commitments-public-sector.md">(FRA) About commitments (Public sector)</A>.</P>



## What do you want to do?

Learn more about...

Create a new consolidation opportunity

Add a line item on a purchase requisition to an existing consolidation opportunity

Modify a consolidation opportunity

Delete a consolidation opportunity

Close a consolidation opportunity

Create a purchase order from a consolidation opportunity

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About demand consolidation](about-demand-consolidation.md)

## Create a new consolidation opportunity

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase requisitions** \> **Release approved purchase requisitions**.

2.  On the **Action Pane**, on the **Release** tab, click **Consolidation opportunities**.

3.  In the **Purchase requisition consolidation** form, click **New**.

4.  In the **Create a new consolidation opportunity** form, follow these steps:
    
      - In the **Name** field, enter a name for the consolidation opportunity.
    
      - In the **Currency** field, enter the currency that you want to use for the consolidation lines.
    
      - In the **Targeted end date** field, enter the date that you expect to finish generating purchase orders for all purchase requisition lines in the consolidation opportunity.

5.  Click **Add to opportunity**. In the **Add to consolidation opportunity** form, select the purchase requisition lines that you want to add to the consolidation opportunity.

The line items that you selected are copied from the **Release approved purchase requisitions** page to the **Purchase requisition consolidation** form. In the **Purchase requisition consolidation** form, you can modify, reject, or process each line item in the consolidation opportunity.

Back to top

## Add a line item on a purchase requisition to an existing consolidation opportunity

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase requisitions** \> **Release approved purchase requisitions**.

2.  On the **Action Pane**, on the **Release** tab, click **Consolidation opportunities**.

3.  In the **Purchase requisition consolidation** form, select the consolidation opportunity that you want to add lines to, and then click **Add to opportunity**.

4.  In the **Add to consolidation opportunity** form, select the purchase requisition lines that you want to add to the selected consolidation opportunity.
    
    To remove a consolidation line from an existing consolidation opportunity, select the line, and then click **Remove**. On the **Release approved purchase requisitions** page, the consolidation status of the purchase requisition line is changed from **Pending consolidation** to **None**. You can then add the line to another consolidation opportunity.

Back to top

## Modify a consolidation opportunity

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase requisitions** \> **Release approved purchase requisitions**.

2.  On the **Action Pane**, on the **Release** tab, click **Consolidation opportunities**.

3.  In the **Purchase requisition consolidation** form, select the consolidation opportunity that you want to modify, select the line items that you want to modify, and then click **Edit**.

4.  In the **Bulk edit opportunity lines in opportunity** form, follow any of these steps:
    
      - To modify the requested date for the selected line items, enter a new date in the **Requested date** field.
    
      - To modify the price of the selected line items, select the **Use a new unit price** check box, and then enter a new unit price.
        

        > [!NOTE]
        > <P>The line items that you select must use the same currency. The net amount of the line items is recalculated.</P>

    
      - To modify the discount for the selected line items, select the **Use a new discount** check box. Then either select **Apply discount amount** and enter a new amount, or select **Apply discount percentage** and enter a new discount percentage. Indicate whether you want to apply the new discount instead of the current discount or in addition to the current discount.
    
      - To replace the current vendor with a new vendor for the selected line items, select a new vendor in the **Vendor account** field.
    
      - To add or modify the consolidation quotation number of the selected line items, enter a new quotation number in the **Consolidation quotation number** field. The quotation number is applied to all the line items that you selected. The quotation number is also copied to the purchase order when a purchase order is created.

5.  To apply your changes to the selected consolidation lines, click **Apply to lines**. To close the **Bulk edit opportunity lines in opportunity** form without applying your changes to the consolidation lines, click **Cancel**.

Back to top

## Delete a consolidation opportunity

Use this procedure to delete a consolidation opportunity. Only open consolidation opportunities can be deleted.

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase requisitions** \> **Release approved purchase requisitions**.

2.  On the **Action Pane**, on the **Release** tab, click **Consolidation opportunities**.

3.  In the **Purchase requisition consolidation** form, select the consolidation opportunity that you want to delete, and then click **Delete**.

4.  In the **Delete consolidation opportunity** dialog box, click **Yes**.

All line items are removed from the consolidation opportunity, the consolidation status of the purchase requisition line is cleared, and the consolidation opportunity is deleted. The line items can then be used in another consolidation opportunity.

Back to top

## Close a consolidation opportunity

Use this procedure to close a consolidation opportunity. You close a consolidation opportunity when you have completed demand consolidation for the consolidation opportunity lines and are ready to generate a purchase order for the consolidation lines. When you close the consolidation opportunity, the status of the selected opportunity is changed to **Closed**. After a consolidation opportunity is closed, you cannot add purchase requisition lines to it.

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase requisitions** \> **Release approved purchase requisitions**.

2.  On the **Action Pane**, on the **Release** tab, click **Consolidation opportunities**.

3.  In the **Purchase requisition consolidation** form, select the consolidation opportunity that you want to close, and then click **Close opportunity**.

The status of the consolidation opportunity is changed to **Closed**, the consolidation status of the consolidation opportunity is changed to **Consolidated**, and the **Create purchase order** button becomes available.

Back to top

## Create a purchase order from a consolidation opportunity

Use this procedure to create a purchase order for all the lines that are selected in the consolidation opportunity. When you create a purchase order for the consolidation lines, the purchase requisition lines are removed from the **Release approved purchase requisitions** form.


> [!NOTE]
> <P>You must close the consolidation opportunity before you can create a purchase order for the consolidation lines.</P>



1.  Click **Procurement and sourcing** \> **Common** \> **Purchase requisitions** \> **Release approved purchase requisitions**.

2.  On the **Action Pane**, on the **Release** tab, click **Consolidation opportunities**.

3.  In the **Purchase requisition consolidation** form, select the consolidation opportunity that you want to create a purchase order for, and then click **Create purchase order**.

A message is displayed to indicate that purchase orders were created for the selected consolidation opportunity. If an error occurred for any of the purchase requisition lines, the message also indicates which lines contain errors. The status of the purchase requisition lines that were processed is changed to **Closed**, and the lines are removed from the **Release approved purchase requisitions** page.

Back to top

## Find form help

[Release approved purchase requisition (form)](https://technet.microsoft.com/en-us/library/hh242658\(v=ax.60\))

[Purchase requisition consolidation (form)](https://technet.microsoft.com/en-us/library/hh227441\(v=ax.60\))

[Create consolidation opportunity (form)](https://technet.microsoft.com/en-us/library/hh209697\(v=ax.60\))

[Bulk edit opportunity lines in opportunity (form)](https://technet.microsoft.com/en-us/library/hh242459\(v=ax.60\))

[Purchase order creation and demand consolidation rule (form)](https://technet.microsoft.com/en-us/library/hh209698\(v=ax.60\))

## Find related tasks

[Create purchase orders manually from purchase requisitions](create-purchase-orders-manually-from-purchase-requisitions.md)

[Set up rules for demand consolidation and for creating purchase orders](set-up-rules-for-demand-consolidation-and-for-creating-purchase-orders.md)

  


