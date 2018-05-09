---
title: ITransactionServicesV1.ValidateCustomerStatus Method  (Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices)
TOCTitle: ValidateCustomerStatus Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.ValidateCustomerStatus(System.Boolean@,System.String@,System.String,System.Decimal,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.transactionservices.itransactionservicesv1.validatecustomerstatus(v=AX.60)
ms:contentKeyID: 47128122
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.ValidateCustomerStatus
dev_langs:
- CSharp
- C++
- VB
---

# ValidateCustomerStatus Method

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub ValidateCustomerStatus ( _
    ByRef valid As Boolean, _
    ByRef comment As String, _
    customerId As String, _
    amount As Decimal, _
    currencyCode As String _
)
'Usage
Dim instance As ITransactionServicesV1
Dim valid As Boolean
Dim comment As String
Dim customerId As String
Dim amount As Decimal
Dim currencyCode As String

instance.ValidateCustomerStatus(valid, _
    comment, customerId, amount, currencyCode)
```

``` csharp
void ValidateCustomerStatus(
    ref bool valid,
    ref string comment,
    string customerId,
    decimal amount,
    string currencyCode
)
```

``` c++
void ValidateCustomerStatus(
    bool% valid, 
    String^% comment, 
    String^ customerId, 
    Decimal amount, 
    String^ currencyCode
)
```

#### Parameters

  - valid  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ITransactionServicesV1 Interface](itransactionservicesv1-interface-microsoft-dynamics-retail-pos-contracts-transactionservices.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices Namespace](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)

