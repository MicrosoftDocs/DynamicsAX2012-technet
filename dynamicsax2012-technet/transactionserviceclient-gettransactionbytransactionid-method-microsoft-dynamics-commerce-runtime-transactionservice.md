---
title: TransactionServiceClient.GetTransactionByTransactionId Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: GetTransactionByTransactionId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetTransactionByTransactionId(System.String,System.Int32@,Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionHeader@,Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionItem[]@,System.String@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.gettransactionbytransactionid(v=AX.60)
ms:contentKeyID: 62211341
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetTransactionByTransactionId
dev_langs:
- CSharp
- C++
- VB
---

# GetTransactionByTransactionId Method

Gets the transaction by transaction identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub GetTransactionByTransactionId ( _
    transactionId As String, _
    ByRef foundTransCount As Integer, _
    ByRef transHeader As TransactionHeader, _
    ByRef transItems As TransactionItem(), _
    ByRef transLoyaltyCardNumber As String _
)
'Usage
Dim instance As TransactionServiceClient
Dim transactionId As String
Dim foundTransCount As Integer
Dim transHeader As TransactionHeader
Dim transItems As TransactionItem()
Dim transLoyaltyCardNumber As String

instance.GetTransactionByTransactionId(transactionId, _
    foundTransCount, transHeader, transItems, _
    transLoyaltyCardNumber)
```

``` csharp
public void GetTransactionByTransactionId(
    string transactionId,
    ref int foundTransCount,
    ref TransactionHeader transHeader,
    ref TransactionItem[] transItems,
    ref string transLoyaltyCardNumber
)
```

``` c++
public:
void GetTransactionByTransactionId(
    String^ transactionId, 
    int% foundTransCount, 
    TransactionHeader^% transHeader, 
    array<TransactionItem^>^% transItems, 
    String^% transLoyaltyCardNumber
)
```

#### Parameters

  - transactionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - foundTransCount  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - transHeader  
    Type: [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionHeader](transactionheader-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)  

<!-- end list -->

  - transItems  
    Type: [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionItem](transactionitem-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)\[\]  

<!-- end list -->

  - transLoyaltyCardNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

