---
title: GetTransferOrderServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetTransferOrderServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTransferOrderServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrder})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.gettransferorderserviceresponse.gettransferorderserviceresponse(v=AX.60)
ms:contentKeyID: 62209002
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTransferOrderServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetTransferOrderServiceResponse Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the GetTransferOrderServiceResponse class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    transferOrders As IEnumerable(Of TransferOrder) _
)
'Usage
Dim transferOrders As IEnumerable(Of TransferOrder)

Dim instance As New GetTransferOrderServiceResponse(transferOrders)
```

``` csharp
public GetTransferOrderServiceResponse(
    IEnumerable<TransferOrder> transferOrders
)
```

``` c++
public:
GetTransferOrderServiceResponse(
    IEnumerable<TransferOrder^>^ transferOrders
)
```

#### Parameters

  - transferOrders  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[TransferOrder](transferorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetTransferOrderServiceResponse Class](gettransferorderserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

