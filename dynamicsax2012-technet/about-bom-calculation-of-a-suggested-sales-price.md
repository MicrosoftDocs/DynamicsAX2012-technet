---
title: About BOM calculation of a suggested sales price
TOCTitle: About BOM calculation of a suggested sales price
ms:assetid: 67d59744-b8b9-4753-a470-a49bb8e29a69
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg231564(v=AX.60)
ms:contentKeyID: 36057943
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About BOM calculation of a suggested sales price 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Bill of material (BOM) calculations can be used to calculate a manufactured item’s suggested sales price, based on a cost-plus markup approach. By using a cost-plus markup approach, the item’s calculated sales price reflects the set of profit-setting percentages that is specified for the BOM calculation and the costs that are associated with its component items, routing operations, and applicable manufacturing overheads. The markup reflects profit-setting percentages that are assigned to cost groups and the cost groups that are assigned to items, cost categories for routing operations, and the indirect cost calculation formulas for manufacturing overheads.

The sets of profit-setting percentages are labeled Standard, Profit 1, Profit 2, and Profit 3. Within the Profit 1 set, for example, a profit-setting percentage of 50 percent could be defined for a cost group that is assigned to purchased material, and a profit-setting percentage of 80 percent could be defined for a cost group that is assigned to cost categories for routing operations.

The context of the BOM calculation determines how the results of a calculated sales price will be handled:

  - BOM calculation for an item and specified costing version − The BOM calculation generates a pending sales price record the costing version. This sales price record provides the starting point for viewing the calculation details, such as viewing the **Calculate item cost** form. The sales price record primarily acts as reference information, and it is not used as the basis for a sales price on sales orders.

  - Order-specific BOM calculation − A variation of the BOM calculation form is used in the context of a sales order, sales quotation, or service order line item. An order-specific BOM calculation generates a calculation record that is displayed on the **BOM calculation results** form instead of a record in a costing version. This calculation record provides the starting point for viewing the calculation details, such as viewing the **Calculate item cost** form. Information about a selected calculation record can be transferred to the originating line item, such as transferring the calculated sales price to a sales order line item.

## See also

[About BOM calculations](about-bom-calculations.md)

[About costing versions containing item sales prices related to BOM calculations](about-costing-versions-containing-item-sales-prices-related-to-bom-calculations.md)

[About order-specific BOM calculations](about-order-specific-bom-calculations.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

