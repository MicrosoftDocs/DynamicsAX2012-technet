---
title: About planned purchase order lead times
TOCTitle: About planned purchase order lead times
ms:assetid: 4ff7ba91-925c-4f4b-87d7-826046a051b7
ms:mtpsurl: https://technet.microsoft.com/library/Aa497131(v=AX.60)
ms:contentKeyID: 36931871
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- item coverage settings
- item lead time
- purchase order lead time
- vendor lead time
- vendor trade agreement
- planned order lead time
- planned order lead times
audience: Application User
ms.search.region: Global
---

# About planned purchase order lead times 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can set up purchase lead times on a vendor, a vendor trade agreement, an item's coverage settings, or an item. During master scheduling, Microsoft Dynamics AX searches for the purchase lead time according to the following priority:

1.  The **Item coverage** form \> **Lead time** tab. If the **Purchase** check box is selected, the **Purchase time** field is used.

2.  The **Site specific order settings** form \> **Purchase order** \> tab \> **Purchase lead time** field.

3.  The **Default order settings** form \> **Purchase order** \> tab \> **Purchase lead time** field.

A purchase lead time that is found by using this method can be overridden if a vendor is found based on trade agreements. Then the lead time from the trade agreement is used. This applies in these conditions:

  - No vendor is assigned to the item.

  - The **Find trade agreements** check box is selected on the **Master planning parameters** form \> **Planned orders** tab.

## See also

[Item coverage (form)](https://technet.microsoft.com/library/aa619147\(v=ax.60\))

  


