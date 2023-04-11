---
title: About variants
TOCTitle: About variants
ms:assetid: 5a719b98-375c-4172-a655-99d3b061b1f4
ms:mtpsurl: https://technet.microsoft.com/library/Hh597103(v=AX.60)
ms:contentKeyID: 39519151
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- variant
- variants
audience: Application User
ms.search.region: Global
---

# About variants 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

You can define a product as a *product master*. After you define a product master, you can use dimensions, such as size, color, and style, to define product variants. For example, a particular shirt might have variants that are combinations of size, color, and style.

To create a product variant, you must define at least one product dimension for a product master. You can also rename dimensions.

For more information about products and product masters, see [Key tasks: Define products](key-tasks-define-products.md). For more information about product dimensions, see [About product dimensions](about-product-dimensions.md).

After you define dimensions, you can set up variant groups. For example, a size group that is named **Men's Shoes** contains the specific sizes in which men’s shoes are available. Alternatively, a color group that is named **Television** contains the specific colors in which television sets are available, such as **Gray**, **Silver**, and **Black**.

You can assign a variant group directly to a product. However, to save time, you can assign the variant group to a category in a retail hierarchy. Then, when you assign a new product to the retail hierarchy, the variant group is assigned automatically to the product.

To create product variants, you must complete the following tasks:

1.  Set up dimensions, such as size, color, and style.

2.  Set up variant groups.

3.  Assign variant groups to a retail hierarchy.

4.  Create a product master and variants.


> [!NOTE]
> <P>If you do not set up bar codes for the variants, cashiers must enter the product master, and then select the variant. If you want cashiers to be able to enter variants directly, set up bar codes for the variants. For more information, see <A href="about-setting-up-bar-codes.md">About setting up bar codes</A>.</P>



## See also

[Key tasks: Define products](key-tasks-define-products.md)

[About product dimensions](about-product-dimensions.md)

  


