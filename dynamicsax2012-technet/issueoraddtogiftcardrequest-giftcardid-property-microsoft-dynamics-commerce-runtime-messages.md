---
title: IssueOrAddToGiftCardRequest.GiftCardId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GiftCardId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.IssueOrAddToGiftCardRequest.GiftCardId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.issueoraddtogiftcardrequest.giftcardid(v=AX.60)
ms:contentKeyID: 62214364
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.IssueOrAddToGiftCardRequest.GiftCardId
dev_langs:
- CSharp
- C++
- VB
---

# GiftCardId Property

Gets the gift card identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<DataMemberAttribute> _
Public Property GiftCardId As String
    Get
    Private Set
'Usage
Dim instance As IssueOrAddToGiftCardRequest
Dim value As String

value = instance.GiftCardId
```

``` csharp
[RequiredAttribute]
[DataMemberAttribute]
public string GiftCardId { get; private set; }
```

``` c++
[RequiredAttribute]
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

[IssueOrAddToGiftCardRequest Class](issueoraddtogiftcardrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

