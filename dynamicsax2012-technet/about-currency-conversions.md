---
title: About currency conversions
TOCTitle: About currency conversions
ms:assetid: 278df97a-af65-4b98-8d24-d4b833f958f5
ms:mtpsurl: https://technet.microsoft.com/library/Aa496831(v=AX.60)
ms:contentKeyID: 36056211
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About currency conversions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When the currency code on the original sales order and the intercompany purchase order differ, the following fields are currency-converted if synchronization is enabled:

  - **Unit price**

  - **Sales charges** or **Charges on purchases**

  - **Discount**

  - **Multiline discount**

These fields are then synchronized with the intercompany sales order line.

However, because the currency on the intercompany purchase order and the intercompany sales order is always synchronized, the following fields are synchronized without using currency conversion:

  - **Unit price**

  - **Sales charges** or **Charges on purchases**

  - **Discount**

  - **Discount percent**

  - **Multiline discount**

  - **Multiline discount percentage**

  


