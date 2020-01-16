---
title: 'Example: Rounding payments made to sales tax authorities'
TOCTitle: 'Example: Rounding payments made to sales tax authorities'
ms:assetid: 27f356de-3786-40b0-b866-05aaacf69dfa
ms:mtpsurl: https://technet.microsoft.com/library/Aa496835(v=AX.60)
ms:contentKeyID: 39519075
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- rounding sales tax payments
audience: Application User
ms.search.region: Global
---

# Example: Rounding payments made to sales tax authorities 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The sales tax ledger account for a legal entity shows a credit balance of -98,765.43. The legal entity collected more sales taxes than it paid. Therefore, the legal entity owes money to the tax authority.

The legal entity wants to use a rounding method that rounds the balance to the nearest 1.00. The user who is responsible for sales tax accounting performs the following steps.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax authorities**.

2.  On the **General** FastTab, select **Normal** in the **Rounding form** field.

3.  In the **Round-off** field, enter 1.00.

4.  When it is time to pay the sales taxes to the tax authority, open the **Sales tax payment** form. (Click **General ledger** \> **Periodic** \> **Sales tax payments** \> **Sales tax payments**.) Run the periodic job. For more information, see [Sales tax payments (form)](https://technet.microsoft.com/library/aa583763\(v=ax.60\)).

5.  On the sales tax payments report, the tax amount of 98,765.43 is rounded to 98,765.

The following table shows how an amount of 98,765.43 is rounded by using each rounding method that is available in the **Rounding form** field in the **Sales tax authorities** form. For more information, see [Sales tax authorities (form)](https://technet.microsoft.com/library/aa552841\(v=ax.60\)).

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Rounding form</strong> option</p></th>
<th><p><strong>Round-off</strong> value = 0.01</p></th>
<th><p><strong>Round-off</strong> value = 0.10</p></th>
<th><p><strong>Round-off</strong> value = 1.00</p></th>
<th><p><strong>Round-off</strong> value = 100.00</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Normal</strong></p></td>
<td><p>98,765.43</p></td>
<td><p>98,765.40</p></td>
<td><p>98,765.00</p></td>
<td><p>98,800.00</p></td>
</tr>
<tr class="even">
<td><p><strong>Downward</strong></p></td>
<td><p>98,765.43</p></td>
<td><p>98,765.40</p></td>
<td><p>98,765.00</p></td>
<td><p>98,700.00</p></td>
</tr>
<tr class="odd">
<td><p><strong>Rounding-up</strong></p></td>
<td><p>98,765.43</p></td>
<td><p>98,765.50</p></td>
<td><p>98,766.00</p></td>
<td><p>98,800.00</p></td>
</tr>
<tr class="even">
<td><p><strong>Own advantage</strong>, for a credit balance</p>
<p></p></td>
<td><p>98,765.43</p></td>
<td><p>98,765.40</p></td>
<td><p>98,765.00</p></td>
<td><p>98,700.00</p></td>
</tr>
<tr class="odd">
<td><p><strong>Own advantage</strong>, for a debit balance</p>
<p></p></td>
<td><p>98,765.43</p></td>
<td><p>98,765.50</p></td>
<td><p>98,766.00</p></td>
<td><p>98,800.00</p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>If you select <STRONG>Own advantage</STRONG>, the rounding is always to the advantage of the legal entity.</P>



## See also

[Set up sales tax authorities](set-up-sales-tax-authorities.md)

  


