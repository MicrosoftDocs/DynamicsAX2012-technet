---
title: ITransactionServicesV1.PaySalesOrder Method  (Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices)
TOCTitle: PaySalesOrder Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.PaySalesOrder(System.Boolean@,System.String@,System.String,System.Decimal,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.transactionservices.itransactionservicesv1.paysalesorder(v=AX.60)
ms:contentKeyID: 47128956
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.PaySalesOrder
dev_langs:
- CSharp
- C++
- VB
---

# PaySalesOrder Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PaySalesOrder ( _
    ByRef retValue As Boolean, _
    ByRef comment As String, _
    salesId As String, _
    amount As Decimal, _
    transactionId As String _
)
'Usage
Dim instance As ITransactionServicesV1
Dim retValue As Boolean
Dim comment As String
Dim salesId As String
Dim amount As Decimal
Dim transactionId As String

instance.PaySalesOrder(retValue, comment, _
    salesId, amount, transactionId)
```

``` csharp
void PaySalesOrder(
    ref bool retValue,
    ref string comment,
    string salesId,
    decimal amount,
    string transactionId
)
```

``` c++
void PaySalesOrder(
    bool% retValue, 
    String^% comment, 
    String^ salesId, 
    Decimal amount, 
    String^ transactionId
)
```

#### Parameters

  - retValue  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - salesId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - transactionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ITransactionServicesV1 Interface](itransactionservicesv1-interface-microsoft-dynamics-retail-pos-contracts-transactionservices.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices Namespace](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)

