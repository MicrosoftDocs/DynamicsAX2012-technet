---
title: IPricingDataManagerV2.GetThresholdTiersByOfferIds Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetThresholdTiersByOfferIds Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2.GetThresholdTiersByOfferIds(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.ipricingdatamanagerv2.getthresholdtiersbyofferids(v=AX.60)
ms:contentKeyID: 62208598
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2.GetThresholdTiersByOfferIds
dev_langs:
- CSharp
- C++
- VB
---

# GetThresholdTiersByOfferIds Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get all the threshold tiers associated with the given offers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetThresholdTiersByOfferIds ( _
    offerIds As IEnumerable(Of String) _
) As ReadOnlyCollection(Of ThresholdDiscountTier)
'Usage
Dim instance As IPricingDataManagerV2
Dim offerIds As IEnumerable(Of String)
Dim returnValue As ReadOnlyCollection(Of ThresholdDiscountTier)

returnValue = instance.GetThresholdTiersByOfferIds(offerIds)
```

``` csharp
ReadOnlyCollection<ThresholdDiscountTier> GetThresholdTiersByOfferIds(
    IEnumerable<string> offerIds
)
```

``` c++
ReadOnlyCollection<ThresholdDiscountTier^>^ GetThresholdTiersByOfferIds(
    IEnumerable<String^>^ offerIds
)
```

#### Parameters

  - offerIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ThresholdDiscountTier](thresholddiscounttier-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Collection of tiers (if any) associated with the given offer Ids.  

## See Also

#### Reference

[IPricingDataManagerV2 Interface](ipricingdatamanagerv2-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

