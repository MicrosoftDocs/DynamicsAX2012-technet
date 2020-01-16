---
title: (AUS) About low value pool depreciation
TOCTitle: (AUS) About low value pool depreciation
ms:assetid: 8afa18af-e006-44a6-bca4-e186a3ea0e3a
ms:mtpsurl: https://technet.microsoft.com/library/Gg242863(v=AX.60)
ms:contentKeyID: 36058472
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Australia
---

# (AUS) About low value pool depreciation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Low value pool depreciation is a reducing balance depreciation method used in Australia. You can allocate assets to a low value pool if they are either low cost assets or low value assets with a cost or opening adjustable value of less than a specified amount. There are three low value types.

  - A low cost asset has an opening net book value that is less than a set amount, after GST credits or adjustments.

  - A low value asset is not a low cost asset, and it has a net book value of less than a set amount.

  - A second element cost is an acquisition adjustment to a low value pool. The cost must be less than the set amount.

A low value pool is created when a low cost or low value asset is created in or transferred into a low value pool.

You can use the low value pool depreciation method in the **Depreciation profiles** form for your company, if the primary addresses of the legal entities are in Australia. It is assumed that your company is using Australian dollars as the functional currency.

## Low value pool depreciation profile

To use the low value pool depreciation method, you must enter information in the following fields on the **General** tab in the **Depreciation profiles** form:

  - **Low cost value**

  - **Low value pool % first year**

  - **Low value pool %**

## Example

Suppose you enter the following information in the **Depreciation profiles** form.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Value</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Low cost value</strong></p></td>
<td><p>AUD 1000.00</p></td>
</tr>
<tr class="even">
<td><p><strong>Low value pool % first year</strong></p></td>
<td><p>18.75%</p></td>
</tr>
<tr class="odd">
<td><p><strong>Low value pool %</strong></p></td>
<td><p>37.5%</p></td>
</tr>
</tbody>
</table>


If you have a low cost asset with a net book value of AUD 800.00, the first-year depreciation for the asset will be 18.75 percent of the AUD 800.00, or AUD 150.00. The depreciation amount for the second year will be 37.5 percent of the net book value (AUD 800.00 – AUD 150.00 = AUD 650.00), or AUD 243.75.

If you have a low value asset with a net book value of AUD 800.00, the first year the asset is depreciated using the low value pool method, the depreciation will be 37.5 percent of the AUD 800.00, or AUD 300.00. The depreciation amount for the second year will also be 37.5 percent of the net book value (AUD 800.00 - AUD 300.00 = AUD 500.00), or AUD 187.50.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Depreciation year</p></th>
<th><p>Low cost asset</p></th>
<th><p>Low value asset</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>First year using low value pool depreciation method</p></td>
<td><p>18.75%</p>
<p>(AUD 150.00)</p></td>
<td><p>37.5% or AUD 300.00</p></td>
</tr>
<tr class="even">
<td><p>Second year</p></td>
<td><p>37.5%</p>
<p>(AUD 243.75)</p></td>
<td><p>37.5% or AUD 187.50</p></td>
</tr>
</tbody>
</table>


## See also

[(AUS) Transfer one or more low value assets to a low value pool](aus-transfer-one-or-more-low-value-assets-to-a-low-value-pool.md)

  


