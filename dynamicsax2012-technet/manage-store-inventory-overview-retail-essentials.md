---
title: Manage store inventory overview (Retail essentials)
TOCTitle: Manage store inventory overview (Retail essentials)
ms:assetid: 357769dc-709a-47ba-8612-b51ed3a07e83
ms:mtpsurl: https://technet.microsoft.com/library/Dn716067(v=AX.60)
ms:contentKeyID: 62200322
author: Khairunj
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Manage store inventory overview (Retail essentials) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

The topics in this section provide information about how to create and record inventory transactions for retail stores. Information includes how to create purchase orders and transfer orders, perform stock counts, and post these documents.

[Create inventory documents for retail stores (Retail essentials)](create-inventory-documents-for-retail-stores-retail-essentials.md)

[Post completed store inventory documents (Retail essentials)](post-completed-store-inventory-documents-retail-essentials.md)

You can use the following types of documents to manage your organization's inventory.

## Purchase orders

Purchase orders are created at the head office. If a retail warehouse is included in the purchase order header, the order can be received at the store by using Retail essentials. After the quantities that are received at the store are entered, they can be saved locally for additional modification. Alternatively, the quantities can be committed and sent to the head office. At the head office, the quantities that were received at the store are displayed in Retail essentials, in the **Receive now** field on the purchase order.

## Transfer orders

A transfer order may specify that a particular store is a location that items can be shipped from. In this case, the transfer order appears at the store as a picking request in Retail essentials. After the quantities that are requested are picked, they are committed and sent to the head office. At the head office, the quantities that were picked at the store are displayed in Retail essentials, in the **Ship now** field on the transfer order.

A transfer order may specify that a particular store is a location that items can be shipped to. In this case, the transfer order appears at the store as a receiving request in Retail essentials. After the quantities that are received at the store are entered, they can be saved locally for additional modification. Alternatively, the quantities can be committed and sent to the head office. At the head office, the quantities that were received at the store are displayed in Retail essentials, in the **Receive now** field on the transfer order.

## Stock counts

Stock counts can be either scheduled or unscheduled. Scheduled stock counts are initiated at the head office, which specifies the items that must be counted. The head office creates a counting document that can be received at the store, where the quantities of actual on-hand stock are entered in Retail essentials. Unscheduled stock counts are initiated at a store, and the quantities of actual on-hand stock are updated in Retail essentials. Unlike scheduled stock counts, unscheduled stock counts do not have a predefined list of items.

When a stock count of either type is completed, it is committed and sent to the head office. At the head office, the count is validated and posted.

  


