---
title: 'Deprecated: (CHN) GB/T19581 export accounting data standard'
TOCTitle: (CHN) GB/T19581 export accounting data standard
ms:assetid: dce67915-f84b-4672-9443-5ce811be89a0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527250(v=AX.60)
ms:contentKeyID: 59623378
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: (CHN) GB/T19581 export accounting data standard 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Microsoft Dynamics AX 2009 SP1 GLSCON release provides a function that can export the ledger transaction data and financial statement data of a specified fiscal period into an XML file. The schema for the XML is defined in Chinese national standard GB/T19581, Accounting software data exchange interface. In Microsoft Dynamics AX 2012 R2, this feature is replaced with the new GB/T24589 national standard.

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
<td><p>The new GB/T24589 standard was published in December 2010. Microsoft Dynamics AX is required to comply with this new standard, which replaces the GB/T19581 standard.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. The feature has been removed, and a replacement feature, GB/T24589, is available. The GB/T24589 feature lets you export general ledger data, and also data from accounts receivable, accounts payable, and fixed assets.</p>
<p>For more information, see <a href="chn-key-tasks-set-up-and-export-financial-information-for-gb-t-24589-2010.md">(CHN) Key tasks: Set up and export financial information for GB/T 24589-2010</a>.</p></td>
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
<td><p>Upgrade scripts are provided that move existing parameters of GB/T19581 to the new standard. The upgrade scripts also modify data, such as the organization number and organization type, to fit the new standard.</p></td>
</tr>
</tbody>
</table>

  


