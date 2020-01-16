---
title: TransactionServiceClient.GetTransferOrders Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: GetTransferOrders Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetTransferOrders(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.gettransferorders(v=AX.60)
ms:contentKeyID: 62208191
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetTransferOrders
dev_langs:
- CSharp
- C++
- VB
---

# GetTransferOrders Method

Gets open transfer orders from Ax.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function GetTransferOrders ( _
    storeNumber As String _
) As ReadOnlyCollection(Of PickReceiveDocument)
'Usage
Dim instance As TransactionServiceClient
Dim storeNumber As String
Dim returnValue As ReadOnlyCollection(Of PickReceiveDocument)

returnValue = instance.GetTransferOrders(storeNumber)
```

``` csharp
public ReadOnlyCollection<PickReceiveDocument> GetTransferOrders(
    string storeNumber
)
```

``` c++
public:
ReadOnlyCollection<PickReceiveDocument^>^ GetTransferOrders(
    String^ storeNumber
)
```

#### Parameters

  - storeNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[PickReceiveDocument](pickreceivedocument-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)\>  
A collection of picking documents.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

