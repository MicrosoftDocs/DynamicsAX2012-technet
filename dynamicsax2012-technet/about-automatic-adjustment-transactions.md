---
title: About automatic adjustment transactions
TOCTitle: About automatic adjustment transactions
ms:assetid: 6442910b-8caf-4698-a3fa-2a2bc77f4045
ms:mtpsurl: https://technet.microsoft.com/library/Hh242422(v=AX.60)
ms:contentKeyID: 36057711
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- adjustment
- adjust transaction
- adjustment transaction
audience: Application User
ms.search.region: Global
---

# About automatic adjustment transactions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Your Microsoft Dynamics AX administrator may have configured the system to always create two new adjustment records, regardless of which field on the entry line is adjusted. One of these transactions is created to cancel the original entry with a negative amount, and the other new entry is created with the adjusted amount.

If the system is not configured to always create new adjustment lines automatically, some adjustments still result in new transactions when you create adjustments by using the **Adjustment** form. The following table defines whether adjustments to a particular field result in new transactions.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Adjusted field</strong></p></th>
<th><p><strong>New transaction created</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Project ID</strong></p></td>
<td><p>Always</p></td>
</tr>
<tr class="even">
<td><p><strong>Category</strong></p></td>
<td><p>Always</p></td>
</tr>
<tr class="odd">
<td><p><strong>Quantity</strong></p></td>
<td><p>Always</p></td>
</tr>
<tr class="even">
<td><p><strong>Line property</strong></p></td>
<td><p>Only if the transaction includes accrued revenue and the line property is changed from a line property where the <strong>Accrue revenue</strong> check box is selected to a line property where this check box is not selected.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Currency</strong></p></td>
<td><p>Only if the transaction includes accrued revenue.</p></td>
</tr>
<tr class="even">
<td><p><strong>Sales price</strong></p></td>
<td><p>Only if the transaction includes accrued revenue.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Cost price</strong></p></td>
<td><p>Only if the ledger status is Profit &amp; loss or Balance.</p></td>
</tr>
<tr class="even">
<td><p><strong>Dimension</strong></p></td>
<td><p>Only if the transaction includes accrued revenue and the ledger status is Profit &amp; loss or Balance.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Activity</strong></p></td>
<td><p>Never</p></td>
</tr>
<tr class="even">
<td><p><strong>Item sales tax group</strong></p></td>
<td><p>Never</p></td>
</tr>
<tr class="odd">
<td><p><strong>Sales tax group</strong></p></td>
<td><p>Never</p></td>
</tr>
<tr class="even">
<td><p><strong>Description</strong></p></td>
<td><p>Never</p></td>
</tr>
</tbody>
</table>


## See also

[Adjust transactions](adjust-transactions.md)

[Adjustments (form)](https://technet.microsoft.com/library/aa553205\(v=ax.60\))

[Overview of adjustable and nonadjustable fields](overview-of-adjustable-and-nonadjustable-fields.md)

[Configure settings for adjustment transactions](configure-settings-for-adjustment-transactions.md)

[View transaction adjustment history](view-transaction-adjustment-history.md)

  


