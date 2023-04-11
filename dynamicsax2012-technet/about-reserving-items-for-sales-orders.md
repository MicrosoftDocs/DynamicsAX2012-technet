---
title: About reserving items for sales orders
TOCTitle: About reserving items for sales orders
ms:assetid: 63bb9716-a782-489f-9801-7e1f56b075e5
ms:mtpsurl: https://technet.microsoft.com/library/Aa571137(v=AX.60)
ms:contentKeyID: 36057691
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- inventory reservation
- item reservation
- sales order reservation
- reserve for sales order
audience: Application User
ms.search.region: Global
---

# About reserving items for sales orders 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can reserve inventory quantities for sales orders when you create or change sales order lines. If available inventory quantities are reserved automatically, reserved inventory cannot be withdrawn from the warehouse for any other orders.

Inventory is reserved according to the setup of:

  - Manual or automatic reservation.

  - Reserved ordered items or only items on-hand.

  - Warehouse proposal.

  - Date reservation.


> [!NOTE]
> <P>The general setup and reservation rules that are valid when an order is created are valid for the order until you make manual changes to the base data of the order. For example, if automatic reservation is selected when the order is created, any changes or additions to the order lines are reserved automatically until you change the value in the <STRONG>Reservation</STRONG> field on the order line (on the <STRONG>Setup</STRONG> tab).</P>


  


