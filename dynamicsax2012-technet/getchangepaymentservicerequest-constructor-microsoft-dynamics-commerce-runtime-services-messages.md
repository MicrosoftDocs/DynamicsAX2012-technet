---
title: GetChangePaymentServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetChangePaymentServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetChangePaymentServiceRequest.#ctor(System.Decimal,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getchangepaymentservicerequest.getchangepaymentservicerequest(v=AX.60)
ms:contentKeyID: 65319033
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetChangePaymentServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetChangePaymentServiceRequest Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    changeAmount As Decimal, _
    currencyCode As String, _
    paymentTenderTypeId As String _
)
'Usage
Dim changeAmount As Decimal
Dim currencyCode As String
Dim paymentTenderTypeId As String

Dim instance As New GetChangePaymentServiceRequest(changeAmount, _
    currencyCode, paymentTenderTypeId)
```

``` csharp
public GetChangePaymentServiceRequest(
    decimal changeAmount,
    string currencyCode,
    string paymentTenderTypeId
)
```

``` c++
public:
GetChangePaymentServiceRequest(
    Decimal changeAmount, 
    String^ currencyCode, 
    String^ paymentTenderTypeId
)
```

#### Parameters

  - changeAmount  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - paymentTenderTypeId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetChangePaymentServiceRequest Class](getchangepaymentservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

