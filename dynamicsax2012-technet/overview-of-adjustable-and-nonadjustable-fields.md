---
title: Overview of adjustable and nonadjustable fields
TOCTitle: Overview of adjustable and nonadjustable fields
ms:assetid: 7d033834-373a-4657-b307-deeaf19d42c7
ms:mtpsurl: https://technet.microsoft.com/library/Hh209270(v=AX.60)
ms:contentKeyID: 36058272
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- adjustable
- nonadjustable
- project transaction types
audience: Application User
ms.search.region: Global
---

# Overview of adjustable and nonadjustable fields 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can adjust transactions by using the **Adjustment** form and the **Create adjustment transactions** form.

The following table provides an overview of which field values in projects can be adjusted for each of the five transaction types.

<table style="width:100%;">
<colgroup>
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Adjustment field</strong></p></th>
<th><p><strong>Hour</strong></p></th>
<th><p><strong>Item</strong></p></th>
<th><p><strong>Expense</strong></p></th>
<th><p><strong>Fee</strong></p></th>
<th><p><strong>On-account</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Project ID</strong></p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p><strong>Category</strong></p></td>
<td><p>Yes*</p></td>
<td><p>Yes*</p></td>
<td><p>Yes*</p></td>
<td><p>Yes*</p></td>
<td><p>Yes*</p></td>
</tr>
<tr class="odd">
<td><p><strong>Line property</strong></p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>No</p></td>
</tr>
<tr class="even">
<td><p><strong>Description</strong></p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="odd">
<td><p><strong>Quantity</strong></p></td>
<td><p>Yes**</p></td>
<td><p>Yes**</p></td>
<td><p>Yes**</p></td>
<td><p>No</p></td>
<td><p>Yes**</p></td>
</tr>
<tr class="even">
<td><p><strong>Cost price</strong></p></td>
<td><p>Yes</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="odd">
<td><p><strong>Sales currency</strong></p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p><strong>Sales price</strong></p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="odd">
<td><p><strong>Sales tax group</strong></p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p><strong>Item sales tax group</strong></p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="odd">
<td><p><strong>Worker</strong></p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
</tr>
<tr class="even">
<td><p><strong>Item</strong></p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
</tr>
<tr class="odd">
<td><p><strong>Funding source name</strong></p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
</tr>
</tbody>
</table>


\* This field value can be adjusted only to a category of the same type.

\*\* The quantity value can be adjusted only when a transaction is split into multiple lines. The total of the new lines must add up to the quantity of the original transaction.

## See also

[Adjust transactions](adjust-transactions.md)

[Adjustments (form)](https://technet.microsoft.com/library/aa553205\(v=ax.60\))

[Adjust transactions in projects](adjust-transactions-in-projects.md)

[About automatic adjustment transactions](about-automatic-adjustment-transactions.md)

[Configure settings for adjustment transactions](configure-settings-for-adjustment-transactions.md)

[View transaction adjustment history](view-transaction-adjustment-history.md)

[Adjust transactions (class form) (Project)](https://technet.microsoft.com/library/aa583326\(v=ax.60\))

[Create adjustment transactions (class form)](https://technet.microsoft.com/library/aa634561\(v=ax.60\))

  


