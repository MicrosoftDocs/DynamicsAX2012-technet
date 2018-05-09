---
title: VoidGiftCardServiceRequest.GiftCardId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GiftCardId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.VoidGiftCardServiceRequest.GiftCardId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.voidgiftcardservicerequest.giftcardid(v=AX.60)
ms:contentKeyID: 62213016
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.VoidGiftCardServiceRequest.GiftCardId
dev_langs:
- CSharp
- C++
- VB
---

# GiftCardId Property

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
Dim instance As VoidGiftCardServiceRequest
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

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[VoidGiftCardServiceRequest Class](voidgiftcardservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

