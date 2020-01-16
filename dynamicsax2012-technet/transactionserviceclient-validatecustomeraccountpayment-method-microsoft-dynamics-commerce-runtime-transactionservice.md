---
title: TransactionServiceClient.ValidateCustomerAccountPayment Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: ValidateCustomerAccountPayment Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.ValidateCustomerAccountPayment(System.String,System.Decimal,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.validatecustomeraccountpayment(v=AX.60)
ms:contentKeyID: 62213352
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.ValidateCustomerAccountPayment
dev_langs:
- CSharp
- C++
- VB
---

# ValidateCustomerAccountPayment Method

Validate customer account payment.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub ValidateCustomerAccountPayment ( _
    customerId As String, _
    amount As Decimal, _
    currencyCode As String _
)
'Usage
Dim instance As TransactionServiceClient
Dim customerId As String
Dim amount As Decimal
Dim currencyCode As String

instance.ValidateCustomerAccountPayment(customerId, _
    amount, currencyCode)
```

``` csharp
public void ValidateCustomerAccountPayment(
    string customerId,
    decimal amount,
    string currencyCode
)
```

``` c++
public:
void ValidateCustomerAccountPayment(
    String^ customerId, 
    Decimal amount, 
    String^ currencyCode
)
```

#### Parameters

  - customerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

