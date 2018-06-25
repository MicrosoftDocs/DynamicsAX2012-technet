---
title: Configure Enterprise Portal to access data in a partition
TOCTitle: Configure Enterprise Portal to access data in a partition
ms:assetid: 53b2e382-28ee-46f5-a337-5d6f7894dabc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ670113(v=AX.60)
ms:contentKeyID: 49478231
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Configure Enterprise Portal to access data in a partition [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to configure Enterprise Portal so that users can access data and reports in a specific partition. For more information about data partitioning, see [What's new: Data partitioning](what-s-new-data-partitioning.md) and [Data partitioning architecture](data-partitioning-architecture.md).

## Overview of Enterprise Portal and partitions

By default, Enterprise Portal sites are not configured to use a partition, which means they are partition independent. You can specify a partition for an Enterprise Portal site on the **General** tab of the **Administration of Web sites** form. When a user attempts to log on to a site, Enterprise Portal reads the user’s client-configuration file. If a partition is specified, the user is automatically redirected to the Enterprise Portal site and the partition specified in the configuration file. If a user tries to log into a site and they have not been granted permission in the partition they receive an access denied message. For more information about partitions and client-configuration files, see [Configure clients to access data in a partition](configure-clients-to-access-data-in-a-partition.md).


> [!WARNING]
> <P>By default, Enterprise Portal web sites are partition independent. If Microsoft Dynamics AX is configured to use multiple partitions and Enterprise Portal is partition independent, then Enterprise Portal users could view or share documents across partitions. If you do not want users to view or share documents across partitions you must configure Enterprise Portal for a specific partition, as described in the following procedure.</P>



## Before you begin

Before you configure partitions for Enterprise Portal, verify the following.

1.  You are member of the System administrator role in Microsoft Dynamics AX.

2.  You have the partition key(s) from the **System administration** \> **Setup** \> **Partitions** form.

3.  All users who require access to a designated partition are listed on the **Users** form for that partition.

## Configure an Enterprise Portal site for a specific partition

1.  Open the Microsoft Dynamics AX client in the partition that you want to configure Enterprise Portal to access.

2.  Click **System administration** \> **Setup** \> **Enterprise Portal** \> **Web sites**.

3.  Click the site that you want to specify a partition for, and then click the **General** tab.

4.  Clear the **Partition independent** option. When you clear this option, it sets the **Partition** field to the partition you are logged into.
    

    > [!IMPORTANT]
    > <P>Enterprise Portal sites that depend on a specific company must also depend on a specific partition.</P>



5.  Click **Close** to save your changes.

## See also

[Checklists for deploying Enterprise Portal sites](checklists-for-deploying-enterprise-portal-sites.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

