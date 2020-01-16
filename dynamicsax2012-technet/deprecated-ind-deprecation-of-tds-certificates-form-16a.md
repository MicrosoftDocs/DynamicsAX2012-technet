---
title: 'Deprecated: (IND) Deprecation of TDS certificates (Form 16A)'
TOCTitle: (IND) Deprecation of TDS certificates (Form 16A)
ms:assetid: 78135193-a8c8-4390-88e7-ae575dc44d8b
ms:mtpsurl: https://technet.microsoft.com/library/Dn527146(v=AX.60)
ms:contentKeyID: 59623275
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: (IND) Deprecation of TDS certificates (Form 16A) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Microsoft Dynamics AX 2009 lets you generate a Tax Deducted at Source (TDS) certificate (Form 16A) that is issued to the deductee after a TDS statement is filed with the tax authorities.

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
<td><p>According to instructions from the Central Board of Direct Taxes (CBDT), all deductors must issue a TDS certificate in a Form 16A for all sums that are deducted on or after the April 1, 2012, under any of the provisions of Chapter-XVII-B except section 192. This requirement applies even to government deductors who deposit TDS in the Central Government Account through book entry.</p>
<p>The TDS certificate (Form 16A) must be generated through the TIN Central System and downloaded from the TIN website, and must have a unique TDS certificate number. In other words, any duly verified TDS certificate in a Form 16A that is issued by a deductor of any category must be issued through the TIN Central System. The deductor must download a certificate from the TIN Central System, verify the correctness of the certificate’s contents, and authenticate the correctness of the content before the certificate is issued.</p>
<p>Note that this requirement applies only to TDS certificates (Form 16A), not to Tax Collected at Source (TCS) certificates (Form 27D).</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>This functionality is deprecated in Microsoft Dynamics AX 2012 R2 for TDS certificates (Form 16A). However, because Form 16A can now be downloaded from the TIN website, new functionality is provided that records Form 16A certificates that are downloaded.</p>
<p>For more information, see <a href="ind-setting-up-tax-deducted-at-source-tds.md">(IND) Setting up Tax Deducted at Source (TDS)</a>.</p></td>
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

  


