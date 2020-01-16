---
title: TransactionServiceClient.LockCreditMemo Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: LockCreditMemo Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.LockCreditMemo(System.String,System.String,System.String,System.String@,System.Decimal@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.lockcreditmemo(v=AX.60)
ms:contentKeyID: 62210252
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.LockCreditMemo
dev_langs:
- CSharp
- C++
- VB
---

# LockCreditMemo Method

Reserves the credit memo so it cannot be used from different terminal.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub LockCreditMemo ( _
    creditMemoId As String, _
    storeId As String, _
    terminalId As String, _
    <OutAttribute> ByRef memoCurrencyCode As String, _
    <OutAttribute> ByRef amount As Decimal _
)
'Usage
Dim instance As TransactionServiceClient
Dim creditMemoId As String
Dim storeId As String
Dim terminalId As String
Dim memoCurrencyCode As String
Dim amount As Decimal

instance.LockCreditMemo(creditMemoId, _
    storeId, terminalId, memoCurrencyCode, _
    amount)
```

``` csharp
public void LockCreditMemo(
    string creditMemoId,
    string storeId,
    string terminalId,
    out string memoCurrencyCode,
    out decimal amount
)
```

``` c++
public:
void LockCreditMemo(
    String^ creditMemoId, 
    String^ storeId, 
    String^ terminalId, 
    [OutAttribute] String^% memoCurrencyCode, 
    [OutAttribute] Decimal% amount
)
```

#### Parameters

  - creditMemoId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - storeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - memoCurrencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

