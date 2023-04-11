---
title: UnlockGiftCardServiceRequest.GiftCardId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GiftCardId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UnlockGiftCardServiceRequest.GiftCardId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.unlockgiftcardservicerequest.giftcardid(v=AX.60)
ms:contentKeyID: 62211018
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UnlockGiftCardServiceRequest.GiftCardId
dev_langs:
- CSharp
- C++
- VB
---

# GiftCardId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the gift card identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property GiftCardId As String
    Get
    Private Set
'Usage
Dim instance As UnlockGiftCardServiceRequest
Dim value As String

value = instance.GiftCardId
```

``` csharp
[DataMemberAttribute]
public string GiftCardId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ GiftCardId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[UnlockGiftCardServiceRequest Class](unlockgiftcardservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

