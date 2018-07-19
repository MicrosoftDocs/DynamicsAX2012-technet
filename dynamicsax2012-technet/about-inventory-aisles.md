---
title: About inventory aisles
TOCTitle: About inventory aisles
ms:assetid: 6a7fa1ba-7ee5-46ae-90e7-c97f2df57823
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa571177(v=AX.60)
ms:contentKeyID: 36057979
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About inventory aisles 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic applies to features in the **Inventory management** module. It does not apply to features in the [Warehouse management](warehouse-management.md) module.

An inventory aisle has an aisle identification (ID) and an aisle number, which can be the same. The aisle ID, which typically is the first part of the location name, is an alphanumeric identifier for an aisle. The letters help identify a particular warehouse or area in the warehouse.

The aisle number is a numeric identifier of the aisle in the warehouse. Use the aisle number to generate sorting codes.


> [!NOTE]
> <P>Do not add zeros as placeholders at the beginning of the aisle number.</P>



You can assign unique IDs to the inventory aisle by using the **Warehouse** and **Aisle** fields in the **Inventory aisle** form.

## Inventory location model

The following model is used for inventory locations:

  - Inventory aisles are composed of racks.

  - Racks are composed of shelves.

  - Shelves contain bins.

Together, these make up the inventory location.


> [!TIP]
> <P>To view the inventory aisles from the <STRONG>Warehouses</STRONG> form, click <STRONG>Inquiries</STRONG> &gt; <STRONG>Inventory aisles</STRONG>. To attach locations to a warehouse automatically from the <STRONG>Warehouses</STRONG> form, click <STRONG>Functions</STRONG> &gt; <STRONG>Location Wizard</STRONG>.</P>



## See also

[About locations](about-locations.md)

[Create locations](create-locations.md)

  


