---
title: About setting up retail products
TOCTitle: About setting up retail products
ms:assetid: 997d514e-c9a7-4eb0-b522-bca615eb6965
ms:mtpsurl: https://technet.microsoft.com/library/Hh597185(v=AX.60)
ms:contentKeyID: 39519250
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About setting up retail products 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Before you can offer products for resale in your retail channels, you must create and configure the products in Microsoft Dynamics AX. Retail uses the product features in Microsoft Dynamics AX to create organization-wide products in the product master. You can create the products, define the product properties and attributes, and assign the products to retail category hierarchies. To make the products available to your retail channels and add them to an active assortment, you must release the products to the legal entities in which they are available.

## Setting up retail products

To set up the products that you sell by using retail channels, complete the following tasks:

1.  Define a retail product hierarchy. By using the category hierarchy features in Microsoft Dynamics AX, you can define retail category hierarchies to group and categorize the products that you distribute to your retail channels. User-defined and system attributes can be defined at the category level. Then, all products that are assigned to the category inherit those attributes. Multiple category hierarchies can be defined, and each product can be assigned to multiple hierarchies. However, in a single hierarchy, each product can be assigned to only one category. For more information about how to set up category hierarchies for retail products, see [Set up a retail hierarchy](set-up-a-retail-hierarchy.md).

2.  Add products and product variants to the product master. Products that are added to the product master represent a global list of products. You can add products manually, one at a time, or you can import product data from your vendors. For information about how to set up products manually, see [Key tasks: Define products](key-tasks-define-products.md). For information about how to import product data from a vendor, see [Import a product file from a vendor](import-a-product-file-from-a-vendor.md).

3.  Release the products to legal entities. Only products that have been released to legal entities can be made available to your retail channels. When you first define a product, you define it on an organization-wide level. You can then select one or more legal entities to release the product to. The product then becomes available to multiple retail channels across your organization. You can use this functionality to create a product one time, add and update product attributes and properties in one place, and then distribute the product across your organization, to the retail channels in which it is available. For more information about how to release products to legal entities, see [Key tasks: Define products](key-tasks-define-products.md).

4.  Add products to assortments. An assortment represents a collection of products that you offer in your retail channels. You can define one or more assortments, and each product can be assigned to one or more assortments. To assign products to retail channels, you assign the assortments to those retail channels. When you create an assortment, you can add products that have not yet been released to a legal entity. However, you must release the products to a legal entity before those products can be made available to the retail channels. For more information about how to set up an assortment, see [Set up an assortment](set-up-an-assortment.md).

  


