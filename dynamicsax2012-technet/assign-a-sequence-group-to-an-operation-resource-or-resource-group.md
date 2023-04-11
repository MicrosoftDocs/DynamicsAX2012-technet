---
title: Assign a sequence group to an operation resource or resource group
TOCTitle: Assign a sequence group to an operation resource or resource group
ms:assetid: 28ef5fb5-0858-4724-8552-6d79a163caad
ms:mtpsurl: https://technet.microsoft.com/library/JJ838727(v=AX.60)
ms:contentKeyID: 50120610
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Assign a sequence group to an operation resource or resource group 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to assign a sequence group to an operation resource or a resource group. You can use the sequence group to sequence the operations that are assigned to the resource or resource groups. You can assign a sequence group to a resource group, and then assign another sequence group to a resource within that resource group. When you assign the resource group as the requirement type for an operation in the route, the sequencing of operations is performed based on the sequence group assigned to the resource group.

1.  Click **Organization administration** \> **Common** \> **Resources** \> **Resources**.
    
    –or–
    
    Click **Organization administration** \> **Common** \> **Resources** \> **Resource groups**.

2.  Select or create an operation resource or a resource group. For more information, see [Create and maintain operations resources](create-and-maintain-operations-resources.md) or [Set up and define resource groups for operations resources](set-up-and-define-resource-groups-for-operations-resources.md).

3.  Click the **General** FastTab.

4.  In the **Sequence group ID** field, select the identification code of the sequence group to assign to the operation resource or resource group.

## See also

[Create a production route for a product](create-a-production-route-for-a-product.md)

[(PM) Resources (form)](https://technet.microsoft.com/library/jj838773\(v=ax.60\))

[(PM) Resource groups (form)](https://technet.microsoft.com/library/jj838756\(v=ax.60\))

  


