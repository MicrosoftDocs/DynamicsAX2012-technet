---
title: About factor depreciation
TOCTitle: About factor depreciation
ms:assetid: b45d4fb3-6638-4ce3-8852-6039599ef125
ms:mtpsurl: https://technet.microsoft.com/library/Aa572027(v=AX.60)
ms:contentKeyID: 36059075
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About factor depreciation 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Factors are the percentages that are used to depreciate assets. When you set up a fixed asset depreciation profile and select **Factor** in the **Method** field in the **Depreciation profiles** form, you can set up progressive, digressive, or straight line depreciation:

  - If you select progressive depreciation, the amount of depreciation increases with each depreciation period.

  - If you select digressive depreciation, the amount of depreciation per period decreases over time.

  - If you select straight line depreciation, the depreciation is the same in each period.

The rules and examples that follow indicate how you can set up factors for each type of depreciation.


> [!NOTE]
> <P>When you select <STRONG>Factor</STRONG> in the <STRONG>Method</STRONG> field, the <STRONG>Factor</STRONG> field and the <STRONG>Interval</STRONG> field are displayed.</P>



## Progressive depreciation

The value in the **Factor** field is greater than (\>) 50.

**Example**

The acquisition price is 100,000, the factor is 70, the service life is 10 years, and depreciation starts on January 1. The depreciation amounts and net book value amounts are shown only for the first six years of service life.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Year</p></th>
<th><p>Period</p></th>
<th><p>Depreciation amount</p></th>
<th><p>Net book value amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>1</p></td>
<td><p>December 31</p></td>
<td><p>307.69</p></td>
<td><p>99,692.31</p></td>
</tr>
<tr class="even">
<td><p>2</p></td>
<td><p>December 31</p></td>
<td><p>1,447.21</p></td>
<td><p>98,245.10</p></td>
</tr>
<tr class="odd">
<td><p>3</p></td>
<td><p>December 31</p></td>
<td><p>3,104.50</p></td>
<td><p>95,140.60</p></td>
</tr>
<tr class="even">
<td><p>4</p></td>
<td><p>December 31</p></td>
<td><p>5,150.21</p></td>
<td><p>89,990.39</p></td>
</tr>
<tr class="odd">
<td><p>5</p></td>
<td><p>December 31</p></td>
<td><p>7,522.95</p></td>
<td><p>82,467.44</p></td>
</tr>
<tr class="even">
<td><p>6</p></td>
<td><p>December 31</p></td>
<td><p>10,184.06</p></td>
<td><p>72,283.38</p></td>
</tr>
</tbody>
</table>


## Digressive depreciation

The value in the **Factor** field is less than (\<) 50.

**Example**

The acquisition price is 100,000, the factor is 20, the service life is 10 years, and depreciation starts on January 1. The depreciation amounts and net book value amounts are shown only for the first six years of service life.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Year</p></th>
<th><p>Period</p></th>
<th><p>Depreciation amount</p></th>
<th><p>Net book value amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>1</p></td>
<td><p>December 31</p></td>
<td><p>56,080.43</p></td>
<td><p>43,919.57</p></td>
</tr>
<tr class="even">
<td><p>2</p></td>
<td><p>December 31</p></td>
<td><p>10,665.70</p></td>
<td><p>33,253.87</p></td>
</tr>
<tr class="odd">
<td><p>3</p></td>
<td><p>December 31</p></td>
<td><p>7,156.22</p></td>
<td><p>26,097.65</p></td>
</tr>
<tr class="even">
<td><p>4</p></td>
<td><p>December 31</p></td>
<td><p>5,538.06</p></td>
<td><p>20,559.59</p></td>
</tr>
<tr class="odd">
<td><p>5</p></td>
<td><p>December 31</p></td>
<td><p>4,579.89</p></td>
<td><p>15,979.70</p></td>
</tr>
<tr class="even">
<td><p>6</p></td>
<td><p>December 31</p></td>
<td><p>3,937.36</p></td>
<td><p>12,042.34</p></td>
</tr>
</tbody>
</table>


## Straight line depreciation

The value in the **Factor** field is equal to (=) 50.

In this case, the depreciation is the same in each period, and you should consider the implications of your choices in other fields, as described in [About straight line service life depreciation](about-straight-line-service-life-depreciation.md).

## See also

[Set up depreciation profiles](set-up-depreciation-profiles.md)

  


