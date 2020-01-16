---
title: About round-off depreciation
TOCTitle: About round-off depreciation
ms:assetid: 32142156-da14-4552-b8a1-563cd4efb547
ms:mtpsurl: https://technet.microsoft.com/library/Aa553105(v=AX.60)
ms:contentKeyID: 36676381
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About round-off depreciation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Enter the lowest depreciation amount that is allowed for this value model.

The round-off amount is used in inquiries about the fixed asset that show the future depreciation and value for the fixed asset. The round-off amount is also used in depreciation proposals. Regardless of the rounding that is set up, the depreciation amount in the last depreciation period is not rounded. At the end of the last depreciation period, the value of the fixed asset must be zero or the scrap value, if scrap value is used.

**Example**

Depreciation without rounding is calculated as 2,444.44.

Depending on how rounding is set up, different amounts are suggested, as the following table shows.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Rounding method</p></th>
<th><p>Depreciation amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Rounding 0.1</p></td>
<td><p>2,444.40</p></td>
</tr>
<tr class="even">
<td><p>Rounding 1.00</p></td>
<td><p>2,444.00</p></td>
</tr>
<tr class="odd">
<td><p>Rounding 10.00</p></td>
<td><p>2,440.00</p></td>
</tr>
<tr class="even">
<td><p>Rounding 100.00</p></td>
<td><p>2,400.00</p></td>
</tr>
</tbody>
</table>

  


