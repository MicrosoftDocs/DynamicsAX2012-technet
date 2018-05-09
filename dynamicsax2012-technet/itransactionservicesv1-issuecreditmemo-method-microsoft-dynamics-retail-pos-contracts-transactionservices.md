---
title: ITransactionServicesV1.IssueCreditMemo Method  (Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices)
TOCTitle: IssueCreditMemo Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.IssueCreditMemo(System.Boolean@,System.String@,System.String@,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Decimal,System.DateTime)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.transactionservices.itransactionservicesv1.issuecreditmemo(v=AX.60)
ms:contentKeyID: 47129177
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.IssueCreditMemo
dev_langs:
- CSharp
- C++
- VB
---

# IssueCreditMemo Method

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub IssueCreditMemo ( _
    ByRef retValue As Boolean, _
    ByRef comment As String, _
    ByRef id As String, _
    storeId As String, _
    terminalId As String, _
    staffId As String, _
    transactionId As String, _
    receiptId As String, _
    lineNum As String, _
    currencyCode As String, _
    amount As Decimal, _
    date As DateTime _
)
'Usage
Dim instance As ITransactionServicesV1
Dim retValue As Boolean
Dim comment As String
Dim id As String
Dim storeId As String
Dim terminalId As String
Dim staffId As String
Dim transactionId As String
Dim receiptId As String
Dim lineNum As String
Dim currencyCode As String
Dim amount As Decimal
Dim date As DateTime

instance.IssueCreditMemo(retValue, comment, _
    id, storeId, terminalId, staffId, _
    transactionId, receiptId, lineNum, _
    currencyCode, amount, date)
```

``` csharp
void IssueCreditMemo(
    ref bool retValue,
    ref string comment,
    ref string id,
    string storeId,
    string terminalId,
    string staffId,
    string transactionId,
    string receiptId,
    string lineNum,
    string currencyCode,
    decimal amount,
    DateTime date
)
```

``` c++
void IssueCreditMemo(
    bool% retValue, 
    String^% comment, 
    String^% id, 
    String^ storeId, 
    String^ terminalId, 
    String^ staffId, 
    String^ transactionId, 
    String^ receiptId, 
    String^ lineNum, 
    String^ currencyCode, 
    Decimal amount, 
    DateTime date
)
```

#### Parameters

  - retValue  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - id  
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

  - lineNum  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - date  
    Type: [System.DateTime](https://technet.microsoft.com/en-us/library/03ybds8y\(v=ax.60\))  

## See Also

#### Reference

[ITransactionServicesV1 Interface](itransactionservicesv1-interface-microsoft-dynamics-retail-pos-contracts-transactionservices.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices Namespace](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)

