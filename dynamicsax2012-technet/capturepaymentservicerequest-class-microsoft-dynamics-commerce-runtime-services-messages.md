---
title: CapturePaymentServiceRequest Class (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CapturePaymentServiceRequest Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CapturePaymentServiceRequest
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.capturepaymentservicerequest(v=AX.60)
ms:contentKeyID: 62213694
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CapturePaymentServiceRequest
dev_langs:
- CSharp
- C++
- VB
---

# CapturePaymentServiceRequest Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Encapsulates a request to capture payment.

A valid request expects the payment in question to be already authorized.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public NotInheritable Class CapturePaymentServiceRequest _
    Inherits PaymentServiceRequestBase
'Usage
Dim instance As CapturePaymentServiceRequest
```

``` csharp
[DataContractAttribute]
public sealed class CapturePaymentServiceRequest : PaymentServiceRequestBase
```

``` c++
[DataContractAttribute]
public ref class CapturePaymentServiceRequest sealed : public PaymentServiceRequestBase
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ServiceRequest](servicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PaymentServiceRequestBase](paymentservicerequestbase-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
        Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CapturePaymentServiceRequest  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

