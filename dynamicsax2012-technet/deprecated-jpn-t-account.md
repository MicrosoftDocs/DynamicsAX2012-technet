---
title: 'Deprecated: (JPN) T-account'
TOCTitle: (JPN) T-account
ms:assetid: 6de014fb-4ac9-4697-97dd-9bb97e6742c1
ms:mtpsurl: https://technet.microsoft.com/library/Dn527143(v=AX.60)
ms:contentKeyID: 59623272
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: (JPN) T-account 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

For Japanese installations, Microsoft Dynamics AX 2009 includes a country-specific feature that is named T-account. The T-account feature lets Japanese users enter journal lines in a T-account format.

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
<td><p>In AX 2009, the T-account information that is stored is manually entered by the user in a temporary table. When the user completes the final posting, the information is transferred to a journal. Because of foundational changes in Microsoft Dynamics AX 2012 R2, this country-specific modification is no longer required.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>In AX 2012 R2, the user can enter debit and credit information in separate grids that are independent of each other. Both grids are based on the LedgerJournalTrans table.</p>
<p>For more information, see <a href="create-and-validate-journals-and-journal-lines.md">Create and validate journals and journal lines</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>General ledger</p></td>
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

  


