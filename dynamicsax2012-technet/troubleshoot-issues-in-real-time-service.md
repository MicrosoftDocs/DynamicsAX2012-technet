---
title: Troubleshoot issues in Real-time Service
TOCTitle: Troubleshoot issues in Real-time Service
ms:assetid: cbf66b4f-3ecb-41d2-9cee-a639f8518c66
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn343752(v=AX.60)
ms:contentKeyID: 56115643
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Troubleshoot issues in Real-time Service 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

You can view Commerce Data Exchange: Real-time Service messages in the following locations.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Monitoring tool</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Real-time Service event trace log file</p></td>
<td><p>Real-time Service saves error information in a log file. By default, the logging level is set to <strong>Warning</strong>. You can change the level of logging.</p>
<p>By default, the event trace log is located at C:\ Windows\Temp\RetailLogs\w3wp.exe.xml.</p>
<p>To read the contents of the log file, you must use Service Trace Viewer. To start Service Trace Viewer, click <strong>Start</strong>, and then search for <strong>Service Trace Viewer</strong>. You can also start Service Trace Viewer from C:\Program Files (x86)\ Microsoft SDKs\Windows\v7.0A\Bin\NETFX 4.0 Tools\SvcTraceViewer.exe.</p></td>
</tr>
<tr class="even">
<td><p>Windows event log</p></td>
<td><p>Depending on how logging is configured for Real-time Service, you might be able to view full logs of Real-time Service events in the Windows event log of the host computer.</p>
<p>By default, the logging level is set to <strong>Error</strong>. You can change the level of logging.</p></td>
</tr>
</tbody>
</table>


For information about how to configure logging for Real-time Service, see [Configure settings for Real-time Service](configure-settings-for-real-time-service.md).

## Issues and resolutions

For the latest information about how to troubleshoot Real-time Service, see the following post on the AX Support Blog:

[AX for Retail 2012 R2: Troubleshooting the Real-time Service](http://blogs.msdn.com/b/axsupport/archive/2012/12/31/ax-for-retail-2012-r2-troubleshooting-the-real-time-service.aspx)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

