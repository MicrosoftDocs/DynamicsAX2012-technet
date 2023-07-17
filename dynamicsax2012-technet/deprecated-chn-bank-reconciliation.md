---
title: 'Deprecated: (CHN) Bank reconciliation'
TOCTitle: (CHN) Bank reconciliation
ms:assetid: 0a449586-79c2-43e4-8f2e-1711165526b2
ms:mtpsurl: https://technet.microsoft.com/library/Dn507145(v=AX.60)
ms:contentKeyID: 59623230
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: (CHN) Bank reconciliation 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

For Chinese installations, the Microsoft Dynamics AX 2009 SP1 GLSCON release provides country/region-specific features that import electronic bank statement files into the reconciliation journal, and that perform basic auto-matching between statements and Microsoft Dynamics AX bank records. Because the bank reconciliation features in Microsoft Dynamics AX 2012 provide this functionality, country/region-specific modifications are not required.

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
<td><p>Bank reconciliation features in AX 2012 support the import of bank statement files into the reconciliation journal, and auto-matching between the statement and bank records. Therefore, country/region-specific functionality is no longer required.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. The local feature has been removed and is now supported by the bank reconciliation features in AX 2012.</p>
<p>For more information, see <a href="cash-and-bank-management.md">Cash and bank management</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>Cash and bank management</p></td>
</tr>
<tr class="even">
<td><p>Changes to installation</p></td>
<td><p>This change does not affect application installation.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to upgrade</p></td>
<td><p>Upgrade scripts are provided that migrate existing reconciled statements and make the statements available as historical records.</p></td>
</tr>
</tbody>
</table>

  


