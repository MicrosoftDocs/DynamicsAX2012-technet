---
title: TransactionServiceClient.MarkItemsReturned Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: MarkItemsReturned Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.MarkItemsReturned(Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.ItemReturn[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.markitemsreturned(v=AX.60)
ms:contentKeyID: 62213675
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.MarkItemsReturned
dev_langs:
- CSharp
- C++
- VB
---

# MarkItemsReturned Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Updates the RetailTransactionSalesTrans.returnQty for each returned item.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub MarkItemsReturned ( _
    returnedItems As ItemReturn() _
)
'Usage
Dim instance As TransactionServiceClient
Dim returnedItems As ItemReturn()

instance.MarkItemsReturned(returnedItems)
```

``` csharp
public void MarkItemsReturned(
    ItemReturn[] returnedItems
)
```

``` c++
public:
void MarkItemsReturned(
    array<ItemReturn^>^ returnedItems
)
```

#### Parameters

  - returnedItems  
    Type: [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.ItemReturn](itemreturn-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)\[\]  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

