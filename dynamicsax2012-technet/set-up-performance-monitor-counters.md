---
title: Set up Performance Monitor counters
TOCTitle: Set up Performance Monitor counters
ms:assetid: 909bc83a-c26b-4fc9-ae44-38a9cb20db3e
ms:mtpsurl: https://technet.microsoft.com/library/Aa834416(v=AX.60)
ms:contentKeyID: 39555385
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Set up Performance Monitor counters 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use Performance Monitor objects and counters to collect information about the performance of each component of the architecture: Application Object Server (AOS), the database server, and Internet Information Services (IIS). We recommend that you run monitor performance primarily in a test environment. The recommended collection interval is 30 seconds.

You can use the Performance Monitor counters that are included with Microsoft Dynamics AX to help monitor the usage of system resources. By using counters, you can collect and view real-time performance data about server resources, such as processor and memory use, and about Microsoft Dynamics AX and Microsoft SQL Server resources, such as locks and transactions.

## Types of performance counters to monitor

## AOS counters

The following table describes the counters for the Microsoft Dynamics AX Object Server object.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Counter</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Active Sessions</p></td>
<td><p>The number of currently active server sessions.</p></td>
</tr>
<tr class="even">
<td><p>Number of Bytes Received by Server</p></td>
<td><p>The number of bytes received by the AOS instance since it started.</p></td>
</tr>
<tr class="odd">
<td><p>Number of Bytes Sent by Server</p></td>
<td><p>The number of bytes that the AOS instance has sent since it started.</p></td>
</tr>
<tr class="even">
<td><p>Number of Client Requests</p></td>
<td><p>The number of client-to-server requests since the AOS instance started.</p></td>
</tr>
<tr class="odd">
<td><p>Number of Client Requests per Second</p></td>
<td><p>The number of client-to-server requests that the AOS instance processes per second.</p></td>
</tr>
<tr class="even">
<td><p>Number of Server Requests</p></td>
<td><p>The number of server-to-client requests that have been processed since the AOS instance started.</p></td>
</tr>
<tr class="odd">
<td><p>Total Sessions</p></td>
<td><p>The total number of active sessions since the AOS instance started.</p></td>
</tr>
<tr class="even">
<td><p>Total Number of Clears</p></td>
<td><p>The total number of times the cache was cleared of all contents.</p></td>
</tr>
<tr class="odd">
<td><p>Total Number of Clears Triggered by AOS</p></td>
<td><p>The total number of times the cache was cleared because of AOS synchronization.</p></td>
</tr>
<tr class="even">
<td><p>Total Number of Deletes from Data Cache</p></td>
<td><p>The total number of times records were deleted from the data cache.</p></td>
</tr>
<tr class="odd">
<td><p>Total Number of Hits</p></td>
<td><p>The total number of times a record was found successfully in the cache.</p></td>
</tr>
<tr class="even">
<td><p>Total Number of Misses</p></td>
<td><p>The total number of time record was not found in the cache.</p></td>
</tr>
<tr class="odd">
<td><p>Total Number of Remove Oldest</p></td>
<td><p>The total number of times the cache was flushed due to size.</p></td>
</tr>
<tr class="even">
<td><p>Total Number of Selects on Cached Tables</p></td>
<td><p>The total number of selects on tables that are cached.</p></td>
</tr>
</tbody>
</table>


## Client counters

The following table describes the counters for the Microsoft Dynamics AX client.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>AOD Cache Cleanups #</p></td>
<td><p>The number of times the AOD cache cleaned up older items.</p></td>
</tr>
<tr class="even">
<td><p>AOD Cache Count #</p></td>
<td><p>The number of AOD items currently cached.</p></td>
</tr>
<tr class="odd">
<td><p>Remote Calls #</p></td>
<td><p>The number of remote calls made.</p></td>
</tr>
<tr class="even">
<td><p>X++ Cache Cleanups #</p></td>
<td><p>The number of times the X++ cache cleaned up older items.</p></td>
</tr>
<tr class="odd">
<td><p>X++ Cache Count #</p></td>
<td><p>The number of X++ methods currently cached.</p></td>
</tr>
</tbody>
</table>


## Service counters

You can use standard service and endpoint performance counters to monitor the performance of the Microsoft Dynamics AX services. For more information, see [Service Performance Counters](https://msdn.microsoft.com/library/ms731087.aspx) and [Endpoint Performance Counters](https://msdn.microsoft.com/library/ms732207.aspx).

## Enterprise Portal counters

The following table describes the counters available for the Microsoft Dynamics AX: Enterprise Portal object. All Enterprise Portal counters are .NET Business Connector counters. If you call .NET Business Connector through another application, the same counters can be used.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Counter</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Number of Sessions</p></td>
<td><p>The number of .NET Business Connector sessions that are currently active.</p></td>
</tr>
<tr class="even">
<td><p>Web Part Execution Time</p></td>
<td><p>The time, in seconds, that is required to execute and display a Web Part.</p></td>
</tr>
<tr class="odd">
<td><p>Fatal Session Exceptions</p></td>
<td><p>The number of fatal .NET Business Connector session exceptions.</p>
<p>For Enterprise Portal, a fatal session exception indicates that the page was not displayed. Instead, a Windows SharePoint Services error page was displayed to the user.</p></td>
</tr>
<tr class="even">
<td><p>Nonfatal Session Exceptions</p></td>
<td><p>The number of nonfatal .NET Business Connector session exceptions.</p>
<p>For Enterprise Portal, a nonfatal session exception indicates that the page was displayed, but some Web Parts on the page were not displayed.</p></td>
</tr>
<tr class="odd">
<td><p>Xpp Session Exceptions</p></td>
<td><p>The number of X++ .NET session exceptions.</p></td>
</tr>
<tr class="even">
<td><p>Sessions Allocated</p></td>
<td><p>The total number of .NET Business Connector sessions that have been allocated since AOS started.</p></td>
</tr>
<tr class="odd">
<td><p>Sessions Disposed</p></td>
<td><p>The total number of .NET Business Connector sessions that have been disposed of since AOS started.</p></td>
</tr>
<tr class="even">
<td><p>Session Allocation Rate</p></td>
<td><p>The number of .NET Business Connector sessions that are allocated per second.</p></td>
</tr>
</tbody>
</table>


## Server counters

The following table lists the counters that are typically monitored for the AOS process (Ax32Serv), database servers, IIS servers, and Terminal Services servers.

<table style="width:100%;">
<colgroup>
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Object</p></th>
<th><p>Counter</p></th>
<th><p>Database server</p></th>
<th><p>AOS</p></th>
<th><p>IIS</p></th>
<th><p>Terminal Services</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Memory</p></td>
<td><p>Available Mbytes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p>Paging File</p></td>
<td><p>%Usage</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="odd">
<td><p>Process (sqlservr, Ax32Serv, w3wp)</p></td>
<td><p>%Processor Time,%User Time,%Privileged Time</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p>Processor</p></td>
<td><p>%Processor Time,%User Time,%Privileged Time</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="odd">
<td><p>Network</p></td>
<td><p></p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p>PhysicalDisk</p></td>
<td><p>Avg. Disk sec/Read (All instances)</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="odd">
<td><p>PhysicalDisk</p></td>
<td><p>Avg. Disk sec/Write (All instances)</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
</tbody>
</table>


## SQL Server counters

The following table lists the counters that are typically monitored for SQL Server.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Object</p></th>
<th><p>Counter</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>SQLServer:Access Methods</p></td>
<td><p>Forwarded Records/sec</p></td>
</tr>
<tr class="even">
<td><p>SQLServer:Access Methods</p></td>
<td><p>FreeSpace Scans/sec</p></td>
</tr>
<tr class="odd">
<td><p>SQLServer:Access Methods</p></td>
<td><p>Full Scans/sec</p></td>
</tr>
<tr class="even">
<td><p>SQLServer:Access Methods</p></td>
<td><p>Workfiles Created/sec</p></td>
</tr>
<tr class="odd">
<td><p>SQLServer:Access Methods</p></td>
<td><p>Worktables Created/sec</p></td>
</tr>
<tr class="even">
<td><p>SQL Server:Buffer Manager</p></td>
<td><p>Buffer Cache hit ratio</p></td>
</tr>
<tr class="odd">
<td><p>SQL Server:Buffer Manager</p></td>
<td><p>Free list stalls/sec</p></td>
</tr>
<tr class="even">
<td><p>SQL Server:Buffer Manager</p></td>
<td><p>Lazy Writes/sec</p></td>
</tr>
<tr class="odd">
<td><p>SQL Server:Buffer Manager</p></td>
<td><p>Page Life Expectancy</p></td>
</tr>
<tr class="even">
<td><p>SQLServer:Buffer Manager</p></td>
<td><p>Page lookups/sec</p></td>
</tr>
<tr class="odd">
<td><p>SQL Server:Locks</p></td>
<td><p>Lock Requests/sec</p></td>
</tr>
<tr class="even">
<td><p>SQLServer:SQL Statistics</p></td>
<td><p>SQL Compilations/sec</p></td>
</tr>
<tr class="odd">
<td><p>SQLServer:SQL Statistics</p></td>
<td><p>SQL Re-Compilations/sec</p></td>
</tr>
<tr class="even">
<td><p>SQLServer:SQL Statistics</p></td>
<td><p>Batch Requests/sec</p></td>
</tr>
</tbody>
</table>


## Add counters

1.  Open the **Performance** window. Click **Start** \> **Administrative Tools** \> **Performance**.

2.  Click **Add** or press CTRL+I.

3.  In the **Add Counters** dialog box, verify that the correct server name appears.

4.  Select **Select Counters from Computer**.

5.  In the **Performance Object** list, select an object to add counters for, such as **Microsoft Dynamics AX Object Server**.

6.  Select all counters for the object, or select individual counters.

7.  Click **Add**, and then click **Close**.

## Set up an alert on a Performance Monitor counter

1.  In the navigation tree of the **Performance** window, expand **Performance Logs and Alerts**.

2.  Right-click **Alerts**, and then click **New Alert Settings**.

3.  In the **New Alert Settings** dialog box, type a name for the new alert, and then click **OK**.

4.  On the **General** tab of the dialog box for the new alert, add a comment, and then click **Add** to add a counter to the alert.
    
    All alerts must have at least one counter.

5.  In the **Add Counters** dialog box, in the **Performance Object** list, select a Microsoft Dynamics AX object. Then, in the **Select counters from** list, select a counter.

6.  To add the counter to the alert, click **Add**.

7.  Repeat steps 5 and 6 to add more counters to the alert. When you have finished adding counters, click **Close** to return to the dialog box for the new alert.

8.  In the dialog box for the new alert, in the **Alert when the value is** list, select either **Over** or **Under**. Then, in the **Limit** box, enter a threshold value.

9.  Click **Apply**.
    
    The alert is generated when the value for the counter is more than or less than the threshold value, depending on whether you selected **Over** or **Under**.

10. In the **Sample data every** boxes, set the sampling frequency.

11. On the **Action** tab, set the actions that occur every time that the alert is triggered.

12. On the **Schedule** tab, set the start and stop schedule for the alert scan.

  


