---
title: 'Deprecated: (BRA) Sales and receipt texts'
TOCTitle: (BRA) Sales and receipt texts
ms:assetid: c78a1f27-4112-4463-9ea5-3d42999c6914
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527254(v=AX.60)
ms:contentKeyID: 59623382
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: (BRA) Sales and receipt texts 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

For Brazilian installations, Microsoft Dynamics AX 2009 provides country-specific modifications that support text that is linked to sales orders and purchase orders. This text information is meant to be printed as additional information for fiscal documents and, in some cases, to be booked as fiscal information in SPED files. This text information is stored and maintained in independent tables and forms for sales and purchasing modules.

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
<td><p>Microsoft Dynamics AX 2012 provides a single framework for fiscal document texts in both sales and purchasing by unifying the parameterization and handling of legal text for fiscal documents.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. This feature has been removed and has been replaced by fiscal document text templates that are known as fiscal document source text. Fiscal document source text can be linked to customers, vendors, CFOP, and purchase and sales orders, just as legal texts used to be.</p>
<p>For more information, see <a href="bra-attach-fiscal-document-texts-to-a-fiscal-document.md">(BRA) Attach fiscal document texts to a fiscal document</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>Sales and marketing</p>
<p>Procurement and sourcing</p></td>
</tr>
<tr class="even">
<td><p>Changes to installation</p></td>
<td><p>This change does not affect application installation.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to upgrade</p></td>
<td><p>Upgrade scripts are provided that support the migration of sales and receipt text records to the new fiscal document format.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

