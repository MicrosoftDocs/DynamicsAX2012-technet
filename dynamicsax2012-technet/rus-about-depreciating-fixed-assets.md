---
title: (RUS) About depreciating fixed assets
TOCTitle: (RUS) About depreciating fixed assets
ms:assetid: 42811470-b9c6-42de-8ab8-c7b8a9c2f7ea
ms:mtpsurl: https://technet.microsoft.com/library/JJ923410(v=AX.60)
ms:contentKeyID: 52075369
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) About depreciating fixed assets 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Depreciation is calculated over the entire useful life of a fixed asset or an intangible asset. Parameters, such as the depreciation method and useful life, are determined for the depreciation group within the framework of the value model, and by default, are assigned to all assets that belong to this group. However, the default depreciation profile and the useful life of a fixed asset or inventory asset can be changed.

Transactions that affect a depreciated asset also affect the useful life of the asset. The change history is recorded in the relevant journal. The depreciation calculation transaction is created from the first date of the period that the depreciation is calculated for.

Depreciation is not calculated during major repairs or temporary deactivation. During this time, the **Temporary closing-down** status is assigned. Depreciation calculation then resumes when the asset is reactivated. Depreciation is calculated until the value of the asset is fully depreciated, and the asset is assigned a status of **Closed** or **Written off**.

## See also

[(RUS) Create the product output or mileage of a fixed asset](rus-create-the-product-output-or-mileage-of-a-fixed-asset.md)

[(RUS) Calculate or reverse fixed asset depreciation](rus-calculate-or-reverse-fixed-asset-depreciation.md)

[(RUS) Calculate a bonus depreciation](rus-calculate-a-bonus-depreciation.md)

  


