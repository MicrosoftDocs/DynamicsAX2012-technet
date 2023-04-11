---
title: About sales agreements
TOCTitle: About sales agreements
ms:assetid: 987e841f-9a5c-4dc8-8620-0f84caae9619
ms:mtpsurl: https://technet.microsoft.com/library/Aa498438(v=AX.60)
ms:contentKeyID: 36058679
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- sales
- agreements
- blanket order
- sales agreement
- blanket orders
- contract
- sales contract
- contracts
- release orders
- sales contracts
audience: Application User
ms.search.region: Global
---

# About sales agreements 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A sales agreement is a contract that commits the customer to buy a product in a certain quantity or amount over time in exchange for special prices and discounts. The prices and discounts of the sales agreement overrule any prices and discounts that are stated in any trade agreements that might exist.

In the **Sales agreements** form you can create, apply, and follow up on sales agreements that exist between your organization and the customer. For example, after you create a sales agreement, you can order directly from it.

A sales agreement is valid for a period that is defined by the person who creates it. The **Requested ship date** of a sale that is specified in the **Sales order** form should be in the validity period. By default, a sales agreement is on hold. You can order from a sales agreement only when it is set to **Effective**.


> [!NOTE]
> <P>In earlier versions of Microsoft Dynamics AX, sales agreements were referred to as <STRONG>blanket sales orders</STRONG>.</P>



## Commitment types

Each line in a sales agreement expresses a commitment to sell something. There are two types of commitments:

  - Value agreement – You sell a product or sales category for a specific amount.

  - Quantity agreement – You sell a product in a specific quantity.

## Applying sales agreements in the ordering process

You can also create orders by using the **Sales order** form and applying the terms of a sales agreement. If you select a sales agreement when you create a new sales order, on the lines, you can select products and categories that are specified in the sales agreement. You can also select products and categories that are not specified in the sales agreement.

## Automatic search for sales agreements

In some of the situations in which sales orders are created indirectly, you can control whether Microsoft Dynamics AX should search automatically for applicable sales agreements. For example, when you create a credit note or intercompany sales orders.

## Financial dimensions on sales agreements

You can copy financial dimensions to document headers or to individual lines of a sales agreement. You can change the dimensions in the agreement header or agreement line at any time, and the dimensions are then automatically copied to the release header or release line of release orders.

## See also

[View purchase or sales release order lines](view-purchase-or-sales-release-order-lines.md)

[View customer invoice lines for a sales agreement](view-customer-invoice-lines-for-a-sales-agreement.md)

[View history of confirmed sales agreements](view-history-of-confirmed-sales-agreements.md)

[Print the status of a sales agreement](print-the-status-of-a-sales-agreement.md)

  


