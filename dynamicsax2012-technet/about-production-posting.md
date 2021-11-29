---
title: About production posting
TOCTitle: About production posting
ms:assetid: 0e39ce5a-c10e-4674-b338-71c3e1f75af8
ms:mtpsurl: https://technet.microsoft.com/library/Aa496407(v=AX.60)
ms:contentKeyID: 36056008
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- finished item cost
- inventory issues
- item consumption
- material consumption
- post productions
- production posting
- production posting accounts
audience: Application User
ms.search.region: Global
---

# About production posting 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Production posting activities follow the production process.

  - As items are consumed during production they are recorded in the production order. This process generates issue transactions to make up for the missing raw materials.

  - As the materials are consumed, they are posted to both the **Picking list issue** account and the **Picking list offset account**.

When the production is reported as finished, a receipt transaction is posted to the finished item. The cost calculated for the finished item is then posted to both the **Report as finished receipt** account and the **Reported as finished offset account**.

Finally, when production is complete, all accounts are updated with the final calculations. The raw materials that were actually consumed are credited to the account tracking inventory issues and debited from the account tracking item consumption. The overall cost of the finished item is debited from the inventory **Receipt** account and credited to the inventory **Issues** account.


> [!NOTE]
> <P>If the standard method for calculating the cost of the finished item was used, the final transactions also reflect this. If there is a difference between actual costs and costs calculated using the standard method, it is posted to the account showing profit or loss.</P>



## Summation of accounts the transactions are posted to during production

  - Picking list issue

  - Picking list offset account

  - Report as finished receipt

  - Reported as finished offset account

  - Issue

  - Issue offset account

  - Receipt

  - Receipt offset account

## See also

[About sales order posting types](about-sales-order-posting-types.md)

[About purchase order posting types](about-purchase-order-posting-types.md)

  


