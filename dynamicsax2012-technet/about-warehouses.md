---
title: About warehouses
TOCTitle: About warehouses
ms:assetid: b5b6ac8d-761c-4d49-bd5e-41683256e14f
ms:mtpsurl: https://technet.microsoft.com/library/Aa550469(v=AX.60)
ms:contentKeyID: 36059082
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- warehouse
audience: Application User
ms.search.region: Global
---

# About warehouses 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you have several warehouses, you can divide the total on-hand inventory among these warehouses. All item transactions can be marked with warehouses, which follow the transactions throughout the system.

When you create a warehouse, you must specify a warehouse type. The types are **Default**, **Quarantine**, and **Transit**.

The warehouse is one of the inventory dimensions that is used in the inventory system. You can set up which dimensions will appear on the **Overview** tab in inventory journals, for example. In addition, you can set up the warehouse dimension individually in all forms in which the inventory dimensions are used – for example, in the **On-hand** form.

You can use warehouse levels to create a hierarchy that supports inter-warehouse transfer orders. Based on this setup, master scheduling calculates item requirements at the individual warehouse level and generates planned transfer orders from an assigned source warehouse to fulfill them. By using the warehouse-management module, you can attach warehouse-management settings to each warehouse and copy locations from one warehouse to another.


> [!NOTE]
> <P>If you have to delete a warehouse, first check that there is no on-hand inventory in the warehouse. If there is on-hand inventory in the warehouse, it must be moved to another warehouse.</P>



## See also

[Create warehouses](create-warehouses.md)

[Set up warehouses for transfer orders](set-up-warehouses-for-transfer-orders.md)

[Assign product dimensions to a product master](assign-product-dimensions-to-a-product-master.md)

[About product dimensions](about-product-dimensions.md)

  


