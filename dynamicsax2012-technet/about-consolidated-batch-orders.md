---
title: About consolidated batch orders
TOCTitle: About consolidated batch orders
ms:assetid: 03ec075c-f667-4dbb-b0f0-5fae83e59c71
ms:mtpsurl: https://technet.microsoft.com/library/Hh352178(v=AX.60)
ms:contentKeyID: 36687809
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- bulk item conversion
- bulk orders
- consolidated batch orders
- firm batch orders
- group batch orders
- manage consolidated batch orders
- packed orders
audience: Application User
ms.search.region: Global
---

# About consolidated batch orders 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In process manufacturing, you use consolidated batch orders to group one or multiple batch orders that produce a bulk item and one or multiple packed items. A bulk item is a parent item, and a packed item is a child item. The packed items can be packaged in a single container or else in multiple containers that are considered as one unit. When you consolidate orders, you can view all of the related batch orders in a single form to help you determine any remaining work that must be completed.

A consolidated batch order can contain any combination of the following orders:

  - One or multiple bulk orders and one or multiple related packed orders. For example: a single bulk order and multiple packed orders; multiple bulk orders and multiple packed orders; or multiple bulk orders and a single packed order.

  - Only packed orders.

To manage consolidated batch orders and their associated bulk and packed orders, you use the **Consolidated batch orders** form. You can also use this form to set up consolidated orders manually. Click **Production control** \> **Common** \> **Consolidated batch orders**.

When you set up a consolidated batch order, you must convert packed formula items to their bulk items by using a specified conversion factor. To set up and run this conversion, use the **Bulk item conversion** form. Click **Inventory management** \> **Setup** \> **Formula** \> **Bulk item conversion**.

You firm and consolidate batch orders in the **Planned orders** form by using the **Firm and Consolidate** button. Click **Master planning** \> **Common** \> **Planned orders**. You can firm individual orders or multiple orders.

## See also

[Bulk item conversion (form)](https://technet.microsoft.com/library/hh209242\(v=ax.60\))

[Consolidated batch orders (form)](https://technet.microsoft.com/library/hh328731\(v=ax.60\))

[Planned orders (form)](https://technet.microsoft.com/library/aa620351\(v=ax.60\))

  


