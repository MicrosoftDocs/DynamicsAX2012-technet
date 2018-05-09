---
title: GenerateCardTokenPaymentServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GenerateCardTokenPaymentServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GenerateCardTokenPaymentServiceResponse.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine,Microsoft.Dynamics.Commerce.Runtime.DataModel.TokenizedPaymentCard,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.generatecardtokenpaymentserviceresponse.generatecardtokenpaymentserviceresponse(v=AX.60)
ms:contentKeyID: 65316430
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GenerateCardTokenPaymentServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GenerateCardTokenPaymentServiceResponse Constructor

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

Dim instance As New GenerateCardTokenPaymentServiceResponse(tenderLine, _
    tokenizedPaymentCard, tokenResponsePaymentProperties)
```

``` csharp
public GenerateCardTokenPaymentServiceResponse(
    TenderLine tenderLine,
    TokenizedPaymentCard tokenizedPaymentCard,
    string tokenResponsePaymentProperties
)
```

``` c++
public:
GenerateCardTokenPaymentServiceResponse(
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
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GenerateCardTokenPaymentServiceResponse Class](generatecardtokenpaymentserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

