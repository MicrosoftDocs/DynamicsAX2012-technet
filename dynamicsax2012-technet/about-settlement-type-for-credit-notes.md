---
title: About settlement type for credit notes
TOCTitle: About settlement type for credit notes
ms:assetid: 962fffb2-98ec-4baa-834c-0736c1ae81b5
ms:mtpsurl: https://technet.microsoft.com/library/Aa556179(v=AX.60)
ms:contentKeyID: 36931876
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- settle credit note
- settlement type
audience: Application User
ms.search.region: Global
---

# About settlement type for credit notes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you create a credit note in the **Purchase order** form, the specified settlement type is transferred to the **Settlement type** field. The **Settlement type** field is located on the **Setup** FastTab on the purchase order.

The settlement types that apply are:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Values</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>None</strong></p></td>
<td><p>The invoice transaction will not be settled.</p></td>
</tr>
<tr class="even">
<td><p><strong>Open transactions</strong></p></td>
<td><p>The transactions will be offset against open transactions. The First In First Out (FIFO) principle applies.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Designated transactions</strong></p></td>
<td><p>The transactions will be settled with regard to a specific invoice.</p></td>
</tr>
</tbody>
</table>


## See also

[About settlement type](https://technet.microsoft.com/library/aa600189\(v=ax.60\))

[Purchase order (form)](https://technet.microsoft.com/library/aa557983\(v=ax.60\))

  


