---
title: 'Deprecated: (BRA) Special parameter to enable NF-e (Federal)'
TOCTitle: (BRA) Enable NF-e (Federal)
ms:assetid: d4ae0baf-a82d-442b-9975-a2f16bd89bfc
ms:mtpsurl: https://technet.microsoft.com/library/Dn527235(v=AX.60)
ms:contentKeyID: 59623363
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: (BRA) Special parameter to enable NF-e (Federal) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

For Brazilian installations, Microsoft Dynamics AX 2009 provides country-specific modifications that support an option to enable NF-e (Federal) in Brazilian parameters.

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
<td><p>The <strong>Enable (Federal)</strong> parameter controlled the Federal electronic fiscal document (NF-e) that, by legislation, is mandatory for fiscal document model 55. The fiscal document model that is found on the fiscal document type is now used to enable the NF-e process.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. The feature was replaced by the fiscal document model that is found on the fiscal document type. Whenever a fiscal document is generated for which the fiscal document type is set up with model 55, the NF-e process is enabled.</p>
<p>For more information, see <a href="bra-about-the-nf-e-process.md">(BRA) About the NF-e process</a>.</p></td>
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

  


