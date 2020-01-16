---
title: About demand consolidation
TOCTitle: About demand consolidation
ms:assetid: 7d243b18-571a-4733-b751-2239a7e2c5ae
ms:mtpsurl: https://technet.microsoft.com/library/Hh209280(v=AX.60)
ms:contentKeyID: 36058294
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- demand consolidation
- purchase requisition aggregation
- requisition consolidation
audience: Application User
ms.search.region: Global
---

# About demand consolidation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

By consolidating purchase requisition lines from multiple purchase requisitions, you can increase your negotiating power with your vendors to achieve better pricing, lower shipping and handling costs, and reduce overhead costs.

Purchase requisition lines are eligible for demand consolidation only if the following statements are true:

  - The purchase requisition has been approved.

  - The purchase requisition meets the purchasing policy rule criteria for manual processing and demand consolidation.

For information about how to set up a purchasing policy for manual purchase order processing and demand consolidation, see [Set up rules for demand consolidation and for creating purchase orders](set-up-rules-for-demand-consolidation-and-for-creating-purchase-orders.md).

Approved purchase requisition lines that meet the criteria for manual processing are listed in the **Release approved purchase requisitions** form. If the purchase requisition line also meets the criteria for demand consolidation, the line can be added to a consolidation opportunity.

A consolidation opportunity is a set of purchase requisition lines that are grouped together so that the purchasing professional can negotiate the best deal with vendors. Purchase requisition lines that you select for a consolidation opportunity appear in the **Purchase requisition consolidation** form, where you can modify the lines as necessary. You can also add new lines or remove existing lines from the consolidation opportunity.

After you add the requisition lines to the consolidation opportunity and make any changes, you can create a purchase order for the consolidated purchase requisition lines.


> [!NOTE]
> <P>Changes that you make to a purchase requisition line in the <STRONG>Purchase requisition consolidation</STRONG> form are reflected on the purchase order that you create. In the purchase requisition, the line remains unchanged so that its history is preserved.</P>



Purchase requisition lines that are not eligible for demand consolidation or that are not selected for a consolidation opportunity must be processed manually to create a purchase order.

## Consolidating purchase requisition lines

The process for demand consolidation starts at the point when a purchase requisition is approved in workflow and the budget reservations and pre-encumbrances have been recorded, if budget control is configured for your organization. The following diagram illustrates the process flow for demand consolidation.

![RequisitionAggregation\_ProcessFlow](images/Hh209280.RequisitionAggregation_ProcessFlow(AX.60).gif "RequisitionAggregation_ProcessFlow")

To consolidate approved purchase requisition lines, follow these steps:

1.  Review approved requisition lines that have been held for manual processing and that are eligible for demand consolidation.

2.  Select the lines that you want to add to a consolidation opportunity.

3.  Create a new consolidation opportunity or add requisition lines to an existing consolidation opportunity.
    
    For more information about how to create a new consolidation opportunity and how to add requisition lines to an existing consolidation opportunity, see [Key tasks: Consolidate purchase requisitions](key-tasks-consolidate-purchase-requisitions.md).

4.  Apply any changes that you want to make to the requisition lines, and remove requisition line items that you no longer want to include in the consolidation opportunity.
    
    For more information about how to modify or reject requisition lines that are included in a consolidation opportunity, see [Key tasks: Consolidate purchase requisitions](key-tasks-consolidate-purchase-requisitions.md).

5.  Create purchase orders for consolidated requisition lines or for purchase requisition lines in a consolidation opportunity.
    
    For more information about how to create a purchase order for a consolidation opportunity, see [Key tasks: Consolidate purchase requisitions](key-tasks-consolidate-purchase-requisitions.md).

## See also

[Create purchase orders manually from purchase requisitions](create-purchase-orders-manually-from-purchase-requisitions.md)

  


