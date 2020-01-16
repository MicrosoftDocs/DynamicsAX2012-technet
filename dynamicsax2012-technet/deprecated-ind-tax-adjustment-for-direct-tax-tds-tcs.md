---
title: 'Deprecated: (IND) Tax adjustment for Direct Tax (TDS/TCS)'
TOCTitle: (IND) Tax adjustment for Direct Tax (TDS/TCS)
ms:assetid: 815eb5f6-2598-4b18-8077-04a27f597f26
ms:mtpsurl: https://technet.microsoft.com/library/Dn527152(v=AX.60)
ms:contentKeyID: 59623281
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: (IND) Tax adjustment for Direct Tax (TDS/TCS) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Microsoft Dynamics AX 2009, the tax adjustment functionality lets users select specific transactions and change the Tax Deducted at Source (TDS)/Tax Collected at Source (TCS) group that is applied on the original transaction.

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
<td><p>Microsoft Dynamics AX 2012 supports subledger journal and source documents, and therefore streamlines the process for posting financial entries to <strong>General ledger</strong>. The existing functionality for withholding tax adjustments is a country-specific feature for India. This functionality was deprecated and was replaced by a more flexible journal-based adjustment of withholding tax through the <strong>Create withholding tax journal</strong> in <strong>General ledger</strong>.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. Users can still adjust the posted TDS/TCS by using either of the following methods:</p>
<ul>
<li><p>Adjust tax liability general ledger accounts by using the <strong>Create withholding tax journal</strong> in General ledger to pass adjustment entries.*</p></li>
<li><p>Adjust the original source document by using, for example, a credit note.</p></li>
</ul>
<p>*This method does not affect the original source document or the distribution entries. This method only adjusts the tax in the TDS/TCS Payable/Recoverable accounts.</p>
<ul>
<li><p>Users can use the adjustment journal functionality to adjust the posted TDS/TCS amount that is not yet reported to the tax department. The amount can be adjusted either up or down.</p></li>
<li><p>Users can also link the adjustment entry for the TDS/TCS with the appropriate parent transaction. In this case, the reports net off the overall result to reflect the change in tax liability that corresponds to the specific document.</p></li>
</ul>
<p>For more information, see <a href="https://technet.microsoft.com/library/jj664896(v=ax.60)">(IND) Create withholding tax journal (form)</a>.</p></td>
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

  


