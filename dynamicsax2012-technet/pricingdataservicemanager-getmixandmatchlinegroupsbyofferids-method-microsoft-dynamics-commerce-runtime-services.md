---
title: PricingDataServiceManager.GetMixAndMatchLineGroupsByOfferIds Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: GetMixAndMatchLineGroupsByOfferIds Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetMixAndMatchLineGroupsByOfferIds(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingdataservicemanager.getmixandmatchlinegroupsbyofferids(v=AX.60)
ms:contentKeyID: 65318140
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetMixAndMatchLineGroupsByOfferIds
dev_langs:
- CSharp
- C++
- VB
---

# GetMixAndMatchLineGroupsByOfferIds Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Function GetMixAndMatchLineGroupsByOfferIds ( _
    offerIds As IEnumerable(Of String) _
) As ReadOnlyCollection(Of MixAndMatchLineGroup)
'Usage
Dim instance As PricingDataServiceManager
Dim offerIds As IEnumerable(Of String)
Dim returnValue As ReadOnlyCollection(Of MixAndMatchLineGroup)

returnValue = instance.GetMixAndMatchLineGroupsByOfferIds(offerIds)
```

``` csharp
public ReadOnlyCollection<MixAndMatchLineGroup> GetMixAndMatchLineGroupsByOfferIds(
    IEnumerable<string> offerIds
)
```

``` c++
public:
virtual ReadOnlyCollection<MixAndMatchLineGroup^>^ GetMixAndMatchLineGroupsByOfferIds(
    IEnumerable<String^>^ offerIds
) sealed
```

#### Parameters

  - offerIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[MixAndMatchLineGroup](mixandmatchlinegroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Implements

[IPricingDataManagerV2.GetMixAndMatchLineGroupsByOfferIds(IEnumerable\<String\>)](ipricingdatamanagerv2-getmixandmatchlinegroupsbyofferids-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[PricingDataServiceManager Class](pricingdataservicemanager-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

