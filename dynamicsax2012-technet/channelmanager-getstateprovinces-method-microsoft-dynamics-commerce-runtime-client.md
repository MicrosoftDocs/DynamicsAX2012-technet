---
title: ChannelManager.GetStateProvinces Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetStateProvinces Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetStateProvinces(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.channelmanager.getstateprovinces(v=AX.60)
ms:contentKeyID: 65320666
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetStateProvinces
dev_langs:
- CSharp
- C++
- VB
---

# GetStateProvinces Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetStateProvinces ( _
    countryRegion As String, _
    settings As QueryResultSettings _
) As PagedResult(Of StateProvinceInfo)
'Usage
Dim instance As ChannelManager
Dim countryRegion As String
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of StateProvinceInfo)

returnValue = instance.GetStateProvinces(countryRegion, _
    settings)
```

``` csharp
public PagedResult<StateProvinceInfo> GetStateProvinces(
    string countryRegion,
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<StateProvinceInfo^>^ GetStateProvinces(
    String^ countryRegion, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - countryRegion  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[StateProvinceInfo](stateprovinceinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ChannelManager Class](channelmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

