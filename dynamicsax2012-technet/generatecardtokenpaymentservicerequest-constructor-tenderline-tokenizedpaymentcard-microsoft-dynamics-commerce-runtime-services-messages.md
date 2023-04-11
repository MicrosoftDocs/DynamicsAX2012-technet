---
title: GenerateCardTokenPaymentServiceRequest Constructor (TenderLine, TokenizedPaymentCard) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GenerateCardTokenPaymentServiceRequest Constructor (TenderLine, TokenizedPaymentCard)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GenerateCardTokenPaymentServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine,Microsoft.Dynamics.Commerce.Runtime.DataModel.TokenizedPaymentCard)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.generatecardtokenpaymentservicerequest.generatecardtokenpaymentservicerequest(v=AX.60)
ms:contentKeyID: 65315726
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GenerateCardTokenPaymentServiceRequest Constructor (TenderLine, TokenizedPaymentCard)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    tenderLine As TenderLine, _
    tokenizedPaymentCard As TokenizedPaymentCard _
)
'Usage
Dim tenderLine As TenderLine
Dim tokenizedPaymentCard As TokenizedPaymentCard

Dim instance As New GenerateCardTokenPaymentServiceRequest(tenderLine, _
    tokenizedPaymentCard)
```

``` csharp
public GenerateCardTokenPaymentServiceRequest(
    TenderLine tenderLine,
    TokenizedPaymentCard tokenizedPaymentCard
)
```

``` c++
public:
GenerateCardTokenPaymentServiceRequest(
    TenderLine^ tenderLine, 
    TokenizedPaymentCard^ tokenizedPaymentCard
)
```

#### Parameters

  - tenderLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - tokenizedPaymentCard  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TokenizedPaymentCard](tokenizedpaymentcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GenerateCardTokenPaymentServiceRequest Class](generatecardtokenpaymentservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GenerateCardTokenPaymentServiceRequest Overload](generatecardtokenpaymentservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

