---
title: About setting up bar codes
TOCTitle: About setting up bar codes
ms:assetid: 2745cf12-876b-482f-8a4c-444d7dd7fda3
ms:mtpsurl: https://technet.microsoft.com/library/Hh580589(v=AX.60)
ms:contentKeyID: 39519072
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- bar code
- bar codes
audience: Application User
ms.search.region: Global
---

# About setting up bar codes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

You can use bar codes to purchase and sell products, track product variants, and set up customers and employees. You can also use bar codes to issue and endorse coupons, gift cards, and credit memos. You can set up retail products so that they have standard bar codes or custom, in-house bar codes.

Products can have more than one bar code. For example, a product may have multiple bar codes if it comes from various manufacturers, or if it has variants that are based on size, style, or color. Bar codes can include the weight or price of the product.

Bar code masks are templates that are used to create bar codes.


> [!NOTE]
> <P>By assigning a unique bar code to each variant combination, you can scan the bar code at the register and let the program determine which variant of the product is being sold. You can also collect and view statistics about sales by variant.</P>
> <P>Each size, color, and style group can be assigned a unique number that identifies that group in the bar code. Microsoft Dynamics AX uses the bar code mask to generate bar codes automatically for each variant combination. This functionality can be useful if there are many sizes, colors, and styles, because the number of combinations increases significantly as each variant code is added. If this functionality is not used, bar codes must be manually assigned to each combination that represents a product variant.</P>



You can create bar codes manually or automatically. The following topics describe the steps. Complete the steps in the order in which they are listed.

1.  [Set up bar code mask characters](set-up-bar-code-mask-characters.md)

2.  [Set up bar code masks](set-up-bar-code-masks.md)

3.  [Configure bar code setups](configure-bar-code-setups.md)

4.  [Create bar codes for products](create-bar-codes-for-products.md)

For information about how to print bar codes on labels, see [Generate and print product labels](generate-and-print-product-labels.md).

## See also

[Setting up retail products](setting-up-retail-products.md)

  


