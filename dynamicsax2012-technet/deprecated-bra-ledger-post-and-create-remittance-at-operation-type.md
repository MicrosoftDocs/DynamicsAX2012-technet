---
title: 'Deprecated: (BRA) Ledger post and Create remittance at operation type'
TOCTitle: (BRA) Ledger post and Create remittance at operation type
ms:assetid: b65276d1-fe66-4290-aad8-a9b35357a7c8
ms:mtpsurl: https://technet.microsoft.com/library/Dn527230(v=AX.60)
ms:contentKeyID: 59623358
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: (BRA) Ledger post and Create remittance at operation type 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

For Brazilian installations, Microsoft Dynamics AX 2009 provides country-specific modifications that support the option to create general ledger transactions when sales and purchase invoices are posted. Additionally a fiscal document can be marked as **Create remittance** in the setup of the operation type.

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
<td><p>All invoices that are posted from sales orders and purchase orders generate general ledger transactions, based on the operation and taxes that are specified on the invoice. The option to not post in the ledger was removed. Additionally, the option to mark an operation type as <strong>Create remittance</strong> was removed, because this option had no other use that was supported by Brazilian country-specific functionality.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>No. The feature was removed, and there is no replacement feature.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>Accounts payable</p>
<p>Accounts receivable</p></td>
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

  


