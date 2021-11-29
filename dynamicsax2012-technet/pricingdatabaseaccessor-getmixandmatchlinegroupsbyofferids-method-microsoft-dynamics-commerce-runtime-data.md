---
title: PricingDatabaseAccessor.GetMixAndMatchLineGroupsByOfferIds Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetMixAndMatchLineGroupsByOfferIds Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.PricingDatabaseAccessor.GetMixAndMatchLineGroupsByOfferIds(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.pricingdatabaseaccessor.getmixandmatchlinegroupsbyofferids(v=AX.60)
ms:contentKeyID: 62214402
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.PricingDatabaseAccessor.GetMixAndMatchLineGroupsByOfferIds
dev_langs:
- CSharp
- C++
- VB
---

# GetMixAndMatchLineGroupsByOfferIds Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get all the mix and match line groups associated with the given offers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetMixAndMatchLineGroupsByOfferIds ( _
    offerIds As IEnumerable(Of String) _
) As ReadOnlyCollection(Of MixAndMatchLineGroup)
'Usage
Dim instance As PricingDatabaseAccessor
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
Collection of mix and match line groups associated with the given offer Ids.  

#### Implements

[IPricingDataManagerV2.GetMixAndMatchLineGroupsByOfferIds(IEnumerable\<String\>)](ipricingdatamanagerv2-getmixandmatchlinegroupsbyofferids-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[PricingDatabaseAccessor Class](pricingdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

