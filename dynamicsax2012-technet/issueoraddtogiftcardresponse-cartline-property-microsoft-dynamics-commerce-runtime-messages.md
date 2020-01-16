---
title: IssueOrAddToGiftCardResponse.CartLine Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CartLine Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.IssueOrAddToGiftCardResponse.CartLine
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.issueoraddtogiftcardresponse.cartline(v=AX.60)
ms:contentKeyID: 62210866
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.IssueOrAddToGiftCardResponse.CartLine
dev_langs:
- CSharp
- C++
- VB
---

# CartLine Property

Gets the cart line that represent the gift card operation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CartLine As CartLine
    Get
    Private Set
'Usage
Dim instance As IssueOrAddToGiftCardResponse
Dim value As CartLine

value = instance.CartLine
```

``` csharp
[DataMemberAttribute]
public CartLine CartLine { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property CartLine^ CartLine {
    CartLine^ get ();
    private: void set (CartLine^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [CartLine](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[IssueOrAddToGiftCardResponse Class](issueoraddtogiftcardresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

