---
title: About working with store inventory
TOCTitle: About working with store inventory
ms:assetid: 4dce671c-f6bf-49b3-91f6-1a26c32d99e8
ms:mtpsurl: https://technet.microsoft.com/library/Hh580633(v=AX.60)
ms:contentKeyID: 39519124
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- store inventory
audience: Application User
ms.search.region: Global
---

# About working with store inventory 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

You can use the following types of documents to manage your organization's inventory.

## Purchase orders

Purchase orders are created at the head office. If a retail warehouse is included in the purchase order header, the order can be received at the store by using Microsoft Dynamics AX for Retail POS. After the quantities that are received at the store are entered, they can be saved locally for additional modification. Alternatively, the quantities can be committed and sent to the head office. At the head office, the quantities that were received at the store are displayed in Microsoft Dynamics AX, in the **Receive now** field on the purchase order.

## Transfer orders

A transfer order may specify that a particular store is a location that items can be shipped from. In this case, the transfer order appears at the store as a picking request in Retail POS or Enterprise Portal for Microsoft Dynamics AX. After the quantities that are requested are picked, they are committed and sent to the head office. At the head office, the quantities that were picked at the store are displayed in Microsoft Dynamics AX, in the **Ship now** field on the transfer order.

A transfer order may specify that a particular store is a location that items can be shipped to. In this case, the transfer order appears at the store as a receiving request in Retail POS or Enterprise Portal. After the quantities that are received at the store are entered, they can be saved locally for additional modification. Alternatively, the quantities can be committed and sent to the head office. At the head office, the quantities that were received at the store are displayed in Microsoft Dynamics AX, in the **Receive now** field on the transfer order.

## Stock counts

Stock counts can be either scheduled or unscheduled. Scheduled stock counts are initiated at the head office, which specifies the items that must be counted. The head office creates a counting document that can be received at the store, where the quantities of actual on-hand stock are entered in Retail POS or Enterprise Portal. Unscheduled stock counts are initiated at a store, and the quantities of actual on-hand stock are updated in either Retail POS or Enterprise Portal. Unlike scheduled stock counts, unscheduled stock counts do not have a predefined list of items.

When a stock count of either type is completed, it is committed and sent to the head office. At the head office, the count is validated and posted.

  


