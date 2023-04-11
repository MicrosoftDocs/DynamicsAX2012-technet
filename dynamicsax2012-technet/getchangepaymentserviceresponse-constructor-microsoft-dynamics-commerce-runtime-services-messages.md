---
title: GetChangePaymentServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetChangePaymentServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetChangePaymentServiceResponse.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getchangepaymentserviceresponse.getchangepaymentserviceresponse(v=AX.60)
ms:contentKeyID: 62212280
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetChangePaymentServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetChangePaymentServiceResponse Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetChangePaymentServiceResponse](getchangepaymentserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

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

Dim instance As New GetChangePaymentServiceResponse(tenderLine)
```

``` csharp
public GetChangePaymentServiceResponse(
    TenderLine tenderLine
)
```

``` c++
public:
GetChangePaymentServiceResponse(
    TenderLine^ tenderLine
)
```

#### Parameters

  - tenderLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetChangePaymentServiceResponse Class](getchangepaymentserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

