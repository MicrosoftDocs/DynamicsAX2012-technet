---
title: GetCountiesServiceResponse Constructor (IEnumerable(CountyInfo)) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetCountiesServiceResponse Constructor (IEnumerable(CountyInfo))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCountiesServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CountyInfo})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getcountiesserviceresponse.getcountiesserviceresponse(v=AX.60)
ms:contentKeyID: 62207653
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCountiesServiceResponse Constructor (IEnumerable(CountyInfo))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetCountiesServiceResponse](getcountiesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    counties As IEnumerable(Of CountyInfo) _
)
'Usage
Dim counties As IEnumerable(Of CountyInfo)

Dim instance As New GetCountiesServiceResponse(counties)
```

``` csharp
public GetCountiesServiceResponse(
    IEnumerable<CountyInfo> counties
)
```

``` c++
public:
GetCountiesServiceResponse(
    IEnumerable<CountyInfo^>^ counties
)
```

#### Parameters

  - counties  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[CountyInfo](countyinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetCountiesServiceResponse Class](getcountiesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetCountiesServiceResponse Overload](getcountiesserviceresponse-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

