---
title: Create a financial dimension set
TOCTitle: Create a financial dimension set
ms:assetid: 84d7673d-7023-474d-91fd-9b0de56c85eb
ms:mtpsurl: https://technet.microsoft.com/library/Aa571570(v=AX.60)
ms:contentKeyID: 37832516
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create a financial dimension set 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Financial dimension sets** form to create financial dimension. A financial dimension set contains either financial dimensions or financial dimension combinations. The main account is always included and can be combined with other financial dimensions. The main account can also be the only financial dimension that is included in a financial dimension set.

The order in which financial dimensions in a set are displayed determines how transactions are sorted and fields are printed on reports.

For example, a financial dimension set includes the Department and Cost center financial dimensions. The financial dimension set is set up so that the Department amounts are displayed first on reports, followed by the Cost center amounts.

When you view or report on financial transactions, the financial dimension sets that are defined can be used individually or in pairs. You can select a primary and secondary financial dimension set. The secondary financial dimension set includes more detailed information about the amounts that are in the primary financial dimension set.

1.  Click **General ledger** \> **Setup** \> **Financial dimensions** \> **Financial dimension sets**.

2.  Click **New** to create a line for a dimension set.

3.  In the **Financial dimension set** field, enter a unique identifier for the dimension set.

4.  In the **Name** field, enter a brief description of the dimension set.

5.  Move all the financial dimensions that you want to include in the set from the **Available financial dimensions** group to the **Selected financial dimensions** group. The financial dimension that you want to be displayed first must appear first in the **Selected financial dimensions** group.

## See also

[Financial dimension sets (form)](https://technet.microsoft.com/library/aa597282\(v=ax.60\))

  


