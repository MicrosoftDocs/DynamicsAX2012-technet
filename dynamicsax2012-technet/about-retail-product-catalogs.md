---
title: About retail product catalogs
TOCTitle: About retail product catalogs
ms:assetid: 8e37d8c7-926a-4460-a2a5-6b7d2a086323
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ728697(v=AX.60)
ms:contentKeyID: 49556626
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- product catalog
- retail
- product catalogs
---

# About retail product catalogs 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use retail product catalogs to identify the products that you want to offer in your online stores. When you create the catalog, you identify the online stores that the products are offered in, add the products that you want to include, and enhance the product offerings by adding merchandising details. You can create multiple catalogs for an online store.

The following diagram illustrates the components that are included in a retail product catalog.

![Components in a retail product catalog](images/JJ728697.RetailProductCatalogComponents(AX.60).gif "Components in a retail product catalog")

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Component</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Attributes</p></td>
<td><p>Attributes contain details about the product. You can assign attributes to the retail channel or to a category. Assign attributes to the retail channel if the attributes apply to the entire channel. Assign attributes to a category if the attributes apply only to the products that are assigned to that category. Attribute values can be modified in the catalog.</p>
<p>Products that you add to the catalog inherit the attributes that you set at the channel or category level. The attributes and attribute values appear in the online store. For example, an attribute might be <strong>Color</strong>, and an attribute value might be <strong>Green</strong>.</p>
<p>You can also combine attributes into attribute groups. This makes it easier to assign multiple attributes to categories or retail channels at one time.</p></td>
</tr>
<tr class="even">
<td><p>HTML rich text</p></td>
<td><p>HTML rich text is an attribute type that you can use to add rich text details to highlight your catalog products or your retail product categories. When the catalog is published, the rich text appears in the online store.</p>
<p>For example, you can advertise a big sale or promotion and use HTML rich text to catch the shopper’s attention in the online store.</p>
<p></p></td>
</tr>
<tr class="odd">
<td><p>Images and videos</p></td>
<td><p>Images and videos are attribute types that you can use to add images or demonstration videos to your products.</p>
<p>For example, if your online store offers clothing, you can display images of the clothing in different styles or colors. If your online store offers exercise equipment, you can show a demonstration of the exercise equipment. You add images and videos by entering the URL for the location where the image and video styles are stored. You can add multiple images and demonstration videos to your products.</p></td>
</tr>
<tr class="even">
<td><p>Products</p></td>
<td><p>You select products to add to a retail product catalog from the product assortments that are assigned to the online stores. You can add products from one or more assortments. Any products that you include in the catalog must also be included in the assortments that are assigned to the online stores. Otherwise, those products cannot be published to the online store.</p></td>
</tr>
<tr class="odd">
<td><p>Product relations</p></td>
<td><p>Products that you add to the retail product catalog may be associated with other products, such as accessories or products that offer an upsell opportunity. You can include all related products in the catalog or you can select specific related products.</p></td>
</tr>
<tr class="even">
<td><p>Retail channel</p></td>
<td><p>Retail channels include brick-and-mortar stores, online stores, and online marketplaces. Retail product catalogs can be published only to online stores. Select the online stores where the products in the catalog are offered.</p>
<div class="alert">

> [!NOTE]
> <P>Before you can publish the product catalog, you must publish the online store. For more information about how to publish an online store, see <A href="set-up-an-online-store.md">Set up an online store</A>.</P>


</div></td>
</tr>
</tbody>
</table>


## Catalog process flow

Creating and processing a catalog is a four-step process. The following diagram illustrates the catalog process flow:

![Retail product catalog process flow](images/JJ728697.RetailCatalogProcess(AX.60).gif "Retail product catalog process flow")

  
After you add the catalog components to the catalog, you must validate the catalog. The validation process ensures that all the required data is included and is valid so that the publishing process can succeed. After the validation process is completed, you can view a detailed explanation for any warnings or errors that are found. Products that generate a warning cannot be published to the online store. A catalog that contains any errors cannot be published until the errors are resolved.


> [!NOTE]
> <P>You can publish a catalog that contains products that have warnings. But those products do not appear in the online store.</P>



After the catalog is validated, you must submit it to the workflow system for review and approval. After the catalog is reviewed and approved, you can publish it. You can publish the entire catalog, or you can publish only the products that have changed.

Before you publish the catalog, you must publish any online stores that are assigned to the catalog. Publishing the online store generates the online store structure, the navigation categories, and the channel attributes to a SharePoint site. Publishing the catalog generates the product listings that appear in the online store. After the catalog is published, you can view the product listings that were generated during the publishing process in the Microsoft Dynamics AX client.

You can publish a catalog manually or by using a batch process. The effective date that you defined for the catalog determines when the products are available in the online store. The expiration date that you defined for the catalog determines when the products are removed from the online store.

## See also

[Key tasks: Create retail product catalogs](key-tasks-create-retail-product-catalogs.md)

[Set up workflow for retail catalogs](set-up-workflow-for-retail-catalogs.md)

[Set up an online store](set-up-an-online-store.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

