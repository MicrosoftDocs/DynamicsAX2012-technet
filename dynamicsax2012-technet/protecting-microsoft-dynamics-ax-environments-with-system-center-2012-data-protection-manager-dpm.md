---
title: Protecting Microsoft Dynamics AX environments with System Center 2012 Data Protection Manager (DPM)
TOCTitle: Protecting Microsoft Dynamics AX environments with DPM
ms:assetid: 0c68fed3-93b5-4738-b45c-2c249ea99ce6
ms:mtpsurl: https://technet.microsoft.com/library/Dn527684(v=AX.60)
ms:contentKeyID: 59626217
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Protecting Microsoft Dynamics AX environments with System Center 2012 Data Protection Manager (DPM) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Volume Shadow Copy Service (VSS) makes it easier to back up Microsoft server solutions by using a centralized API. As of cumulative update 7, Microsoft Dynamics AX 2012 R2 includes a VSS writer (the AX VSS writer) that is integrated with the Windows VSS backup framework. Therefore, Microsoft System Center 2012 Data Protection Manager (DPM) can back up and restore AX 2012 R2 data, configuration information for Microsoft SQL Server Analysis Services, and connections, reports, and report definitions for Microsoft SQL Server Reporting Services. After recovery, DPM restores the business, model, Reporting Services, and Analysis Services databases. DPM also connects Microsoft Dynamics AX Application Object Server (AOS), restores Analysis Services and Reporting Services connections, and redeploys reports.

A VSS solution consists of the following parts:

  - VSS service – The VSS service is part of the Windows operating system. The service makes sure that the other components can correctly communicate with each other and work together.

  - VSS requester – The VSS requester makes the actual request to create a backup. Typically, the requester is a backup application, such as DPM.

  - VSS writer – The VSS writer is the product-specific component that guarantees a consistent set of data for backup.

  - VSS provider – The VSS provider is the component that creates and maintains the shadow copy. Windows contains a provider.

For more information about VSS, see [Volume Shadow Copy Service](http://technet.microsoft.com/en-us/library/ee923636.aspx).

## Introduction to the AX VSS writer

The AX VSS writer performs the following functions when it is triggered by DPM:

  - Back up protected components, either as an environment or individually.

  - Restore protected components to computers that have the same names in the same domain, and reestablish connections.

The following table describes some of the scenarios that the AX VSS writer supports.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Component</p></th>
<th><p>Scenarios</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Business and model store databases</p></td>
<td><ul>
<li><p>Perform full and differential backups of the AX 2012 R2 business and model store databases. You will experience no downtime during the backup process. Backups will be consistent from a transaction perspective, but not necessarily from a business process perspective.</p></li>
<li><p>Restore full and differential backups of the Microsoft Dynamics AX business and model store databases in a running Microsoft Dynamics AX environment. You will experience minimal downtime during the restore process.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>AOS instance</p></td>
<td><ul>
<li><p>Back up an AOS configuration. The backup includes service account credentials and database connections.</p></li>
<li><p>Restore the original AOS configuration in a newly installed AX 2012 R2 environment that includes an AOS instance that uses temporary credentials and is connected to a temporary database. The permanent database must already have been restored. After the restore process is completed, the previous names are used, and you do not have to compile.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Reporting Services database</p></td>
<td><ul>
<li><p>Perform full and differential backups of the Reporting Services database. You will experience no downtime during the backup process. Backups will be consistent from a transaction perspective, but not necessarily from a business process perspective.</p></li>
<li><p>Restore full and differential backups of the Reporting Services databases in a running AX 2012 R2 environment. You will experience minimal downtime during the restore process.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Reporting Services configuration</p></td>
<td><ul>
<li><p>Back up a Reporting Services configuration for AX 2012 R2. The backup includes service account credentials and database connections.</p></li>
<li><p>Restore the original Reporting Services configuration in a newly installed AX 2012 R2 environment that includes an AOS instance and Reporting Services extensions that use temporary credentials and are connected to a temporary database. After the restore process is completed, the previous names are used, and you do not have to redeploy reports.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Analysis Services database</p></td>
<td><ul>
<li><p>Perform full and differential backups of the Analysis Services database. You will experience downtime throughout the backup process.</p></li>
<li><p>Restore full and differential backups of the Analysis Services databases in a running AX 2012 R2 environment. You will experience downtime throughout the restore process.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Analysis Services configuration</p></td>
<td><ul>
<li><p>Back up an Analysis Services configuration for AX 2012 R2. The backup includes service account credentials and database connections.</p></li>
<li><p>Restore the original Analysis Services configuration in a partially installed AX 2012 R2 environment that includes a fully configured AOS instance and Analysis Services. The Analysis Services extensions do not have to be reinstalled after you run Setup. After the restore process is completed, the previous names are used, and the AOS instance and Analysis Services are connected appropriately.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Limitations of the AX VSS writer

The following list describes some of the limitations of the AX VSS writer:

  - Use of the AX VSS writer is only supported with System Center 2012 DPM. Although third-party applications might take advantage of the AX VSS writer, Microsoft will not provide support for these application.

  - Only one AOS instance per computer can be protected.

  - Only one Reporting Services instance per computer can be protected.

  - The restoration environment is assumed to be a newly installed AX 2012 R2 environment that uses a temporary name and is connected to a temporary database. You must restore the database, AOS, and then Reporting Services or Analysis Services, in that order.

  - The same service accounts that were previously used must be available in the environment.

  - After you restore the AX 2012 R2 database, AOS instances must be restarted manually.

  - Enterprise Portal for Microsoft Dynamics AX is assumed to be protected by using DPM and the SharePoint VSS writer as part of SharePoint farm protection.

  - Enterprise Search is assumed to be protected by using DPM and the SharePoint VSS writer as part of SharePoint farm protection.

## See also

[Install the VSS writer for Microsoft Dynamics AX](install-the-vss-writer-for-microsoft-dynamics-ax.md)

[Protect a Microsoft Dynamics AX 2012 R2 environment with System Center 2012 Data Protection Manager](protect-a-microsoft-dynamics-ax-2012-r2-environment-with-system-center-2012-data-protection-manager.md)

[Recover a Microsoft Dynamics AX 2012 R2 environment with System Center 2012 Data Protection Manager](recover-a-microsoft-dynamics-ax-2012-r2-environment-with-system-center-2012-data-protection-manager.md)

  


