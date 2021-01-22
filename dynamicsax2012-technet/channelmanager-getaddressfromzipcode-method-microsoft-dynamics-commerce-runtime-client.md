---
title: ChannelManager.GetAddressFromZipCode Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetAddressFromZipCode Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetAddressFromZipCode(System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.channelmanager.getaddressfromzipcode(v=AX.60)
ms:contentKeyID: 65322630
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetAddressFromZipCode
dev_langs:
- CSharp
- C++
- VB
---

# GetAddressFromZipCode Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetAddressFromZipCode ( _
    countryRegion As String, _
    zipPostalCode As String, _
    settings As QueryResultSettings _
) As PagedResult(Of ZipCodeInfo)
'Usage
Dim instance As ChannelManager
Dim countryRegion As String
Dim zipPostalCode As String
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of ZipCodeInfo)

returnValue = instance.GetAddressFromZipCode(countryRegion, _
    zipPostalCode, settings)
```

``` csharp
public PagedResult<ZipCodeInfo> GetAddressFromZipCode(
    string countryRegion,
    string zipPostalCode,
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<ZipCodeInfo^>^ GetAddressFromZipCode(
    String^ countryRegion, 
    String^ zipPostalCode, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - countryRegion  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - zipPostalCode  
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

