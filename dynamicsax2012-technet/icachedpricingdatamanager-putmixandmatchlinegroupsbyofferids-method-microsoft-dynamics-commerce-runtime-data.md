---
title: ICachedPricingDataManager.PutMixAndMatchLineGroupsByOfferIds Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutMixAndMatchLineGroupsByOfferIds Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutMixAndMatchLineGroupsByOfferIds(System.Collections.Generic.IEnumerable{System.String},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.MixAndMatchLineGroup})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedpricingdatamanager.putmixandmatchlinegroupsbyofferids(v=AX.60)
ms:contentKeyID: 62211440
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutMixAndMatchLineGroupsByOfferIds
dev_langs:
- CSharp
- C++
- VB
---

# PutMixAndMatchLineGroupsByOfferIds Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Stores the result of a call to retrieve the mix and match line groups by offer ids.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutMixAndMatchLineGroupsByOfferIds ( _
    offerIds As IEnumerable(Of String), _
    result As ReadOnlyCollection(Of MixAndMatchLineGroup) _
)
'Usage
Dim instance As ICachedPricingDataManager
Dim offerIds As IEnumerable(Of String)
Dim result As ReadOnlyCollection(Of MixAndMatchLineGroup)

instance.PutMixAndMatchLineGroupsByOfferIds(offerIds, _
    result)
```

``` csharp
void PutMixAndMatchLineGroupsByOfferIds(
    IEnumerable<string> offerIds,
    ReadOnlyCollection<MixAndMatchLineGroup> result
)
```

``` c++
void PutMixAndMatchLineGroupsByOfferIds(
    IEnumerable<String^>^ offerIds, 
    ReadOnlyCollection<MixAndMatchLineGroup^>^ result
)
```

#### Parameters

  - offerIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[MixAndMatchLineGroup](mixandmatchlinegroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedPricingDataManager Interface](icachedpricingdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

