---
title: About sales price models
TOCTitle: About sales price models
ms:assetid: 02d4b589-6f84-4277-87d0-9411d5eec814
ms:mtpsurl: https://technet.microsoft.com/library/Aa569699(v=AX.60)
ms:contentKeyID: 42117746
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- miscellaneous charges
- sales price
- contribution ratio
- Misc. charges
- sales price model
- search direction
- search priority
audience: Application User
ms.search.region: Global
---

# About sales price models 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you set up sales prices for project expense transactions and hour transactions, you can apply a sales price model. A sales price model specifies the calculation method that is used to determine the final sales price for a transaction. The numbers that you enter in the **Pricing** fields in the **Sales price (hour)** form and **Sales price (expense)** form are either amounts or percentages, depending on the selection in the **Sales price model** field.

The following table describes the affect that each sales price model has on how a sales price is determined.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Sales price model</p></th>
<th><p>Description</p></th>
<th><p>Formula</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Qty.</strong></p></td>
<td><p>The amount that you enter in the <strong>Pricing</strong> field is the actual cost per quantity or unit.</p></td>
<td><p>No formula is used for this sales price model. The number that you enter in the <strong>Pricing</strong> field is the price per quantity.</p></td>
</tr>
<tr class="even">
<td><p><strong>Contribution ratio</strong></p></td>
<td><p>The number that you enter in the <strong>Pricing</strong> field is the contribution ratio expressed as a percentage of the sales price.</p></td>
<td><p>(100 * cost price) / (100 - Pricing)</p>
<p><strong>Example</strong></p>
<p>You want a contribution ratio of 10 percent for an hour category. The cost price for the category is EUR 50. You use the following calculation:</p>
<p>(100 * 50) / (100 - 10) = Sales price EUR 55.55</p></td>
</tr>
<tr class="odd">
<td><p><strong>Charges percentage</strong></p></td>
<td><p>The sales price per transaction is the cost price per transaction multiplied by the charges percentage. You enter the charges percentage in the <strong>Pricing</strong> field.</p></td>
<td><p>Cost price * (100 + pricing) / 100</p>
<p><strong>Example</strong></p>
<p>The charges percentage for a particular hour category is 5 percent. The cost price is EUR 20. You use the following calculation:</p>
<p>(20 * (100 + 5)) / 100 = Sales price EUR 21.00</p></td>
</tr>
<tr class="even">
<td><p><strong>Charges amount</strong></p></td>
<td><p>The sales price per transaction is the cost price per transaction plus the charges amount. You enter the charges amount in the <strong>Pricing</strong> field.</p></td>
<td><p>Cost price + pricing amount</p>
<p><strong>Example</strong></p>
<p>The fixed-price administration charge on a particular expense category is EUR 10. The cost price is EUR 90. You use the following calculation:</p>
<p>EUR 90 + EUR 10 = Sales price EUR 100.00</p></td>
</tr>
</tbody>
</table>


## See also

[Set up cost prices and sales prices for projects](set-up-cost-prices-and-sales-prices-for-projects.md)

[Sales price - hour (form)](https://technet.microsoft.com/library/aa634053\(v=ax.60\))

[Sales price - expenses (form)](https://technet.microsoft.com/library/aa599787\(v=ax.60\))

[About cost prices, sales prices, and transfer prices in projects](about-cost-prices-sales-prices-and-transfer-prices-in-projects.md)

  


