---
title: 'Deprecated: (BRA) Generate the ICMS 1/48 fixed asset credit fiscal document from purchase orders'
TOCTitle: (BRA) Generate the ICMS 1/48 fixed asset credit fiscal document from purchase orders
ms:assetid: c9eae61f-42b8-4e9c-b9ed-a58778bc6b4b
ms:mtpsurl: https://technet.microsoft.com/library/Dn527219(v=AX.60)
ms:contentKeyID: 59623348
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: (BRA) Generate the ICMS 1/48 fixed asset credit fiscal document from purchase orders 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

For Brazilian installations, Microsoft Dynamics AX 2009 provides country-specific modifications that support the ICMS 1/48 fixed asset credit fiscal document from purchase orders. To have the right to credit ICMS tax on fixed assets, a company must generate this document at the end of the month.

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
<td><p>The ICMS 1/48 fixed asset credit fiscal document is an entrance fiscal document that is issued to generate the ICMS tax credit. The document does not affect a vendor’s balance. This feature was removed from purchase orders and was replaced by the new tax fiscal document feature.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. This feature has been replaced by a tax fiscal document that generates fiscal documents that do not affect vendor or customer balances. Instead, the fiscal document generates tax transactions, such as the ICMS 1/48 fixed asset credit fiscal document and ICMS tax transfers between fiscal establishments.</p>
<p>For more information, see <a href="bra-about-icms-tax-fiscal-documents.md">(BRA) About ICMS tax fiscal documents</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>Accounts payable</p>
<p>General ledger</p></td>
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

  


