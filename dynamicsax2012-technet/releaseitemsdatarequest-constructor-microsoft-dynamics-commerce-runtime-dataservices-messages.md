---
title: ReleaseItemsDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ReleaseItemsDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReleaseItemsDataRequest.#ctor(System.Collections.Generic.IEnumerable{System.Guid})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.releaseitemsdatarequest.releaseitemsdatarequest(v=AX.60)
ms:contentKeyID: 65319549
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReleaseItemsDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# ReleaseItemsDataRequest Constructor

Initializes a new instance of the [ReleaseItemsDataRequest](releaseitemsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    reservationIds As IEnumerable(Of Guid) _
)
'Usage
Dim reservationIds As IEnumerable(Of Guid)

Dim instance As New ReleaseItemsDataRequest(reservationIds)
```

``` csharp
public ReleaseItemsDataRequest(
    IEnumerable<Guid> reservationIds
)
```

``` c++
public:
ReleaseItemsDataRequest(
    IEnumerable<Guid>^ reservationIds
)
```

#### Parameters

  - reservationIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Guid](https://technet.microsoft.com/library/cey1zx63\(v=ax.60\))\>  

## See Also

#### Reference

[ReleaseItemsDataRequest Class](releaseitemsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

