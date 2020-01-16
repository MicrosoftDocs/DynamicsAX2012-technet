---
title: CapturePaymentServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CapturePaymentServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CapturePaymentServiceResponse.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.capturepaymentserviceresponse.capturepaymentserviceresponse(v=AX.60)
ms:contentKeyID: 62213358
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CapturePaymentServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# CapturePaymentServiceResponse Constructor

Initializes a new instance of the [CapturePaymentServiceResponse](capturepaymentserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

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

Dim instance As New CapturePaymentServiceResponse(tenderLine)
```

``` csharp
public CapturePaymentServiceResponse(
    TenderLine tenderLine
)
```

``` c++
public:
CapturePaymentServiceResponse(
    TenderLine^ tenderLine
)
```

#### Parameters

  - tenderLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CapturePaymentServiceResponse Class](capturepaymentserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

