---
title: TransactionServiceClient.IssueCreditMemo Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: IssueCreditMemo Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.IssueCreditMemo(System.String,System.String,System.String,System.String,System.String,System.String,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.issuecreditmemo(v=AX.60)
ms:contentKeyID: 62204587
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.IssueCreditMemo
dev_langs:
- CSharp
- C++
- VB
---

# IssueCreditMemo Method

Issue new credit memo.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function IssueCreditMemo ( _
    storeId As String, _
    terminalId As String, _
    staffId As String, _
    transactionId As String, _
    receiptId As String, _
    currencyCode As String, _
    amount As Decimal _
) As String
'Usage
Dim instance As TransactionServiceClient
Dim storeId As String
Dim terminalId As String
Dim staffId As String
Dim transactionId As String
Dim receiptId As String
Dim currencyCode As String
Dim amount As Decimal
Dim returnValue As String

returnValue = instance.IssueCreditMemo(storeId, _
    terminalId, staffId, transactionId, _
    receiptId, currencyCode, amount)
```

``` csharp
public string IssueCreditMemo(
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
String^ IssueCreditMemo(
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

  - storeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - staffId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - transactionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - receiptId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Idenitifier of issued credit memo.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

