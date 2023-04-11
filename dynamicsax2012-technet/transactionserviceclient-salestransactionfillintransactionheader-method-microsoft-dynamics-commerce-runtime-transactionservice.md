---
title: TransactionServiceClient.SalesTransactionFillInTransactionHeader Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: SalesTransactionFillInTransactionHeader Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.SalesTransactionFillInTransactionHeader(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionHeader)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.salestransactionfillintransactionheader(v=AX.60)
ms:contentKeyID: 62215115
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.SalesTransactionFillInTransactionHeader
dev_langs:
- CSharp
- C++
- VB
---

# SalesTransactionFillInTransactionHeader Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Fills in the sales transaction with transaction header data.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub SalesTransactionFillInTransactionHeader ( _
    salesTransaction As SalesTransaction, _
    transHeader As TransactionHeader _
)
'Usage
Dim salesTransaction As SalesTransaction
Dim transHeader As TransactionHeader

TransactionServiceClient.SalesTransactionFillInTransactionHeader(salesTransaction, _
    transHeader)
```

``` csharp
public static void SalesTransactionFillInTransactionHeader(
    SalesTransaction salesTransaction,
    TransactionHeader transHeader
)
```

``` c++
public:
static void SalesTransactionFillInTransactionHeader(
    SalesTransaction^ salesTransaction, 
    TransactionHeader^ transHeader
)
```

#### Parameters

  - salesTransaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - transHeader  
    Type: [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionHeader](transactionheader-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

