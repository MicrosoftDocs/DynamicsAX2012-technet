---
title: About item-related cost price fields
TOCTitle: About item-related cost price fields
ms:assetid: 3b04590f-433a-4872-a1e2-eb90872b78fb
ms:mtpsurl: https://technet.microsoft.com/library/Hh694708(v=AX.60)
ms:contentKeyID: 42117753
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About item-related cost price fields 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following example illustrates how the mathematical equations in the **Cost price** field group are calculated in the **Item** form. (Click **Project management and accounting** \> **Inquiries** \> **Transactions** \> **Item**.)

**Example**

The following assumptions apply to the example:

  - An organization in the United States has a customer in France.

  - The accounting currency of the organization is USD, and the item costs are expressed in USD, also.

  - The customer purchases a quantity of 100 items at a price of USD 20 per item.

The following table explains how the amounts in the item-related cost price fields are calculated in this example.

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
<td><p><strong>Quantity</strong></p></td>
<td><p>Quantity of items purchased</p></td>
<td><p>100</p></td>
<td><p>100</p></td>
</tr>
<tr class="even">
<td><p><strong>Cost price</strong></p></td>
<td><p>Price per item</p></td>
<td><p>1 x 15</p></td>
<td><p>USD 15</p></td>
</tr>
<tr class="odd">
<td><p><strong>Cost amount</strong></p></td>
<td><p>Quantity of items x cost price per item</p></td>
<td><p>100 x 15</p></td>
<td><p>USD 1,500</p></td>
</tr>
</tbody>
</table>


## See also

[Item transactions (form)](https://technet.microsoft.com/library/aa599479\(v=ax.60\))

[Set up cost prices and sales prices for projects](set-up-cost-prices-and-sales-prices-for-projects.md)

[Configuring cost prices, sales prices, and transfer prices](configuring-cost-prices-sales-prices-and-transfer-prices.md)

  


