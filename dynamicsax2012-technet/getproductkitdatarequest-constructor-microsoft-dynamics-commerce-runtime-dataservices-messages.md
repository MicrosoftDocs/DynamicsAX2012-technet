---
title: GetProductKitDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetProductKitDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductKitDataRequest.#ctor(System.Collections.Generic.IEnumerable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductkitdatarequest.getproductkitdatarequest(v=AX.60)
ms:contentKeyID: 65317688
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductKitDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetProductKitDataRequest Constructor

Initializes a new instance of the [GetProductKitDataRequest](getproductkitdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    kitMasterProductIds As IEnumerable(Of Long) _
)
'Usage
Dim kitMasterProductIds As IEnumerable(Of Long)

Dim instance As New GetProductKitDataRequest(kitMasterProductIds)
```

``` csharp
public GetProductKitDataRequest(
    IEnumerable<long> kitMasterProductIds
)
```

``` c++
public:
GetProductKitDataRequest(
    IEnumerable<long long>^ kitMasterProductIds
)
```

#### Parameters

  - kitMasterProductIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

## See Also

#### Reference

[GetProductKitDataRequest Class](getproductkitdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

