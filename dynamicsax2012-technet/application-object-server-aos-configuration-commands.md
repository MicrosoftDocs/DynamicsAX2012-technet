---
title: Application Object Server (AOS) configuration commands
TOCTitle: Application Object Server (AOS) configuration commands
ms:assetid: fd29570f-4ab6-47bd-8d82-27d550dc6493
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa569637(v=AX.60)
ms:contentKeyID: 39555433
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Application Object Server (AOS) configuration commands 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Configuration commands set the options that are used when an Application Object Server (AOS) instance starts. Configuration commands can be run directly from the following locations:

  - In a configuration file

  - In the **Configuration Command to run at kernel startup** field in the Microsoft Dynamics AX 2012 Server Configuration utility

  - From a command prompt using Ax32Serv.exe, which is located in the *Drive*:\\Program Files\\Microsoft Dynamics AX\\60\\Server\\MicrosoftDynamicsAX\\bin directory

Configuration commands require that you use different syntax if you are setting them in a configuration file, executing them in the **Configuration Command to run at kernel startup** field, or executing them from a command prompt. Syntax variations are provided in the following tables.

## General options

This table describes the general options you can use to work with configurations and files.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Command in configuration file</p></th>
<th><p>Command from command line</p></th>
<th><p>Configuration utility option</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>This command cannot be set in a file.</p></td>
<td><p>-<strong>regConfig</strong>=&lt;configname&gt;</p></td>
<td><p><strong>Configuration</strong></p></td>
<td><p>Specify the configuration to use when this AOS instance starts.</p></td>
</tr>
</tbody>
</table>


## Application Object Server options

This table describes the options you can use to manage how an AOS functions.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Command in configuration file</p></th>
<th><p>Command from command line</p></th>
<th><p>Configuration utility option</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>bindir,Text,&lt;path&gt;</p></td>
<td><p>-<strong>bindir</strong>=&lt;path&gt;</p></td>
<td><p><strong>Alternate bin directory</strong></p></td>
<td><p>Specify a directory location that contains an alternate kernel text data (ktd) file.</p></td>
</tr>
<tr class="even">
<td><p>compressiondisabled,Int,1</p></td>
<td><p>-<strong>compressiondisabled</strong></p></td>
<td><p>Option not available in utility</p></td>
<td><p>This is a binary command that is not set by default. When this value is absent, data sent between the AOS and Microsoft Dynamics AX clients is compressed to improve performance.</p>
<p>If the value is present, then packets are not compressed. Disabling compression can have a negative impact on system performance. To compress packets, remove the value from the configuration file.</p></td>
</tr>
<tr class="odd">
<td><p>compressionminsize,Text,&lt;number&gt;</p></td>
<td><p>-<strong>compressionminsize</strong>=&lt;number&gt;</p></td>
<td><p><strong>Minimum packet size to compress</strong></p></td>
<td><p>Specify the smallest useful packet size to compress. The larger the packet size chosen, the smaller the gains in speed.</p></td>
</tr>
<tr class="even">
<td><p>exposeserverprinters,Int,1</p></td>
<td><p>-<strong>exposeserverprinters</strong></p></td>
<td><p><strong>Allow clients to connect to printers on this server</strong></p></td>
<td><p>This is a binary command that is not set by default. When this value is present, clients are allowed to connect to printers that are connected to the AOS computer.</p></td>
</tr>
<tr class="odd">
<td><p>port,Text,&lt;portnumber&gt;</p></td>
<td><p>-<strong>port</strong>=&lt;portnumber&gt;</p></td>
<td><p><strong>TCP/IP port</strong></p></td>
<td><p>The TCP/IP port that the AOS instance should use to connect to clients. The default value is 2712.</p></td>
</tr>
<tr class="even">
<td><p>xppdebug,Text,&lt;0,1&gt;</p></td>
<td><p>-<strong>xppdebug</strong>=&lt;0,1&gt;</p></td>
<td><p><strong>Enable breakpoints to debug X++ code running on this server</strong></p></td>
<td><p>Enable clients to trace their interactions with this AOS instance. The default is off (0).</p></td>
</tr>
<tr class="odd">
<td><p>caslevel,Text,&lt;enable/disable/trace&gt;</p></td>
<td><p>-<strong>caslevel</strong>=&lt;enable/disable/trace&gt;</p></td>
<td><p>Option not available in utility</p></td>
<td><p>Code Access Security (CAS) is the mechanism in Microsoft Dynamics AX that is used to protect specific APIs.</p>
<p>Enable, the default setting, activates CAS for all CAS-protected APIs. If a CAS-protected API is invoked without following the correct consumer steps, an error is generated.</p>
<p>Trace is used to simulate CAS being enabled. An error is not generated if a CAS-protected API is invoked incorrectly. Instead, debug information is written to the Infolog. Use in development or test environments to determine the changes that need to be made to get the system working.</p>
<div class="alert">

> [!IMPORTANT]
> <P>Do not set the <STRONG>caslevel</STRONG> to Trace in production environments.</P>


</div>
<p>Disable disables CAS entirely.</p>
<div class="alert">

> [!IMPORTANT]
> <P>Do not set the <STRONG>caslevel</STRONG> to Disable in production environments.</P>


</div></td>
</tr>
<tr class="even">
<td><p>MaxConcurrentUISessions,Text,&lt;value&gt;</p></td>
<td><p>-<strong>MaxConcurrentUISessions</strong>=&lt;value&gt;</p></td>
<td><p></p></td>
<td><p>Set the maximum number of concurrent Microsoft Dynamics AX client sessions.</p>
<p>The minimum value is 0, the maximum value (and default) is 65535.</p></td>
</tr>
<tr class="odd">
<td><p>MaxConcurrentGuestSessions,Text,&lt;value&gt;</p></td>
<td><p>-<strong>MaxConcurrentGuestSessions</strong>=&lt;value&gt;</p></td>
<td><p></p></td>
<td><p>Set the maximum number of concurrent Guest (anonymous user) sessions.</p>
<p>The minimum value is 0, the maximum value (and default) is 65535.</p></td>
</tr>
<tr class="even">
<td><p>MaxConcurrentWebSessions,Text,&lt;value&gt;</p></td>
<td><p>-<strong>MaxConcurrentWebSessions</strong>=&lt;value&gt;</p></td>
<td><p></p></td>
<td><p>Set the maximum number of concurrent Enterprise Portal sessions, including Guest sessions.</p>
<p>The minimum value is 0, the maximum value (and default) is 65535.</p></td>
</tr>
<tr class="odd">
<td><p>MaxConcurrentBCSessions,Text,&lt;value&gt;</p></td>
<td><p>-<strong>MaxConcurrentBCSessions</strong>=&lt;value&gt;</p></td>
<td><p></p></td>
<td><p>Set the maximum number of concurrent Business Connector sessions, including all Web sessions (all Web sessions come through Business Connector).</p>
<p>The default value is 65535.</p></td>
</tr>
<tr class="even">
<td><p>MaxMemLoad,Text,&lt;value&gt;</p></td>
<td><p>-<strong>MaxMemLoad</strong>=&lt;value&gt;</p></td>
<td><p></p></td>
<td><p>Set the maximum amount of memory usage (the maximum percentage of physical memory that is in use on the computer).</p>
<p>The default value is 0.</p></td>
</tr>
<tr class="odd">
<td><p>MaxConcurrentSessions,Int,&lt;value&gt;</p></td>
<td><p>-<strong>MaxConcurrentSessions</strong>=&lt;value&gt;</p></td>
<td><p><strong>Maximum number of client sessions</strong></p></td>
<td><p>Set the maximum number of client sessions this AOS instance will accept.</p>
<p>The minimum value is 0, the maximum value (and default) is 65535.</p></td>
</tr>
<tr class="even">
<td><p>startupcmd,Text,&lt;command&gt;</p></td>
<td><p>-<strong>startupCmd</strong>=&lt;command&gt;</p></td>
<td><p><strong>Command to run at application startup</strong></p></td>
<td><p>Enter a <strong>SysStartupCmd</strong> method to run when this client application starts. For details, see <a href="execute-configuration-commands.md">Execute configuration commands</a>.</p></td>
</tr>
<tr class="odd">
<td><p>extracmd,Text,&lt;command&gt;</p></td>
<td><p>-<strong>extracmd</strong>=&lt;command&gt;</p></td>
<td><p><strong>Configuration command to run at kernel startup</strong></p></td>
<td><p>Enter any configuration command to run when the kernel starts.</p></td>
</tr>
</tbody>
</table>


## Database connection options

This table describes the options you can use to connect to a database.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Command in configuration file</p></th>
<th><p>Command from command line</p></th>
<th><p>Configuration utility option</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>createdsn,Text, &lt;microsoftsqlserver&gt;</p>
<p></p></td>
<td><p><strong>createdsn</strong>=&lt;microsoftsqlserver&gt;</p></td>
<td><p>Option not available in utility</p></td>
<td><p>Create the data source in the ODBC manager.</p></td>
</tr>
<tr class="even">
<td><p>dsn,text,&lt;portnumber&gt;</p></td>
<td><p><strong>-dsn=</strong>&lt;portnumber&gt;</p></td>
<td><p>Option not available in utility</p></td>
<td><p>Point to a specific data source.</p></td>
</tr>
<tr class="odd">
<td><p>database,Text,&lt;databasename&gt;</p></td>
<td><p><strong>-database</strong>=&lt;databasename&gt;</p></td>
<td><p><strong>Database to connect to</strong></p>
<p></p></td>
<td><p>Specify the database to connect to.</p></td>
</tr>
<tr class="even">
<td><p>dbcli,Text,&lt;ODBC&gt;</p></td>
<td><p>-<strong>dbcli</strong>=&lt;ODBC&gt;</p></td>
<td><p>Option not available in utility</p></td>
<td><p>Run Microsoft Dynamics AX in ODBC mode.</p></td>
</tr>
<tr class="odd">
<td><p>dbserver,Text,&lt;servername&gt;</p></td>
<td><p><strong>-dbserver</strong>=&lt;servername&gt;</p></td>
<td><p>Option not available in utility</p></td>
<td><p>SQL Server name.</p></td>
</tr>
</tbody>
</table>


## Database tuning options

This table describes the options you can use to tune database performance.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Command in configuration file</p></th>
<th><p>Command from command line</p></th>
<th><p>Configuration utility option</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>connectionidletimeout,Text,&lt;0,1&gt;</p>
<p></p></td>
<td><p><strong>-connectionidletimeout</strong>=&lt;0,1&gt;</p></td>
<td><p><strong>Leave the connection running when idle</strong></p></td>
<td><p>Retain a connection to the database when no transactions are running.</p></td>
</tr>
<tr class="even">
<td><p>connectionidletimeout,Text,&lt;time&gt;</p>
<p></p></td>
<td><p><strong>-connectionidletimeout</strong>=&lt;time&gt;</p></td>
<td><p><strong>Maximum idle time before closing</strong></p></td>
<td><p>Specify the amount of time to leave a database connection idle before closing it.</p></td>
</tr>
<tr class="odd">
<td><p>fetchahead,Text,&lt;number&gt;</p>
<p></p></td>
<td><p><strong>-fetchahead</strong>=&lt;number&gt;</p></td>
<td><p><strong>Array fetch ahead</strong></p></td>
<td><p>Specify the maximum number of records that the system fetches at the same time. Starts as your local default computer setting of 100.</p></td>
</tr>
<tr class="even">
<td><p>hint,Text,1</p>
<p></p></td>
<td><p><strong>-hint</strong>=&lt;0, 1&gt;</p></td>
<td><p><strong>Allow INDEX hints in queries</strong></p></td>
<td><p>Enable any query written with an INDEX hint to override the index selected by the database management system.</p></td>
</tr>
<tr class="odd">
<td><p>hint,Text,2</p></td>
<td><p><strong>-hint</strong>=&lt;0, 2&gt;</p></td>
<td><p><strong>Include LTRIM in all SELECT statements to remove leading space from right-aligned columns</strong></p></td>
<td><p>Add LTRIM to all queries generated by Microsoft Dynamics AX. Using LTRIM forces the database to perform a table scan, which can slow query results. Set to 2 to enable this feature, and 0 to disable it.</p></td>
</tr>
<tr class="even">
<td><p>ignoredatasourceindex,Text,&lt;0,1&gt;</p>
<p></p></td>
<td><p><strong>-ignoredatasourceindex</strong>=&lt;0, 1&gt;</p></td>
<td><p><strong>Generate ORDER BY clauses from WHERE clauses</strong></p></td>
<td><p>Set to 1 to override the ordering specified by the index on the data source, using the order of the columns as specified in the WHERE clause. This can improve query performance.</p></td>
</tr>
<tr class="odd">
<td><p>newconnectionretrycount,Text,&lt;number&gt;</p>
<p></p></td>
<td><p><strong>-newconnectionretrycount</strong>=&lt;number&gt;</p></td>
<td><p><strong>Number of connection retries</strong></p></td>
<td><p>Specify the number of times to try connecting to the database before failing.</p></td>
</tr>
<tr class="even">
<td><p>newconnectionretrydelayms,Text,&lt;time&gt;</p>
<p></p></td>
<td><p><strong>-newconnectionretrydelayms</strong>=&lt;time&gt;</p></td>
<td><p><strong>Connection retry interval</strong></p></td>
<td><p>Specify the interval between attempts to connect to the database in milliseconds.</p></td>
</tr>
<tr class="odd">
<td><p>opencursors,Text,&lt;number&gt;</p>
<p></p></td>
<td><p><strong>-opencursors</strong>=&lt;number&gt;</p></td>
<td><p><strong>Maximum open cursors</strong></p></td>
<td><p>Specify the maximum number of database cursors to keep open for reuse in a connection. Starts as your local computer setting, which defaults to 90.</p></td>
</tr>
<tr class="even">
<td><p>retry,Text,&lt;time&gt;</p>
<p></p></td>
<td><p><strong>-retry</strong>=&lt;time&gt;</p></td>
<td><p><strong>Transaction retry interval (in seconds)</strong></p></td>
<td><p>Specify the delay before re-executing a transaction after a deadlock. The default value is 5 seconds.</p></td>
</tr>
<tr class="odd">
<td><p>sqlbuffer,Text,&lt;number&gt;</p>
<p></p></td>
<td><p><strong>-sqlbuffer</strong>=&lt; number&gt;</p></td>
<td><p><strong>Maximum buffer size</strong></p></td>
<td><p>Specify the maximum size of the data retrieval buffer. The larger the buffer, the greater the number of records transferred at the same time. Starts as your local default computer setting of 24.</p></td>
</tr>
<tr class="even">
<td><p>sqlcomplexliterals,Text,&lt;0,1&gt;</p></td>
<td><p><strong>-sqlcomplexliterals</strong>=&lt;0,1&gt;</p></td>
<td><p><strong>Use literals in complex joins from X++</strong></p></td>
<td><p>Specify that Microsoft Dynamics AX use literals rather than parameters for complex joins to optimize performance.</p></td>
</tr>
<tr class="odd">
<td><p>sqlformliterals,Text, &lt;0,1&gt;</p></td>
<td><p><strong>-sqlformliterals</strong>=&lt;0, 1&gt;</p></td>
<td><p><strong>Use literals in join queries from forms and reports</strong></p></td>
<td><p>Specify that Microsoft Dynamics AX use literals rather than parameters in long-running queries to optimize performance.</p></td>
</tr>
</tbody>
</table>


## Unfamiliar configuration options

In the configuration files generated by Microsoft Dynamics AX, you may see unfamiliar options. Some are legacy options (configuration options from previous versions) that are not in use. Other configuration options remain in both the client or server configuration files, although they only apply to client or server, because in previous product versions the utilities were combined. We recommend that you do not change values for these options; unexpected results may occur.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Value in configuration file</p></th>
<th><p>Applies to</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>directory,Text,&lt;pathname&gt;</p></td>
<td><p>Server</p></td>
</tr>
<tr class="even">
<td><p>client,Text,thin</p></td>
<td><p>Legacy</p></td>
</tr>
<tr class="odd">
<td><p>broadcast,Text,</p></td>
<td><p>Legacy</p></td>
</tr>
<tr class="even">
<td><p>sql,Int,1</p></td>
<td><p>Server</p></td>
</tr>
<tr class="odd">
<td><p>native,Int,0</p></td>
<td><p>Legacy</p></td>
</tr>
<tr class="even">
<td><p>fetchahead,Text,</p></td>
<td><p>Server</p></td>
</tr>
<tr class="odd">
<td><p>opencursors,Text,</p></td>
<td><p>Server</p></td>
</tr>
<tr class="even">
<td><p>database,Text,</p></td>
<td><p>Server</p></td>
</tr>
<tr class="odd">
<td><p>dsn,Text,</p></td>
<td><p>Server</p></td>
</tr>
<tr class="even">
<td><p>sqluser,Text,</p></td>
<td><p>Legacy</p></td>
</tr>
<tr class="odd">
<td><p>hint,Text,</p></td>
<td><p>Server</p></td>
</tr>
<tr class="even">
<td><p>sqlbuffer,Text,</p></td>
<td><p>Server</p></td>
</tr>
<tr class="odd">
<td><p>log,Text,</p></td>
<td><p>Server</p></td>
</tr>
<tr class="even">
<td><p>hassqlpwd,Int,0</p></td>
<td><p>Legacy</p></td>
</tr>
<tr class="odd">
<td><p>sqlpwd,Text,</p></td>
<td><p>Legacy</p></td>
</tr>
<tr class="even">
<td><p>retry,Text,</p></td>
<td><p>Server</p></td>
</tr>
<tr class="odd">
<td><p>dbserver,Text,</p></td>
<td><p>Server</p></td>
</tr>
<tr class="even">
<td><p>localappldoc,Int,0</p></td>
<td><p>Legacy</p></td>
</tr>
<tr class="odd">
<td><p>localsysdoc,Int,0</p></td>
<td><p>Legacy</p></td>
</tr>
<tr class="even">
<td><p>applshare,Int,1</p></td>
<td><p>Legacy</p></td>
</tr>
<tr class="odd">
<td><p>applexclusive,Int,0</p></td>
<td><p>Legacy</p></td>
</tr>
<tr class="even">
<td><p>hascompwd,Int,0</p></td>
<td><p>Legacy</p></td>
</tr>
<tr class="odd">
<td><p>compwd,Text,</p></td>
<td><p>Legacy</p></td>
</tr>
<tr class="even">
<td><p>hasserveridletimeout,Int,0</p></td>
<td><p>Server</p></td>
</tr>
<tr class="odd">
<td><p>serveridletimeout,Text,</p></td>
<td><p>Server</p></td>
</tr>
<tr class="even">
<td><p>connectionidletimeout,Text,</p></td>
<td><p>Server</p></td>
</tr>
<tr class="odd">
<td><p>port,Text,</p></td>
<td><p>Server</p></td>
</tr>
<tr class="even">
<td><p>createdsn,Text,</p></td>
<td><p>Server</p></td>
</tr>
<tr class="odd">
<td><p>allowunauth,Int,0</p></td>
<td><p>Legacy</p></td>
</tr>
<tr class="even">
<td><p>sqlformliterals,Text,1</p></td>
<td><p>Server</p></td>
</tr>
<tr class="odd">
<td><p>sqlcomplexliterals,Text,1</p></td>
<td><p>Server</p></td>
</tr>
<tr class="even">
<td><p>ignoredatasourceindex,Text,0</p></td>
<td><p>Server</p></td>
</tr>
<tr class="odd">
<td><p>dbcli,Text,odbc</p></td>
<td><p>Server</p></td>
</tr>
<tr class="even">
<td><p>dbunicodeenabled,Text,1</p></td>
<td><p>Legacy</p></td>
</tr>
<tr class="odd">
<td><p>newconnectionretrydelayms,Text,</p></td>
<td><p>Server</p></td>
</tr>
<tr class="even">
<td><p>newconnectionretrycount,Text,</p></td>
<td><p>Server</p></td>
</tr>
<tr class="odd">
<td><p>cachesynctime,Text,</p></td>
<td><p>Server</p></td>
</tr>
<tr class="even">
<td><p>_clientadname,Text,</p></td>
<td><p>Legacy</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

