---
title: (IND) About EXIM duty drawback (DBK) incentive schemes
TOCTitle: (IND) About EXIM duty drawback (DBK) incentive schemes
ms:assetid: 8c0c6201-6e45-47aa-a3b1-0c3bdd543b22
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678028(v=AX.60)
ms:contentKeyID: 49385989
ms.date: 05/01/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- india
- incentive scheme
- EXIM
- DBK
- EXIM DBK incentive scheme
audience: Application User
ms.search.region: India
---

# (IND) About EXIM duty drawback (DBK) incentive schemes 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Duty drawback (DBK) incentive schemes are issued by the Directorate of Drawback. DBK is the rebate of any duty that is chargeable on imported or excisable materials that you use to manufacture or process goods that you then export from India. Duty drawback is the sum of the following amounts:

  - Customs duty that is paid on imported input goods. This includes Special Addition Duty (SAD)

  - Excise duty that is paid on indigenous input goods

  - Duty that is paid on packing material

If customs or excise duty is paid for a portion of the input goods, only that portion is eligible for duty drawback. Input goods that you obtain without paying customs or excise duty are not eligible for DBK.

Rate types for duty drawback include the following:

  - **All Industry Rates** – These rates apply to various product categories as a percentage of the Free on Board (FOB) price of the exported products. A value cap is applied to certain product categories.

  - **Brand Rate** – This rate pertains only to special products.

  - **Special Brand Rate** – A company can apply for this rate if the actual duty that is paid on the input goods is higher than the All Industry Rate that is fixed for the product.

## Calculating duty drawback

Allowed duty drawback is calculated based on the following factors:

  - The minimum percent of duty drawback

  - The minimum amount of duty drawback

  - The duty drawback amount

You set the minimum percent of duty drawback and the minimum amount of duty drawback in the **DBK** area in the **Incentive scheme parameters** form. The following conditions are applied to these values to determine the amount of duty drawback that is allowed.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Condition</p></th>
<th><p>Allowed duty drawback</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>The duty drawback amount is greater than the minimum percent of duty drawback <em>and</em> greater than the minimum amount of duty drawback.</p></td>
<td><p>Duty drawback amount</p></td>
</tr>
<tr class="even">
<td><p>The duty drawback amount is less than the minimum percent of duty drawback <em>and</em> less than the minimum amount of duty drawback.</p></td>
<td><p>0 (zero)</p></td>
</tr>
<tr class="odd">
<td><p>If the duty drawback amount is greater than or equal to the minimum amount of duty drawback, the following condition applies:</p>
<ul>
<li><p>The drawback amount is greater than or equal to (export value) * (minimum percent of duty drawback/100)</p></li>
</ul></td>
<td><p>Duty drawback amount</p></td>
</tr>
<tr class="even">
<td><p>If the duty drawback amount is less than or equal to the minimum amount of duty drawback, the following condition applies:</p>
<ul>
<li><p>The drawback amount is less than (export value) * (minimum percent of duty drawback/100)</p></li>
</ul></td>
<td><p>0 (zero)</p></td>
</tr>
</tbody>
</table>


## Examples of calculations for allowed duty drawback

The following examples illustrate various duty drawback calculations. In these examples, the following values remain constant:

  - Minimum amount for duty drawback = 500.00

  - Minimum percent for duty drawback = 1.00

## Example 1

The duty drawback amount is greater than the minimum amount for duty drawback and the minimum percent for duty drawback.

Drawback amount = 509.25

509.25 \> 500.00 and 509.25 \> 5.00

Allowed duty drawback = 509.25

## Example 2

The duty drawback amount is greater than or equal to the minimum amount for duty drawback.

Drawback amount = 6,208.00

Export value = 64,000.00

64,000.00 \* (1.00)/100) = 640.00

6,208.00 ≥ 640.00

Allowed duty drawback = 6,208.00

## Example 3

The duty drawback amount is less than or equal to the minimum amount for duty drawback.

Drawback amount = 242.00

Export value = 48,500.00

48,500.00 \* (1.00)/100) = 485

242.00 \< 485.00

Allowed drawback = 0 (zero)

## See also

[(IND) Apply for duty drawback (DBK) for an export order](ind-apply-for-duty-drawback-dbk-for-an-export-order.md)

[(IND) Duty drawback (form)](https://technet.microsoft.com/en-us/library/jj664713\(v=ax.60\))

[(IND) Total Duty Drawback amount (form)](https://technet.microsoft.com/en-us/library/jj678025\(v=ax.60\))

  


