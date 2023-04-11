---
title: ICachedPricingDataManager.PutMixAndMatchLineGroupsByOffer Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutMixAndMatchLineGroupsByOffer Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutMixAndMatchLineGroupsByOffer(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.MixAndMatchLineGroup})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedpricingdatamanager.putmixandmatchlinegroupsbyoffer(v=AX.60)
ms:contentKeyID: 65319118
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutMixAndMatchLineGroupsByOffer
dev_langs:
- CSharp
- C++
- VB
---

# PutMixAndMatchLineGroupsByOffer Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutMixAndMatchLineGroupsByOffer ( _
    offerId As String, _
    settings As QueryResultSettings, _
    result As ReadOnlyCollection(Of MixAndMatchLineGroup) _
)
'Usage
Dim instance As ICachedPricingDataManager
Dim offerId As String
Dim settings As QueryResultSettings
Dim result As ReadOnlyCollection(Of MixAndMatchLineGroup)

instance.PutMixAndMatchLineGroupsByOffer(offerId, _
    settings, result)
```

``` csharp
void PutMixAndMatchLineGroupsByOffer(
    string offerId,
    QueryResultSettings settings,
    ReadOnlyCollection<MixAndMatchLineGroup> result
)
```

``` c++
void PutMixAndMatchLineGroupsByOffer(
    String^ offerId, 
    QueryResultSettings^ settings, 
    ReadOnlyCollection<MixAndMatchLineGroup^>^ result
)
```

#### Parameters

  - offerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[MixAndMatchLineGroup](mixandmatchlinegroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedPricingDataManager Interface](icachedpricingdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

