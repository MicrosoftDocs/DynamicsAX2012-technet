---
title: AuthorizePaymentServiceRequest Constructor (TenderLine, PaymentCard, Boolean, Boolean) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: AuthorizePaymentServiceRequest Constructor (TenderLine, PaymentCard, Boolean, Boolean)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthorizePaymentServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine,Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard,System.Boolean,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.authorizepaymentservicerequest.authorizepaymentservicerequest(v=AX.60)
ms:contentKeyID: 65321032
author: tonyafehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# AuthorizePaymentServiceRequest Constructor (TenderLine, PaymentCard, Boolean, Boolean)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    tenderLine As TenderLine, _
    paymentCard As PaymentCard, _
    skipLimitValidation As Boolean, _
    isCardTokenRequired As Boolean _
)
'Usage
Dim tenderLine As TenderLine
Dim paymentCard As PaymentCard
Dim skipLimitValidation As Boolean
Dim isCardTokenRequired As Boolean

Dim instance As New AuthorizePaymentServiceRequest(tenderLine, _
    paymentCard, skipLimitValidation, _
    isCardTokenRequired)
```

``` csharp
public AuthorizePaymentServiceRequest(
    TenderLine tenderLine,
    PaymentCard paymentCard,
    bool skipLimitValidation,
    bool isCardTokenRequired
)
```

``` c++
public:
AuthorizePaymentServiceRequest(
    TenderLine^ tenderLine, 
    PaymentCard^ paymentCard, 
    bool skipLimitValidation, 
    bool isCardTokenRequired
)
```

#### Parameters

  - tenderLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - paymentCard  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard](paymentcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - skipLimitValidation  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - isCardTokenRequired  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[AuthorizePaymentServiceRequest Class](authorizepaymentservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[AuthorizePaymentServiceRequest Overload](authorizepaymentservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

