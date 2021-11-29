---
title: AuthorizePaymentServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: AuthorizePaymentServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthorizePaymentServiceResponse.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.authorizepaymentserviceresponse.authorizepaymentserviceresponse(v=AX.60)
ms:contentKeyID: 62213008
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthorizePaymentServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# AuthorizePaymentServiceResponse Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [AuthorizePaymentServiceResponse](authorizepaymentserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    tenderLine As TenderLine _
)
'Usage
Dim tenderLine As TenderLine

Dim instance As New AuthorizePaymentServiceResponse(tenderLine)
```

``` csharp
public AuthorizePaymentServiceResponse(
    TenderLine tenderLine
)
```

``` c++
public:
AuthorizePaymentServiceResponse(
    TenderLine^ tenderLine
)
```

#### Parameters

  - tenderLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[AuthorizePaymentServiceResponse Class](authorizepaymentserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

