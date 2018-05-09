---
title: 'Deprecated: Client-side batch framework'
TOCTitle: Client-side batch framework
ms:assetid: f3f1a0fc-7fdf-49f8-98a5-f1e66d543bb7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527265(v=AX.60)
ms:contentKeyID: 59623393
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: Client-side batch framework 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The batch framework in Microsoft Dynamics AX 4.0 and earlier versions required an active client connection to run batch jobs. Users could submit batch jobs, but the batch jobs were not run until a batch operator ran a “batch processing form” and left the client running while the jobs were run.

## Overview

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Reason for deprecation</p></td>
<td><p>The functionality that this feature provided was limited. In Microsoft Dynamics AX 2009, a new server-bound batch framework was introduced that enables batch jobs to run on the server without requiring a client. This framework is more stable and has better performance than the client framework, and provides various new features. Additionally, batch jobs can be run without consuming a client license.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. A new server-side batch framework was introduced in AX 2009. This framework provides all the capabilities of the client-side batch framework, but is more stable, has better performance, and provides much richer functionality with regard to job scheduling and execution. The client-side batch framework is still supported in Microsoft Dynamics AX 2012, but support will be removed in the next version.</p>
<p>For more information, see <a href="batch-server-overview.md">Batch server overview</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>All</p></td>
</tr>
<tr class="even">
<td><p>Changes to installation</p></td>
<td><p>This change does not affect application installation.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to upgrade</p></td>
<td><p>This change does not affect application upgrade.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

