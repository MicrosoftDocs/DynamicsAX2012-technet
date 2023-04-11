---
title: ChannelManager.GetCities Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetCities Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetCities(System.String,System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.channelmanager.getcities(v=AX.60)
ms:contentKeyID: 65316660
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetCities
dev_langs:
- CSharp
- C++
- VB
---

# GetCities Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetCities ( _
    countryRegion As String, _
    stateProvinceId As String, _
    countyId As String, _
    settings As QueryResultSettings _
) As PagedResult(Of CityInfo)
'Usage
Dim instance As ChannelManager
Dim countryRegion As String
Dim stateProvinceId As String
Dim countyId As String
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of CityInfo)

returnValue = instance.GetCities(countryRegion, _
    stateProvinceId, countyId, settings)
```

``` csharp
public PagedResult<CityInfo> GetCities(
    string countryRegion,
    string stateProvinceId,
    string countyId,
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<CityInfo^>^ GetCities(
    String^ countryRegion, 
    String^ stateProvinceId, 
    String^ countyId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - countryRegion  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - stateProvinceId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - countyId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[CityInfo](cityinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ChannelManager Class](channelmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

