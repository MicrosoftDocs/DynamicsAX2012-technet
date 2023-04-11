---
title: About intercompany orders and return orders
TOCTitle: About intercompany orders and return orders
ms:assetid: 61c842b0-0118-4ebb-ac49-7c213ef1f702
ms:mtpsurl: https://technet.microsoft.com/library/Gg231528(v=AX.60)
ms:contentKeyID: 36057657
author: tfehr
ms.author: daxcpft
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- intercompany
- intercompany orders
- intercompany purchase order
- intercompany return order
- intercompany planning
- intercompany sales order
audience: Application User
ms.search.region: Global
---

# About intercompany orders and return orders 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how intercompany purchase orders, sales orders, return orders, purchase agreements, and sales agreements are created and updated.


> [!NOTE]
> <P>This topic includes information about features that were added or changed for Microsoft Dynamics AX 2012 R2. This information also applies to AX 2012 R3. See the section later in this topic.</P>



## About intercompany orders

When you create an intercompany sales order, Microsoft Dynamics AX creates a corresponding purchase order automatically. Similarly, creating an intercompany purchase order prompts the automatic creation of a corresponding intercompany sales order.

This is true for two-legged orders (transactions between two related companies) and for most three-legged companies (when an intercompany transaction originates with a sales order for an external customer).

## Example

You have two related companies. Company A is a sales subsidiary, and Company B is a distribution unit. Intercompany sales orders and purchase orders are created automatically in the following scenarios:

  - When Company A creates a purchase order and the vendor is Company B, an intercompany sales order is created automatically in Company B. The two-legged order chain consists of a purchase order in Company A and an intercompany sales order in Company B.

  - When Company B creates a sales order and the customer is Company A, an intercompany purchase order is created automatically in Company A. The two-legged order chain consists of a sales order in Company B and an intercompany purchase order in Company A.

  - When Company A first creates a sales order for an external customer, a purchase order can be created automatically in Company A. This, in turn prompts the automatic creation of an intercompany sales order in Company B. The three-legged order chain consists of a sales order and a purchase order in Company A and an intercompany sales order in Company B.

## About intercompany return orders

You can return intercompany items much like ordinary returns. However, with intercompany items, the return order from the external customer creates an intercompany purchase order. This, in turn, leads to the automatic creation of an intercompany sales return order. You can also return an intercompany item without an external customer return order.

Intercompany return orders, similar to regular return orders, are initiated in the **Create return order** form.

## New or changed for Microsoft Dynamics AX 2012 R2 and AX 2012 R3

In Microsoft Dynamics AX 2012 R2 and AX 2012 R3, intercompany sales and purchase agreements are automatically updated to reflect a returned item. The sales or purchase agreement commitment for that item is automatically adjusted to reflect the change in the quantity or the amount when an item is returned.

## Example

Company A creates a purchase order that is linked to a purchase agreement for an intercompany item. An intercompany sales order is automatically created in Company B that is linked to the corresponding sales agreement. The purchase agreement and the sales agreement are related as intercompany agreements.

Company A returns the intercompany item to Company B. Company B creates a return order for the item, and a purchase return order is automatically created in Company A. The commitments on both the purchase agreement and the sales agreement that are linked to the original orders are automatically adjusted to reflect the change in quantity or amount.

## See also

[Create and invoice an intercompany purchase order for internal use](create-and-invoice-an-intercompany-purchase-order-for-internal-use.md)

[Maintain intercompany sales orders](maintain-intercompany-sales-orders.md)

  


