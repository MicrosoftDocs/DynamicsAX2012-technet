---
title: SQL Server topology recommendations for availability and performance
TOCTitle: SQL Server topology recommendations for availability and performance
ms:assetid: c526201c-e55b-4d39-94bf-4ac85a2ef60f
ms:mtpsurl: https://technet.microsoft.com/library/Dd362068(v=AX.60)
ms:contentKeyID: 39555407
author: Khairunj
ms.date: 03/15/2017
mtps_version: v=AX.60
---

# SQL Server topology recommendations for availability and performance 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The choice topology of the Microsoft SQL Server environment that supports Microsoft Dynamics AX is driven primarily by requirements for availability and performance.

## General topology recommendations

We recommend the following guidelines as a baseline for your topology:

  - Follow the documented best practices for SQL Server.

  - Use a dedicated server that is running SQL Server 2012, SQL Server 2008 R2 or SQL Server 2008.

  - Use a single instance of SQL Server that is dedicated to running the Microsoft Dynamics AX production database.

  - Store your test and development databases on a separate server from the production database.

## Availability recommendations

SQL Server provides several options that can help you achieve high availability: Windows Server Failover Clustering, SQL Server database mirroring, SQL Server log shipping, and SQL Server 2012 AlwaysOn Availability Groups. Of these options, failover clustering and availability groups provide the least amount of downtime. However, replication, database mirroring, log shipping, and availability groups can satisfy other requirements. For example, some of these options can be used to provide a reporting environment that can reduce the load on your production server. The high availability option that you select for your implementation of Microsoft Dynamics AX depends on your availability requirements, a cost/benefit analysis, and the risk tolerance of your organization.


> [!IMPORTANT]
> <P>Before you select a high availability option for SQL Server, we strongly recommend that you contact your value-added reseller (VAR) or Microsoft Support to make sure that the option that you want to use is supported.</P>



Determine and document your availability needs carefully, and test the solution that you select to make sure that it provides the expected availability. The following table lists supported high availability configurations.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>High availability configuration</p></th>
<th><p>Support status</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Windows Server Failover Clustering (WSFC)</p></td>
<td><p>Supported</p></td>
</tr>
<tr class="even">
<td><p>Log shipping</p></td>
<td><p>Supported</p></td>
</tr>
<tr class="odd">
<td><p>Transactional replication</p></td>
<td><p>Supported. Requires KB 2765281.</p></td>
</tr>
<tr class="even">
<td><p>Snapshot replication</p></td>
<td><p>Supported</p></td>
</tr>
<tr class="odd">
<td><p>Database mirroring</p></td>
<td><p>Not supported, because database information change and AOS restart are required when failover occurs.</p></td>
</tr>
<tr class="even">
<td><p>Merge replication</p></td>
<td><p>Not supported, because complex resolution is required to guarantee data integrity</p></td>
</tr>
<tr class="odd">
<td><p>SQL Server 2012 AlwaysOn Availability groups</p></td>
<td><p>Supported. Both synchronous and asynchronous secondary configurations are supported.</p></td>
</tr>
</tbody>
</table>


If you are running SQL Server 2012, we recommend that you deploy AlwaysOn Availability Groups.

If you are running SQL Server 2008, we recommend that you deploy a Windows Server Failover Cluster with one active node and one inactive node.

Availability groups and failover clusters do not require a restart of the Application Object Server (AOS) service.

The following figure shows a SQL Server failover topology.

![SQL Server failover topology](images/Dd362068.SQLTopology(AX.60).png "SQL Server failover topology")

When you use SQL Server failover clustering, note the following behavior:

  - The failover is transparent to AOS, and the service typically does not require a restart.

  - In-process transactions are rolled back, and the user may have to reenter data that was being entered at the time of failure.


> [!NOTE]
> <P>We recommend that a failover cluster be configured so the active node will fail over to an inactive node. If the active node fails over to another active node in the cluster, you must make sure there is sufficient capacity to sustain the Microsoft Dynamics AX database workload, otherwise performance may be degraded significantly.</P>




> [!WARNING]
> <P>Microsoft SQL Server Reporting Services cannot be installed on a failover cluster, because you cannot run the Reporting Services service as part of a failover cluster. However, you can install the report server database on a computer that has a failover cluster installed.</P>



For more information about availability options, see:

  - [Getting started with SQL Server 2008 R2 Failover Clustering](https://go.microsoft.com/fwlink/?linkid=216763)

  - [Windows Server Failover Clustering (WSFC) with SQL Server](https://technet.microsoft.com/library/hh270278.aspx)

  - [Database mirroring](https://go.microsoft.com/fwlink/?linkid=216767)

  - [Log shipping](https://go.microsoft.com/fwlink/?linkid=216765)

  - [Transactional replication](https://go.microsoft.com/fwlink/?linkid=216768)

  - [Snapshot replication](https://go.microsoft.com/fwlink/?linkid=216769)

  - [Host a Report Server Database in a SQL Server Failover Cluster](https://technet.microsoft.com/library/bb630402.aspx)

## Performance recommendations

The performance of the database can significantly affect overall Microsoft Dynamics AX performance.

To achieve the best performance, the SQL Server environment and storage subsystem must be correctly configured. For more information, see [Configure SQL Server and storage settings](configure-sql-server-and-storage-settings.md).

  


