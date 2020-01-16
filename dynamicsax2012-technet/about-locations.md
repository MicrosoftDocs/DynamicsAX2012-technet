---
title: About locations
TOCTitle: About locations
ms:assetid: 19894f01-36a1-46b4-a2d2-b401473eef61
ms:mtpsurl: https://technet.microsoft.com/library/Aa569916(v=AX.60)
ms:contentKeyID: 36056113
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- location
- warehouse location
audience: Application User
ms.search.region: Global
---

# About locations 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic applies to features in the **Inventory management** module. It does not apply to features in the [Warehouse management](warehouse-management.md) module.

The term location refers to the place that items are drawn from.

For each location, the place where the item is inserted can also be specified. By default, they are the same. Items are usually inserted and drawn from the same side of a location, but not always. For example, items that are stored in live storage racks are inserted from one aisle and drawn from another.

The main input is given by a location name, which is usually determined by its coordinates: warehouse, aisle, rack, shelf, and bin. This name or ID can be entered manually or generated from the location coordinates—for example, 001-002-03-4 for aisle 1, rack 2, shelf 3, bin 4 in the **Inventory locations** form.


> [!NOTE]
> <P>You can automatically attach locations to a warehouse. In the <STRONG>Inventory locations</STRONG> form, click <STRONG>Functions</STRONG>, and then select <STRONG>Location Wizard</STRONG>.</P>



## Location properties

A location has the following characteristics:

  - Size (number of pallets, height, width, and depth)

  - Pallet type group

  - Storage area

  - Picking area

  - Location type (inbound dock, outbound dock, pick location, or bulk location)

Check text can be used in online systems to verify that the operator has selected the correct location for a specific item. This check text can be created manually or by default.

## Sort codes

Use sort codes to optimize the handling of picking lines, which describe the information that is required for picking items from inventory, including the picking order. Sort codes can be specified by the aisle and other coordinates, or assigned manually for the location.

## Blocked locations

Occasionally, you must block a location for a period of time, for example, to allow for repairs. At other times, you may want to block only the input or the output. It is possible to block either or both of these.

## Location types

The following location types are used in Microsoft Dynamics AX:

  - **Bulk location** – The area in the warehouse where received items are stored until they are transported to picking locations. Bulk locations are used to replenish picking locations as their stock decreases, and to pick full pallets.

  - **Picking location** – The area where items are stored until they are picked for shipment. They are kept here to guarantee that they can be easily picked. The picking location is used for picking small quantities of an item. An item can have only one picking location in each warehouse.

  - **Inbound dock** – The locations in the warehouse where goods are received.

  - **Outbound dock** – The locations in the warehouse where goods are shipped from.

## Location placement

Location placement can be categorized in terms of input areas and picking areas.

## Input areas

Input areas are areas in the warehouse that are designated for item placement upon receipt. Items are grouped based on similar characteristics or the order in which they are placed in their locations. For example, items that require cold storage would be in one input area, and items that can be stored in the general warehouse storage area would be in another.

## Picking areas

Picking areas are assigned throughout a warehouse to group items that should be picked at the same time or by the same person. For example, items that require a forklift for picking and transport would be in one picking area, and items that can be picked individually from floor level by a person with a hand truck would be in another.

## Tree structure tab

In the **Inventory locations** form, you can view a graphical representation of the locations. Locations appear in a tree structure based on their coordinates. The tree structure can also be used to find a specific location.

To define the setup of the tree structure, click **Setup \>\>**, and then select the data to be displayed. Select the **Summation** check box to view the number of locations in underlying levels of the tree, such as the number of racks in an aisle or the number of shelves on a rack.

## Related tasks

[Create locations](create-locations.md)

## See also

[About inventory aisles](about-inventory-aisles.md)

  


