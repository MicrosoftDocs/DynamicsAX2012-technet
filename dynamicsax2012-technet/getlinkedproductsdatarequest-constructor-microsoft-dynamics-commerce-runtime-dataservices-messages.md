---
title: GetLinkedProductsDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetLinkedProductsDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLinkedProductsDataRequest.#ctor(System.Collections.Generic.IEnumerable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getlinkedproductsdatarequest.getlinkedproductsdatarequest(v=AX.60)
ms:contentKeyID: 65318100
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLinkedProductsDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetLinkedProductsDataRequest Constructor

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

Dim instance As New GetLinkedProductsDataRequest(productIds)
```

``` csharp
public GetLinkedProductsDataRequest(
    IEnumerable<long> productIds
)
```

``` c++
public:
GetLinkedProductsDataRequest(
    IEnumerable<long long>^ productIds
)
```

#### Parameters

  - productIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

## See Also

#### Reference

[GetLinkedProductsDataRequest Class](getlinkedproductsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

