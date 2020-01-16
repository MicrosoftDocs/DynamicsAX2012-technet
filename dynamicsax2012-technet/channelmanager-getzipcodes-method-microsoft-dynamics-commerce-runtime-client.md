---
title: ChannelManager.GetZipCodes Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetZipCodes Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetZipCodes(System.String,System.String,System.String,System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.channelmanager.getzipcodes(v=AX.60)
ms:contentKeyID: 65318189
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetZipCodes
dev_langs:
- CSharp
- C++
- VB
---

# GetZipCodes Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetZipCodes ( _
    countryRegion As String, _
    stateProvinceId As String, _
    countyId As String, _
    city As String, _
    district As String, _
    settings As QueryResultSettings _
) As PagedResult(Of ZipCodeInfo)
'Usage
Dim instance As ChannelManager
Dim countryRegion As String
Dim stateProvinceId As String
Dim countyId As String
Dim city As String
Dim district As String
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of ZipCodeInfo)

returnValue = instance.GetZipCodes(countryRegion, _
    stateProvinceId, countyId, city, _
    district, settings)
```

``` csharp
public PagedResult<ZipCodeInfo> GetZipCodes(
    string countryRegion,
    string stateProvinceId,
    string countyId,
    string city,
    string district,
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<ZipCodeInfo^>^ GetZipCodes(
    String^ countryRegion, 
    String^ stateProvinceId, 
    String^ countyId, 
    String^ city, 
    String^ district, 
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

  - district  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[ZipCodeInfo](zipcodeinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ChannelManager Class](channelmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

