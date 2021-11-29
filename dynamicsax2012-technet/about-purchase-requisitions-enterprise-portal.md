---
title: About purchase requisitions (Enterprise Portal)
TOCTitle: About purchase requisitions
ms:assetid: 5a3aefec-f67b-4d13-8d79-92ea7b7c94b0
ms:mtpsurl: https://technet.microsoft.com/library/Hh271540(v=AX.60)
ms:contentKeyID: 36384172
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About purchase requisitions (Enterprise Portal) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Depending on how your organization is set up, you can create purchase requisitions for products that your organization uses. A purchase requisition is an internal document that authorizes the purchasing department to buy items or services.

After a purchase requisition is approved, the purchase requisition can be used to create a purchase order. Purchase orders are the external documents that the purchasing department submits to vendors.


> [!NOTE]
> <P>This topic includes information about features that were added or changed for Microsoft Dynamics AX 2012 R2. This information also applies to AX 2012 R3. See the section later in this topic.</P>



## Creating purchase requisitions

You can create purchase requisitions in one of two ways in Enterprise Portal for Microsoft Dynamics AX:

  - Use Enterprise Portal to create a purchase requisition by clicking **Procurement** \> **Purchase requisitions prepared by me** \> **Purchase requisition** and adding the items and services that you need. On the **Add items** page, you can perform the following actions:
    
      - Select items from a procurement catalog that your organization has created, and add them to a requisition.
    
      - Request items that are not found in a catalog by entering the product details on the **Non-catalog items** tab, and then add them to a requisition.
    
    For more information about creating purchase requisitions in Enterprise Portal for Microsoft Dynamics AX, see [Create and maintain purchase requisitions](create-and-maintain-purchase-requisitions.md).

  - Use the Employee services site in Enterprise Portal to access the **Order products** site. On the **Order products** site, you can perform the following actions:
    
      - Browse through the procurement catalog, select the items or services that you want, and add them to your shopping cart.
    
      - Order items or services that are not found in the catalog by selecting a vendor or a procurement category. Then, enter the details for the items that you need and add them to your shopping cart.
    
      - Order items or services directly from an external vendor’s catalog, if your organization allows this. Then either check out directly from the vendor’s catalog site, or add the items to your shopping cart and check out from within Microsoft Dynamics AX.
    
    For more information about creating purchase requisitions on the Employee services site, see [Check out products and create a purchase requisition](check-out-products-and-create-a-purchase-requisition.md).

Before you can create purchase requisitions, you must enter additional information about purchase requisitions. For more information, see “Key tasks: Create and submit a purchase requisition” in the Application User Help for the Microsoft Dynamics AX client.

After a purchase requisition is created, it must be submitted for review. You use the workflow system to move a purchase requisition through the review process from an initial status of **Draft** to a final status of **Approved**. For more information about the workflow process for purchase requisitions, see [About purchase requisition workflows](about-purchase-requisition-workflows.md).

## Distributing costs to multiple financial accounts

You can distribute the cost of a product that is included in a purchase requisition to multiple financial accounts. If your organization uses dimensions, such as cost centers and departments, you can distribute the cost of a product to dimensions for financial accounts. For more information about financial dimensions, see “About dimensions” in the Application User Help for the Microsoft Dynamics AX client.

## New or changed for Microsoft Dynamics AX 2012 R2

In Microsoft Dynamics AX 2012 R2, the concept of a requisition purpose has been introduced. A requisition purpose allows for more flexibility in how requisition demand can be fulfilled. When you create a requisition, you can assign one of two purposes to it: consumption or replenishment. The default purpose is consumption. This is equivalent to a purchase requisition in earlier versions of Microsoft Dynamics AX, where the replenishment purpose was not available. Depending on the requisition purpose and how your organization is set up, requisition demand can be fulfilled by a purchase order, transfer order, production order, or kanban.

You can control the requisition purposes that are available when a requisition is created for your organization in the Microsoft Dynamics AX 2012 R2 client. For more information, see “Requisition purpose rule (form)” in the Application User Help for the Microsoft Dynamics AX 2012 R2 client.

**Requisitions that have a purpose of consumption**

A requisition that has a purpose of consumption represents a demand for items or services that will be used internally by your organization. The demand that is created by this kind of requisition is always fulfilled by a purchase order. If Microsoft Dynamics AX is set up to automatically create purchase orders, purchase orders are created after the purchase requisition is approved.

**Requisitions that have a purpose of replenishment**

A requisition that has a purpose of replenishment represents a demand to replenish inventory. For example, you may want to create a requisition to replenish items so that they can be sold at a specific retail location at a specific time. The demand can be fulfilled by a purchase order, transfer order, production order, or kanban. When the requisition purpose is replenishment, demand is expressed as a quantity instead of a monetary amount. Therefore, encumbrance accounting, budgetary control, business rules for fixed asset determination (BRAD), project accounting, and any related rules do not apply. Only products that are stocked and released to the specified legal entity can fulfill replenishment requisition demand. For more information about how to define the products that are available when the requisition purpose is replenishment, see “Replenishment category access policy rule (form)” in the Application User Help in the Microsoft Dynamics AX 2012 R2 client.

To use purchase requisitions that have a purpose of replenishment, Microsoft Dynamics AX 2012 R2 must be set up to include requisition demand in master planning. After this is set up, the fulfillment method for the demand that is created by a requisition that has a purpose of replenishment is automatically determined. It is determined by the supply policies that have been set up for the items in your organization and planned by using master planning. For more information about how to include requisition demand in master planning, see “Set up master planning for requisitions” in the Application User Help in the Microsoft Dynamics AX 2012 R2 client.

## See also

[About purchase requisition statuses](about-purchase-requisition-statuses.md)

[About purchase requisition workflows](about-purchase-requisition-workflows.md)

[Create and maintain purchase requisitions](create-and-maintain-purchase-requisitions.md)

[Check out products and create a purchase requisition](check-out-products-and-create-a-purchase-requisition.md)

  


