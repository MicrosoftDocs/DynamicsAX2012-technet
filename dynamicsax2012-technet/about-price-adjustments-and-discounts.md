---
title: About price adjustments and discounts
TOCTitle: About price adjustments and discounts
ms:assetid: 7dbdf115-b5ed-447b-9ad9-43cf4865bb4b
ms:mtpsurl: https://technet.microsoft.com/library/Hh597143(v=AX.60)
ms:contentKeyID: 39519199
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About price adjustments and discounts 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

In **Retail**, you can make price adjustments to products, as well as set up discounts that are applied to a line item or a transaction at the point of sale. Both price adjustments and discounts can be linked to specific price groups. You can also specify start dates and end dates. You can delete a price adjustment or a discount. However, statistical information is lost.

Price adjustments and discounts can be applied to products, variants, or retail hierarchies. If more than one discount applies to a product, a customer may receive either one discount or a combined discount. Microsoft Dynamics AX for Retail POS automatically applies the discount or combination of discounts that gives the best price to the customer.

Before you set up a price adjustment or a discount, confirm that price groups are assigned to the correct stores. Also, if you want to automatically generate the discount ID, you can set up number sequences in the **Retail parameters** form before you define a new discount or price adjustment.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed for Microsoft Dynamics AX 2012 R2 and AX 2012 R3. See the sections later in this topic.</P>



## New or changed for Microsoft Dynamics AX 2012 R3

A new type of retail discount has been added, called a threshold discount. There are now four types of retail discounts:

  - **Simple discount** – A single percentage or amount.

  - **Quantity discount** – A discount for the purchase of one or more specific quantities.

  - **Threshold discount** – A discount for a transaction total.

  - **Mix and match discount** – A discount for purchasing a combination of products.

For more information, see [Set up a threshold discount](set-up-a-threshold-discount.md).

Both price adjustments and discounts can be associated with specific price groups, which can then be associated with channels, catalogs, affiliations, and loyalty programs. For information, see [About setting prices by using price groups](about-setting-prices-by-using-price-groups.md).

## New or changed for Microsoft Dynamics AX 2012 R2

The pricing service that provides the best price and discounts for products in Retail POS also provides the best price and discounts for products that are offered in the online store.

When a catalog is created and published, the pricing service is automatically turned on. The catalog products and their prices are published to the online store. The prices that are displayed for the products are determined by using the product trade agreements and any available price adjustments for the products. Any available discounts for the products are calculated and displayed after the product is added to the shopping cart at checkout time.

For more information about how to create a catalog for an online store, see [Key tasks: Create retail product catalogs](key-tasks-create-retail-product-catalogs.md).

When a customer views a product in the online store and adds the product to the shopping cart, the price is automatically updated to reflect any price adjustments or additional discounts. When the customer selects the product for purchase, the final price is calculated for the product.

## See also

[Setting up prices using price groups](setting-up-prices-using-price-groups.md)

[Setting up affiliations](setting-up-affiliations.md)

  


