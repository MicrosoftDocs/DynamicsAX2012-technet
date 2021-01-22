---
title: AuthorizePaymentServiceRequest Class (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: AuthorizePaymentServiceRequest Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthorizePaymentServiceRequest
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.authorizepaymentservicerequest(v=AX.60)
ms:contentKeyID: 62209307
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthorizePaymentServiceRequest
dev_langs:
- CSharp
- C++
- VB
---

# AuthorizePaymentServiceRequest Class

Request object to process authorization payment.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public NotInheritable Class AuthorizePaymentServiceRequest _
    Inherits PaymentServiceRequestBase
'Usage
Dim instance As AuthorizePaymentServiceRequest
```

``` csharp
[DataContractAttribute]
public sealed class AuthorizePaymentServiceRequest : PaymentServiceRequestBase
```

``` c++
[DataContractAttribute]
public ref class AuthorizePaymentServiceRequest sealed : public PaymentServiceRequestBase
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ServiceRequest](servicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PaymentServiceRequestBase](paymentservicerequestbase-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
        Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthorizePaymentServiceRequest  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

