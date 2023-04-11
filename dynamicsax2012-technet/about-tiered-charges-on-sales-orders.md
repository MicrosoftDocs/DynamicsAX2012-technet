---
title: About tiered charges on sales orders
TOCTitle: About tiered charges on sales orders
ms:assetid: ddd5b0f9-a958-4ed5-9c39-257291827cd3
ms:mtpsurl: https://technet.microsoft.com/library/JJ683231(v=AX.60)
ms:contentKeyID: 49684855
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About tiered charges on sales orders 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can define charges that are applied automatically to a sales order based on the order total. By defining the **From amount** and **To amount** in the **Auto charges** form, you can set up tiers that determine the charge to be applied to the order header. The charge is calculated and applied when you click **Tiered charges** in the **Sales order** form. Any existing tiered charges that no longer apply are removed from the order header and replaced with tiered charges. Charges that have not been applied based on tiers, such as charges for specific items or modes of delivery, are not removed from the order header. It is possible to define and apply tiered charges only at the header level.

## Examples

You can use the **From amount** and **To amount** fields in the **Auto charges** form in the following ways to define tiered charges:

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>From amount</strong></p></th>
<th><p><strong>To amount</strong></p></th>
<th><p>Result</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Blank</p></td>
<td><p>Blank</p></td>
<td><p>No tiered charges are defined.</p></td>
</tr>
<tr class="even">
<td><p>10</p></td>
<td><p>Blank</p></td>
<td><p>When the order total exceeds 10 of the specified currency, the charge is applied.</p></td>
</tr>
<tr class="odd">
<td><p>Blank</p></td>
<td><p>10</p></td>
<td><p>When the order total exceeds zero but is less than 10 of the specified currency, the charge is applied.</p></td>
</tr>
</tbody>
</table>


## See also

[Auto charges (form)](https://technet.microsoft.com/library/aa582856\(v=ax.60\))

[Sales orders (form)](https://technet.microsoft.com/library/aa585863\(v=ax.60\))

  


