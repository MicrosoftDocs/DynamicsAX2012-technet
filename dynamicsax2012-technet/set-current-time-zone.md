---
title: Set current time zone
TOCTitle: Set current time zone
ms:assetid: cf2df842-ba73-4da9-820d-9dcf0ba5f64f
ms:mtpsurl: https://technet.microsoft.com/library/Gg731954(v=AX.60)
ms:contentKeyID: 35132892
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- UTC
- Universal Coordinated Time
---

# Set current time zone 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you upgrade your data from Microsoft Dynamics AX 4.0, you must specify your local time zone. This task opens the **Current time zone** form so that you can enter this information.


> [!IMPORTANT]
> <P>This checklist item applies only when you are upgrading from Microsoft Dynamics AX 4.0. The <STRONG>Data upgrade checklist</STRONG> will always display this task prior to communication between the source and target databases. At that point, the task disappears unless a Microsoft Dynamics AX 4.0 source system is detected.</P>



The preferred method of storing date and time data in Microsoft Dynamics AX is Coordinated Universal Time (UTC), as specified by the utcDateTime data type. During data upgrade, both shipped and custom tables are scanned to identify system date and time fields. Your local time zone setting determines the offsets to apply to these fields when they are converted to UTC.

If custom date or time fields have been added to Microsoft Dynamics AX, you must decide whether those fields should be merged into new utcDateTime fields during upgrade. For more information, see [Walkthrough: upgrading date and time table field pairs into UtcDateTime](https://technet.microsoft.com/library/dd362070\(v=ax.60\)).

  


