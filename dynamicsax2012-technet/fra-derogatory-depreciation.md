---
title: (FRA) Derogatory depreciation
TOCTitle: (FRA) Derogatory depreciation
ms:assetid: 536d211c-fde1-41db-9e19-b15ee8440f18
ms:mtpsurl: https://technet.microsoft.com/library/Hh208952(v=AX.60)
ms:contentKeyID: 36057297
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: France
---

# (FRA) Derogatory depreciation 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Derogatory depreciation is an additional depreciation amount that is calculated from the difference between the tax value model depreciation amount and the accounting value model depreciation amount during the life of the fixed asset. If the amount is positive, the transaction type is **Derogatory decrease**. If the amount is negative, the transaction type is **Derogatory increase**.

For example, a EUR 1,000 fixed asset is depreciated in accounting for five years and in tax for three years. In this example, the accounting depreciation for the first year is EUR 200 (1000/5), and the extra tax amount is EUR 133.33 (1000/3 – 1000/5, or 333.33 -200.00).

The accounting and tax books can use the same depreciation profile, or they can use different depreciation profiles. For example, the accounting book may use a straight line profile, whereas the tax book can use a reducing balance profile. For more information about depreciation profiles, see [Set up depreciation profiles](set-up-depreciation-profiles.md).

To use derogatory depreciation, the value models must meet the following requirements:

  - You clear the **Allow negative net book value** check box in the **Value models** form for both the accounting and tax value models.

  - You select the same calendar for fixed assets in the **Value models** form for both the accounting and tax value models.

  - If the depreciation method for the depreciation profile is **Reducing balance**, you select the **Full depreciation** check box for the tax value model in the **Depreciation profiles** form.

  - The depreciation profiles that are selected for both the accounting and tax value models have the same depreciation year and period frequency.

  - The placed-in-service date for both the accounting and tax value models are the same as soon as the value models are assigned to an asset.

## See also

[Depreciation profiles (form)](https://technet.microsoft.com/library/aa549887\(v=ax.60\))

[Create a depreciation profile](create-a-depreciation-profile.md)

[Value models (form)](https://technet.microsoft.com/library/aa590830\(v=ax.60\))

[Set up value models](set-up-value-models.md)

  


