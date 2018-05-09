---
title: "What's new: Backup and recovery"
TOCTitle: Backup and recovery
ms:assetid: 94bd9f02-cd04-44bf-82f2-32ebfae1e6b5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527176(v=AX.60)
ms:contentKeyID: 59623305
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# What's new: Backup and recovery 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

We have added functionality for backup and recovery in cumulative update 7 for Microsoft Dynamics AX 2012 R2.

The Volume Shadow Copy Service (VSS) simplifies the process for backing up Microsoft server solutions by using a centralized API. As of cumulative update 7, Microsoft Dynamics AX 2012 R2 includes a VSS writer that integrates with the Windows VSS backup framework. Therefore, Microsoft System Center 2012 Data Protection Manager (DPM) can back up and restore AX 2012 R2 data, configuration information for Microsoft SQL Server Analysis Services, and connections, reports, and report definitions for Microsoft SQL Server Reporting Services. When a recovery is performed, DPM restores the business, model, Analysis Services, and Reporting Services databases. DPM also connects Microsoft Dynamics AX Application Object Server (AOS), restores Analysis Services and Reporting Services connections, and redeploys reports.

For more information, see [Protecting Microsoft Dynamics AX environments with System Center 2012 Data Protection Manager (DPM)](protecting-microsoft-dynamics-ax-environments-with-system-center-2012-data-protection-manager-dpm.md).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

