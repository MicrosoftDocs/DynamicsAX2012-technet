---
title: Create a channel data group (Retail essentials)
TOCTitle: Create a channel data group (Retail essentials)
ms:assetid: 0bef7e59-9f5c-4c2f-98f5-aca5cb8c8b5c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn716042(v=AX.60)
ms:contentKeyID: 62200306
ms.date: 11/13/2014
mtps_version: v=AX.60
f1_keywords:
- 0bef7e59-9f5c-4c2f-98f5-aca5cb8c8b5c
- MsDynAx060.0bef7e59-9f5c-4c2f-98f5-aca5cb8c8b5c
---

# Create a channel data group (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to create a group of one or more retail store databases. When you run a distribution schedule, a data package is generated for each data group. All store databases in a data group subscribe to the same data. A database can belong to only one data group.


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



To create a channel data group, follow these steps:

1.  Click **Retail essentials** \> **Data synchronization** \> **Setup** \> **Store integration** \> **Channel data group**.

2.  Enter a name and description for the channel data group.

3.  In the **Retail channel schema** field, select a schema, and, if appropriate, select the type of channel that is included in the data group.

4.  Select a configuration of working folders. Working folders store data packages when data is uploaded and downloaded.

5.  The **Channel database** FastTab displays the store databases that are included in the group, but you can’t change this information in this form. To change the data group that a database belongs to, use the **Channel database** form. For more information, see [Set up a channel database profile (Retail essentials)](set-up-a-channel-database-profile-retail-essentials.md).

## See also

[Set up connection profiles (Retail essentials)](set-up-connection-profiles-retail-essentials.md)

  


