---
title: Price simulation examples
TOCTitle: Price simulation examples
ms:assetid: 75d2be36-8cc4-4b48-a1f8-ee8720bf4d98
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa550031(v=AX.60)
ms:contentKeyID: 36058178
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Price simulation examples [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following examples use price simulation for quotation headers and single line items.

## Price simulation for quotation headers

You create a quotation that has the following lines:

10 units of item BR-12 (cost price per unit USD 9.52 and sales price per unit USD 15.32)

12 units of item BR-14 (cost price per unit USD 7.48 and sales price per unit USD 13.75)

The following table shows the quotation lines.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p></p></td>
<td><p><strong>Calculation</strong></p></td>
<td><p><strong>Result</strong></p></td>
</tr>
<tr class="even">
<td><p>Sales quantity</p></td>
<td><p>10 units + 12 units</p></td>
<td><p>22 units</p></td>
</tr>
<tr class="odd">
<td><p>Sales value in USD</p></td>
<td><p>(10*15.32) + (12*13.75)</p></td>
<td><p>318.20</p></td>
</tr>
<tr class="even">
<td><p>Cost value in USD</p></td>
<td><p>(10*9.52) + (12*7.48)</p></td>
<td><p>184.96</p></td>
</tr>
<tr class="odd">
<td><p>Contribution margin in USD</p></td>
<td><p>318.20 – 184.96</p></td>
<td><p>133.24</p></td>
</tr>
<tr class="even">
<td><p>Contribution ratio</p></td>
<td><p>(318.20 – (10*9.52)/318.20) * 100</p></td>
<td><p>41.87%</p></td>
</tr>
</tbody>
</table>


You run a price simulation and apply a 15 percent total discount for the whole quotation, or the quotation header. The following table shows the new totals of the quotation after the price simulation is run.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p></p></td>
<td><p><strong>Calculation</strong></p></td>
<td><p><strong>Result</strong></p></td>
</tr>
<tr class="even">
<td><p>Sales quantity</p></td>
<td><p>10 units + 12 units</p></td>
<td><p>22 units</p></td>
</tr>
<tr class="odd">
<td><p>Old sales value in USD</p></td>
<td><p>(10*15.32) + (12*13.75)</p></td>
<td><p>318.20</p></td>
</tr>
<tr class="even">
<td><p>Old cost value in USD</p></td>
<td><p>(10*9.52) + (12*7.48)</p></td>
<td><p>184.96</p></td>
</tr>
<tr class="odd">
<td><p>Old contribution margin in USD</p></td>
<td><p>318.20 – 184.96</p></td>
<td><p>133.24</p></td>
</tr>
<tr class="even">
<td><p>Old contribution ratio</p></td>
<td><p>(318.20 – (10*9.52)/318.20) * 100</p></td>
<td><p>41.87%</p></td>
</tr>
<tr class="odd">
<td><p>Price simulation of 15% total discount in USD</p></td>
<td><p>(15*318.2)/100</p></td>
<td><p>47.73</p></td>
</tr>
<tr class="even">
<td><p>New sales value in USD</p></td>
<td><p>318.20 – 47.73</p></td>
<td><p>270.47</p></td>
</tr>
<tr class="odd">
<td><p>New contribution margin in USD</p></td>
<td><p>270.47 – 184.96</p></td>
<td><p>85.51</p></td>
</tr>
<tr class="even">
<td><p>New contribution ratio</p></td>
<td><p>((270.47 – 184.96)/270.47) * 100</p></td>
<td><p>31.61%</p></td>
</tr>
</tbody>
</table>


## Price simulation for single line items

You create a quotation that has the following lines:

10 units of item BR-12 (cost price per unit USD 9.52 and sales price per unit USD 15.32)

12 units of item BR-14 (cost price per unit USD 7.48 and sales price per unit USD 13.75)

The following table shows the quotation lines.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p></p></td>
<td><p><strong>Result</strong></p></td>
<td><p><strong>Calculation</strong></p></td>
</tr>
<tr class="even">
<td><p>Sales quantity</p></td>
<td><p>10 units + 12 units</p></td>
<td><p>22 units</p></td>
</tr>
<tr class="odd">
<td><p>Sales value in USD for BR-12</p></td>
<td><p>10*15.32</p></td>
<td><p>153.20</p></td>
</tr>
<tr class="even">
<td><p>Sales value in USD for BR-14</p></td>
<td><p>12*13.75</p></td>
<td><p>165.00</p></td>
</tr>
<tr class="odd">
<td><p>Cost value in USD for BR-12</p></td>
<td><p>10*9.52</p></td>
<td><p>95.20</p></td>
</tr>
<tr class="even">
<td><p>Cost value in USD for BR-14</p></td>
<td><p>12*7.48</p></td>
<td><p>89.76</p></td>
</tr>
<tr class="odd">
<td><p>Contribution margin in USD for BR-12</p></td>
<td><p>153.20 – 95.20</p></td>
<td><p>58.00</p></td>
</tr>
<tr class="even">
<td><p>Contribution margin in USD for BR-14</p></td>
<td><p>165.00 – 89.76</p></td>
<td><p>75.24</p></td>
</tr>
<tr class="odd">
<td><p>Contribution ratio in USD for BR-12</p></td>
<td><p>((153.20 – 95.20)/153.20) * 100</p></td>
<td><p>37.86</p></td>
</tr>
<tr class="even">
<td><p>Contribution ratio in USD for BR-14</p></td>
<td><p>((165.00 – 89.76)/165.00) * 100</p></td>
<td><p>45.60</p></td>
</tr>
<tr class="odd">
<td><p>Total sales value in USD</p></td>
<td><p>(10*15.32) + (12*13.75)</p></td>
<td><p>318.20</p></td>
</tr>
<tr class="even">
<td><p>Total cost value in USD</p></td>
<td><p>(10*9.52) + (12*7.48)</p></td>
<td><p>184.96</p></td>
</tr>
<tr class="odd">
<td><p>Total contribution margin in USD</p></td>
<td><p>318.20 – 184.96</p></td>
<td><p>133.24</p></td>
</tr>
<tr class="even">
<td><p>Total contribution ratio</p></td>
<td><p>(318.20 – 184.96)/318.20) * 100</p></td>
<td><p>41.87%</p></td>
</tr>
</tbody>
</table>


You run a price simulation and apply a 10 percent total discount to the BR-12 units. The following table shows the new totals of the quotation after the price simulation is run for the single line item.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p></p></td>
<td><p><strong>Calculation</strong></p></td>
<td><p><strong>Result</strong></p></td>
</tr>
<tr class="even">
<td><p>Sales quantity</p></td>
<td><p>10 units + 12 units</p></td>
<td><p>22 units</p></td>
</tr>
<tr class="odd">
<td><p>Old sales value in USD for BR-12</p></td>
<td><p>10*15.32</p></td>
<td><p>153.20</p></td>
</tr>
<tr class="even">
<td><p>Price simulation of 10% discount for BR-12</p></td>
<td><p>(10*153.2)/100</p></td>
<td><p>15.32</p></td>
</tr>
<tr class="odd">
<td><p>New sales value in USD for BR-12</p></td>
<td><p>(10*15.32) – 15.32</p></td>
<td><p>137.88</p></td>
</tr>
<tr class="even">
<td><p>Sales value in USD for BR-14</p></td>
<td><p>12*13.75</p></td>
<td><p>165.00</p></td>
</tr>
<tr class="odd">
<td><p>Cost value in USD for BR-12</p></td>
<td><p>10*9.52</p></td>
<td><p>95.20</p></td>
</tr>
<tr class="even">
<td><p>Cost value in USD for BR-14</p></td>
<td><p>12*7.48</p></td>
<td><p>89.76</p></td>
</tr>
<tr class="odd">
<td><p>New contribution margin in USD for BR-12</p></td>
<td><p>137.88 – 95.20</p></td>
<td><p>42.68</p></td>
</tr>
<tr class="even">
<td><p>Contribution margin in USD for BR-14</p></td>
<td><p>165.00 – 89.76</p></td>
<td><p>75.24</p></td>
</tr>
<tr class="odd">
<td><p>New contribution ratio in USD for BR-12</p></td>
<td><p>((137.88 – 95.20)/137.88) * 100</p></td>
<td><p>30.95</p></td>
</tr>
<tr class="even">
<td><p>Contribution ratio in USD for BR-14</p></td>
<td><p>((165.00 – 89.76)/165.00) * 100</p></td>
<td><p>45.60</p></td>
</tr>
<tr class="odd">
<td><p>New total sales value in USD</p></td>
<td><p>(10*15.32 – 15.32) + (12*13.75)</p></td>
<td><p>302.88</p></td>
</tr>
<tr class="even">
<td><p>Total cost value in USD</p></td>
<td><p>(10*9.52) + (12*7.48)</p></td>
<td><p>184.96</p></td>
</tr>
<tr class="odd">
<td><p>New total contribution margin in USD</p></td>
<td><p>302.88 – 184.96</p></td>
<td><p>117.92</p></td>
</tr>
<tr class="even">
<td><p>New total contribution ratio</p></td>
<td><p>((302.88 – 184.96)/302.88) * 100</p></td>
<td><p>38.91%</p></td>
</tr>
</tbody>
</table>


The price simulation affects only the line to which it is applied, reducing the total for that line.

## See also

[Price simulation](price-simulation.md)

[Use price simulations](use-price-simulations.md)

[Price simulation and discounts](price-simulation-and-discounts.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

