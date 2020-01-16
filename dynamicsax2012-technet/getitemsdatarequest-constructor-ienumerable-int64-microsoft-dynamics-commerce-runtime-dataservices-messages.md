---
title: GetItemsDataRequest Constructor (IEnumerable(Int64)) (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetItemsDataRequest Constructor (IEnumerable(Int64))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetItemsDataRequest.#ctor(System.Collections.Generic.IEnumerable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getitemsdatarequest.getitemsdatarequest(v=AX.60)
ms:contentKeyID: 65319157
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetItemsDataRequest Constructor (IEnumerable(Int64))

Initializes a new instance of the [GetItemsDataRequest](getitemsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    productIds As IEnumerable(Of Long) _
)
'Usage
Dim productIds As IEnumerable(Of Long)

Dim instance As New GetItemsDataRequest(productIds)
```

``` csharp
public GetItemsDataRequest(
    IEnumerable<long> productIds
)
```

``` c++
public:
GetItemsDataRequest(
    IEnumerable<long long>^ productIds
)
```

#### Parameters

  - productIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

## See Also

#### Reference

[GetItemsDataRequest Class](getitemsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[GetItemsDataRequest Overload](getitemsdatarequest-constructor-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

