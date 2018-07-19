---
title: 'Deprecated: (BRA) CNPJ or CPF validation by using categories'
TOCTitle: (BRA) CNPJ or CPF validation by using categories
ms:assetid: 1269d6e8-05c6-4090-a819-06dced8f215d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn507134(v=AX.60)
ms:contentKeyID: 59623222
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: (BRA) CNPJ or CPF validation by using categories 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Microsoft Dynamics AX 2009, a category is used to classify each customer and vendor as an organization, person, or foreigner. This information is used to validate the subscription number as CNPJ or CPF. The category was removed in Microsoft Dynamics AX 2012.

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
<td><p>AX 2012 identifies an organization and a person by using the record type that is specified when the party to which customers, vendors, and legal entities are related is created. The record type is now used to determine the validation of CNPJ/CPF for customers, vendors, and legal entities.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. The feature was replaced by the record type that is specified for the party as part of the global address book. When the <strong>Record type</strong> is <strong>Organization</strong>, the CNPJ/CPF is validated as CNPJ. When the <strong>Record type</strong> is <strong>Person</strong>, the CNPJ/CPF is validated as CPF. If the primary address of a customer or vendor is in a country/region that differs from the primary address of the legal entity, the customer or vendor is recognized as a foreigner.</p>
<p>For more information, see <a href="global-address-book-overview.md">Global address book overview</a>.</p></td>
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
<td><p>Upgrade scripts are provided that enable customers and vendors to be migrated from the deprecated category to the record type.</p></td>
</tr>
</tbody>
</table>

  


