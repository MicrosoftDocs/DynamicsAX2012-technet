---
title: About setting prices by using price groups
TOCTitle: About setting prices by using price groups
ms:assetid: 78853eb3-dc01-4bec-922f-57633f637a0f
ms:mtpsurl: https://technet.microsoft.com/library/Hh597133(v=AX.60)
ms:contentKeyID: 39519187
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About setting prices by using price groups 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

In Microsoft Dynamics AX, you can use price groups to create and manage prices and discounts for retail products. For example, you could use price groups to offer specific products at different prices to different groups of customers in different stores.

The following illustration shows the many-to-many relationship between prices and discounts, and channels, catalogs, affiliations, and loyalty programs.

![The many-to-many relationship of price groups](images/Hh597133.Retailpricegroups(AX.60).png "The many-to-many relationship of price groups")

  

The following sections describe the overall process for using price groups to manage prices and discounts.

## Step 1: Create a price group

Create a price group and give it a descriptive name. For example, if you have several stores in Chicago, you could name the price group “Chicago price group,” and then use it to link the Chicago stores with the prices and discounts that apply to them.

For more information, see [Create a price group](create-a-price-group.md).

## Step 2: Link prices or discounts to the price group

Set prices or create discounts, and then link them with the price group that you created in step 1. To continue the example, if you create a quantity discount for your stores in Chicago, in the **Quantity discounts** form, click **Price groups**, and then select “Chicago price group.”

For information about how to set prices, see [Set category-based prices](set-category-based-prices.md).

For information about how to create price adjustments and discounts, see [About price adjustments and discounts](about-price-adjustments-and-discounts.md).

## Step 3: Link channels, catalogs, affiliations, or loyalty programs to the price group

Link the price group that you created in step 1 with a channel, catalog, affiliation, or loyalty program. To finish the example, in the **Stores** form for each Chicago store, click **Price groups**, and then select “Chicago price group.”

For more information, see the following topics:

  - [Setting up retail channels](setting-up-retail-channels.md)

  - [Setting up retail product catalogs](setting-up-retail-product-catalogs.md)

  - [Set up a call center](set-up-a-call-center.md)

  - [Create call center catalogs](create-call-center-catalogs.md)

  - [Setting up affiliations](setting-up-affiliations.md)

  - [Setting up loyalty programs](setting-up-loyalty-programs.md)

## See also

[Setting up price adjustments and discounts](setting-up-price-adjustments-and-discounts.md)

[Setting up affiliations](setting-up-affiliations.md)

  


