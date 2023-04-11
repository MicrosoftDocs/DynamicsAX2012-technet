---
title: Verify that you have the required permissions for installation
TOCTitle: Verify that you have the required permissions for installation
ms:assetid: 23fa1a7e-5fb1-4c2b-b3ad-ac90b7b8cce8
ms:mtpsurl: https://technet.microsoft.com/library/Aa496457(v=AX.60)
ms:contentKeyID: 35132581
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Verify that you have the required permissions for installation 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you begin the installation of Microsoft Dynamics AX, work with a system administrator to make sure that the account that you log on with at each server has appropriate permissions. The permissions in the following table are recommended based on the principle of least privilege.

In all cases, you must be a member of the **Administrators** group on the local computer where you are installing a component. The following table lists the permissions that are required in addition to administrator access on the local computer.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Component</p></th>
<th><p>Additional permissions that are required to install the component</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Databases</p></td>
<td><ul>
<li><p>Membership in the <strong>dbcreator</strong> server role in Microsoft SQL Server</p></li>
<li><p>Membership in the <strong>securityadmin</strong> server role in SQL Server</p></li>
<li><p>Membership in the <strong>db_accessadmin</strong> database role in SQL Server for the Microsoft Dynamics AX database</p></li>
</ul>
<p>If you install the databases remotely from a computer other than the database server, you must log on to the remote computer by using an account that is an administrator on the SQL Server computer. Setup requires access to SQL Server services.</p></td>
</tr>
<tr class="even">
<td><p>Application Object Server (AOS)</p></td>
<td><p>Membership in the <strong>sysadmin</strong> role on the instance of SQL Server that you want to connect to</p></td>
</tr>
<tr class="odd">
<td><p>Enterprise Portal for Microsoft Dynamics AX</p></td>
<td><ul>
<li><p>Membership in the <strong>System administrator</strong> role in Microsoft Dynamics AX</p></li>
<li><p>Membership in the <strong>Administrators</strong> group in Windows on the Web server</p></li>
<li><p>Membership in the <strong>Farm Administrators</strong> group in Microsoft SharePoint 2010 products</p></li>
<li><p>Membership in the <strong>dbcreator</strong> role on the instance of SQL Server that is used for SharePoint 2010 products</p></li>
<li><p>Membership in the <strong>WSS_Content_Application_Pools</strong> database role in the SharePoint_Config database</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Enterprise Search</p></td>
<td><ul>
<li><p>Membership in the <strong>System administrator</strong> role in Microsoft Dynamics AX</p></li>
<li><p>Membership in the <strong>Administrator</strong> group in Microsoft SharePoint Services</p></li>
<li><p>Membership in the <strong>dbcreator</strong> role on the instance of SQL Server that is used for Microsoft SharePoint Services</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Help server</p></td>
<td><p>Membership in the <strong>System administrator</strong> role in Microsoft Dynamics AX</p></td>
</tr>
<tr class="even">
<td><p>Management Reporter (server components)</p></td>
<td><ul>
<li><p>Membership in the <strong>sysadmin</strong> role on the instance of SQL Server that you want to connect to.</p></li>
<li><p>To finish the initial configuration of Management Reporter, membership is required in the <strong>Administrator</strong> role in Management Reporter.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Microsoft SQL Server Reporting Services extensions</p></td>
<td><p>Membership in the <strong>System administrator</strong> role in Microsoft Dynamics AX</p></td>
</tr>
<tr class="even">
<td><p>Microsoft SQL Server Analysis Services configuration</p></td>
<td><ul>
<li><p>Membership in the <strong>System administrator</strong> role in Microsoft Dynamics AX</p></li>
<li><p>Membership in the SQL Server <strong>securityadmin</strong> server role</p></li>
<li><p>Membership in the SQL Server <strong>db_owner</strong> database role for the Microsoft Dynamics AX database</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Client</p></td>
<td><p>None</p></td>
</tr>
<tr class="even">
<td><p>Microsoft Office add-ins</p></td>
<td><p>None</p></td>
</tr>
<tr class="odd">
<td><p>Remote Desktop Services integration</p></td>
<td><p>None</p></td>
</tr>
<tr class="even">
<td><p>Report Designer for Management Reporter (client component)</p></td>
<td><p>None</p></td>
</tr>
<tr class="odd">
<td><p>Debugger</p></td>
<td><p>None</p></td>
</tr>
<tr class="even">
<td><p>Visual Studio Tools</p></td>
<td><p>None</p></td>
</tr>
<tr class="odd">
<td><p>Trace Parser</p></td>
<td><p>None</p></td>
</tr>
<tr class="even">
<td><p>Web services on Internet Information Services (IIS)</p></td>
<td><p>Membership in the <strong>System administrator</strong> role in Microsoft Dynamics AX</p></td>
</tr>
<tr class="odd">
<td><p>.NET Business Connector</p></td>
<td><p>None</p></td>
</tr>
<tr class="even">
<td><p>Synchronization proxy</p></td>
<td><ul>
<li><p>Membership in the <strong>dbowner</strong> database role in the SQL Server database for Microsoft Project Server</p></li>
<li><p>Membership in the <strong>System administrator</strong> role in Microsoft Dynamics AX</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Synchronization service</p></td>
<td><p>Membership in the <strong>System administrator</strong> role in Microsoft Dynamics AX</p></td>
</tr>
<tr class="even">
<td><p>Management utilities</p></td>
<td><p>None</p></td>
</tr>
<tr class="odd">
<td><p>Retail Headquarters</p></td>
<td><p>None</p></td>
</tr>
<tr class="even">
<td><p>Retail POS</p></td>
<td><p>None</p></td>
</tr>
<tr class="odd">
<td><p>Commerce Data Exchange: Synch Service (Retail Store Connect)</p></td>
<td><p>To install Synch Service, no additional permissions are required. To configure Synch Service, membership is required in the <strong>sysadmin</strong> role on the instance of SQL Server that you want to connect to.</p></td>
</tr>
<tr class="even">
<td><p>Commerce Data Exchange: Real-time Service (Retail Transaction Service)</p></td>
<td><p>None</p></td>
</tr>
<tr class="odd">
<td><p>Commerce Data Exchange: Async Server</p></td>
<td><p>To install Async Server, no additional permissions are required. To configure Async Server, membership is required in the <strong>sysadmin</strong> role on the instance of SQL Server that you want to connect to.</p></td>
</tr>
<tr class="even">
<td><p>Commerce Data Exchange: Async Client</p></td>
<td><p>To install Async Client, no additional permissions are required. To configure Async Client, membership is required in the <strong>sysadmin</strong> role on the instance of SQL Server that you want to connect to.</p></td>
</tr>
<tr class="odd">
<td><p>Retail Channel Configuration Utility (Retail Store Database Utility)</p></td>
<td><p>To install the utility, no additional permissions are required. To configure databases, membership is required in the <strong>sysadmin</strong> role on the instance of SQL Server that you want to connect to.</p></td>
</tr>
<tr class="even">
<td><p>Retail SDK (Retail POS Plug-ins)</p></td>
<td><p>None</p></td>
</tr>
<tr class="odd">
<td><p>Retail Online Channel</p></td>
<td><p>None</p></td>
</tr>
<tr class="even">
<td><p>Retail Server</p></td>
<td><p>None</p></td>
</tr>
<tr class="odd">
<td><p>Retail mass deployment toolkit</p></td>
<td><p>None</p></td>
</tr>
<tr class="even">
<td><p>Modern POS</p></td>
<td><p>None</p></td>
</tr>
<tr class="odd">
<td><p>Retail channel database</p></td>
<td><p>None</p></td>
</tr>
<tr class="even">
<td><p>Retail hardware station</p></td>
<td><p>None</p></td>
</tr>
<tr class="odd">
<td><p>RapidStart Connector</p></td>
<td><p>None</p></td>
</tr>
<tr class="even">
<td><p>Warehouse Mobile Devices Portal</p></td>
<td><p>None</p></td>
</tr>
<tr class="odd">
<td><p>Data Import/Export Framework</p></td>
<td><ul>
<li><p>Membership in the <strong>dbdatareader</strong> and <strong>dbdatawriter</strong> roles on the instance of SQL Server that you want to connect to</p></li>
<li><p>Membership in the <strong>System administrator</strong> role in Microsoft Dynamics AX</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>VSS writer</p></td>
<td><p>Membership in the <strong>Administrators</strong> group on the computer where Microsoft System Center 2012 Data Protection Manager (DPM) is installed</p></td>
</tr>
<tr class="odd">
<td><p>Connector for Microsoft Dynamics</p></td>
<td><ul>
<li><p>Permission to query for entries in Active Directory</p></li>
<li><p>Membership in the SQL Server <strong>dbcreator</strong> server role</p></li>
<li><p>Membership in the SQL Server <strong>securityadmin</strong> server role</p></li>
<li><p>Membership in the <strong>sysadmin</strong> database role on the SQL Server instance that hosts the Microsoft Dynamics Integration (MSDI) database</p></li>
</ul></td>
</tr>
</tbody>
</table>

  


