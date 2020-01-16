---
title: ChannelManager.GetDistricts Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetDistricts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetDistricts(System.String,System.String,System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.channelmanager.getdistricts(v=AX.60)
ms:contentKeyID: 65318972
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetDistricts
dev_langs:
- CSharp
- C++
- VB
---

# GetDistricts Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetDistricts ( _
    countryRegion As String, _
    stateProvinceId As String, _
    countyId As String, _
    city As String, _
    settings As QueryResultSettings _
) As PagedResult(Of DistrictInfo)
'Usage
Dim instance As ChannelManager
Dim countryRegion As String
Dim stateProvinceId As String
Dim countyId As String
Dim city As String
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of DistrictInfo)

returnValue = instance.GetDistricts(countryRegion, _
    stateProvinceId, countyId, city, _
    settings)
```

``` csharp
public PagedResult<DistrictInfo> GetDistricts(
    string countryRegion,
    string stateProvinceId,
    string countyId,
    string city,
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<DistrictInfo^>^ GetDistricts(
    String^ countryRegion, 
    String^ stateProvinceId, 
    String^ countyId, 
    String^ city, 
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

  - city  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[DistrictInfo](districtinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ChannelManager Class](channelmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

