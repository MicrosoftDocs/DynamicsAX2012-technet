---
title: 'Deprecated: (RUS) Contracts'
TOCTitle: (RUS) Contracts
ms:assetid: cdbc9e15-9c2d-414c-9f7f-ca8e2d8dc83c
ms:mtpsurl: https://technet.microsoft.com/library/Dn527246(v=AX.60)
ms:contentKeyID: 59623374
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: (RUS) Contracts 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Russian installations of Microsoft Dynamics AX 2009 let users perform the following tasks:

  - Register a contract together with all its financial parameters (parties, dates, contract amount, method of payment, different special tax parameters, prices, and discounts). These parameters might be used as default values in all documents that are associated with a business transaction (sales orders, purchase orders, free text invoices, and journals).

  - Print the contract details in printed forms, such as invoices, payment orders, and invoices for payment.

  - Cross-verify mutual liabilities with the partner according to the contract, and generate an act of reconciliation with the partner.

  - Restrict customer/vendor transaction settlement to the transactions that are related to one contract.

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
<td><p>The new Financial dimension framework and Purchase and sales agreement framework that are implemented in Microsoft Dynamics AX 2012 provide similar capabilities. Therefore, the country/region-specific contract features are obsolete.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. The following frameworks are implemented in AX 2012:</p>
<ul>
<li><p>Financial dimension framework – For more information, see the white paper <a href="https://go.microsoft.com/fwlink/?linkid=213133">Implementing the Account and Financial Dimension Framework</a>.</p></li>
<li><p>Purchase and sales agreements framework – For more information, see the white paper <a href="https://download.microsoft.com/download/4/e/3/4e36b655-568e-4d4a-b161-152b28baaf30/implementing_the_agreement_framework_ax2012.pdf">Implementing the Agreement Framework</a>.</p></li>
<li><p>Dimension control for settlements (Russian country/region-specific feature) – For more information, see <a href="rus-set-up-a-dimension-set-for-dimensions-control-for-settlements.md">(RUS) Set up a dimension set for dimensions control for settlements</a>.</p></li>
</ul>
<p></p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>General ledger</p>
<p>Accounts payable</p>
<p>Accounts receivable</p></td>
</tr>
<tr class="even">
<td><p>Changes to installation</p></td>
<td><p>This change does not affect application installation.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to upgrade</p></td>
<td><p>Upgrade scripts are provided that migrate Russian contract data to the new AX 2012 framework.</p></td>
</tr>
</tbody>
</table>

  


