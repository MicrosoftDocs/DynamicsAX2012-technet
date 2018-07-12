---
title: About product variants
TOCTitle: About product variants
ms:assetid: fef0de51-1a49-480b-8767-2f6bc352dadb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa573452(v=AX.60)
ms:contentKeyID: 39519394
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# About product variants 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Product variants are created from product masters. You can use product variants to create variations of a product instead of creating several products that have to be maintained. Product variants could, for example, be one t-shirt in different sizes and colors. The t-shirt is the product master and the combinations of the sizes and the colors are the variants.

## Product variants and product dimensions

You create product variants based on the product dimensions that are associated with the product master. For more information about product dimensions, see [About product dimensions](about-product-dimensions.md).

## When product variants are created

You can create product variants when you create a product master or any time after that. You can also, at any time, create additional variants for a product master. For more information about how to create products and product variants, see [Key tasks: Define products](key-tasks-define-products.md).

## Identification of product variants

When you create a product variant, an identification sequence is generated from the item number of the product master and the product dimensions that are associated with the variant.

## Example

  - Item number of the product master – ABB\_01

  - Product dimensions – Configuration: ABX, Size: Small, Color: Green

The identification sequence for the variant based on the product master ABB\_01 is:

  - ABB\_01:ABX:Small:Green


> [!TIP]
> <P>The identification sequence of the product variant is displayed in the FactBox for related product variants. You can view this information in the <STRONG>Released product details</STRONG> form or on the <STRONG>Released products</STRONG> list page.</P>



## Shared and company-specific product variants

Product variants can be created for product masters at the shared level and for released product masters. Product variants that are created for a shared product master at the shared level can be released together with the product master. You can also release product variants to companies individually. However, variants can only be released to companies where the product master already exists. For more information, see “Release product variants” in [Key tasks: Release products](key-tasks-release-products.md).

## When product variants are configured

The product configuration technology that is associated with a product master controls when and how product variants are configured.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Configuration technology</strong></p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Predefined variant</strong></p></td>
<td><p>Variants are configured by using the product dimensions when the variants are created. Therefore, after you create the product master, you can assign product dimensions and create product variants.</p></td>
</tr>
<tr class="even">
<td><p><strong>Dimension-based configuration</strong></p></td>
<td><p>Variants are configured by using the <strong>Configuration</strong> dimension when the variants are added to transaction lines. The <strong>Configuration</strong> dimension must be active in the product dimension group that is associated with the product master.</p>
  
> [!TIP]
> <P>The <STRONG>Size</STRONG> and <STRONG>Color</STRONG> dimensions can also be used with this configuration technology.</P>

</td>
</tr>
<tr class="odd">
<td><p><strong>Rule-based configuration</strong></p></td>
<td><p>Variants are configured by using Product Builder when the variants are added to transaction lines.</p></td>
</tr>
<tr class="even">
<td><p><strong>Constraint-based configuration</strong></p></td>
<td><p>Variants are configured by using the Product configurator when the variants are added to transaction lines.</p></td>
</tr>
</tbody>
</table>


## See also

[About product dimensions](about-product-dimensions.md)

[Key tasks: Define products](key-tasks-define-products.md)

[Key tasks: Release products](key-tasks-release-products.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

