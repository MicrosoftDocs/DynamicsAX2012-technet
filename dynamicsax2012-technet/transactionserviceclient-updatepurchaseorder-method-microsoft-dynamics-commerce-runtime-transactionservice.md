---
title: TransactionServiceClient.UpdatePurchaseOrder Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: UpdatePurchaseOrder Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.UpdatePurchaseOrder(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.updatepurchaseorder(v=AX.60)
ms:contentKeyID: 62207560
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.UpdatePurchaseOrder
dev_langs:
- CSharp
- C++
- VB
---

# UpdatePurchaseOrder Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Updates a purchase order in Ax.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function UpdatePurchaseOrder ( _
    orderXML As String _
) As ReadOnlyCollection(Of PickReceiveDocument)
'Usage
Dim instance As TransactionServiceClient
Dim orderXML As String
Dim returnValue As ReadOnlyCollection(Of PickReceiveDocument)

returnValue = instance.UpdatePurchaseOrder(orderXML)
```

``` csharp
public ReadOnlyCollection<PickReceiveDocument> UpdatePurchaseOrder(
    string orderXML
)
```

``` c++
public:
ReadOnlyCollection<PickReceiveDocument^>^ UpdatePurchaseOrder(
    String^ orderXML
)
```

#### Parameters

  - orderXML  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[PickReceiveDocument](pickreceivedocument-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)\>  
The saved order as a document.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

