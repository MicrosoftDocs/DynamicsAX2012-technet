---
title: TransactionServiceClient.GetPickingList Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: GetPickingList Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetPickingList(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.getpickinglist(v=AX.60)
ms:contentKeyID: 62213374
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetPickingList
dev_langs:
- CSharp
- C++
- VB
---

# GetPickingList Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a picking list with lines from Ax.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function GetPickingList ( _
    orderId As String, _
    storeNumber As String _
) As PickReceiveDocument
'Usage
Dim instance As TransactionServiceClient
Dim orderId As String
Dim storeNumber As String
Dim returnValue As PickReceiveDocument

returnValue = instance.GetPickingList(orderId, _
    storeNumber)
```

``` csharp
public PickReceiveDocument GetPickingList(
    string orderId,
    string storeNumber
)
```

``` c++
public:
PickReceiveDocument^ GetPickingList(
    String^ orderId, 
    String^ storeNumber
)
```

#### Parameters

  - orderId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - storeNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.PickReceiveDocument](pickreceivedocument-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)  
A receiving document.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

