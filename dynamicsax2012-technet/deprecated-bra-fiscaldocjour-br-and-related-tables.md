---
title: 'Deprecated: (BRA) FiscalDocJour_BR and related tables'
TOCTitle: (BRA) FiscalDocJour_BR and related tables
ms:assetid: 4341c4d4-a9fd-4573-ad41-176f50fc79c1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn507114(v=AX.60)
ms:contentKeyID: 59623203
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: (BRA) FiscalDocJour\_BR and related tables 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Microsoft Dynamics AX 2009 provides country-specific functionality that is related to fiscal documents. Information about fiscal documents is maintained in one set of tables and is also kept in the original transaction tables.

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
<td><p>The FiscalDocJour_BR table and related tables did not contain all relevant information for fiscal reporting. In some cases, these tables also contained credit invoices. Microsoft Dynamics AX 2012 R2 provides a fiscal document framework that includes a set of fiscal document tables. Additionally, AX 2012 R2 provides validations and a set of rules that are applied uniformly, regardless of the transactions that generate or receive a fiscal document.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. The functionality was replaced by the fiscal document framework that is available in AX 2012 R2. This framework controls and stores all the fiscal documents, and all information that is related to the fiscal documents, in a single location. Electronic fiscal documents (NF-e) and fiscal reporting are then processed from this location.</p>
<p>For more information, see <a href="bra-about-fiscal-documents-and-the-fiscal-document-framework.md">(BRA) About fiscal documents and the fiscal document framework</a>.</p></td>
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
<td><p>Upgrade scripts are provided that migrate fiscal documents to the new fiscal document framework.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

