---
title: Configure an AOS to access a different database
TOCTitle: Configure an AOS to access a different database
ms:assetid: 139fc6d4-9f78-4549-b6cf-8dfa0304aa17
ms:mtpsurl: https://technet.microsoft.com/library/Aa569613(v=AX.60)
ms:contentKeyID: 36941282
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Configure an AOS to access a different database 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can connect an instance of Application Object Server (AOS) to a different database. You may want to do this in the following situations:

  - You are moving from a development or staging environment to a production environment.

  - You are upgrading a Microsoft Dynamics AX system.

Before you can connect an AOS instance to a different database, you must configure permissions for the AOS account. The AOS account is the domain account or Network Service account that is associated with the AOS service.

## Connect to a different database

1.  Open the server configuration utility. Click **Start** \> **Administrative Tools** \> **Microsoft Dynamics AX 2012 Server Configuration**.

2.  Verify that the AOS instance and configuration that you want to modify are selected.

3.  On the **Database Connection** tab, use the lists to select a server, database, and baseline database, and then click **OK**. When you are prompted, click **Yes** to restart the AOS instance. If you do not restart the AOS instance, it does not connect to the new database.

## See also

[Configure an AOS to access a different bin directory](configure-an-aos-to-access-a-different-bin-directory.md)

[Remove an AOS from load balancing](remove-an-aos-from-load-balancing.md)

[Manage AOS performance and availability](manage-aos-performance-and-availability.md)

  


