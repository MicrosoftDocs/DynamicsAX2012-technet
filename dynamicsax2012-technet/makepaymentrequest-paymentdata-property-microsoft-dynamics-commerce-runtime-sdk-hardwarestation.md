---
title: MakePaymentRequest.PaymentData Property  (Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation)
TOCTitle: PaymentData Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.MakePaymentRequest.PaymentData
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.sdk.hardwarestation.makepaymentrequest.paymentdata(v=AX.60)
ms:contentKeyID: 65320580
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.MakePaymentRequest.PaymentData
dev_langs:
- CSharp
- C++
- VB
---

# PaymentData Property

Gets the merchant's payment data.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation](microsoft-dynamics-commerce-runtime-sdk-hardwarestation-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation (in Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PaymentData As PaymentData
    Get
    Private Set
'Usage
Dim instance As MakePaymentRequest
Dim value As PaymentData

value = instance.PaymentData
```

``` csharp
[DataMemberAttribute]
public PaymentData PaymentData { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property PaymentData^ PaymentData {
    PaymentData^ get ();
    private: void set (PaymentData^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.PaymentData](paymentdata-class-microsoft-dynamics-commerce-runtime-sdk-hardwarestation.md)  
Returns [PaymentData](paymentdata-class-microsoft-dynamics-commerce-runtime-sdk-hardwarestation.md).  

## See Also

#### Reference

[MakePaymentRequest Class](makepaymentrequest-class-microsoft-dynamics-commerce-runtime-sdk-hardwarestation.md)

[Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation Namespace](microsoft-dynamics-commerce-runtime-sdk-hardwarestation-namespace.md)

