---
title: ChannelManager.GetCountries Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetCountries Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetCountries(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.channelmanager.getcountries(v=AX.60)
ms:contentKeyID: 65319249
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetCountries
dev_langs:
- CSharp
- C++
- VB
---

# GetCountries Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetCountries ( _
    languageId As String, _
    settings As QueryResultSettings _
) As PagedResult(Of CountryRegionInfo)
'Usage
Dim instance As ChannelManager
Dim languageId As String
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of CountryRegionInfo)

returnValue = instance.GetCountries(languageId, _
    settings)
```

``` csharp
public PagedResult<CountryRegionInfo> GetCountries(
    string languageId,
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<CountryRegionInfo^>^ GetCountries(
    String^ languageId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - languageId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[CountryRegionInfo](countryregioninfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ChannelManager Class](channelmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

