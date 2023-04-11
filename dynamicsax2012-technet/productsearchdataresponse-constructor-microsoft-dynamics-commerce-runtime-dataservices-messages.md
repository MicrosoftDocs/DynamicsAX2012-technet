---
title: ProductSearchDataResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ProductSearchDataResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ProductSearchDataResponse.#ctor(System.Collections.Generic.ICollection{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.productsearchdataresponse.productsearchdataresponse(v=AX.60)
ms:contentKeyID: 65320577
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ProductSearchDataResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# ProductSearchDataResponse Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [ProductSearchDataResponse](productsearchdataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    productIds As ICollection(Of Long) _
)
'Usage
Dim productIds As ICollection(Of Long)

Dim instance As New ProductSearchDataResponse(productIds)
```

``` csharp
public ProductSearchDataResponse(
    ICollection<long> productIds
)
```

``` c++
public:
ProductSearchDataResponse(
    ICollection<long long>^ productIds
)
```

#### Parameters

  - productIds  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

## See Also

#### Reference

[ProductSearchDataResponse Class](productsearchdataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

