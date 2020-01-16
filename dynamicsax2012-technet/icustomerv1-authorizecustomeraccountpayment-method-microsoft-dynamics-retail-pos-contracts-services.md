---
title: ICustomerV1.AuthorizeCustomerAccountPayment Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: AuthorizeCustomerAccountPayment Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomerV1.AuthorizeCustomerAccountPayment(System.Boolean@,System.String@,System.String@,System.String,System.Decimal,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icustomerv1.authorizecustomeraccountpayment(v=AX.60)
ms:contentKeyID: 47343840
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomerV1.AuthorizeCustomerAccountPayment
dev_langs:
- CSharp
- C++
- VB
---

# AuthorizeCustomerAccountPayment Method

Authenticates a payment from customer account.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub AuthorizeCustomerAccountPayment ( _
    ByRef valid As Boolean, _
    ByRef comment As String, _
    ByRef manualAuthenticationCode As String, _
    customerId As String, _
    amount As Decimal, _
    retailTransaction As IRetailTransaction _
)
'Usage
Dim instance As ICustomerV1
Dim valid As Boolean
Dim comment As String
Dim manualAuthenticationCode As String
Dim customerId As String
Dim amount As Decimal
Dim retailTransaction As IRetailTransaction

instance.AuthorizeCustomerAccountPayment(valid, _
    comment, manualAuthenticationCode, _
    customerId, amount, retailTransaction)
```

``` csharp
void AuthorizeCustomerAccountPayment(
    ref bool valid,
    ref string comment,
    ref string manualAuthenticationCode,
    string customerId,
    decimal amount,
    IRetailTransaction retailTransaction
)
```

``` c++
void AuthorizeCustomerAccountPayment(
    bool% valid, 
    String^% comment, 
    String^% manualAuthenticationCode, 
    String^ customerId, 
    Decimal amount, 
    IRetailTransaction^ retailTransaction
)
```

#### Parameters

  - valid  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - manualAuthenticationCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ICustomerV1 Interface](icustomerv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

