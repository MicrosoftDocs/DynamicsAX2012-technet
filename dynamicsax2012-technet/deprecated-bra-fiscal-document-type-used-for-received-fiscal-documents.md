---
title: 'Deprecated: (BRA) Fiscal document type used for received fiscal documents'
TOCTitle: (BRA) Fiscal document type used for received fiscal documents
ms:assetid: e99cbf10-004f-46b7-bac3-d18e344c9e5f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527249(v=AX.60)
ms:contentKeyID: 59623377
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: (BRA) Fiscal document type used for received fiscal documents 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Microsoft Dynamics AX 2009 for Brazilian installations, a fiscal document type is required to receive a fiscal document. Foundation changes in Microsoft Dynamics AX 2012 changed the functionality for the receipt of fiscal documents. Therefore, the country-specific feature is not required.

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
<td><p>When a fiscal document was received, fiscal document types were required to identify the model, series, and species of the fiscal document. Because of foundation changes in AX 2012, the fiscal document type is no longer required.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. The receipt of fiscal documents requires fields for the model, series, and species of the fiscal document. Information from the last fiscal document that was received for the party is reused.</p>
<p>For more information, see <a href="bra-about-fiscal-documents-and-the-fiscal-document-framework.md">(BRA) About fiscal documents and the fiscal document framework</a> and <a href="bra-receive-an-inbound-transfer-fiscal-document.md">(BRA) Receive an inbound transfer fiscal document</a>.</p></td>
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
<td><p>This change does not affect application upgrade.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

