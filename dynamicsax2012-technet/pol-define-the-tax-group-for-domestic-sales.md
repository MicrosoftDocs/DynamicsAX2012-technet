---
title: (POL) Define the tax group for domestic sales
TOCTitle: (POL) Define the tax group for domestic sales
ms:assetid: 3034b38a-efbe-461d-b260-6e6bb122f489
ms:mtpsurl: https://technet.microsoft.com/library/JJ678170(v=AX.60)
ms:contentKeyID: 49386893
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Poland
---

# (POL) Define the tax group for domestic sales 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The domestic value-added tax (VAT) for export sales between members of the European Union (EU) must be posted, unless you receive either a single administrative document (SAD) from the customer or a confirmation of dispatch departure from the customs authority.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  Click **New**, and then enter the sales tax code and the sales tax name.

3.  In the **Type of tax** field, select **Standard VAT**.

4.  On the **General** FastTab, select the settlement period and the ledger posting group, and then click **Values**.

5.  In the **Values** form, click **New**, and then enter the start and end dates for when the sales tax code value is valid.

6.  Enter the minimum and maximum amounts to which the sales tax code can be applied, the tax percentage per unit, and any percentage of the tax amount that is exempt from the tax code. Close the form.

7.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**.

8.  Click **New**, and then enter information about the sales tax group.

9.  On the **Setup** FastTab, click **Add**, and then, in the **Sales tax code** field, select the sales tax code for VAT. Close the form.

10. Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

11. In the left pane, click **General**, and then, on the **Sales** FastTab, in the **Tax group for domestic sales** field, select the VAT sales tax group.

## See also

[(POL) Post VAT transactions](pol-post-vat-transactions.md)

[(POL) Accounts receivable parameters (modified form)](https://technet.microsoft.com/library/jj678183\(v=ax.60\))

  


