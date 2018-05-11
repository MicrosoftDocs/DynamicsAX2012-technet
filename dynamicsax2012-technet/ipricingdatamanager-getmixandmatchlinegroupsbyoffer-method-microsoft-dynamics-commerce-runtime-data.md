﻿---
title: IPricingDataManager.GetMixAndMatchLineGroupsByOffer Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetMixAndMatchLineGroupsByOffer Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManager.GetMixAndMatchLineGroupsByOffer(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.ipricingdatamanager.getmixandmatchlinegroupsbyoffer(v=AX.60)
ms:contentKeyID: 65321851
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManager.GetMixAndMatchLineGroupsByOffer
dev_langs:
- CSharp
- C++
- VB
---

# GetMixAndMatchLineGroupsByOffer Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetMixAndMatchLineGroupsByOffer ( _
    offerId As String, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of MixAndMatchLineGroup)
'Usage
Dim instance As IPricingDataManager
Dim offerId As String
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of MixAndMatchLineGroup)

returnValue = instance.GetMixAndMatchLineGroupsByOffer(offerId, _
    settings)
```

``` csharp
ReadOnlyCollection<MixAndMatchLineGroup> GetMixAndMatchLineGroupsByOffer(
    string offerId,
    QueryResultSettings settings
)
```

``` c++
ReadOnlyCollection<MixAndMatchLineGroup^>^ GetMixAndMatchLineGroupsByOffer(
    String^ offerId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - offerId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[MixAndMatchLineGroup](mixandmatchlinegroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[IPricingDataManager Interface](ipricingdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)
