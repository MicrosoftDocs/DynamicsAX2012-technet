---
title: VoidPaymentServiceRequest Constructor (TenderLine, PaymentCard) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: VoidPaymentServiceRequest Constructor (TenderLine, PaymentCard)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.VoidPaymentServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine,Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.voidpaymentservicerequest.voidpaymentservicerequest(v=AX.60)
ms:contentKeyID: 65322957
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# VoidPaymentServiceRequest Constructor (TenderLine, PaymentCard)

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

Dim instance As New VoidPaymentServiceRequest(tenderLine, _
    paymentCard)
```

``` csharp
public VoidPaymentServiceRequest(
    TenderLine tenderLine,
    PaymentCard paymentCard
)
```

``` c++
public:
VoidPaymentServiceRequest(
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

[VoidPaymentServiceRequest Class](voidpaymentservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[VoidPaymentServiceRequest Overload](voidpaymentservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

