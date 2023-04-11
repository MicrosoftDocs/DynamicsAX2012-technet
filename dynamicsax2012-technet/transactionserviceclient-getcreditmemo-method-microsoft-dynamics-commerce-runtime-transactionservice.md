---
title: TransactionServiceClient.GetCreditMemo Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: GetCreditMemo Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetCreditMemo(System.String,System.String@,System.Decimal@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.getcreditmemo(v=AX.60)
ms:contentKeyID: 62214059
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetCreditMemo
dev_langs:
- CSharp
- C++
- VB
---

# GetCreditMemo Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get the credit memo balance.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub GetCreditMemo ( _
    creditMemoId As String, _
    <OutAttribute> ByRef creditMemoCurrencyCode As String, _
    <OutAttribute> ByRef balance As Decimal _
)
'Usage
Dim instance As TransactionServiceClient
Dim creditMemoId As String
Dim creditMemoCurrencyCode As String
Dim balance As Decimal

instance.GetCreditMemo(creditMemoId, _
    creditMemoCurrencyCode, balance)
```

``` csharp
public void GetCreditMemo(
    string creditMemoId,
    out string creditMemoCurrencyCode,
    out decimal balance
)
```

``` c++
public:
void GetCreditMemo(
    String^ creditMemoId, 
    [OutAttribute] String^% creditMemoCurrencyCode, 
    [OutAttribute] Decimal% balance
)
```

#### Parameters

  - creditMemoId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - creditMemoCurrencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - balance  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

