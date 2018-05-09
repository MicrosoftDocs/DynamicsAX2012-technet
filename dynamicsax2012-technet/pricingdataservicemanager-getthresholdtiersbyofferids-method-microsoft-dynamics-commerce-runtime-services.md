---
title: PricingDataServiceManager.GetThresholdTiersByOfferIds Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: GetThresholdTiersByOfferIds Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetThresholdTiersByOfferIds(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.pricingdataservicemanager.getthresholdtiersbyofferids(v=AX.60)
ms:contentKeyID: 65321659
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetThresholdTiersByOfferIds
dev_langs:
- CSharp
- C++
- VB
---

# GetThresholdTiersByOfferIds Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Function GetThresholdTiersByOfferIds ( _
    offerIds As IEnumerable(Of String) _
) As ReadOnlyCollection(Of ThresholdDiscountTier)
'Usage
Dim instance As PricingDataServiceManager
Dim offerIds As IEnumerable(Of String)
Dim returnValue As ReadOnlyCollection(Of ThresholdDiscountTier)

returnValue = instance.GetThresholdTiersByOfferIds(offerIds)
```

``` csharp
public ReadOnlyCollection<ThresholdDiscountTier> GetThresholdTiersByOfferIds(
    IEnumerable<string> offerIds
)
```

``` c++
public:
virtual ReadOnlyCollection<ThresholdDiscountTier^>^ GetThresholdTiersByOfferIds(
    IEnumerable<String^>^ offerIds
) sealed
```

#### Parameters

  - offerIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[ThresholdDiscountTier](thresholddiscounttier-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Implements

[IPricingDataManagerV2.GetThresholdTiersByOfferIds(IEnumerable\<String\>)](ipricingdatamanagerv2-getthresholdtiersbyofferids-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[PricingDataServiceManager Class](pricingdataservicemanager-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

