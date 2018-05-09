---
title: MakePaymentRequest.PaymentCard Property  (Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation)
TOCTitle: PaymentCard Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.MakePaymentRequest.PaymentCard
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.sdk.hardwarestation.makepaymentrequest.paymentcard(v=AX.60)
ms:contentKeyID: 65319395
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.MakePaymentRequest.PaymentCard
dev_langs:
- CSharp
- C++
- VB
---

# PaymentCard Property

Gets the payment card.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation](microsoft-dynamics-commerce-runtime-sdk-hardwarestation-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation (in Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PaymentCard As PaymentCard
    Get
    Private Set
'Usage
Dim instance As MakePaymentRequest
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

[MakePaymentRequest Class](makepaymentrequest-class-microsoft-dynamics-commerce-runtime-sdk-hardwarestation.md)

[Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation Namespace](microsoft-dynamics-commerce-runtime-sdk-hardwarestation-namespace.md)

