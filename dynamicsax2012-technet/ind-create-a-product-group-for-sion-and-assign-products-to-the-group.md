---
title: (IND) Create a product group for SION and assign products to the group
TOCTitle: (IND) Create a product group for SION and assign products to the group
ms:assetid: 09e94141-b3e5-4d98-a2f3-cf7f4801c159
ms:mtpsurl: https://technet.microsoft.com/library/JJ664462(v=AX.60)
ms:contentKeyID: 49385541
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- item
- (IND)
- india
- attach product group
- product group
audience: Application User
ms.search.region: India
---

# (IND) Create a product group for SION and assign products to the group 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create product groups based on Standard Input Output Norms (SION), and then assign products to the product groups to classify products for export-import (EXIM) transactions.

Use the following procedures to create a product group for the SION, and then assign products to the product group.


> [!NOTE]
> <P>You can complete these procedures only if you have enabled incentive schemes in the <STRONG>General ledger parameters</STRONG> form.</P>



## Create a product group

1.  Click **Inventory management** \> **Setup** \> **EXIM** \> **Product groups**.

2.  In the **Product groups** form, click **New**.

3.  In the **Product group** field, enter a unique identifier for the product group.

4.  In the **Description** field, enter a brief description of the product group.

## Assign a product to a product group


> [!NOTE]
> <P>After you assign a product to a product group for the SION, you cannot delete the product.</P>



1.  Click **Product information management** \> **Common** \> **Released products**. In the **Released products** list, open a product. Or, on the **Action Pane**, on the **Product** tab, in the **New** group, click **Product** to create a new one. If you create a new product, open it.

2.  In the **Released product details** form, on the **Action Pane**, on the **Product** tab, in the **Maintain** group, click **Edit**.

3.  On the **Foreign trade** FastTab, in the **EXIM incentive schemes** group, select a product group for the product.

## See also

[(IND) Set up the SION](ind-set-up-the-sion.md)

[(IND) Set up the SION items](ind-set-up-the-sion-items.md)

[(IND) Released product details (modified form)](https://technet.microsoft.com/library/jj677909\(v=ax.60\))

  


