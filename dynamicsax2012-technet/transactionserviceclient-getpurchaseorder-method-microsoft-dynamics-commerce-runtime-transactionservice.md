---
title: TransactionServiceClient.GetPurchaseOrder Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: GetPurchaseOrder Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetPurchaseOrder(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.getpurchaseorder(v=AX.60)
ms:contentKeyID: 62203997
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetPurchaseOrder
dev_langs:
- CSharp
- C++
- VB
---

# GetPurchaseOrder Method

Gets a purchase order with lines from Ax.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function GetPurchaseOrder ( _
    orderId As String, _
    storeNumber As String _
) As PickReceiveDocument
'Usage
Dim instance As TransactionServiceClient
Dim orderId As String
Dim storeNumber As String
Dim returnValue As PickReceiveDocument

returnValue = instance.GetPurchaseOrder(orderId, _
    storeNumber)
```

``` csharp
public PickReceiveDocument GetPurchaseOrder(
    string orderId,
    string storeNumber
)
```

``` c++
public:
PickReceiveDocument^ GetPurchaseOrder(
    String^ orderId, 
    String^ storeNumber
)
```

#### Parameters

  - orderId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - storeNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.PickReceiveDocument](pickreceivedocument-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)  
A receiving document.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

