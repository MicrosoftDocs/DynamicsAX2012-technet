---
title: 'Deprecated: Support for RunBase framework'
TOCTitle: RunBase
ms:assetid: 9a8a31f9-c594-4d38-95a9-aecc86a22ce0
ms:mtpsurl: https://technet.microsoft.com/library/Dn527190(v=AX.60)
ms:contentKeyID: 59623319
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: Support for RunBase framework 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2009 and earlier versions, the **formletter** class controls the posting form (RunBase), creates parm table records and journal records, performs the actual posting, and controls printer settings.

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
<td><p>The functionality that is provided by the RunBase framework is limited and had to be refactored.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. The feature has been removed, and a replacement feature is available. The RunBase framework has been replaced by the SysOperations Framework, which is more robust and has significant performance improvements.</p>
<p>For more information, see <a href="https://technet.microsoft.com/library/gg862488(v=ax.60)">SysOperation Framework Overview</a>.</p></td>
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

  


