---
title: AddToGiftCardServiceRequest.CardCurrencyCode Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CardCurrencyCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AddToGiftCardServiceRequest.CardCurrencyCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.addtogiftcardservicerequest.cardcurrencycode(v=AX.60)
ms:contentKeyID: 62210706
author: tonyafehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AddToGiftCardServiceRequest.CardCurrencyCode
dev_langs:
- CSharp
- C++
- VB
---

# CardCurrencyCode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the gift card currency code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CardCurrencyCode As String
    Get
    Private Set
'Usage
Dim instance As AddToGiftCardServiceRequest
Dim value As String

value = instance.CardCurrencyCode
```

``` csharp
[DataMemberAttribute]
public string CardCurrencyCode { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ CardCurrencyCode {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[AddToGiftCardServiceRequest Class](addtogiftcardservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

