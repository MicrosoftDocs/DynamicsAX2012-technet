---
title: 'Deprecated: Purchase order subscription'
TOCTitle: Purchase order subscription
ms:assetid: db7cf136-02de-449a-8f9c-0626bf2a2dac
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527259(v=AX.60)
ms:contentKeyID: 59623387
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: Purchase order subscription 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Purchase order subscription is an order type that enables one purchase order to be processed multiple times. This feature works by renewing inventory transactions, thereby enabling new receipts on the same purchase order.

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
<td><p>The implementation of subscription orders does not comply with the source document, distributions, and ledger budget.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>No. The feature is no longer available, and there is no replacement feature. However, the Agreement Framework in Microsoft Dynamics AX 2012 replaces the data model and functionality that blanket orders provide in Microsoft Dynamics AX 2009.</p>
<p>For more information about the Agreement Framework, see the white paper <a href="http://download.microsoft.com/download/4/e/3/4e36b655-568e-4d4a-b161-152b28baaf30/implementing_the_agreement_framework_ax2012.pdf">Implementing the Agreement Framework</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>Procurement and sourcing</p></td>
</tr>
<tr class="even">
<td><p>Changes to installation</p></td>
<td><p>This change does not affect application installation.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to upgrade</p></td>
<td><p>Code that is related to subscription orders is removed. Any customization in this area must also be removed.</p></td>
</tr>
</tbody>
</table>

  


