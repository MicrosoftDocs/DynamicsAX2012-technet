---
title: About futures messages
TOCTitle: About futures messages
ms:assetid: 87705bfd-ad24-4f7d-acd8-10ddca1c33ee
ms:mtpsurl: https://technet.microsoft.com/library/Aa571583(v=AX.60)
ms:contentKeyID: 36676397
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- master planning
- master scheduling
- forward scheduled order due date
- futures message
- lead times
- order due date
audience: Application User
ms.search.region: Global
---

# About futures messages 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A futures message is a system-generated order with a due date that is based on lead times for all levels of items. A futures date is generated if master scheduling calculates an order date, perhaps for a lower-level item, that precedes today's date. Master scheduling then forward-schedules the order from today's date and includes lead times which start with any lower-level component items. The futures date is a realistic due date based on the current data.

There are situations where you may choose not to use a futures date. It may be possible to expedite lead times by other means. For example, an item that is usually sent by truck could be air-freighted instead to reduce the lead time.

You can configure how you want futures messages to be calculated for a coverage group, which you can attach to an item. For more information, see [Coverage groups (form)](https://technet.microsoft.com/library/aa552922\(v=ax.60\)).

In the **Master planning parameters** form, you can set the futures time, which is used to calculate all futures dates.

## See also

[About scheduling helpers](about-scheduling-helpers.md)

[About master scheduling plans](about-master-scheduling-plans.md)

  


