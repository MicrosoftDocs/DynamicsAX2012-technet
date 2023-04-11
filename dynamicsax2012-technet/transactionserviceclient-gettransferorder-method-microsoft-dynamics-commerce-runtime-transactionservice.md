---
title: TransactionServiceClient.GetTransferOrder Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: GetTransferOrder Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetTransferOrder(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.gettransferorder(v=AX.60)
ms:contentKeyID: 62212369
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetTransferOrder
dev_langs:
- CSharp
- C++
- VB
---

# GetTransferOrder Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a transfer order with lines from Ax.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function GetTransferOrder ( _
    orderId As String _
) As PickReceiveDocument
'Usage
Dim instance As TransactionServiceClient
Dim orderId As String
Dim returnValue As PickReceiveDocument

returnValue = instance.GetTransferOrder(orderId)
```

``` csharp
public PickReceiveDocument GetTransferOrder(
    string orderId
)
```

``` c++
public:
PickReceiveDocument^ GetTransferOrder(
    String^ orderId
)
```

#### Parameters

  - orderId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.PickReceiveDocument](pickreceivedocument-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)  
A picking document.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

