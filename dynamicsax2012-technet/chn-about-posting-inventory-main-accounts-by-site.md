---
title: (CHN) About posting inventory main accounts by site
TOCTitle: (CHN) About posting inventory main accounts by site
ms:assetid: b586a0a1-2b40-42ea-ba50-e04823b72840
ms:mtpsurl: https://technet.microsoft.com/library/JJ664103(v=AX.60)
ms:contentKeyID: 49384686
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- CN - 00006
audience: Application User
ms.search.region: China (PRC)
---

# (CHN) About posting inventory main accounts by site 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You must determine the value of your inventory items to determine on-hand inventory, taxable amount on inventory, and opening and closing balances for inventory receipts and issues during a specific reporting period. You can create main accounts for inventory or select the main accounts that display the value of your inventory for inventory item groups that can be used for inventory posting. For more information about how to manage inventory by creating item groups, see [About item groups](about-item-groups.md).

You can calculate the inventory value for an item group from the corresponding main account. For example, you can create a main account for the Raw materials item group to track its inventory value.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Main account</p></th>
<th><p>Item group</p></th>
<th><p>Balance</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>15067</p></td>
<td><p>Bulbs</p></td>
<td><p>10,721,065</p></td>
</tr>
<tr class="even">
<td><p>15065</p></td>
<td><p>Raw materials</p></td>
<td><p>6,299,398</p></td>
</tr>
</tbody>
</table>


Organizations that stock more than 100 inventory items, and also maintain several sites, are required to organize main accounts by site and by item group. For example, an organization can have more than one site, and each site can have multiple groups of items. In the following table, you can view the inventory value of the Bulbs item group for Site 1, and the inventory value of the Raw materials item group for Site 2.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Main account</p></th>
<th><p>Item group</p></th>
<th><p>Site</p></th>
<th><p>Balance</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>15080</p></td>
<td><p>Bulbs</p></td>
<td><p>Site 1</p></td>
<td><p>5,721,065</p></td>
</tr>
<tr class="even">
<td><p>15085</p></td>
<td><p>Raw materials</p></td>
<td><p>Site 2</p></td>
<td><p>3,299,398</p></td>
</tr>
</tbody>
</table>


By setting up main accounts for inventory values by site, you can post inventory transactions, such as inventory journals, sales orders, purchase orders, production journals, and project item journals, for each site.

## See also

[(CHN) Inventory and warehouse management parameters (modified form)](https://technet.microsoft.com/library/jj664079\(v=ax.60\))

[(CHN) Activate transaction combinations (modified form)](https://technet.microsoft.com/library/jj664107\(v=ax.60\))

[(CHN) Item posting (modified form)](https://technet.microsoft.com/library/jj664026\(v=ax.60\))

[(CHN) Set up item posting by site](chn-set-up-item-posting-by-site.md)

[(CHN) Activate an inventory transaction combination by site](chn-activate-an-inventory-transaction-combination-by-site.md)

  


