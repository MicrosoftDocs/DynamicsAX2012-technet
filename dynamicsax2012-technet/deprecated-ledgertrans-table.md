---
title: 'Deprecated: LedgerTrans table'
TOCTitle: LedgerTrans table
ms:assetid: 3c486a69-11b7-477e-80e2-1efee05dd55c
ms:mtpsurl: https://technet.microsoft.com/library/Dn507106(v=AX.60)
ms:contentKeyID: 59623196
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: LedgerTrans table 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2009, the LedgerTrans table holds the posted general ledger details. These details include the vouchers, dates, ledger account, dimension codes, posting layer, and amounts.

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
<td><p>Because of architectural changes in the application, the LedgerTrans table had to be refactored to support the new financial dimension and subledger journal frameworks.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. The feature has been deprecated, and the following new tables replace the LedgerTrans table:</p>
<ul>
<li><p>GeneralJournalEntry</p></li>
<li><p>GeneralJournalAccountEntry</p></li>
<li><p>LedgerEntryJournal</p></li>
<li><p>LedgerEntry</p></li>
<li><p>SubledgerVoucherGeneralJournalEntry</p></li>
<li><p>LedgerEntryJournalizing</p></li>
</ul>
<p>For more information, see <a href="what-s-new-ledger-and-subledger-lines-and-distributions.md">What's new: Ledger and subledger lines and distributions</a>.</p></td>
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
<td><p>The LedgerTrans records are upgraded to the new data model, except in virtual companies, where the LedgerTrans table is in a TableCollection. If the LedgerTrans table is used in a virtual company setup, the upgrade fails, and you are instructed to contact your partner or Support. The records must be moved out of the virtual company before upgrade.</p></td>
</tr>
</tbody>
</table>

  


