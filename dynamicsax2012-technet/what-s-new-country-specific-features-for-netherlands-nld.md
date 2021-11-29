---
title: "What's new: Country-specific features for Netherlands (NLD)"
TOCTitle: Country-specific features for Netherlands
ms:assetid: 11d3c884-783c-449e-878a-f15297629107
ms:mtpsurl: https://technet.microsoft.com/library/Dn507144(v=AX.60)
ms:contentKeyID: 59623229
author: Khairunj
ms.date: 06/08/2015
mtps_version: v=AX.60
---

# What's new: Country-specific features for Netherlands (NLD) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Microsoft Dynamics AX 2012 R2, we changed and added country-specific functionality for Netherlands. For more information, see the tables that apply to your version of the product.

## What’s new in AX 2012 R2

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Payment formats for Single Euro Payments Area (SEPA) credit transfers are available.</p></td>
<td><p>The payment format for SEPA credit transfers (ISO 20022 XML) has been updated to the latest version.</p>
<p>For more information, see <a href="aut-bel-deu-esp-fin-fra-ita-nld-create-a-country-region-specific-sepa-credit-transfer-payment-file.md">(AUT, BEL, DEU, ESP, FIN, FRA, ITA, NLD) Create a country/region-specific SEPA credit transfer payment file</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in cumulative update 7 for Microsoft Dynamics AX 2012 R2

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Generate electronic payment files for SEPA direct debits.</p></td>
<td><p>You can generate electronic payment files for SEPA direct debits in the updated ISO 20022 XML format and the pain.008.001.02 version. You can also select the SEPA country/region format for which to generate the payment files.</p>
<p>For more information, see <a href="create-payments-for-customers-who-have-direct-debit-mandates.md">Create payments for customers who have direct debit mandates</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R3

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Submit value-added tax (VAT) and intra-community performance (ICP) reports by using Digipoort.</p></td>
<td><p>You can generate VAT and ICP reports in eXtensible Business Reporting Language (XBRL) format. You can then send the digitally signed XBRL documents to the tax authorities by using the Digipoort service.</p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R3 Cumulative Update 9

Updates to the VAT returns and ICP declarations have been made to allow customers to generate VAT and ICP declarations in XBRL format in accordance to the Taxonomy version 9.0. In accordance with the new Taxonomy version, the key updates include:

  - The entry point reference to the XSD was updated.

  - Namespaces references were updated.

  - The length of element bd-alg\_MessageReferenceSupplierVAT was increased to 20.

  - New elements, bd-alg\_ContactInitials and bd-alg\_ContactPrefix, were added to the schema and contain Contact Initials and Contact prefix. This information must be defined in **General ledger** \> **Setup** \> **Sales tax** \> **External** \> **Netherlands** \> **Electronic tax declaration parameters**.

  - Contact address information is no longer in the schema.

  


