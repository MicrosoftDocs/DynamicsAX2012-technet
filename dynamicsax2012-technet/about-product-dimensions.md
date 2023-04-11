---
title: About product dimensions
TOCTitle: About product dimensions
ms:assetid: d5f35982-32f0-40a9-a6e1-4d5505d79be2
ms:mtpsurl: https://technet.microsoft.com/library/Aa499382(v=AX.60)
ms:contentKeyID: 36059532
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- products
- product dimension
audience: Application User
ms.search.region: Global
---

# About product dimensions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Product dimensions are characteristics that serve to identify a product variant. You can use combinations of product dimensions to define product variants. You must define at least one product dimension for a product master in order to create a product variant. For more information about products and product masters, see [Key tasks: Define products](key-tasks-define-products.md).


> [!TIP]
> <P>Product variants are also referred to as items. An item is a tangible product, which is not the same as a service. However, in Microsoft Dynamics AX 2012 it is also possible to define a product master with the <STRONG>Service</STRONG> type. By using the <STRONG>Service</STRONG> type, you can specify product variants that include services. For example, you can specify a product master for Consultancy work and product variants for work that is performed by senior consultants and junior consultants.</P>



The following product dimensions are available: **Configuration**, **Color**, **Size**, and **Style**. If you want to use the **Size** and **Color** product dimensions for different purposes, you can rename these dimensions. For more information, see [Rename product dimensions](rename-product-dimensions.md).

The names of product variants are based on product dimension values. To display the product variant names in a translated version on an external source document, such as an invoice, you can translate the product variant names into the language of the customer. For more information, see [Translations of product-related information](translations-of-product-related-information.md).

Product dimensions are created and maintained in the **Product dimensions** form, which can be accessed from the following locations:

  - Click **Product information management** \> **Common** \> **Products** \> **Product masters**. On the **Action Pane**, in the **Product master** group, click **Product dimensions**.

  - Click **Product information management** \> **Common** \> **Products** \> **All products and product masters**. Select a product master. On the **Action Pane**, in the **Product master** group, click **Product dimensions**.

  - Click **Product information management** \> **Common** \> **Released products**. Select a product master. On the **Action Pane**, in the **Product master** group, click **Product dimensions**.

The number of variants that you can create for an item is limited by the number of possible product dimension combinations.


> [!TIP]
> <P>When you use a product on, for example, an order line, you select the product dimensions to define the product variant that you want to work with.</P>



## Example

A company sells denim jeans. The item, Jeans, uses the **Color** and **Size** product dimensions. The jeans are sold in three different colors and six different sizes.

Colors: Blue, Black, Brown

Sizes: XS, S, M, L, XL, XXL

Not all sizes are available in all the three colors. If all combinations were available, it would create 18 different types of jeans. In this example, only the following nine product variant combinations are produced.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Color</p></th>
<th><p>Size</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Blue</p></td>
<td><p>XS</p></td>
</tr>
<tr class="even">
<td><p>Blue</p></td>
<td><p>S</p></td>
</tr>
<tr class="odd">
<td><p>Blue</p></td>
<td><p>M</p></td>
</tr>
<tr class="even">
<td><p>Black</p></td>
<td><p>M</p></td>
</tr>
<tr class="odd">
<td><p>Black</p></td>
<td><p>L</p></td>
</tr>
<tr class="even">
<td><p>Black</p></td>
<td><p>XL</p></td>
</tr>
<tr class="odd">
<td><p>Brown</p></td>
<td><p>L</p></td>
</tr>
<tr class="even">
<td><p>Brown</p></td>
<td><p>XL</p></td>
</tr>
<tr class="odd">
<td><p>Brown</p></td>
<td><p>XXL</p></td>
</tr>
</tbody>
</table>


## See also

[Assign product dimensions to a product master](assign-product-dimensions-to-a-product-master.md)

[Key tasks: Define products](key-tasks-define-products.md)

[Key tasks: Release products](key-tasks-release-products.md)

  


