---
title: MakePaymentRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation)
TOCTitle: MakePaymentRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.MakePaymentRequest.#ctor(System.Decimal,System.Decimal,System.String,System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard,Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.PaymentData,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.sdk.hardwarestation.makepaymentrequest.makepaymentrequest(v=AX.60)
ms:contentKeyID: 65322442
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.MakePaymentRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# MakePaymentRequest Constructor

Initializes a new instance of the [MakePaymentRequest](makepaymentrequest-class-microsoft-dynamics-commerce-runtime-sdk-hardwarestation.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation](microsoft-dynamics-commerce-runtime-sdk-hardwarestation-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation (in Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    amount As Decimal, _
    cashback As Decimal, _
    currency As String, _
    tenderTypeId As String, _
    paymentType As String, _
    paymentCard As PaymentCard, _
    paymentData As PaymentData, _
    languageId As String _
)
'Usage
Dim amount As Decimal
Dim cashback As Decimal
Dim currency As String
Dim tenderTypeId As String
Dim paymentType As String
Dim paymentCard As PaymentCard
Dim paymentData As PaymentData
Dim languageId As String

Dim instance As New MakePaymentRequest(amount, _
    cashback, currency, tenderTypeId, _
    paymentType, paymentCard, paymentData, _
    languageId)
```

``` csharp
public MakePaymentRequest(
    decimal amount,
    decimal cashback,
    string currency,
    string tenderTypeId,
    string paymentType,
    PaymentCard paymentCard,
    PaymentData paymentData,
    string languageId
)
```

``` c++
public:
MakePaymentRequest(
    Decimal amount, 
    Decimal cashback, 
    String^ currency, 
    String^ tenderTypeId, 
    String^ paymentType, 
    PaymentCard^ paymentCard, 
    PaymentData^ paymentData, 
    String^ languageId
)
```

#### Parameters

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - cashback  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - currency  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - tenderTypeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - paymentType  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - paymentCard  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard](paymentcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - paymentData  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.PaymentData](paymentdata-class-microsoft-dynamics-commerce-runtime-sdk-hardwarestation.md)  

<!-- end list -->

  - languageId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[MakePaymentRequest Class](makepaymentrequest-class-microsoft-dynamics-commerce-runtime-sdk-hardwarestation.md)

[Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation Namespace](microsoft-dynamics-commerce-runtime-sdk-hardwarestation-namespace.md)

