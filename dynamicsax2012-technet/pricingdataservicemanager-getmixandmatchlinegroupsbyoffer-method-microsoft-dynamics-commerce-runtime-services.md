﻿---
title: PricingDataServiceManager.GetMixAndMatchLineGroupsByOffer Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: GetMixAndMatchLineGroupsByOffer Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetMixAndMatchLineGroupsByOffer(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.pricingdataservicemanager.getmixandmatchlinegroupsbyoffer(v=AX.60)
ms:contentKeyID: 65321080
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetMixAndMatchLineGroupsByOffer
dev_langs:
- CSharp
- C++
- VB
---

# GetMixAndMatchLineGroupsByOffer Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Function GetMixAndMatchLineGroupsByOffer ( _
    offerId As String, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of MixAndMatchLineGroup)
'Usage
Dim instance As PricingDataServiceManager
Dim offerId As String
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of MixAndMatchLineGroup)

returnValue = instance.GetMixAndMatchLineGroupsByOffer(offerId, _
    settings)
```

``` csharp
public ReadOnlyCollection<MixAndMatchLineGroup> GetMixAndMatchLineGroupsByOffer(
    string offerId,
    QueryResultSettings settings
)
```

``` c++
public:
virtual ReadOnlyCollection<MixAndMatchLineGroup^>^ GetMixAndMatchLineGroupsByOffer(
    String^ offerId, 
    QueryResultSettings^ settings
) sealed
```

#### Parameters

  - offerId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[MixAndMatchLineGroup](mixandmatchlinegroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Implements

[IPricingDataManager.GetMixAndMatchLineGroupsByOffer(String, QueryResultSettings)](ipricingdatamanager-getmixandmatchlinegroupsbyoffer-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[PricingDataServiceManager Class](pricingdataservicemanager-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)
