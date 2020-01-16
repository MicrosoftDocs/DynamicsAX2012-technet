---
title: ValidateCustomerAccountPaymentRealtimeRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ValidateCustomerAccountPaymentRealtimeRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateCustomerAccountPaymentRealtimeRequest.#ctor(System.String,System.Decimal,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.validatecustomeraccountpaymentrealtimerequest.validatecustomeraccountpaymentrealtimerequest(v=AX.60)
ms:contentKeyID: 65320224
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateCustomerAccountPaymentRealtimeRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# ValidateCustomerAccountPaymentRealtimeRequest Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    accountNumber As String, _
    amount As Decimal, _
    currencyCode As String _
)
'Usage
Dim accountNumber As String
Dim amount As Decimal
Dim currencyCode As String

Dim instance As New ValidateCustomerAccountPaymentRealtimeRequest(accountNumber, _
    amount, currencyCode)
```

``` csharp
public ValidateCustomerAccountPaymentRealtimeRequest(
    string accountNumber,
    decimal amount,
    string currencyCode
)
```

``` c++
public:
ValidateCustomerAccountPaymentRealtimeRequest(
    String^ accountNumber, 
    Decimal amount, 
    String^ currencyCode
)
```

#### Parameters

  - accountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ValidateCustomerAccountPaymentRealtimeRequest Class](validatecustomeraccountpaymentrealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

