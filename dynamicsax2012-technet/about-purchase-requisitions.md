---
title: About purchase requisitions
TOCTitle: About purchase requisitions
ms:assetid: 3609683f-4642-428d-ae62-c5a577b1dac6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg231099(v=AX.60)
ms:contentKeyID: 36056577
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- purchase
- procurement
- purchase requisition
- purchase requisitions
- requisitions
- requisition
- purchases
audience: Application User
ms.search.region: Global
---

# About purchase requisitions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Depending on how your organization is set up, you can create purchase requisitions for products that your organization uses. A purchase requisition is an internal document that authorizes the purchasing department to buy items or services.

After a purchase requisition is approved, it can be used to create the purchase order. Purchase orders are the external documents that the purchasing department submits to vendors.


> [!NOTE]
> <P>Public sector entities that use commitments to manage budget reservations cannot create purchase orders from purchase requisitions. For more information, see <A href="fra-about-commitments-public-sector.md">(FRA) About commitments (Public sector)</A>.</P>




> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed for Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3. For more information, see the sections later in this topic.</P>



## Using workflow

Before a purchase requisition can be submitted for review, workflow must be configured in the Microsoft Dynamics AX client. You use workflow to move a purchase requisition through the review process, from an initial status of **Draft** to a final status of **Approved**. For more information about the purchase requisition workflow process, see [Overview of a purchase requisition workflow](overview-of-a-purchase-requisition-workflow.md).

## Creating purchase requisitions

Before you can create purchase requisitions, you must enter additional information about purchase requisitions. For more information, see [Key tasks: Create and submit a purchase requisition](key-tasks-create-and-submit-a-purchase-requisition.md).

You can create purchase requisitions in one of three ways:

  - Use the Microsoft Dynamics AX client to create a purchase requisition and select the items and services that you need. You can select items from a procurement catalog that your organization has created, or you can request items that are not found in a catalog, by entering the product details in the **Add items** form on the **Non-catalog items** tab. For more information about how to create a purchase requisition in the Microsoft Dynamics AX client, see [Key tasks: Create and submit a purchase requisition](key-tasks-create-and-submit-a-purchase-requisition.md).

  - Use Enterprise Portal for Microsoft Dynamics AX to create a purchase requisition and add the items and services that you need. You can select items from a procurement catalog that your organization has created, or you can request items that are not found in a catalog, by entering the product details on the **Add items** page, **Non-catalog items** tab. For more information about how to use Enterprise Portal, click the **Help** button on any page in Enterprise Portal for Microsoft Dynamics AX.

  - Use the Employee services site in Enterprise Portal to access the **Order products** site. You can browse the procurement catalog, select the items and services that you want, and add them to your shopping cart. You can also order items or services that are not found in the catalog, or you can order directly from an external vendor’s catalog if your organization allows this. For more information about how to use Enterprise Portal, click the Help button on any page in Enterprise Portal for Microsoft Dynamics AX.


> [!NOTE]
> <P>Purchase requisitions can also be imported into Microsoft Dynamics AX from a third-party application by using the <STRONG>PurchReqImportService</STRONG> document service. Importing documents by using services requires a system administrator to configure an integration port that can receive the incoming documents. For more information about how to import documents into Microsoft Dynamics AX by using services, see <A href="services-and-application-integration-framework-aif.md">Services and Application Integration Framework (AIF)</A>.</P>



## Distributing costs to multiple financial accounts

You can distribute the cost of a product that is included in a purchase requisition to multiple financial accounts. If your organization uses dimensions, such as cost centers and departments, you can distribute the cost of a product to dimensions for financial accounts.

## New or changed for Microsoft Dynamics AX 2012 R2

In Microsoft Dynamics AX 2012 R2, the concept of a requisition purpose was introduced. A requisition purpose allows for more flexibility in how requisition demand can be fulfilled. When you create a requisition in AX 2012 R2 or AX 2012 R3, you can assign one of two purposes to it: consumption or replenishment. The default purpose is consumption. This is equivalent to a purchase requisition in earlier versions of Microsoft Dynamics AX, where the replenishment purpose was not available. Depending on the requisition purpose and how your organization is set up, requisition demand can be fulfilled by a purchase order, transfer order, production order, or kanban.

You can control the requisition purposes that are available when a requisition is created for your organization. For more information, see [Requisition purpose rule (form)](https://technet.microsoft.com/en-us/library/jj677434\(v=ax.60\)).

**Requisitions that have a purpose of consumption**

A requisition that has a purpose of consumption represents a demand for items or services that will be used internally by your organization. The demand that is created by this kind of requisition is always fulfilled by a purchase order. If Microsoft Dynamics AX is set up to automatically create purchase orders, purchase orders are created after the purchase requisition is approved. In AX 2012 R2 and AX 2012 R3, requisitions that are imported from a third-party application by using the **PurchReqImportService** document service automatically have a purpose of consumption.

**Requisitions that have a purpose of replenishment**

A requisition that has a purpose of replenishment represents a demand to replenish inventory. For example, you might create a requisition to replenish items so that they can be sold at a specific retail location at a specific time. The demand can be fulfilled by a purchase order, transfer order, production order, or kanban. When the requisition purpose is replenishment, demand is expressed as a quantity instead of a monetary amount. Therefore, encumbrance accounting, budgetary control, business rules for fixed asset determination (BRAD), project accounting, and any related rules do not apply. Only products that are stocked and released to the specified legal entity can fulfill replenishment requisition demand. For more information about how to define the products that are available when the requisition purpose is replenishment, see [Replenishment category access policy rule (form)](https://technet.microsoft.com/en-us/library/jj677448\(v=ax.60\)).

To use purchase requisitions that have a purpose of replenishment, Microsoft Dynamics AX 2012 R2 must be set up to include requisition demand in master scheduling. After this is set up, the fulfillment method for the demand that is created by a requisition that has a purpose of replenishment is automatically determined. The method is determined by the supply policies that have been set up for the items in your organization and planned by using master scheduling. For more information about how to include requisition demand in master plans, see [Set up master plans to include requisitions](set-up-master-plans-to-include-requisitions.md).

## New or changed in eProcurement in Microsoft Dynamics AX 2012 R3

You can place a purchase requisition on hold, by selecting the **On hold** check box on the **Purchase requisition details** form. This prevents further processing of the requisition until you clear the check box.

Note that because in eProcurement the RFQ for your purchase requisition may allow vendors to add alternate lines, approved alternates will end up reflected in your purchase requisition.

## See also

[Key tasks: Create and submit a purchase requisition](key-tasks-create-and-submit-a-purchase-requisition.md)

[About statuses for purchase requisitions](about-statuses-for-purchase-requisitions.md)

[Overview of a purchase requisition workflow](overview-of-a-purchase-requisition-workflow.md)

  


