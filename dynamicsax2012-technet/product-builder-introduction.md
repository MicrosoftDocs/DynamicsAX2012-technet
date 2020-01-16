---
title: Product builder introduction
TOCTitle: Product builder introduction
ms:assetid: 5c5dbf56-e04e-4b29-b535-ffed132b5932
ms:mtpsurl: https://technet.microsoft.com/library/Aa549094(v=AX.60)
ms:contentKeyID: 36057569
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Product builder
audience: Application User
ms.search.region: Global
---

# Product builder introduction 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use **Product Builder** to dynamically configure items, based on a sales order, purchase order, production order, sales quotation, project quotation, or item requirement and a set of modeling variables that are predefined for each item.

Based on a configuration—and from predefined modeling variables—**Product Builder** automatically generates standard bills of materials and standard routes for the production of each item. This simplifies the job production process and improves the interaction of sales and production.

## Item breakdown

The method that has been implemented in **Product Builder** is based on the Object Oriented Analysis. Following this method, an object description is created for each product that is configurable by using the Product Builder.

In an object description, each item is represented by the following attributes:

  - The item variables

  - The rules that govern the connections between variables and calculations

  - The conditions for selecting the item

Before a product model can be created for an item that is to be made configurable, all these parameters must be determined.

## Prerequisites

In order to realize the potential of **Product Builder**, previous experience by the user in one or more of the following areas would be valuable:

  - Sales orders, purchase orders, production orders, and sales quotations in Microsoft Dynamics AX

  - Master planning, trade, logistics, production, and bills of materials in Microsoft Dynamics AX

  - Product modeling in general

  - X++ programming in Microsoft Dynamics AX

## See also

[About Product Builder processes](about-product-builder-processes.md)

[Concepts and data flow](concepts-and-data-flow.md)

  


