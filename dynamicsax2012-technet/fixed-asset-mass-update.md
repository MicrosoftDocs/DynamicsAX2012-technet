---
title: Fixed asset mass update
TOCTitle: Fixed asset mass update
ms:assetid: 60561904-f9a7-4750-96df-d8cf0d8aedc5
ms:mtpsurl: https://technet.microsoft.com/library/Aa571109(v=AX.60)
ms:contentKeyID: 36057618
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Fixed asset mass update 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If you use depreciation books, you can change the depreciation conventions for groups of assets that are part of the same depreciation book. For example, if you are in the United States, and you put more than 40 percent of your assets in service during the fourth quarter of the year, you must use the mid-quarter depreciation convention. You can use the process for a mass update to change all assets that require the new depreciation convention.

When you update the depreciation convention for assets, you delete all depreciation transactions that exist for those assets. You also delete all transactions for depreciation adjustments, transactions for bonus depreciation, and transactions for extraordinary depreciation for those assets.

To update the depreciation convention for assets that have already been disposed of, you must first delete the existing disposal transactions. You must also delete all transactions that were generated because of the disposal process.

After you update the depreciation convention for assets, you can process depreciation and extraordinary depreciation for each asset. You can also make manual depreciation adjustments, if any adjustments are required.

## See also

[Change depreciation conventions for multiple fixed assets](change-depreciation-conventions-for-multiple-fixed-assets.md)

  


