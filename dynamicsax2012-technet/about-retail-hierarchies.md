---
title: About retail hierarchies
TOCTitle: About retail hierarchies
ms:assetid: 772b0031-3ab4-4f4a-a0f5-4b06a304b2ef
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597132(v=AX.60)
ms:contentKeyID: 39519186
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About retail hierarchies 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

You can create a retail category hierarchy to organize the products that you sell through your retail channels. Retail product hierarchies can be used to categorize or group products. These products can then be used to create product assortments and customer loyalty programs. You can also assign product attributes and properties, assign a pricing structure, include the products in product promotions, and use the products for reporting. You can create one retail category hierarchy to represent all the products and categories in your organization, and then use that category hierarchy for multiple purposes. Alternatively, you can create multiple retail category hierarchies for special purposes, such as product promotions.

When you create a retail product hierarchy, you must assign a category hierarchy type to identify the purpose of the category hierarchy. For example, only product hierarchies that are assigned the **Retail vendor product hierarchy** type are referenced when you import product data from retail vendors.


> [!NOTE]
> <P>This topic includes information about features that were added or changed for Microsoft Dynamics AX 2012 R2. This information also applies to AX 2012 R3. See the section later in this topic.</P>



## Retail hierarchy types

The following table lists the types of retail category hierarchies that are available, and the general purpose of each type.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category hierarchy type</p></th>
<th><p>Purpose</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Retail product hierarchy</strong></p></td>
<td><p>Use this hierarchy type to define the overall product hierarchy for your organization. You can use this hierarchy type for merchandising, pricing and promotions, reporting, and assortment planning. Only one retail product hierarchy can be assigned this hierarchy type.</p></td>
</tr>
<tr class="even">
<td><p><strong>Supplemental retail hierarchy</strong></p></td>
<td><p>Use this hierarchy type for any additional retail category hierarchies that you want to create. For example, in the spring, you have a promotion for swimwear. Therefore, you include your swimwear products in a separate category hierarchy and apply the promotional pricing to the various product categories.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Retail vendor product hierarchy</strong></p></td>
<td><p>Use this hierarchy type when you import product data from vendors. You can create a product category hierarchy for a vendor, and then map the product categories for the vendor to your retail product categories.</p></td>
</tr>
<tr class="even">
<td><p><strong>Retail channel navigation hierarchy</strong></p></td>
<td><p>Create a retail channel navigation category hierarchy to set up a category structure for products that you offer through an online store. You define the category hierarchy and assign products, product attribute groups, and attribute values to the categories. Then assign the category hierarchy to an online store.</p>
<div class="alert"> 

> [!NOTE]
> <P>This control is available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed.</P>


</div></td>
</tr>
</tbody>
</table>


By using a retail category hierarchy to structure your products, you can set up and maintain product attributes and properties at the category level. These attributes and properties include settings for product dimensions and point of sale (POS) settings. Any products that you assign to the categories automatically inherit the attributes and properties that you define. You can also copy the property settings for any product to multiple products in a selected category at the same time.

Retail category hierarchies use the category hierarchy features in Microsoft Dynamics AX. For general information about how to use category hierarchies, see [About category hierarchies](about-category-hierarchies.md).

## New or changed for Microsoft Dynamics AX 2012 R2

A retail channel navigation hierarchy is required to create the product navigation structure that is used in the online store. You must create the navigation hierarchy, assign it to a retail channel navigation hierarchy type, and then assign it to the online store. When the online store is published, the category structure that is defined in the retail channel navigation hierarchy is displayed in the online store. You can maintain the online store navigation structure through the retail channel navigation hierarchy in Microsoft Dynamics AX. Any changes that you make are updated when you republish the online store to the Microsoft SharePoint Server 2013 site.

For more information about how to set up an online store, see [Set up an online store](set-up-an-online-store.md).

## See also

[Set up a retail hierarchy](set-up-a-retail-hierarchy.md)

[Retail product hierarchy (form)](https://technet.microsoft.com/en-us/library/hh597208\(v=ax.60\))

[Supplemental retail hierarchies (form)](https://technet.microsoft.com/en-us/library/hh597337\(v=ax.60\))

[Set up a retail vendor hierarchy](set-up-a-retail-vendor-hierarchy.md)

  


