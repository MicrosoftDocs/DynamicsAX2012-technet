---
title: (BRA) About POS customization limitations and predefined blank operations
TOCTitle: (BRA) About POS customization limitations and predefined blank operations
ms:assetid: 7c8c2fe6-0128-40e5-9177-5e8f819924db
ms:mtpsurl: https://technet.microsoft.com/library/Dn497727(v=AX.60)
ms:contentKeyID: 62200240
author: tfehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Brazil
---

# (BRA) About POS customization limitations and predefined blank operations 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

## Limitations of POS customization for Brazil

The binary files of the Microsoft Dynamics AX 2012 R2 POS solution, such as the EXE or DLL file, cannot be changed after its last certification and official registration. Therefore, it is not possible to customize all of the available triggers and services in Brazil as for other countries. The files that cannot be modified are listed in the MD5FileList.txt file.

## Reserved blank operations

The following table explains blank operations that are reserved for implementations of Microsoft Dynamics AX for Retail POS in Brazil.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Operation number</p></th>
<th><p>Operation parameter</p></th>
<th><p>Purpose</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>1</p></td>
<td><p>1</p></td>
<td><p>Configure fiscal printer configuration parameters.</p></td>
</tr>
<tr class="even">
<td><p>1</p></td>
<td><p>2</p></td>
<td><p>Configure electronic funds transfer (EFT) parameters.</p></td>
</tr>
<tr class="odd">
<td><p>2</p></td>
<td><p>None</p></td>
<td><p>Generate the Nota Fiscal Paulista file.</p></td>
</tr>
<tr class="even">
<td><p>3</p></td>
<td><p>None</p></td>
<td><p>Generate the Fiscal document model 2.</p></td>
</tr>
<tr class="odd">
<td><p>4</p></td>
<td><p>None</p></td>
<td><p>Perform administrative functions for EFT.</p></td>
</tr>
<tr class="even">
<td><p>5</p></td>
<td><p>None</p></td>
<td><p>Generate the Ato Cotepe 35/2005 file.</p></td>
</tr>
</tbody>
</table>

  


