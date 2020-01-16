---
title: About hour-related cost price fields
TOCTitle: About hour-related cost price fields
ms:assetid: c8f69c4c-b905-4ee3-a666-9400298e8d64
ms:mtpsurl: https://technet.microsoft.com/library/Hh694719(v=AX.60)
ms:contentKeyID: 42117778
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About hour-related cost price fields 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following example illustrates how the mathematical equations in the **Cost price** field group are calculated in the **Hour** form. (Click **Project management and accounting** \> **Inquiries** \> **Transactions** \> **Hour**.)

**Example**

The following assumptions apply to the example:

  - An organization in the United States has a customer in France.

  - The accounting currency of the organization is USD, and hourly costs are expressed in USD also.

  - The customer utilizes a total of 40 hours, at the sales price of USD 50 per hour.

The following table explains how the amounts in the hour-related cost price fields are calculated for this example.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Method</p></th>
<th><p>Formula</p></th>
<th><p>Total</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Hours</strong></p></td>
<td><p>Hours utilized</p>
<p></p></td>
<td><p>40</p></td>
<td><p>40</p></td>
</tr>
<tr class="even">
<td><p><strong>Cost price</strong></p></td>
<td><p>Price per hour</p></td>
<td><p>1 x 50</p></td>
<td><p>USD 50</p></td>
</tr>
<tr class="odd">
<td><p><strong>Total cost amount</strong></p></td>
<td><p>Hours utilized x cost price per unit</p>
<p></p></td>
<td><p>40 x 50</p></td>
<td><p>USD 2,000</p></td>
</tr>
</tbody>
</table>


## See also

[Hour transactions (form)](https://technet.microsoft.com/library/aa572825\(v=ax.60\))

[Set up cost prices and sales prices for projects](set-up-cost-prices-and-sales-prices-for-projects.md)

[Configuring cost prices, sales prices, and transfer prices](configuring-cost-prices-sales-prices-and-transfer-prices.md)

[Cost price - hour (form)](https://technet.microsoft.com/library/aa572459\(v=ax.60\))

  


