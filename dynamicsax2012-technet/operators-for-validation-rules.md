---
title: Operators for validation rules
TOCTitle: Operators for validation rules
ms:assetid: 7697acc0-6100-4822-9805-420c9af44c48
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa550039(v=AX.60)
ms:contentKeyID: 36058195
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Operators for validation rules 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following operators are available for creating logical expressions in validation rules:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>*</p></td>
<td><p>multiply</p></td>
</tr>
<tr class="even">
<td><p>/</p></td>
<td><p>divide</p></td>
</tr>
<tr class="odd">
<td><p>+</p></td>
<td><p>plus</p></td>
</tr>
<tr class="even">
<td><p>-</p></td>
<td><p>minus</p></td>
</tr>
<tr class="odd">
<td><p>&gt;</p></td>
<td><p>greater than</p></td>
</tr>
<tr class="even">
<td><p>&lt;</p></td>
<td><p>less than</p></td>
</tr>
<tr class="odd">
<td><p>&gt;=</p></td>
<td><p>greater than or equal to</p></td>
</tr>
<tr class="even">
<td><p>&lt;=</p></td>
<td><p>less than or equal to</p></td>
</tr>
<tr class="odd">
<td><p>=</p></td>
<td><p>equal to</p></td>
</tr>
<tr class="even">
<td><p>!=</p></td>
<td><p>not equal to</p></td>
</tr>
<tr class="odd">
<td><p>and</p></td>
<td><p>logical AND</p></td>
</tr>
<tr class="even">
<td><p>or</p></td>
<td><p>logical OR</p></td>
</tr>
</tbody>
</table>


The operators in this table are listed in order of operator precedence. Operator precedence means that operators that appear higher up in the table are evaluated before operators that are listed after them. Therefore, A = B or C = D and A + B \* D = C is evaluated as ((A = B) or (C = D)) and ((A + (B \* D)) = C).

  


