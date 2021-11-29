---
title: About setting up assortments
TOCTitle: About setting up assortments
ms:assetid: 091c784e-ba3e-4f9b-9c36-35dea9a84784
ms:mtpsurl: https://technet.microsoft.com/library/Hh580564(v=AX.60)
ms:contentKeyID: 39519042
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About setting up assortments 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

An assortment is a collection of related products that you assign to a retail channel, such as a brick and mortar store or an online store. You use assortments to identify the products that are available in each store. An assortment can include categories of products. Therefore, all products that are assigned to a specific category are included in the assortment. An assortment can also include specific products and specific variants of products. By setting up an assortment, you can assign thousands of products to your retail channels at that same time, in any combination that your stores require.

You can set up as many product assortments as you require. Each product can be included in one or more assortments, and each assortment can be assigned to one or more retail channels. For example, you define one assortment that includes a base set of products that all stores receive. You then define another assortment that includes only large sporting equipment that only your larger stores receive.

The following diagram illustrates how products can be assigned to assortments, and how those assortments can be assigned to retail channels.

![Product assortment relationships](images/Dn716060.Assortments_relationship(AX.60).gif "Product assortment relationships")

## Prerequisites

Before you can set up an assortment and assign it to a retail channel, you must complete the following tasks.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Description</p></th>
<th><p>Related topic</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Set up a retail channel.</p></td>
<td><p>Retail channels represent a brick and mortar store, an online store, or an online marketplace. You must set up at least one retail channel and configure the options for the store. Assortments are assigned to stores to identify the products that a particular store carries.</p></td>
<td><p><a href="set-up-a-retail-store.md">Set up a retail store</a></p></td>
</tr>
<tr class="even">
<td><p>Create an organization hierarchy.</p></td>
<td><p>After you set up the retail channels for your organization, you must configure a retail organization hierarchy that represents the organizational structure of your retail channels. An organization hierarchy can be used for assortments, replenishment, and reporting.</p>
<p>By adding your retail channels to an organization hierarchy, you can assign assortments to groups of stores. Instead of assigning the assortment individually to each store, you assign the assortment to the high-level organization node. Then, whenever a new retail channel is added to the high-level organization node, that retail channel automatically inherits any assortments that were assigned to the higher-level organization node.</p>
<p>You can assign assortments only to retail channels that are included in an organization hierarchy that is assigned the <strong>Retail assortment</strong> purpose.</p></td>
<td><p><a href="create-or-modify-an-organization-hierarchy.md">Create or modify an organization hierarchy</a></p></td>
</tr>
<tr class="odd">
<td><p>Define products.</p></td>
<td><p>Before you can add products to an assortment, you must add them in Microsoft Dynamics AX. You can add products manually, or you can import them from a vendor. After you add the products, you must release them to a legal entity. Only products that have been released to a legal entity can be made available to your retail channels. Products that have not yet been released to a legal entity can be added to an assortment, and the assortment can be approved. However, until the products have been released to a legal entity, they cannot be made available to the retail channels.</p></td>
<td><p><a href="set-up-retail-products.md">Set up retail products</a></p>
<p><a href="import-a-product-file-from-a-vendor.md">Import a product file from a vendor</a></p></td>
</tr>
<tr class="even">
<td><p>Set up a category hierarchy.</p></td>
<td><p>When you create your retail products, you can group and categorize them by using the category hierarchy feature in Microsoft Dynamics AX. You can create one core hierarchy to group and categorize all products that you distribute through your retail channels. You can also create separate, supplemental category hierarchies to group or categorize your products for special purposes, such as promotions or assortments.</p>
<p>By using category hierarchies, you can assign all products in a specific category to an assortment. Any products that are added to the category that is included in the assortment are automatically included in the assortment. Then, the next time that the retail assortment scheduler is run, these products become available to the retail channels that the assortment is assigned to.</p></td>
<td><p><a href="set-up-a-retail-hierarchy.md">Set up a retail hierarchy</a></p></td>
</tr>
</tbody>
</table>


## Setting up an assortment

After you complete the prerequisites, you can create an assortment and assign it to your retail channels. To set up an assortment, you must complete the following tasks:

1.  Create a new assortment, or copy an existing assortment.

2.  Select the retail channels or the high-level groups of retail channels that the assortment applies to.

3.  Add product categories, individual products, or product variants to the assortment. You can include all products in a specific category, or exclude selected products from a category that is included in the assortment.

4.  Publish the assortment.
    
    When you publish an assortment, the retail assortment scheduler is automatically run. This process generates the list of products. When this process is completed, the products become available to the retail channels that the product assortment is assigned to. If changes are made to an assortment that has been published, or to the retail channels that the assortment is assigned to, the assortment must be updated. To update the assortment when changes are made, you can run the retail assortment scheduler as a batch job. For more information about how to configure and run the retail assortment scheduler as a separate batch job, see [Configure the retail assortments job](configure-the-retail-assortments-job.md).

## See also

[Set up an assortment](set-up-an-assortment.md)

  


