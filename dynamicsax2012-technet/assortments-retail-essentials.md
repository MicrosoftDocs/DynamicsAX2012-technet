---
title: Assortments (Retail essentials)
TOCTitle: Assortments (Retail essentials)
ms:assetid: 22b2f5d7-1585-4eae-a965-4017ec4683d5
ms:mtpsurl: https://technet.microsoft.com/library/Dn716060(v=AX.60)
ms:contentKeyID: 62200325
author: Khairunj
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Assortments (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

An assortment is a collection of related products that you assign to a retail store. You use assortments to identify the products that are available in each store. If you include a category in an assortment, all products that are assigned to that category are included in the assortment. An assortment can also include specific products and specific variants of products. By setting up an assortment, you can assign thousands of products to your retail channels at that same time, in any combination that your stores require.

You can set up as many product assortments as you require. Each product can be included in one or more assortments, and each assortment can be assigned to one or more retail stores. For example, you define one assortment that includes a base set of products that all stores receive. You then define another assortment that includes large sporting equipment that only your larger stores receive.

The following diagram illustrates how products can be assigned to assortments, and how those assortments can be assigned to retail stores.

![Product assortment relationships](images/Dn716060.Assortments_relationship(AX.60).gif "Product assortment relationships")

  

The topics in this section provide information about how to set up assortments.

[Set up an assortment (Retail essentials)](set-up-an-assortment-retail-essentials.md)

[View assortment products (Retail essentials)](view-assortment-products-retail-essentials.md)

## Prerequisites

Before you can set up an assortment and assign it to a retail store, you must complete the tasks that are shown in the following table.

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
<td><p>Set up a retail store.</p></td>
<td><p>Retail stores represent a brick-and-mortar store or a warehouse. You must set up at least one retail store and configure the options for the store. Assortments are assigned to stores to identify the products that a particular store carries.</p></td>
<td><p><a href="set-up-a-retail-store-retail-essentials.md">Set up a retail store (Retail essentials)</a></p></td>
</tr>
<tr class="even">
<td><p>Create an organization hierarchy.</p></td>
<td><p>After you set up the retail stores for your organization, you must configure a retail organization hierarchy that represents the organizational structure of your retail stores. An organization hierarchy can be used for assortments, replenishment, and reporting.</p>
<p>By adding your retail stores to an organization hierarchy, you can assign assortments to groups of stores. Instead of assigning the assortment individually to each store, you assign the assortment to the high-level organization node. Then, whenever a new retail store is added to the high-level organization node, that store automatically inherits any assortments that were assigned to the higher-level organization node.</p>
<p>You can assign assortments only to retail stores that are included in an organization hierarchy that is assigned the <strong>Retail assortment</strong> purpose.</p></td>
<td><p><a href="working-with-organizations-and-organizational-hierarchies-retail-essentials.md">Working with organizations and organizational hierarchies (Retail essentials)</a></p></td>
</tr>
<tr class="odd">
<td><p>Define products.</p></td>
<td><p>Before you can add products to an assortment, you must add them to Retail essentials. After you add the products, you must release them to a legal entity. Unreleased products can be added to an assortment, and the assortment can be approved, but when the assortment is sent to the stores, the unreleased products are not included.</p></td>
<td><p><a href="set-up-retail-products-retail-essentials.md">Set up retail products (Retail essentials)</a></p></td>
</tr>
<tr class="even">
<td><p>Set up a category hierarchy.</p></td>
<td><p>When you create your retail products, you can group and categorize them by using the category hierarchy feature in Retail essentials. You can create one core hierarchy to group and categorize all products that you distribute through your stores. You can also create separate, supplemental category hierarchies to group or categorize your products for special purposes, such as promotions or assortments.</p>
<p>By using category hierarchies, you can assign all products in a specific category to an assortment. Any products that are added to the category that is included in the assortment are automatically included in the assortment. Then, the next time that the retail assortment scheduler is run, these products become available to the retail stores that the assortment is assigned to.</p></td>
<td><p><a href="set-up-a-retail-product-hierarchy-retail-essentials.md">Set up a retail product hierarchy (Retail essentials)</a></p></td>
</tr>
</tbody>
</table>


## See also

[Set up an assortment (Retail essentials)](set-up-an-assortment-retail-essentials.md)

  


