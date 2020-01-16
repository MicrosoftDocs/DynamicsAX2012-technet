---
title: ITransactionServicesV1.ValidateCreditMemo Method  (Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices)
TOCTitle: ValidateCreditMemo Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.ValidateCreditMemo(System.Boolean@,System.String@,System.String@,System.Decimal@,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.transactionservices.itransactionservicesv1.validatecreditmemo(v=AX.60)
ms:contentKeyID: 47128838
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.ValidateCreditMemo
dev_langs:
- CSharp
- C++
- VB
---

# ValidateCreditMemo Method

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub ValidateCreditMemo ( _
    ByRef retValue As Boolean, _
    ByRef comment As String, _
    ByRef currencyCode As String, _
    ByRef amount As Decimal, _
    id As String, _
    storeId As String, _
    terminalId As String _
)
'Usage
Dim instance As ITransactionServicesV1
Dim retValue As Boolean
Dim comment As String
Dim currencyCode As String
Dim amount As Decimal
Dim id As String
Dim storeId As String
Dim terminalId As String

instance.ValidateCreditMemo(retValue, _
    comment, currencyCode, amount, id, _
    storeId, terminalId)
```

``` csharp
void ValidateCreditMemo(
    ref bool retValue,
    ref string comment,
    ref string currencyCode,
    ref decimal amount,
    string id,
    string storeId,
    string terminalId
)
```

``` c++
void ValidateCreditMemo(
    bool% retValue, 
    String^% comment, 
    String^% currencyCode, 
    Decimal% amount, 
    String^ id, 
    String^ storeId, 
    String^ terminalId
)
```

#### Parameters

  - retValue  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - id  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - storeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ITransactionServicesV1 Interface](itransactionservicesv1-interface-microsoft-dynamics-retail-pos-contracts-transactionservices.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices Namespace](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)

