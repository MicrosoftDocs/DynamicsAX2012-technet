---
title: (RUS) Factor depreciation method
TOCTitle: (RUS) Factor depreciation method
ms:assetid: 291efbcd-0ca1-47bb-ba3f-d28e5d5b8401
ms:mtpsurl: https://technet.microsoft.com/library/JJ665223(v=AX.60)
ms:contentKeyID: 49387312
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Factor depreciation method 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



When you use the factor depreciation method, the fixed asset depreciation amount is calculated as a remaining amount, multiplied by a fixed ratio.

Select the period for depreciation accrual in the **Interval** field, in the **Depreciation method** form.

If you select the reducing balance or non-linear depreciation methods, specify the increasing factor. If you select the factor depreciation method, specify the amount of the multiplier.

For the non-linear method, enter the cutoff percentage value in the **Factor** field (for example, 20). When the accrued depreciation amount is calculated, the depreciation amount for the year will be recalculated based on the service life and depreciation profile for the asset. The depreciation is distributed equally across the intervals in the year.


> [!NOTE]
> <P>For more information, see "Factor depreciation" in the Applications and Business Processes Help.</P>



## See also

[(RUS) Depreciation methods (form)](https://technet.microsoft.com/library/jj856184\(v=ax.60\))

[(RUS) Set up depreciation methods](rus-set-up-depreciation-methods.md)

  


