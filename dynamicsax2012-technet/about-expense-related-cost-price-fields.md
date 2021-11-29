---
title: About expense-related cost price fields
TOCTitle: About expense-related cost price fields
ms:assetid: cf35c85b-0700-4781-af80-0b3c9f480624
ms:mtpsurl: https://technet.microsoft.com/library/Aa557411(v=AX.60)
ms:contentKeyID: 36059474
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Expense
- cost price
- expense transaction
audience: Application User
ms.search.region: Global
---

# About expense-related cost price fields 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following example illustrates the relationship between the fields in the **Cost price** group in the **Expense transactions** form.

To access the form, do the following: Click **Project management and accounting** \> **Inquiries** \> **Transactions** \> **Expense**.

**Example**

The following assumptions apply to the example:

  - A company located in the United States has a customer located in France.

  - The expenses incurred are expressed in EUR, and the default currency of the company (known as "company currency" in the example) is USD.

  - A quantity of 10 units is purchased by the customer, at the price of EUR 50 per unit.

  - The exchange rate of EUR 100 is USD 120.

  - The local US tax rate is 3 percent.
    
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
    <th><p>Formula</p></th>
    <th><p>Method</p></th>
    <th><p>Total</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Quantity</strong></p></td>
    <td><p>10</p></td>
    <td><p>Quantity bought</p></td>
    <td><p>10</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Amount</strong></p></td>
    <td><p>10 x 50 = 500</p></td>
    <td><p>Quantity x cost price per unit</p></td>
    <td><p>500</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Cost price</strong></p></td>
    <td><p>1 x 50</p></td>
    <td><p>Price per unit</p></td>
    <td><p>500</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Tax included</strong></p></td>
    <td><p>10 x 50 x .03.</p></td>
    <td><p>Quantity x cost price per unit x tax amount</p></td>
    <td><p>The local US tax amount on the total purchase.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Amount</strong></p></td>
    <td><p>10 x 50 x 1.2 + 3%</p></td>
    <td><p>Quantity x cost price per unit x exchange rate + tax amount</p></td>
    <td><p>USD 618 (local currency)</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Total cost amount</strong></p></td>
    <td><p>10 x 50 x 1.2 + 3%</p></td>
    <td><p>Quantity x cost price per unit x exchange rate + tax amount</p></td>
    <td><p>USD 618 (default currency)</p></td>
    </tr>
    </tbody>
    </table>


## See also

[Expense transactions (form)](https://technet.microsoft.com/library/aa599188\(v=ax.60\))

[Set up cost prices and sales prices for projects](set-up-cost-prices-and-sales-prices-for-projects.md)

[Configuring cost prices, sales prices, and transfer prices](configuring-cost-prices-sales-prices-and-transfer-prices.md)

[Cost price - expense (form)](https://technet.microsoft.com/library/aa571745\(v=ax.60\))

  


