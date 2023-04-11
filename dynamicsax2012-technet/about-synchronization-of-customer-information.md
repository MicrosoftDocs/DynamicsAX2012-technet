---
title: About synchronization of customer information
TOCTitle: About synchronization of customer information
ms:assetid: c58145ef-e77d-4e56-b974-fa91bc747d2b
ms:mtpsurl: https://technet.microsoft.com/library/Aa550753(v=AX.60)
ms:contentKeyID: 36059300
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About synchronization of customer information 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Customer information is synchronized if the **Customer information** field is enabled when the sales order is created or a change is made to the customer, vendor reference, or customer requisition number.

You can always change the value in these synchronization fields. However, you can only determine whether this value is copied to the other intercompany orders by selecting this parameter. If you have enabled the **Customer information** field on the intercompany sales order, a change to the intercompany sales order is synchronized to the intercompany purchase order. If you have also enabled the **Customer information** field on the intercompany purchase order, it is also synchronized back to the original sales order.


> [!NOTE]
> <P>If you have enabled the <STRONG>Customer information</STRONG> field on both the intercompany purchase order and the intercompany sales order, updates that are made by one person in one company are overruled by updates that are made by another person in another company on the same order.</P>
> <P></P>



The best practice is to enable the **Customer information** field on the intercompany purchase order. This enables synchronization between the original sales order and the intercompany purchase order and from the intercompany purchase order to the intercompany sales order.

  


