---
title: About linking BOM lines to route operations
TOCTitle: About linking BOM lines to route operations
ms:assetid: 699501c8-135d-4c6f-9f70-7c158f58767c
ms:mtpsurl: https://technet.microsoft.com/library/Aa571171(v=AX.60)
ms:contentKeyID: 36057970
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About linking BOM lines to route operations 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Click **Inventory management** \> **Journals** \> **Item transactions** \> **Bills of materials**. Select a BOM, and click the **Designer** button.

Use this form to link BOM lines to operation numbers. Route information for the current parent BOM is displayed in the upper-right section of the **Designer** tab. Where there are sub-BOMs, route information changes when you select lines.

Blue arrows in the **Current route** section indicate that there are direct links from the selected route to operations. Gray arrows indicate indirect links. If the operation number is blank, the system functions as if the item is used from the first operation for the parent BOM route.

You can link sub-BOMs to a specific operation by using drag-and-drop functionality. When you link a sub-BOM to an operation, the sub-BOM must be completed and ready for the parent BOM assembly process by the time that the operation starts.


> [!NOTE]
> <P>When you drag link lines from sub-BOMs to route operations, you must lock the parent BOM route to prevent the linking of lines to the wrong BOM route.</P>



## Link BOM lines to route operations

On the **Designer** tab, click the BOM line, and drag it to the specific operation number in the **Current** route section.

## Remove links

Right click the BOM line, and select whether you want to remove the link or delete it.

## See also

[BOM designer (form)](https://technet.microsoft.com/library/aa583042\(v=ax.60\))

  


