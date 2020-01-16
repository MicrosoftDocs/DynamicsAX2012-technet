---
title: GetGiftCardResponse.GiftCard Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GiftCard Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetGiftCardResponse.GiftCard
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getgiftcardresponse.giftcard(v=AX.60)
ms:contentKeyID: 62206253
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetGiftCardResponse.GiftCard
dev_langs:
- CSharp
- C++
- VB
---

# GiftCard Property

Gets the gift card.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property GiftCard As GiftCard
    Get
    Private Set
'Usage
Dim instance As GetGiftCardResponse
Dim value As GiftCard

value = instance.GiftCard
```

``` csharp
[DataMemberAttribute]
public GiftCard GiftCard { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property GiftCard^ GiftCard {
    GiftCard^ get ();
    private: void set (GiftCard^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.GiftCard](giftcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [GiftCard](giftcard-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetGiftCardResponse Class](getgiftcardresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

