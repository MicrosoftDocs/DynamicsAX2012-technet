---
title: GenerateCardTokenPaymentServiceRequest.PaymentCard Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: PaymentCard Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GenerateCardTokenPaymentServiceRequest.PaymentCard
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.generatecardtokenpaymentservicerequest.paymentcard(v=AX.60)
ms:contentKeyID: 62215084
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GenerateCardTokenPaymentServiceRequest.PaymentCard
dev_langs:
- CSharp
- C++
- VB
---

# PaymentCard Property

Gets the payment card associated with the payment.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PaymentCard As PaymentCard
    Get
    Private Set
'Usage
Dim instance As GenerateCardTokenPaymentServiceRequest
Dim value As PaymentCard

value = instance.PaymentCard
```

``` csharp
[DataMemberAttribute]
public PaymentCard PaymentCard { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property PaymentCard^ PaymentCard {
    PaymentCard^ get ();
    private: void set (PaymentCard^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard](paymentcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [PaymentCard](paymentcard-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GenerateCardTokenPaymentServiceRequest Class](generatecardtokenpaymentservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

