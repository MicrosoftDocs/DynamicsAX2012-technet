---
title: About mandatory inventory dimensions
TOCTitle: About mandatory inventory dimensions
ms:assetid: 4fd54dc6-bf0f-4282-bebc-96b1519657f3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg212767(v=AX.60)
ms:contentKeyID: 39519135
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- mandatory dimension
- mandatory storage and tracking dimension
- set dimensions to mandatory
---

# About mandatory inventory dimensions [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic covers the description, usage, and configuration of mandatory inventory dimensions.

## About mandatory dimensions

In Microsoft Dynamics AX 2012, you can set the **Warehouse** dimension to be mandatory for a storage dimension group. When the **Warehouse** dimension is mandatory in a storage dimension group, the dimension must be specified when you include a product on an order line. By default, the **Site** dimension is mandatory. Therefore, a value for this dimension must always be specified when you include a product on an order line.

## Benefits of using mandatory dimensions

Some of the benefits of using mandatory dimensions are as follows:

  - Mandatory dimensions guarantee that users specify dimension values on all inventory transactions.

  - Mandatory dimensions ensure the visibility of dimension values on all inventory transactions. For example, a mandatory **Warehouse** dimension enables users to track the location of inventory items.

  - The **Site** dimension guarantees that all inventory transactions are associated with a site so that master planning functions across all sites.

## Mandatory dimensions and active dimensions

By default the **Warehouse** dimension is **Active**. However, if you want to set it to **Mandatory**, the dimension will be optional. Active and mandatory dimensions are distinguished by the following:

  - If a warehouse dimension is active, the dimension value must be specified in order to handle inventory items in a physical process.

  - If a warehouse dimension is active and mandatory, the dimension value must be already specified when the product is included on a transaction line.

**Example:**

  - Product one is associated with a storage dimension group where the **Warehouse** dimension is active but not mandatory. If you include this product on a sales order line, you do not have to enter a value for the **Warehouse** dimension. If you want to adjust the on-hand quantity for the product, a value must be specified for the **Warehouse** dimension.

  - Product two is associated with a storage dimension group where the **Warehouse** dimension is active and mandatory. In this case, you must specify a value for the **Warehouse** dimension when you include the product on the sales order line.

## Configuration of mandatory dimensions

The mandatory setting varies depending on the dimension. Use the following to help you:

  - You can decide whether to set the storage dimension, **Warehouse**, to mandatory.
    
    Click **Product information management** \> **Setup** \> **Dimension groups** \> **Storage dimension groups**.

  - You cannot set the remaining storage dimensions, **Location** and **Pallet ID**, or the tracking dimensions, **Batch number** and **Serial number**, to mandatory.

When you set an inventory dimension to mandatory, the following configuration values also apply:

  - By default, the **Blank receipt allowed** check box is cleared and unavailable. This setting guarantees that you specify the mandatory dimension whenever you receive items into inventory.

  - The **Blank issue allowed** check box is cleared and unavailable by default. This setting guarantees that you specify the mandatory dimension whenever you deduct items from inventory.

## See also

[About inventory dimensions and dimension groups](about-inventory-dimensions-and-dimension-groups.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

