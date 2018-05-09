---
title: TransactionServiceClient.PayCreditMemo Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: PayCreditMemo Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.PayCreditMemo(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.paycreditmemo(v=AX.60)
ms:contentKeyID: 62211459
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.PayCreditMemo
dev_langs:
- CSharp
- C++
- VB
---

# PayCreditMemo Method

Pay with credit memo.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub PayCreditMemo ( _
    creditMemoId As String, _
    storeId As String, _
    terminalId As String, _
    staffId As String, _
    transactionId As String, _
    receiptId As String, _
    currencyCode As String, _
    amount As Decimal _
)
'Usage
Dim instance As TransactionServiceClient
Dim creditMemoId As String
Dim storeId As String
Dim terminalId As String
Dim staffId As String
Dim transactionId As String
Dim receiptId As String
Dim currencyCode As String
Dim amount As Decimal

instance.PayCreditMemo(creditMemoId, _
    storeId, terminalId, staffId, transactionId, _
    receiptId, currencyCode, amount)
```

``` csharp
public void PayCreditMemo(
    string creditMemoId,
    string storeId,
    string terminalId,
    string staffId,
    string transactionId,
    string receiptId,
    string currencyCode,
    decimal amount
)
```

``` c++
public:
void PayCreditMemo(
    String^ creditMemoId, 
    String^ storeId, 
    String^ terminalId, 
    String^ staffId, 
    String^ transactionId, 
    String^ receiptId, 
    String^ currencyCode, 
    Decimal amount
)
```

#### Parameters

  - creditMemoId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - storeId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - staffId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - transactionId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - receiptId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

