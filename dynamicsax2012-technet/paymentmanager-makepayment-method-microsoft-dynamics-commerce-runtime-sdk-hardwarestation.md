---
title: PaymentManager.MakePayment Method  (Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation)
TOCTitle: MakePayment Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.PaymentManager.MakePayment(System.Decimal,System.Decimal,System.String,System.String,System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard,Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.PaymentData)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.sdk.hardwarestation.paymentmanager.makepayment(v=AX.60)
ms:contentKeyID: 65319355
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.PaymentManager.MakePayment
dev_langs:
- CSharp
- C++
- VB
---

# MakePayment Method

Makes a payment.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation](microsoft-dynamics-commerce-runtime-sdk-hardwarestation-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation (in Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.dll)

## Syntax

``` vb
'Declaration
Public Function MakePayment ( _
    amount As Decimal, _
    cashBack As Decimal, _
    currency As String, _
    tenderTypeId As String, _
    paymentType As String, _
    languageId As String, _
    paymentCard As PaymentCard, _
    merchantPaymentData As PaymentData _
) As TenderLine
'Usage
Dim instance As PaymentManager
Dim amount As Decimal
Dim cashBack As Decimal
Dim currency As String
Dim tenderTypeId As String
Dim paymentType As String
Dim languageId As String
Dim paymentCard As PaymentCard
Dim merchantPaymentData As PaymentData
Dim returnValue As TenderLine

returnValue = instance.MakePayment(amount, _
    cashBack, currency, tenderTypeId, _
    paymentType, languageId, paymentCard, _
    merchantPaymentData)
```

``` csharp
public TenderLine MakePayment(
    decimal amount,
    decimal cashBack,
    string currency,
    string tenderTypeId,
    string paymentType,
    string languageId,
    PaymentCard paymentCard,
    PaymentData merchantPaymentData
)
```

``` c++
public:
TenderLine^ MakePayment(
    Decimal amount, 
    Decimal cashBack, 
    String^ currency, 
    String^ tenderTypeId, 
    String^ paymentType, 
    String^ languageId, 
    PaymentCard^ paymentCard, 
    PaymentData^ merchantPaymentData
)
```

#### Parameters

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - cashBack  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - currency  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - tenderTypeId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - paymentType  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - languageId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - paymentCard  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard](paymentcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - merchantPaymentData  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.PaymentData](paymentdata-class-microsoft-dynamics-commerce-runtime-sdk-hardwarestation.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The tender line.  

## See Also

#### Reference

[PaymentManager Class](paymentmanager-class-microsoft-dynamics-commerce-runtime-sdk-hardwarestation.md)

[Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation Namespace](microsoft-dynamics-commerce-runtime-sdk-hardwarestation-namespace.md)

