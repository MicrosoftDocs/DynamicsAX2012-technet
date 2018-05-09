---
title: 'Deprecated: (JPN) Bill of exchange'
TOCTitle: (JPN) Bill of exchange
ms:assetid: 6e149fa0-9544-4e20-a21a-0819461171f7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527133(v=AX.60)
ms:contentKeyID: 59623262
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: (JPN) Bill of exchange 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Microsoft Dynamics AX 2009 provides management of the life cycle for bills of exchange (BOEs). For example, you can draw BOEs, remit (deposit) them for collection or discount, protest them, and redraw them to settlement. For Japanese installations, there is country-specific functionality for BOE endorsement. This functionality guarantees that the endorsement for the draft that a vendor receives from a customer for payment before BOE maturity applies to both promissory notes and BOEs in accounts receivable.

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
<td><p>Foundational changes in Microsoft Dynamics AX 2012 required that the country-specific BOE functionality for Japan be refactored.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. The country-specific BOE functionality that is available for Japanese installations in AX 2009 was removed. New country-specific BOE functionality for Japanese installations is available in AX 2012.</p>
<p>For more information, see <a href="jpn-set-up-for-bills-of-exchange.md">(JPN) Set up for bills of exchange</a>.</p></td>
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
<td><p>Upgrade scripts are provided that convert BOE transactions that were created in Microsoft Dynamics AX 4.0 or AX 2009 to the new format. Transactions that have been posted, and transactions for which the <strong>Mark</strong> field is selected in the CustBOEEndorsement_JP table, are updated with a status of <strong>Endorsed</strong>.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

