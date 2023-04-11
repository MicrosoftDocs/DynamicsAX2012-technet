---
title: GetOrdersResponse Constructor (IEnumerable(SalesOrder)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetOrdersResponse Constructor (IEnumerable(SalesOrder))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetOrdersResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getordersresponse.getordersresponse(v=AX.60)
ms:contentKeyID: 49833428
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetOrdersResponse Constructor (IEnumerable(SalesOrder))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetOrdersResponse](getordersresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    orders As IEnumerable(Of SalesOrder) _
)
'Usage
Dim orders As IEnumerable(Of SalesOrder)

Dim instance As New GetOrdersResponse(orders)
```

``` csharp
public GetOrdersResponse(
    IEnumerable<SalesOrder> orders
)
```

``` c++
public:
GetOrdersResponse(
    IEnumerable<SalesOrder^>^ orders
)
```

#### Parameters

  - orders  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetOrdersResponse Class](getordersresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetOrdersResponse Overload](getordersresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

