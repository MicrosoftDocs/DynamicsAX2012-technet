---
title: Aggregate Functions
TOCTitle: Aggregate Functions
ms:assetid: 729fcdb6-175c-452e-912d-885b5e2b8367
ms:mtpsurl: https://technet.microsoft.com/library/Cc593112(v=AX.60)
ms:contentKeyID: 28119379
author: Khairunj
ms.author: daxcpft
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Aggregate Functions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use aggregate functions to calculate aggregate values for a report data region that displays numeric data. For example, the Sum aggregate function can calculate the total amount of transactions for a customer group and return a single value for each customer group. Several functions are available for calculating aggregate values. The following table describes the aggregate functions that you can use.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Aggregate function</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>None</p></td>
<td><p>No aggregate function is applied to the data.</p></td>
</tr>
<tr class="even">
<td><p>Count</p></td>
<td><p>Returns the number of non-null items in a set.</p></td>
</tr>
<tr class="odd">
<td><p>CountDistinct</p></td>
<td><p>Returns the number of distinct non-null items in a set.</p></td>
</tr>
<tr class="even">
<td><p>Sum</p></td>
<td><p>Returns the sum of all values in a set.</p></td>
</tr>
<tr class="odd">
<td><p>Avg</p></td>
<td><p>Returns the average (arithmetic mean) of all non-null values in a set.</p></td>
</tr>
<tr class="even">
<td><p>Min</p></td>
<td><p>Returns the minimum value in a set.</p></td>
</tr>
<tr class="odd">
<td><p>Max</p></td>
<td><p>Returns the maximum value in a set.</p></td>
</tr>
<tr class="even">
<td><p>Var</p></td>
<td><p>Returns the variance of the non-null values in a set.</p></td>
</tr>
<tr class="odd">
<td><p>VarP</p></td>
<td><p>Returns the population variance of the non-null values in a set.</p></td>
</tr>
<tr class="even">
<td><p>StDev</p></td>
<td><p>Returns the standard deviation of the non-null values in a set.</p></td>
</tr>
<tr class="odd">
<td><p>StDevP</p></td>
<td><p>Returns the population standard deviation of the non-null values in a set.</p></td>
</tr>
</tbody>
</table>


## See also

[How to: Display Aggregate Values in a Data Region](how-to-display-aggregate-values-in-a-data-region.md)

