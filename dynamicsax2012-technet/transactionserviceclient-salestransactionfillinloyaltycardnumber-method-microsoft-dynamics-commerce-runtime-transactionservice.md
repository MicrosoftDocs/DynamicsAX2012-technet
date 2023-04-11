---
title: TransactionServiceClient.SalesTransactionFillInLoyaltyCardNumber Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: SalesTransactionFillInLoyaltyCardNumber Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.SalesTransactionFillInLoyaltyCardNumber(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.salestransactionfillinloyaltycardnumber(v=AX.60)
ms:contentKeyID: 62208285
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.SalesTransactionFillInLoyaltyCardNumber
dev_langs:
- CSharp
- C++
- VB
---

# SalesTransactionFillInLoyaltyCardNumber Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Fills in the sales transaction with loyalty card number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub SalesTransactionFillInLoyaltyCardNumber ( _
    salesTransaction As SalesTransaction, _
    transLoyaltyCardNumber As String _
)
'Usage
Dim salesTransaction As SalesTransaction
Dim transLoyaltyCardNumber As String

TransactionServiceClient.SalesTransactionFillInLoyaltyCardNumber(salesTransaction, _
    transLoyaltyCardNumber)
```

``` csharp
public static void SalesTransactionFillInLoyaltyCardNumber(
    SalesTransaction salesTransaction,
    string transLoyaltyCardNumber
)
```

``` c++
public:
static void SalesTransactionFillInLoyaltyCardNumber(
    SalesTransaction^ salesTransaction, 
    String^ transLoyaltyCardNumber
)
```

#### Parameters

  - salesTransaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - transLoyaltyCardNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

