---
title: AuthorizeTokenizedCardPaymentServiceRequest Constructor (TenderLine, TokenizedPaymentCard, String, Boolean) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: AuthorizeTokenizedCardPaymentServiceRequest Constructor (TenderLine, TokenizedPaymentCard, String, Boolean)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthorizeTokenizedCardPaymentServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine,Microsoft.Dynamics.Commerce.Runtime.DataModel.TokenizedPaymentCard,System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.authorizetokenizedcardpaymentservicerequest.authorizetokenizedcardpaymentservicerequest(v=AX.60)
ms:contentKeyID: 65319587
author: tonyafehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# AuthorizeTokenizedCardPaymentServiceRequest Constructor (TenderLine, TokenizedPaymentCard, String, Boolean)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    tenderLine As TenderLine, _
    tokenizedPaymentCard As TokenizedPaymentCard, _
    tokenResponsePaymentProperties As String, _
    skipLimitValidation As Boolean _
)
'Usage
Dim tenderLine As TenderLine
Dim tokenizedPaymentCard As TokenizedPaymentCard
Dim tokenResponsePaymentProperties As String
Dim skipLimitValidation As Boolean

Dim instance As New AuthorizeTokenizedCardPaymentServiceRequest(tenderLine, _
    tokenizedPaymentCard, tokenResponsePaymentProperties, _
    skipLimitValidation)
```

``` csharp
public AuthorizeTokenizedCardPaymentServiceRequest(
    TenderLine tenderLine,
    TokenizedPaymentCard tokenizedPaymentCard,
    string tokenResponsePaymentProperties,
    bool skipLimitValidation
)
```

``` c++
public:
AuthorizeTokenizedCardPaymentServiceRequest(
    TenderLine^ tenderLine, 
    TokenizedPaymentCard^ tokenizedPaymentCard, 
    String^ tokenResponsePaymentProperties, 
    bool skipLimitValidation
)
```

#### Parameters

  - tenderLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - tokenizedPaymentCard  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TokenizedPaymentCard](tokenizedpaymentcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - tokenResponsePaymentProperties  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - skipLimitValidation  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[AuthorizeTokenizedCardPaymentServiceRequest Class](authorizetokenizedcardpaymentservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[AuthorizeTokenizedCardPaymentServiceRequest Overload](authorizetokenizedcardpaymentservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

