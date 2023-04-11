---
title: TransactionServiceClient.GetPurchaseOrders Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: GetPurchaseOrders Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetPurchaseOrders(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.getpurchaseorders(v=AX.60)
ms:contentKeyID: 62212071
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetPurchaseOrders
dev_langs:
- CSharp
- C++
- VB
---

# GetPurchaseOrders Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get open purchase orders for a store.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function GetPurchaseOrders ( _
    storeNumber As String _
) As ReadOnlyCollection(Of PickReceiveDocument)
'Usage
Dim instance As TransactionServiceClient
Dim storeNumber As String
Dim returnValue As ReadOnlyCollection(Of PickReceiveDocument)

returnValue = instance.GetPurchaseOrders(storeNumber)
```

``` csharp
public ReadOnlyCollection<PickReceiveDocument> GetPurchaseOrders(
    string storeNumber
)
```

``` c++
public:
ReadOnlyCollection<PickReceiveDocument^>^ GetPurchaseOrders(
    String^ storeNumber
)
```

#### Parameters

  - storeNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[PickReceiveDocument](pickreceivedocument-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)\>  
A collection of receive documents.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

