---
title: About registering picking lists
TOCTitle: About registering picking lists
ms:assetid: 80935187-7228-4eca-ab7a-4204242a297b
ms:mtpsurl: https://technet.microsoft.com/library/Aa571548(v=AX.60)
ms:contentKeyID: 36058347
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About registering picking lists 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Companies that use serial numbers or batch numbers to trace their items must also keep track of the serial numbers and batch numbers of picked items. The intercompany functionality automates the push/pull of serial numbers and batch numbers from one company to another. When you register the batch numbers and serial numbers for the items on an intercompany sales order, you can set up the program to push these numbers automatically to the intercompany purchase order and original sales order. You set up the relevant parameters on the **Intercompany** form for the sales order:

  - If you select the **Batch number** field on the **Sales order policies** page, the batch number is synchronized to the inventory transactions on the intercompany purchase order lines when you post the packing slip of the intercompany sales order.

  - If you select the **Serial number** field, the serial numbers are synchronized to the inventory transactions on the intercompany purchase order lines when you post the packing slip of the intercompany sales order.

  


