---
title: GetTransferOrderResponse Constructor (IEnumerable(TransferOrder)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetTransferOrderResponse Constructor (IEnumerable(TransferOrder))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetTransferOrderResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrder})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.gettransferorderresponse.gettransferorderresponse(v=AX.60)
ms:contentKeyID: 62207566
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetTransferOrderResponse Constructor (IEnumerable(TransferOrder))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    transferOrders As IEnumerable(Of TransferOrder) _
)
'Usage
Dim transferOrders As IEnumerable(Of TransferOrder)

Dim instance As New GetTransferOrderResponse(transferOrders)
```

``` csharp
public GetTransferOrderResponse(
    IEnumerable<TransferOrder> transferOrders
)
```

``` c++
public:
GetTransferOrderResponse(
    IEnumerable<TransferOrder^>^ transferOrders
)
```

#### Parameters

  - transferOrders  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[TransferOrder](transferorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetTransferOrderResponse Class](gettransferorderresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetTransferOrderResponse Overload](gettransferorderresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

