---
title: SQL Server High Availability best practices
TOCTitle: SQL Server High Availability best practices
ms:assetid: d175810d-6d0d-49a3-a889-0bd545c325a2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ244575(v=AX.60)
ms:contentKeyID: 48538676
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# SQL Server High Availability best practices [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

If Microsoft SQL Server high availability services such as failover clustering, mirroring, or log shipping are running in your environment, consider the following best practices:

  - Set up high availability only in your production environment.

  - Disable any high availability service when you perform any operations that might change the database structure and require synchronization. For example, disable log shipping when you apply updates, or when you synchronize the database so that it includes changes from the Application Object Tree (AOT).

For detailed recommendations on how to set up a Microsoft Dynamics AX system for high availability, see [SQL Server topology recommendations for availability and performance](sql-server-topology-recommendations-for-availability-and-performance.md).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

