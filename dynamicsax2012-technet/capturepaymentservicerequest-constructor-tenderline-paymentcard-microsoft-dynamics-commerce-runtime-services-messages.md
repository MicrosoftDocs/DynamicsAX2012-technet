---
title: CapturePaymentServiceRequest Constructor (TenderLine, PaymentCard) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CapturePaymentServiceRequest Constructor (TenderLine, PaymentCard)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CapturePaymentServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine,Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.capturepaymentservicerequest.capturepaymentservicerequest(v=AX.60)
ms:contentKeyID: 65315813
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CapturePaymentServiceRequest Constructor (TenderLine, PaymentCard)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    tenderLine As TenderLine, _
    paymentCard As PaymentCard _
)
'Usage
Dim tenderLine As TenderLine
Dim paymentCard As PaymentCard

Dim instance As New CapturePaymentServiceRequest(tenderLine, _
    paymentCard)
```

``` csharp
public CapturePaymentServiceRequest(
    TenderLine tenderLine,
    PaymentCard paymentCard
)
```

``` c++
public:
CapturePaymentServiceRequest(
    TenderLine^ tenderLine, 
    PaymentCard^ paymentCard
)
```

#### Parameters

  - tenderLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - paymentCard  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard](paymentcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CapturePaymentServiceRequest Class](capturepaymentservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[CapturePaymentServiceRequest Overload](capturepaymentservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

