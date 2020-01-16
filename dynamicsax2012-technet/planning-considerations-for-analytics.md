---
title: Planning considerations for analytics
TOCTitle: Planning considerations for analytics
ms:assetid: 0cfb03b6-336a-4665-be39-b205fd34b5c8
ms:mtpsurl: https://technet.microsoft.com/library/Gg731898(v=AX.60)
ms:contentKeyID: 35132815
author: Khairunj
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Planning considerations for analytics 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you implement the analytical features of Microsoft Dynamics AX, there are several things you must consider. This article describes the things you must consider and the decisions you must make at each step in the planning process.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/Dd309577.TopicIcons_Plan(AX.60).png" title="Plan" alt="Plan" />
<p>Verify prerequisites</p>
<p>Determine your topology</p>
<p>Determine if the cubes that are provided with Microsoft Dynamics AX will meet your needs</p>
<p>Determine which configuration keys you will use</p>
<p>Understand how data partitioning affects cube deployment</p>
<p>Learn the security model</p>
<p>Determine how often you want to process the cubes</p>
<p>Determine how you want to display cube data</p></td>
<td><img src="images/Dn507140.TopicIcons_Resources(AX.60).png" title="Resources" alt="Resources" />
<p><a href="analytics-in-microsoft-dynamics-ax.md">Analytics in Microsoft Dynamics AX</a> (content roadmap)</p>
<p><a href="http://www.microsoft.com/en-us/download/details.aspx?id=38410">Business Intelligence Capabilities and Tools</a> (white paper)</p></td>
</tr>
</tbody>
</table>


## Verify prerequisites

Before you begin the planning process, make sure that the following prerequisites are in place.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisites</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Required knowledge</p></td>
<td><p>Before you begin installing and using the analytical features of Microsoft Dynamics AX, you must be familiar with Microsoft SQL Server Analysis Services.</p></td>
<td><p><a href="http://technet.microsoft.com/en-us/library/bb522607.aspx">Analysis Services 2014</a></p>
<p><a href="http://technet.microsoft.com/en-us/library/bb522607(v=sql.110).aspx">Analysis Services 2012</a></p>
<p><a href="http://technet.microsoft.com/en-us/library/bb522607(v=sql.105).aspx">Analysis Services 2008 R2</a></p>
<p><a href="http://technet.microsoft.com/en-us/library/bb522607(v=sql.100).aspx">Analysis Services 2008</a></p></td>
</tr>
</tbody>
</table>


## Determine your topology

To help plan your Microsoft Dynamics AX implementation, determine a topology that supports the needs of your organization. Consider the following information when determining your topology.

## Performance consideration

To make sure that the online transaction processing (OLTP) database for Microsoft Dynamics AX performs well, we recommend that you install the Analysis Services database on a dedicated server.

## High availability

*High availability* is the ability to provide a service with a minimum of interruptions. You can implement Analysis Services in a highly available environment by using network load balancing (NLB) technologies, failover clustering technologies, or both.

  - **Network load balancing** – You can use network load balancing to improve the response time for queries as the number of end users increases. Network load balancing, which is also referred to as *scale out*, distributes the load among several small servers. For more information, see [Scaling out an Analysis Services Solution](http://msdn.microsoft.com/en-us/library/cc280669.aspx).

  - **Failover clustering** – A failover cluster is a combination of one or more nodes, or servers, with two or more shared disks. A SQL Server failover cluster instance appears on the network as a single computer. However, this instance has functionality that provides failover from one node to another if the current node becomes unavailable. For more information, see [Failover Clustering in Analysis Services](http://msdn.microsoft.com/en-us/library/dd207001.aspx).

## AlwaysOn

SQL Server AlwaysOn is the high availability and disaster recovery solution in SQL Server 2012 and 2014. You can implement the Analysis Services database in an AlwaysOn environment to:

  - Reduce the load on the primary Microsoft Dynamics AX online transaction processing database (OLTP).

  - Reduce data latency in cubes and cube-based reports and key performance indicators (KPIs).

To implement the Analysis Services database in an AlwaysOn environment, complete the following tasks:

1.  Create a read-only copy of the Microsoft Dynamics AX OLTP database.

2.  Modify the data source for the Analysis Services database to point to the replicated database (that was created in step 1). To do so, follow these steps:
    
    1.  In SQL Server Management Studio, connect to your Analysis Services instance.
    
    2.  In the tree view, expand the **Databases** \> **\[Database Name\]** \> **Data Sources** node.
    
    3.  Right-click the **Dynamics Database** data source and choose **Properties**.
    
    4.  In the **Connection String** row, locate the text **Initial Catalog=\[DatabaseName\]**.
    
    5.  Change **\[DatabaseName\]** to the name of the replicated database that was created in step 1.

For more information about AlwaysOn, see [AlwaysOn Architecture Guide](http://msdn.microsoft.com/en-us/library/jj191711) in the SQL Server documentation.

## Determine if the cubes that are provided with Microsoft Dynamics AX will meet your needs

Microsoft Dynamics AX provides cubes that you can use and modify. To see a list of the cubes that are included with Microsoft Dynamics AX and for details about each cube, see the [Cube and KPI reference for Microsoft Dynamics AX](cube-and-kpi-reference-for-microsoft-dynamics-ax.md). If you need to create a custom cube, see [Walkthrough: Creating a cube](walkthrough-creating-a-cube.md).

## Determine which configuration keys you will use

The default cubes that are included with Microsoft Dynamics AX require that you enable specific configuration keys. If you disable a configuration key that is required for a cube, you must complete the following tasks:

1.  Run the Analysis Services Project Wizard to remove the measures, dimensions, and key performance indicators (KPIs) that are no longer available (because the configuration key was disabled). For more information, see [Configure an Existing SQL Server Analysis Services Project](configure-an-existing-sql-server-analysis-services-project.md).

2.  Modify or remove the reports that require the configuration key.

## Understand how data partitioning affects cube deployment

Microsoft Dynamics AX 2012 R2 and R3 enable data isolation by using *data partitions*. For example, an organization has several subsidiaries. If the management of the organization does not want employees of one subsidiary to have access to the data for other subsidiaries, data partitions can provide the boundaries that are required for data isolation.

If your Microsoft Dynamics AX installation has multiple data partitions, you must deploy cubes for each partition. For example, suppose you have two data partitions, *Partition 1* and *Partition 2*. You must deploy cubes for each partition. This means you’ll have a General Ledger cube for Partiton 1, and a separate General Ledger cube for Partition 2.

For more information about data partitions, see [Data partitioning architecture](data-partitioning-architecture.md) and [Partitions, Companies, and Data Isolation in Microsoft Dynamics AX](https://technet.microsoft.com/library/jj677285\(v=ax.60\)). For more information about how to deploy cubes for each partition, see [Deploy the default cubes](deploy-the-default-cubes.md).

## Learn the security model

Security for cubes is set up independently from security for Microsoft Dynamics AX. To grant users access to cubes, you must assign the users to database roles in Analysis Services.

When you deploy the cubes that are included with Microsoft Dynamics AX, default roles are created in the database where you deploy the cubes. These roles correspond to security roles in Microsoft Dynamics AX. For example, if you assign a user to the **Accountant** role in Microsoft Dynamics AX, you should assign that same user to the **Accountant** role in Analysis Services.


> [!IMPORTANT]
> <P>Keep the following information in mind when assigning users to roles in Analysis Services:</P>
> <UL>
> <LI>
> <P>Role members have permission to view all data in the cubes that the role has access to. For example, if you assign a user to the <STRONG>Project supervisor</STRONG> role, that user will have access to all data in the Project accounting cube.</P>
> <LI>
> <P>The default roles that are created in Analysis Services are not synchronized with the security roles in Microsoft Dynamics AX. For example, if you modify the permissions of the <STRONG>Accountant</STRONG> role in Microsoft Dynamics AX, you do not affect the <STRONG>Accountant</STRONG> role in Analysis Services.</P></LI></UL>



For more information, see [Security and protection for analytics](security-and-protection-for-analytics.md).

## Determine how often you want to process the cubes

A cube contains historical, or cached, data. To refresh the data in a cube, you must *process* the cube. Determine how often each cube should be processed. Consider that, when a cube is processed, it accesses the data in the Microsoft Dynamics AX OLTP database. Therefore, processing may affect the performance of that database. For more information about how to process cubes, see [Automate the processing of cubes](automate-the-processing-of-cubes.md).

## Determine how you want to display cube data

You can display cube data in many ways, such as in Microsoft SQL Server Reporting Services reports, key performance indicators (KPIs), and in Excel. For details, see the “Use” section of [Analytics in Microsoft Dynamics AX](analytics-in-microsoft-dynamics-ax.md).

  


