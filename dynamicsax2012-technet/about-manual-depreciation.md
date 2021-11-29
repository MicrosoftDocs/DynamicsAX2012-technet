---
title: About manual depreciation
TOCTitle: About manual depreciation
ms:assetid: 85b49db4-230f-4499-942e-ee5a9f81ec32
ms:mtpsurl: https://technet.microsoft.com/library/Aa571574(v=AX.60)
ms:contentKeyID: 36058407
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- depreciation
- depreciation methods
- manual depreciation
audience: Application User
ms.search.region: Global
---

# About manual depreciation 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you set up a fixed asset depreciation profile and you select **Manual** in the **Method** field in the **Depreciation profiles** form, the depreciation of fixed assets that are assigned to this depreciation profile is determined by the percentage that you enter for each interval in the calendar year.

The intervals that you set up with percentages are posted according to the selection that you make in the **Period frequency** field on the **General** FastTab of the **Depreciation profiles** form. The posting intervals that you can select are as follows:

  - **Yearly**

  - **Monthly**

  - **Quarterly**

  - **Half-Yearly**

  - **Daily**

When you select the posting interval, click **Manual schedules** and set up percentages for each posting interval.

The manual schedules and the posting intervals together define the depreciation amount, as shown in the examples later in this topic. Manual depreciation always is calculated as a percentage of the acquisition price.

With manual depreciation, the percentages that you enter in the intervals of the depreciation do not have to total 100 percent. It is a flexible depreciation method that is often used to define an extraordinary depreciation profile in the **Depreciation books** form, such as a non-periodic depreciation for special (perhaps tax) purposes.


> [!NOTE]
> <P>(ITA) For legal entities whose primary address is in Italy, assets must be depreciated monthly and be fully depreciated using the <STRONG>Manual</STRONG> depreciation method.</P>



## Examples

Acquisition price: 11,000.00

Expected scrap value: 1,000.00

The following table displays the intervals and percentages that you set up in the **Fixed asset depreciation profile schedules** form.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Interval number</strong></p></th>
<th><p><strong>Percentage</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>1</p></td>
<td><p>10.00</p></td>
</tr>
<tr class="even">
<td><p>2</p></td>
<td><p>50.00</p></td>
</tr>
<tr class="odd">
<td><p>3</p></td>
<td><p>8.00</p></td>
</tr>
</tbody>
</table>


The depreciation for each interval is calculated as follows.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p></p></th>
<th><p>Calculation of yearly depreciation amount</p></th>
<th><p>Net book value at the end of the interval</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Interval 1</p></td>
<td><p>(11,000 - 1,000) * 10% = 1,000</p></td>
<td><p>10,000 (11,000 - 1,000)</p></td>
</tr>
<tr class="even">
<td><p>Interval 2</p></td>
<td><p>(11,000 - 1,000) * 50% = 5,000</p></td>
<td><p>5,000 (10,000 - 5,000)</p></td>
</tr>
<tr class="odd">
<td><p>Interval 3</p></td>
<td><p>(11,000 - 1,000) * 8% = 800</p></td>
<td><p>4,200 (5,000 - 800)</p></td>
</tr>
</tbody>
</table>


If you select **Monthly** in the **Period frequency** field, you have set up 12 manual schedule intervals. The depreciation amounts for the first two intervals might be as follows.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>January</p></td>
<td><p>(11,000 - 1,000) * 10% = 1,000</p></td>
</tr>
<tr class="even">
<td><p>February</p></td>
<td><p>(11,000 - 1,000) * 50% = 5,000</p></td>
</tr>
</tbody>
</table>


If you select **Half-Yearly**, you have set up two manual schedule intervals. The depreciation amounts might be as follows.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>June 30</p></td>
<td><p>(11,000 - 1,000) * 10% = 1,000</p></td>
</tr>
<tr class="even">
<td><p>December 31</p></td>
<td><p>(11,000 - 1,000) * 50% = 5,000</p></td>
</tr>
</tbody>
</table>


The total of percentages for all intervals does not have to be 100. However, a message is displayed if the value in the **Cumulative percentage** field in the **Fixed asset depreciation profile schedules** form is not 100.

## See also

[Value models setup (form)](https://technet.microsoft.com/library/aa582567\(v=ax.60\))

[Fixed asset depreciation profile schedules (form)](https://technet.microsoft.com/library/aa575368\(v=ax.60\))

[Set up depreciation profiles](set-up-depreciation-profiles.md)

[Enter a one-time depreciation transaction](enter-a-one-time-depreciation-transaction.md)

  


