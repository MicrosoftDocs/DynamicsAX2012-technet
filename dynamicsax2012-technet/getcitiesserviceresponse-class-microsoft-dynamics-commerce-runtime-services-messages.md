---
title: GetCitiesServiceResponse Class (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetCitiesServiceResponse Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCitiesServiceResponse
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getcitiesserviceresponse(v=AX.60)
ms:contentKeyID: 62203937
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCitiesServiceResponse
dev_langs:
- CSharp
- C++
- VB
---

# GetCitiesServiceResponse Class

Response object for retrieve a list of cities.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class GetCitiesServiceResponse _
    Inherits GetAddressInfoServiceResponse(Of CityInfo)
'Usage
Dim instance As GetCitiesServiceResponse
```

``` csharp
[DataContractAttribute]
public class GetCitiesServiceResponse : GetAddressInfoServiceResponse<CityInfo>
```

``` c++
[DataContractAttribute]
public ref class GetCitiesServiceResponse : public GetAddressInfoServiceResponse<CityInfo^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Response](response-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAddressInfoServiceResponse](getaddressinfoserviceresponse-taddressentityinfo-class-microsoft-dynamics-commerce-runtime-services-messages.md)\<[CityInfo](cityinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
      Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCitiesServiceResponse  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

