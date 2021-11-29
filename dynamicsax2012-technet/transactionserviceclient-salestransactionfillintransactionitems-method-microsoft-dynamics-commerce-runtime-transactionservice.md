---
title: TransactionServiceClient.SalesTransactionFillInTransactionItems Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: SalesTransactionFillInTransactionItems Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.SalesTransactionFillInTransactionItems(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionItem[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.salestransactionfillintransactionitems(v=AX.60)
ms:contentKeyID: 62213080
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.SalesTransactionFillInTransactionItems
dev_langs:
- CSharp
- C++
- VB
---

# SalesTransactionFillInTransactionItems Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Fills in the sales transaction with transaction items data.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub SalesTransactionFillInTransactionItems ( _
    salesTransaction As SalesTransaction, _
    transItems As TransactionItem() _
)
'Usage
Dim salesTransaction As SalesTransaction
Dim transItems As TransactionItem()

TransactionServiceClient.SalesTransactionFillInTransactionItems(salesTransaction, _
    transItems)
```

``` csharp
public static void SalesTransactionFillInTransactionItems(
    SalesTransaction salesTransaction,
    TransactionItem[] transItems
)
```

``` c++
public:
static void SalesTransactionFillInTransactionItems(
    SalesTransaction^ salesTransaction, 
    array<TransactionItem^>^ transItems
)
```

#### Parameters

  - salesTransaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - transItems  
    Type: [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionItem](transactionitem-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)\[\]  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

