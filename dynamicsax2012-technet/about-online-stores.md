---
title: About online stores
TOCTitle: About online stores
ms:assetid: 9006ff23-01a0-4aea-a7f6-8543ee7db676
ms:mtpsurl: https://technet.microsoft.com/library/JJ682097(v=AX.60)
ms:contentKeyID: 49655584
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- web store
- online storefront
- Webstore
audience: Application User
ms.search.region: Global
---

# About online stores 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Retail in Microsoft Dynamics AX supports multiple retail channels. These retail channels include online stores, online marketplaces, and retail stores (also called brick-and-mortar stores). Retail in Microsoft Dynamics AX 2012 R3 also supports call centers as a type of retail channel.

Online stores give an online presence to a retail store so that the store’s customers can purchase products from the retailer’s online store as well as from their brick-and-mortar stores. Customers who purchase products from the online store can have the products shipped to them, or they can pick the products up at a local retail store.

You create an online store in the Microsoft Dynamics AX client. This store represents the online store that is published to a Microsoft SharePoint site. The properties that you define for the online store in Microsoft Dynamics AX control the behavior of the online store. For example, you define the navigation category hierarchy in Microsoft Dynamics AX and assign the navigation category hierarchy to the online store. When you publish the online store to a SharePoint site, the navigation category hierarchy is displayed in the online version of the store. Shoppers use the navigation category hierarchy to browse the online store and to search for products.

For more information about how to configure and deploy the online store in SharePoint, see [Microsoft Dynamics AX for Retail](https://go.microsoft.com/fwlink/?linkid=273877).

To create the online store, you must set up the components that enable transactions to be processed for the store. This includes adding assortments, applying attributes, setting up payment methods, and setting up shipping methods. You can also define prices, promotions, discounts, trade agreements, and shipping terms that are specific to the online store.

After you publish the store to the SharePoint site, you can create retail product catalogs for the online store. The products in the catalog become product listings in the online store. When a shopper purchases products from the online store, the available inventory is updated and synchronized in the Microsoft Dynamics AX client. Also, sales orders are generated for the purchases and sent to the Microsoft Dynamics AX client for order fulfillment and processing.

**Setting up an online store**

To set up an online store, complete the following steps:

1.  Create the online store.

2.  Add the online store to the appropriate organization hierarchies.

3.  Add assortments that include the products that are available in the online store.

4.  Assign or create price groups for the online store.

5.  Set up the modes of delivery that are available for the online store.

6.  Assign the payment methods that are accepted for the online store.

7.  If you allow shoppers to order products online and then pick them up at a local store, assign store locator groups to the online store.

8.  Assign attributes for channels, products, and sales orders to the online store. Channel attributes apply to the entire online store, product attributes apply to the products that are offered in the online store, and sales order attributes apply to the sales orders that are generated from the online store.

9.  Map attributes to set the properties that determine how the attributes behave in the online channel. For example, you can set attributes to be required or searchable.

10. Publish the online store to generate the store structure on the SharePoint site.
    

    > [!IMPORTANT]
    > <P>Before you publish the online store to SharePoint, you must set up a distribution location for the online store. For more information about how to set up distribution locations for the online store, see <A href="create-distribution-locations-for-retail-databases.md">Create distribution locations for retail databases</A>.</P>



## Retail channel navigation hierarchies

Before you create an online store, you must define the retail channel navigation hierarchy that you want to use in the online store. The retail channel navigation hierarchy represents the category hierarchy that is displayed in the online store after the store is published. When you publish retail product catalogs to the online store, the products in the catalog map to the categories in the retail channel navigation hierarchy. The hierarchy is also used by shoppers to navigate in the online store.

For information about how to set up a retail channel navigation hierarchy, see [Set up a retail hierarchy](set-up-a-retail-hierarchy.md).

## Organization hierarchies

Retail uses organization hierarchies to structure retail channels. Organization hierarchies represent the relationships between the organizations that make up your business. When you set up online stores, you can add them to an organization hierarchy. The stores then share the data that is used for assortments, replenishment, and reporting.

When you create an organization hierarchy, you assign a purpose to it. The purpose indicates how the hierarchy is used in the business structure. You can create one organization hierarchy for your store operations, and use that hierarchy for assortments, replenishment, and reporting. Alternatively, you can create a separate organization hierarchy for each purpose. You can also create multiple hierarchies that have the same purpose and assign a channel to each of them.

If you intend to publish retail product catalogs to the online store, you should, at a minimum, add the online stores to an organization hierarchy for assortments. The products in a catalog are selected from the assortments that are assigned to the online store. When the catalog is published, the publishing process compares the effective dates for the assortment that is assigned to the online store with the products that are included in the catalog to determine which products to make available in the online store.

For more information about how to set up an organization hierarchy, see [Create or modify an organization hierarchy](create-or-modify-an-organization-hierarchy.md).

For more information about how to set up a retail product catalog, see [Key tasks: Create retail product catalogs](key-tasks-create-retail-product-catalogs.md)

## See also

[Set up an online store](set-up-an-online-store.md)

  


