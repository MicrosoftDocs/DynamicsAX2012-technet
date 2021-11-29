---
title: About the Whole amount and Interval options for sales tax codes
TOCTitle: About the Whole amount and Interval options for sales tax codes
ms:assetid: 9c9e1646-c721-492a-ae75-cc31c8c488a3
ms:mtpsurl: https://technet.microsoft.com/library/Aa571696(v=AX.60)
ms:contentKeyID: 39519255
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- sales tax
- sales tax codes
- sales tax code
- interval option
- interval options
- whole amount
- whole amounts
audience: Application User
ms.search.region: Global
---

# About the Whole amount and Interval options for sales tax codes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can set up a sales tax code to be calculated based on a whole amount or an interval amount. In the **Sales tax codes** form, use the **Calculation method** field on the **Calculation** FastTab to select how to calculate a sales tax code. (Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.)

  - **Whole amount** – The tax rate is applied to the whole taxable amount.

  - **Interval** – The taxable amount is divided into parts, each of which falls in a range that has a specific sales tax rate. The part of the amount that falls in a given interval is taxed according to the tax rate for that interval. The sales tax is the sum of the tax amounts that are calculated for each amount interval.
    

    > [!NOTE]
    > <P>The <STRONG>Interval</STRONG> option is available only when you select <STRONG>Line</STRONG> in the <STRONG>Calculation method</STRONG> field in the <STRONG>Sales tax</STRONG> area of the <STRONG>General ledger parameters</STRONG> form.</P>



For taxes to be calculated on all taxable amounts, regardless of which calculation method is selected, intervals must follow these rules:

  - The first interval must have a lower limit of zero.

  - The last interval must have an upper limit of zero, which indicates infinity.

  - The upper limit of an interval must be the lower limit of the next interval.

If an amount is the upper limit of the previous interval and the lower limit of the next interval, the sales tax rate of the first interval will be applied to the amount.

If an amount falls outside the intervals that are defined by upper and lower limits, a sales tax rate of zero will be applied.


> [!NOTE]
> <P>To set up tax intervals for the sales tax code that you select in the <STRONG>Sales tax codes</STRONG> form, click <STRONG>Values</STRONG> in that form. For more information, see <A href="https://technet.microsoft.com/library/aa500790(v=ax.60)">Values of sales tax codes (form)</A>.</P>



## Example: Whole amount method of calculation

In the **Values** form, sales tax rates are set up in the following intervals.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Taxable amount interval</p></th>
<th><p>Tax rate</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>0.00 to 50.00</p></td>
<td><p>30%</p></td>
</tr>
<tr class="even">
<td><p>50.00 to 100.00</p></td>
<td><p>20%</p></td>
</tr>
<tr class="odd">
<td><p>100.00 to 0.00</p></td>
<td><p>10%</p></td>
</tr>
</tbody>
</table>


The sales tax is calculated on the whole taxable amount.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Taxable amount (price)</p></th>
<th><p>Calculation</p></th>
<th><p>Sales tax</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>35.00</p></td>
<td><p>35.00 * 0.30</p></td>
<td><p>10.50</p></td>
</tr>
<tr class="even">
<td><p>50.00</p></td>
<td><p>50.00 * 0.30</p></td>
<td><p>15.00</p></td>
</tr>
<tr class="odd">
<td><p>85.00</p></td>
<td><p>85.00 * 0.20</p></td>
<td><p>17.00</p></td>
</tr>
<tr class="even">
<td><p>305.00</p></td>
<td><p>305.00 * 0.10</p></td>
<td><p>30.50</p></td>
</tr>
</tbody>
</table>


## Example: Interval method of calculation

In the **Values** form, sales tax rates are set up in the following intervals.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Taxable amount interval</p></th>
<th><p>Tax rate</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>0.00 to 50.00</p></td>
<td><p>30%</p></td>
</tr>
<tr class="even">
<td><p>50.00 to 100.00</p></td>
<td><p>20%</p></td>
</tr>
<tr class="odd">
<td><p>100.00 to 0.00</p></td>
<td><p>10%</p></td>
</tr>
</tbody>
</table>


The sales tax is the sum of the tax amounts that are calculated for each amount interval.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Taxable amount (price)</p></th>
<th><p>Calculation</p></th>
<th><p>Sales tax</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>35.00</p></td>
<td><p>35.00 * 0.30</p></td>
<td><p>10.50</p></td>
</tr>
<tr class="even">
<td><p>50.00</p></td>
<td><p>50.00 * 0.30</p></td>
<td><p>15.00</p></td>
</tr>
<tr class="odd">
<td><p>85.00</p></td>
<td><p>(50.00 * 0.30 = 15.00) + (35.00 * 0.20 = 7.00)</p></td>
<td><p>22.00</p></td>
</tr>
<tr class="even">
<td><p>305.00</p></td>
<td><p>(50.00 * 0.30 = 15.00) + (50.00 * 0.20 = 10.00) + (205 * 0.10 = 20.50)</p></td>
<td><p>45.50</p></td>
</tr>
</tbody>
</table>


## See also

[About the Marginal base field](about-the-marginal-base-field.md)

  


