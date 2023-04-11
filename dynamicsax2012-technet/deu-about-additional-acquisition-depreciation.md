---
title: (DEU) About additional acquisition depreciation
TOCTitle: (DEU) About additional acquisition depreciation
ms:assetid: 60ff4708-d075-4d5c-88d2-d3dfda3ca666
ms:mtpsurl: https://technet.microsoft.com/library/JJ851017(v=AX.60)
ms:contentKeyID: 50041963
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- DE - 00002
audience: Application User
ms.search.region: Germany
---

# (DEU) About additional acquisition depreciation 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Acquisition adjustments for fixed assets must be calculated as if the adjustments were made on the first day of the business year, regardless of when the adjustment transactions were actually created.

The following formula is used to calculate the base amount of the fixed asset for depreciation:

Net book value of the fixed asset on the last day of the previous business year + All acquisition adjustments for the fixed asset in the current year

## Example

Your organization acquired a fixed asset in 2012 for 60,000, and your organization uses the straight-line life remaining depreciation method over five years. In 2012, when you process the depreciation proposal each month, 1,000 is calculated as the monthly depreciation amount (60,000 / (5 \* 12)). In March 2013, you post an additional acquisition for the fixed asset in the amount of 12,000.

You must treat the additional acquisition as if it was posted on January 1, 2013. Therefore, the monthly depreciation of 12,000 has to be calculated for the remaining four years: 12,000 / (4 \* 12) = 250.

The actual depreciation of the additional acquisition can start only in the month when the additional acquisition occurred, which was March. Therefore, the depreciation amounts for January and February must be added to the depreciation amount for March.

The following table displays the monthly depreciation amounts for both the original acquisition and the acquisition adjustment for the first five months of the year.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Date</p></th>
<th><p>Monthly depreciation amount for the original 60,000 acquisition</p></th>
<th><p>Monthly depreciation amount for the 12,000 acquisition adjustment</p></th>
<th><p>Total depreciation amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>January 2013</p></td>
<td><p>1,000</p></td>
<td><p>0</p></td>
<td><p>1,000</p></td>
</tr>
<tr class="even">
<td><p>February 2013</p></td>
<td><p>1,000</p></td>
<td><p>0</p></td>
<td><p>1,000</p></td>
</tr>
<tr class="odd">
<td><p>March 2013</p></td>
<td><p>1,000</p></td>
<td><p>250 for January</p>
<p>250 for February</p>
<p>250 for March</p></td>
<td><p>1,750</p></td>
</tr>
<tr class="even">
<td><p>April 2013</p></td>
<td><p>1,000</p></td>
<td><p>250</p></td>
<td><p>1,250</p></td>
</tr>
<tr class="odd">
<td><p>May 2013</p></td>
<td><p>1,000</p></td>
<td><p>250</p></td>
<td><p>1,250</p></td>
</tr>
</tbody>
</table>

  


