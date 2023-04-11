---
title: Connect to source database
TOCTitle: Connect to source database
ms:assetid: d6eab5c1-31b3-4008-866e-73a7266d91cf
ms:mtpsurl: https://technet.microsoft.com/library/Gg732103(v=AX.60)
ms:contentKeyID: 35133044
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- connect
- upgrade
---

# Connect to source database 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Connect to source database** task in the **Data upgrade checklist** establishes a connection between the Microsoft Dynamics AX source system database and the target system database. After you make this connection, you can begin preparing the target database for the bulk-copy operation that occurs during data upgrade.

## Configure matching user permissions

Windows integrated security is used to connect to the source database from the target system. If the administrative user who is performing the upgrade on the target system does not have access to the source system database, the source system will reject the database connection. Open Microsoft SQL Server Management Studio on the source system and perform the following steps:

1.  Grant Microsoft Dynamics AX database access to a domain user with administrative privileges on the target Microsoft Dynamics AX 2012 system.

2.  Add the user to the **db\_owner** and **public** roles.

## Connect to source database

Complete the following steps:

1.  In the **Data upgrade checklist**, expand the **Data upgrade** group.

2.  Click **Connect to source database**.

3.  In the **Connect to source database** form, do the following:
    
    1.  In the **Server name** field, type the name of the server and the Microsoft SQL Server database in the format *SERVER\\DATABASE*.
    
    2.  In the **Database** field, type the name of the Microsoft Dynamics AX source database instance, for example, *DynamicsAX50*.

4.  Click **OK**.

The upgrade framework searches the network for the server and database that you specified. When the computers connect successfully, the **Presynchronize** task becomes available in the **Data upgrade checklist**.

  


