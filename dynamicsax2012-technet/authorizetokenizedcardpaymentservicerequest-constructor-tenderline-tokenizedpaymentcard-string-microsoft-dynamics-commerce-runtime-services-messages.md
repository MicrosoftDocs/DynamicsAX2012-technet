---
title: AuthorizeTokenizedCardPaymentServiceRequest Constructor (TenderLine, TokenizedPaymentCard, String) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: AuthorizeTokenizedCardPaymentServiceRequest Constructor (TenderLine, TokenizedPaymentCard, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthorizeTokenizedCardPaymentServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine,Microsoft.Dynamics.Commerce.Runtime.DataModel.TokenizedPaymentCard,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.authorizetokenizedcardpaymentservicerequest.authorizetokenizedcardpaymentservicerequest(v=AX.60)
ms:contentKeyID: 65320384
author: tonyafehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# AuthorizeTokenizedCardPaymentServiceRequest Constructor (TenderLine, TokenizedPaymentCard, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    tenderLine As TenderLine, _
    tokenizedPaymentCard As TokenizedPaymentCard, _
    tokenResponsePaymentProperties As String _
)
'Usage
Dim tenderLine As TenderLine
Dim tokenizedPaymentCard As TokenizedPaymentCard
Dim tokenResponsePaymentProperties As String

Dim instance As New AuthorizeTokenizedCardPaymentServiceRequest(tenderLine, _
    tokenizedPaymentCard, tokenResponsePaymentProperties)
```

``` csharp
public AuthorizeTokenizedCardPaymentServiceRequest(
    TenderLine tenderLine,
    TokenizedPaymentCard tokenizedPaymentCard,
    string tokenResponsePaymentProperties
)
```

``` c++
public:
AuthorizeTokenizedCardPaymentServiceRequest(
    TenderLine^ tenderLine, 
    TokenizedPaymentCard^ tokenizedPaymentCard, 
    String^ tokenResponsePaymentProperties
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

## See Also

#### Reference

[AuthorizeTokenizedCardPaymentServiceRequest Class](authorizetokenizedcardpaymentservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[AuthorizeTokenizedCardPaymentServiceRequest Overload](authorizetokenizedcardpaymentservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

