---
title: 'Deprecated: BizTalk Adapter for Microsoft Dynamics AX'
TOCTitle: BizTalk Adapter for Microsoft Dynamics AX
ms:assetid: aed64cdd-2695-4145-8292-9e683abd7df9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527197(v=AX.60)
ms:contentKeyID: 59623326
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: BizTalk Adapter for Microsoft Dynamics AX 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2009, the BizTalk adapter enables the Microsoft BizTalk Server to interface and integrate with Microsoft Dynamics AX Application Object Server (AOS).

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
<td><p>The BizTalk adapter is no longer required to interface and integrate with AOS. Therefore, the BizTalk adapter is not shipped with Microsoft Dynamics AX 2012. All integrations that currently use this adapter must be recompiled and reconfigured to use the built-in Windows Communication Foundation (WCF) adapter that is shipped with BizTalk Server 2006 R2 and later versions.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>This feature was deprecated because it was no longer required. All services in AX 2012 are completely compliant with WCF. Therefore, the BizTalk Server can communicate directly with Microsoft Dynamics AX by using the built-in WCF adapter. An external additional adapter component is no longer required.</p>
<p>For more information, see <a href="exchanging-documents-between-biztalk-server-and-aif.md">Exchanging documents between BizTalk Server and AIF</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>Microsoft Dynamics AX Application Integration Framework (AIF)</p></td>
</tr>
<tr class="even">
<td><p>Changes to installation</p></td>
<td><p>Any existing integration solutions that involve BizTalk orchestrations through the BizTalk adapter must be updated to use the WCF adapter instead. These orchestrations must be recompiled and redeployed.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to upgrade</p></td>
<td><p>Existing BizTalk orchestrations that use the BizTalk adapter generate errors and fail after upgrade.</p></td>
</tr>
</tbody>
</table>


## See also

[Services and Application Integration Framework (AIF)](services-and-application-integration-framework-aif.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

