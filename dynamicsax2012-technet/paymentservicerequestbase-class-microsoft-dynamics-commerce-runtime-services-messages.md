---
title: PaymentServiceRequestBase Class (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: PaymentServiceRequestBase Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PaymentServiceRequestBase
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.paymentservicerequestbase(v=AX.60)
ms:contentKeyID: 65319091
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PaymentServiceRequestBase
dev_langs:
- CSharp
- C++
- VB
---

# PaymentServiceRequestBase Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public MustInherit Class PaymentServiceRequestBase _
    Inherits ServiceRequest
'Usage
Dim instance As PaymentServiceRequestBase
```

``` csharp
[DataContractAttribute]
public abstract class PaymentServiceRequestBase : ServiceRequest
```

``` c++
[DataContractAttribute]
public ref class PaymentServiceRequestBase abstract : public ServiceRequest
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ServiceRequest](servicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PaymentServiceRequestBase  
        [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthorizePaymentServiceRequest](authorizepaymentservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthorizeTokenizedCardPaymentServiceRequest](authorizetokenizedcardpaymentservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculatePaymentAmountServiceRequest](calculatepaymentamountservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CapturePaymentServiceRequest](capturepaymentservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GenerateCardTokenPaymentServiceRequest](generatecardtokenpaymentservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCardPaymentPropertiesServiceRequest](getcardpaymentpropertiesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SupportedCardTypesPaymentServiceRequest](supportedcardtypespaymentservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.VoidPaymentServiceRequest](voidpaymentservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

