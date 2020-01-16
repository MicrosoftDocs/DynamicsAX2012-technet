---
title: Record accidental substance flows
TOCTitle: Record accidental substance flows
ms:assetid: fb49a5d2-2d83-4abd-b229-b25ed188223d
ms:mtpsurl: https://technet.microsoft.com/library/Hh370707(v=AX.60)
ms:contentKeyID: 36811441
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Record accidental substance flows 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If an accidental substance flow occurs – for example, if a water pipe bursts or a barrel of oil leaks while in storage – you can create a record that identifies the substance flow as accidental. When it is time to calculate how much of a substance your organization used, accidental substance flow records can offer data to help you accurately calculate substance usage.

When you enter substance flows that are not accidental, you must enter the substance flows as occurring between predefined processes that include reference points. You are not required to do this with an accidental substance flow. For example, your organization has three processes: Storage, Manufacturing, and Ecosphere. If the substance flow was planned, a reference from Storage to Manufacturing would represent the regular flow of raw materials. There would also be a reference from Manufacturing to Ecosphere for waste. However, if a barrel in a storage area leaks, you would create a substance flow from Storage to Ecosphere, because the flow was accidental. If the substance flow was not an accident, you could not create that substance flow because that process does not exist.

1.  Click **Compliance and internal controls** \> **Common** \> **Environmental sustainability** \> **Substance flows**.

2.  Click **New** to create a new line, and then enter the appropriate information about the accidental substance flow.

3.  On the **General** tab, select the **Is accidental** check box.

## See also

[Set up substance flows between processes](set-up-substance-flows-between-processes.md)

  


