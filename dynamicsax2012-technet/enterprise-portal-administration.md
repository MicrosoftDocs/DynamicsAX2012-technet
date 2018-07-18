---
title: Enterprise Portal administration
TOCTitle: Enterprise Portal administration
ms:assetid: 89cfacf1-f1ef-4d21-b9f1-94e1f3d8c5a0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh271588(v=AX.60)
ms:contentKeyID: 36384219
ms.date: 05/01/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Enterprise Portal administration 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Most setup and administration tasks for Enterprise Portal for Microsoft Dynamics AX are completed by using the Microsoft Dynamics AX client. In Enterprise Portal, administrators can view alert rules and workflow history, and refresh data that has been cached. These options are available under **Administration** on the Quick Launch on the **Home** page.

Enterprise Portal caches resources from the Application Object Tree (AOT) and data from tables in Microsoft Dynamics AX. If you make changes in the AOT, the changes may not be reflected immediately in Enterprise Portal. Likewise, if you change data in tables in Microsoft Dynamics AX, the changes may not be reflected immediately in Enterprise Portal. Stale data in these caches can cause unexpected results for Enterprise Portal users.

The following table describes the refresh commands in the **Administration** section. For information about alert rules, see [Alerts (Enterprise Portal)](alerts-enterprise-portal.md). For information about Workflow, see [Workflow (Enterprise Portal)](workflow-enterprise-portal.md).

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Command</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Refresh AOD</strong></p></td>
<td><p>Flushes cached information about application objects for all items in the AOT. Use this command when changes that you make in the AOT are not immediately reflected in Enterprise Portal. The system notifies you in Enterprise Portal when the refresh is completed.</p></td>
</tr>
<tr class="even">
<td><p><strong>Refresh data</strong></p></td>
<td><p>Flushes cached database records. Use this command when changes that you make in the database are not immediately reflected in Enterprise Portal. The system notifies you in Enterprise Portal when the refresh is completed.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Refresh dictionary</strong></p></td>
<td><p>Flushes cached information about application objects for items in the <strong>Data Dictionary</strong> node of the AOT. Use this command when changes that you make to resources in the <strong>Data Dictionary</strong> node are not immediately reflected in Enterprise Portal. These resources include tables and extended data types. The system notifies you in Enterprise Portal when the refresh is completed.</p></td>
</tr>
</tbody>
</table>


## For more information

## Help for Enterprise Portal administrators

Information about how to setup, configure, maintain, and troubleshoot Enterprise Portal and Role Center is available on [TechNet](http://go.microsoft.com/fwlink/?linkid=201018%26clcid=0x409).

## Help for developers

Information about how to create pages or customize Enterprise Portal is available in the [software development kit](http://go.microsoft.com/fwlink/?linkid=210740).

  


