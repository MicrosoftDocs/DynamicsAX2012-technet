---
title: GetCitiesServiceResponse Constructor (IEnumerable(CityInfo)) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetCitiesServiceResponse Constructor (IEnumerable(CityInfo))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCitiesServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CityInfo})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getcitiesserviceresponse.getcitiesserviceresponse(v=AX.60)
ms:contentKeyID: 62211452
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCitiesServiceResponse Constructor (IEnumerable(CityInfo))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetCitiesServiceResponse](getcitiesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    cities As IEnumerable(Of CityInfo) _
)
'Usage
Dim cities As IEnumerable(Of CityInfo)

Dim instance As New GetCitiesServiceResponse(cities)
```

``` csharp
public GetCitiesServiceResponse(
    IEnumerable<CityInfo> cities
)
```

``` c++
public:
GetCitiesServiceResponse(
    IEnumerable<CityInfo^>^ cities
)
```

#### Parameters

  - cities  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[CityInfo](cityinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetCitiesServiceResponse Class](getcitiesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetCitiesServiceResponse Overload](getcitiesserviceresponse-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

