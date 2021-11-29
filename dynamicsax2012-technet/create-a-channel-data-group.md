---
title: Create a channel data group
TOCTitle: Create a channel data group
ms:assetid: 9fe5c16a-0119-471a-b466-b4511a5d052d
ms:mtpsurl: https://technet.microsoft.com/library/Dn621060(v=AX.60)
ms:contentKeyID: 62200208
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailCDXDataGroup
- MsDynAx060.Forms.RetailCDXDataGroup
---

# Create a channel data group 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

You can group similar channel databases into a data group. For example, you can group the databases for stores that are in the same region or stores that are of the same type. All channel databases in a data group subscribe to the same data. When you run a distribution schedule, a data package is generated for each data group. Use data groups to reduce the number of data packages that are generated from Microsoft Dynamics AX, and therefore help improve performance.


> [!NOTE]
> <P>The information in this topic applies only if you are using Microsoft Dynamics AX 2012 R3.</P>



The following illustration shows the relationships between stores, databases, data groups, and data packages.

![Channel data groups](images/Dn621060.RetailChannelDB(en-us,AX.60).gif "Channel data groups")

Use the following procedure to create a new channel data group.

1.  Click **Retail** \> **Setup** \> **Retail scheduler** \> **Channel integration** \> **Channel data group**.

2.  Enter a name and description for the channel data group.

3.  In the **Retail channel schema** field, select a schema based on the version of Microsoft Dynamics AX that you are using and the type of channel that is included in the data group.

4.  Select a configuration of working folders. For more information about how to specify working folders, see [Specify working folders for Commerce Data Exchange](specify-working-folders-for-commerce-data-exchange.md).

5.  The **Channel database** FastTab displays the channel databases that are included in the group. You can’t change this information in this form. To change the data group that a database belongs to, use the **Channel database** form. For more information, see [Set up a channel database profile](set-up-a-channel-database-profile.md).

  


