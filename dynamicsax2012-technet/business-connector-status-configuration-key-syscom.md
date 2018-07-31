---
title: Business Connector Status configuration key (SysCOM)
TOCTitle: Business Connector Status configuration key (SysCOM)
ms:assetid: 92f38b1b-ac51-4ab2-8e80-959e9d08f086
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa616648(v=AX.60)
ms:contentKeyID: 43876666
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Data_Dictionary.Configuration_Keys.SysCOM
---

# Business Connector Status configuration key (SysCOM) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

## Features enabled by the .NET Business Connector Status key

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Areas Affected</p></th>
<th><p>Comments</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Controls access to the .NET Business Connector. This includes the following related .NET Business Connector security keys: <strong>SysComExecution</strong>, <strong>SysComIIS</strong>, and <strong>SysComData</strong>.</p></td>
<td><p>Use this security key to grant or deny access to applications that use the .NET Business Connector. If you deny access to this key, members of the selected role cannot access .NET Business Connector.</p></td>
</tr>
</tbody>
</table>


## Remarks

Enable the .NET Business Connector security key for roles that access Microsoft Dynamics AX directly using one of the following types of applications:

  - Microsoft Visual Studio add-ins. This includes the Enterprise Portal and Reporting add-ins for Visual Studio

  - Third-party applications that connect to Microsoft Dynamics AX directly using .NET Business Connector

Do not enable .NET Business Connector security keys for roles that only access Microsoft Dynamics AX using the .NET Business Connector proxy. In earlier versions of Microsoft Dynamics AX, you were required to enable the .NET Business Connector security key so that users and groups could access Enterprise Portal and the Application Integration Framework. You are no longer required to enable the .NET Business Connector security key for roles that access Microsoft Dynamics AX using the .NET Business Connector proxy.

  


