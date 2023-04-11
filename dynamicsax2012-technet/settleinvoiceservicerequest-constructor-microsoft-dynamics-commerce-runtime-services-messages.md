---
title: SettleInvoiceServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SettleInvoiceServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SettleInvoiceServiceRequest.#ctor(System.String,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.settleinvoiceservicerequest.settleinvoiceservicerequest(v=AX.60)
ms:contentKeyID: 65320114
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SettleInvoiceServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# SettleInvoiceServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    invoiceId As String, _
    invoiceAmount As Decimal _
)
'Usage
Dim invoiceId As String
Dim invoiceAmount As Decimal

Dim instance As New SettleInvoiceServiceRequest(invoiceId, _
    invoiceAmount)
```

``` csharp
public SettleInvoiceServiceRequest(
    string invoiceId,
    decimal invoiceAmount
)
```

``` c++
public:
SettleInvoiceServiceRequest(
    String^ invoiceId, 
    Decimal invoiceAmount
)
```

#### Parameters

  - invoiceId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - invoiceAmount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[SettleInvoiceServiceRequest Class](settleinvoiceservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

