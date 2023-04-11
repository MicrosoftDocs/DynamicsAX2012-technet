---
title: GetCommerceListServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetCommerceListServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCommerceListServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceList})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getcommercelistserviceresponse.getcommercelistserviceresponse(v=AX.60)
ms:contentKeyID: 62210130
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCommerceListServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetCommerceListServiceResponse Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetCommerceListServiceResponse](getcommercelistserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    clists As IEnumerable(Of CommerceList) _
)
'Usage
Dim clists As IEnumerable(Of CommerceList)

Dim instance As New GetCommerceListServiceResponse(clists)
```

``` csharp
public GetCommerceListServiceResponse(
    IEnumerable<CommerceList> clists
)
```

``` c++
public:
GetCommerceListServiceResponse(
    IEnumerable<CommerceList^>^ clists
)
```

#### Parameters

  - clists  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[CommerceList](commercelist-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetCommerceListServiceResponse Class](getcommercelistserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

