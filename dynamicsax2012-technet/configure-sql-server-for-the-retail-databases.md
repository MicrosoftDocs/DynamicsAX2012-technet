---
title: Configure SQL Server for the Retail databases
TOCTitle: Configure SQL Server for the Retail databases
ms:assetid: 826d3038-b41d-425d-83e7-f439846a4f90
ms:mtpsurl: https://technet.microsoft.com/library/JJ679922(v=AX.60)
ms:contentKeyID: 49557904
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Configure SQL Server for the Retail databases 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

This topic provides guidance about how to set up Microsoft SQL Server in a Retail implementation.

## Supported SQL Server editions

SQL Server Express editions are supported for channel databases, message databases, and offline databases. However, SQL Server change tracking is required for channel databases and message databases. Change tracking is available only in SQL Server Express with Advanced Services. It is not available in other versions of SQL Server Express Edition.

## Settings that are required for PCI compliance

To comply with the PCI Data Security Standard, you must enter specific settings during SQL Server setup. The following table describes these settings.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Wizard page</p></th>
<th><p>Required settings</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><a href="https://msdn.microsoft.com/library/cc281953.aspx">Server Configuration page, Service Accounts tab</a></p></td>
<td><p>Specify dedicated logon accounts that are not default accounts.</p></td>
</tr>
<tr class="even">
<td><p><a href="https://msdn.microsoft.com/library/cc281849.aspx">Database Engine Configuration page, Account Provisioning tab</a></p></td>
<td><ul>
<li><p>Select Windows authentication.</p></li>
<li><p>Specify SQL Server administrators, but do not use any default accounts.</p></li>
</ul></td>
</tr>
</tbody>
</table>


For more information, see the [Implementation Guide for PCI Compliance](https://go.microsoft.com/fwlink/?linkid=237283).


> [!NOTE]
> <P>If you want to use an existing instance of SQL Server anywhere in the Microsoft Dynamics AX 2012 deployment, you must first verify that the settings for the instance are PCI-compliant. Whenever you can, set up a new instance for Retail that uses the recommended settings. For more information about how to set up a new instance, see <A href="https://msdn.microsoft.com/library/ms130214.aspx">SQL&nbsp;Server Books Online</A>.</P>



## SQL Server collation settings for Retail databases

The collation for each database is based on the Windows locale. To avoid collation issues, verify that the Windows locale of each database computer is set to one of the supported locales for Retail.

## SQL Server logons and database permissions

SQL Server logons are created automatically when you install the following services.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Service</p></th>
<th><p>SQL Server logon</p></th>
<th><p>Logon permissions</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Commerce Data Exchange: Async Server</p></td>
<td><p>Same name as the application pool identity for Async Server</p></td>
<td><p>Provides read (db_datareader) and write (db_datawriter) access to the Async Server message database</p></td>
</tr>
<tr class="even">
<td><p>Commerce Data Exchange: Async Client</p></td>
<td><p>Same name as the service account for Async Client</p></td>
<td><p>Provides read (db_datareader) and write (db_datawriter) access to the Async Client message database</p></td>
</tr>
<tr class="odd">
<td><p>Commerce Data Exchange: Synch Service</p></td>
<td><p>Same name as the service account for the head office instance of Synch Service</p></td>
<td><p>Provides read (db_datareader) and write (db_datawriter) access to the Synch Service message database at headquarters</p></td>
</tr>
</tbody>
</table>


If you change the user account for one of these services, on the server where the component is installed, create a SQL Server logon that has the same name as the user account. The logon must have read and write permissions on the corresponding message database.

When you configure a channel database or an offline database, a local user group for point of sale (POS) users and a corresponding SQL Server logon are created. We recommend that you assign the Windows user accounts of cashiers to this local user group. In AX 2012 R2, we also recommend that you assign the account that is used by Synch Service to this group. In AX 2012 R3, we recommend that you assign the account that is used by Async Client to the RetailDataSyncUsers group.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Database</p></th>
<th><p>SQL Server logon</p></th>
<th><p>Logon permissions</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Message database for Async Server</p></td>
<td><p>RetailHQMessageDBUsers</p></td>
<td><p>Provides read (db_datareader), write (db_datawriter), and execute stored procedure (db_executor) access to the database.</p></td>
</tr>
<tr class="even">
<td><p>Message database for Async Client</p></td>
<td><p>RetailSyncClientDBUser</p></td>
<td><p>Provides read (db_datareader), write (db_datawriter), and execute stored procedure (db_executor) access to the database.</p></td>
</tr>
<tr class="odd">
<td><p>Channel database</p></td>
<td><p>RetailDataSyncUsers</p></td>
<td><p>Assigned to the DataSyncUser role. Gives appropriate read and write permissions at the table level. For example, members of this group have only read permission on transaction tables.</p></td>
</tr>
<tr class="even">
<td><p>Channel database and offline database</p></td>
<td><p>POSUsers</p></td>
<td><p>Corresponds to the local user group for POS users.</p>
<p>Provides read (db_datareader), write (db_datawriter), and execute stored procedure (db_executor) access to the channel database and offline database.</p></td>
</tr>
</tbody>
</table>


On the computer where the channel database is installed, use SQL Server Management Studio to assign the local **RetailOfflineSyncUsers** group read and write permissions to the channel database.

## Enable remote connections and TCP/IP

Any instance of SQL Server that must be accessed from a remote computer must be set up to accept remote connections. For example, any store database server and any computer on which a Synch Service message database is installed without an instance of Synch Service must accept remote connections. Make sure that the TCP/IP protocol is also enabled for SQL Server instances that are accessed remotely.

  


